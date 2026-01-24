# 配置介绍
本配置是基于Sway的Fedora配置，执行配置内容的命令时，请保证在文件夹的根目录下执行。
# 修改镜像源
``` sh
sudo cp /etc/yum.repos.d/fedora.repo /etc/yum.repos.d/fedora.repo.bak
sudo cp /etc/yum.repos.d/fedora-updates.repo /etc/yum.repos.d/fedora-updates.repo.bak

sudo sed -e 's|^metalink=|#metalink=|g' \
         -e 's|^#baseurl=http://download.example/pub/fedora/linux|baseurl=https://mirrors.ustc.edu.cn/fedora|g' \
         -i.bak \
         /etc/yum.repos.d/fedora.repo \
         /etc/yum.repos.d/fedora-updates.repo
```

# 安装软件
``` sh
# Base app
sudo dnf install neovim git zsh kitty stow fcitx5 fcitx5-chinese-addons \
# Build caps-lock tools
cmake libevdev-devel systemd-devel yaml-cpp-devel boost-devel gcc-c++ \
```

# 配置CapsLock功能
## 安装interception-tools
``` sh
cd tools/interception-tools
cmake -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build
sudo cmake --install build
```

## 安装dual-function-keys
``` sh
cd tools/dual-function-keys
make && sudo make install
```

## 添加配置文件
``` sh
sudo mv ./config/capslock-config/interception /etc/
sudo mv ./config/capslock-config/udevmon.service /etc/systemd/system/
```

## 启动服务
``` sh 
# Enable and start the `udevmon` service
sudo systemctl enable --now udevmon.service
# Optionally verify the `udevmon` service is active and running
systemctl status udevmon
```

# 配置中文输入法
使用`fcitx5-configtool`命令打开输入法配置，将`Pinyin`添加到布局
## 添加环境变量
``` sh
sudo tee -a /etc/environment << 'EOF'
XIM=fcitx
GTK_IM_MODULE=fcitx
QT_IM_MODULE=fcitx
XMODIFIERS=@im=fcitx
EOF
```

# 配置dotfiles
``` sh
cd
git clone git@gitlab.com:chenyute/dotfiles.git
cd dotfiles
stow nvim kitty zsh
```