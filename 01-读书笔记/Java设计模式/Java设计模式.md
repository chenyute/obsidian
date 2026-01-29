# 2 面向对象设计原则
![[Java设计模式 (刘伟) (Z-Library).pdf#page=29&rect=137,739,1318,1546|Java设计模式 (刘伟) (Z-Library), p.29]]

## 2.3 开闭原则
![[Java设计模式 (刘伟) (Z-Library).pdf#page=31&rect=156,1037,1287,1134|Java设计模式 (刘伟) (Z-Library), p.31]]

## 2.4 里氏替换原则
![[Java设计模式 (刘伟) (Z-Library).pdf#page=32&rect=143,837,1297,1100|Java设计模式 (刘伟) (Z-Library), p.32]]

## 2.5 依赖倒转原则
![[Java设计模式 (刘伟) (Z-Library).pdf#page=33&rect=152,1763,1292,1861|Java设计模式 (刘伟) (Z-Library), p.33]]

依赖注入的常见方式有三种，分别是构造注入、设值注入、接口注入。
![[Java设计模式 (刘伟) (Z-Library).pdf#page=33&rect=152,1067,1291,1377|Java设计模式 (刘伟) (Z-Library), p.33]]

三种设计原则相辅相成：开闭原则、里氏替换原则、依赖倒转原则
![[Java设计模式 (刘伟) (Z-Library).pdf#page=34&rect=145,873,1302,1011|Java设计模式 (刘伟) (Z-Library), p.34]]

## 2.7 合成复用原则
![[Java设计模式 (刘伟) (Z-Library).pdf#page=36&rect=151,206,1297,598|Java设计模式 (刘伟) (Z-Library), p.36]]

# 创建者模式
![[Java设计模式 (刘伟) (Z-Library).pdf#page=44&rect=139,760,1305,1596|Java设计模式 (刘伟) (Z-Library), p.44]]

# 3 简单工厂模式(⭐⭐⭐)

> [!NOTE] 简单工厂模式总结
> 一个具体工厂；一个抽象产品、多个具体产品
> 具体工厂接受具体参数，根据参数确定要创建的具体产品


![[Java设计模式 (刘伟) (Z-Library).pdf#page=45&rect=146,936,1297,1306|Java设计模式 (刘伟) (Z-Library), p.45]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=46&rect=204,1269,1261,1869|Java设计模式 (刘伟) (Z-Library), p.46]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=52&rect=149,705,1296,1103|Java设计模式 (刘伟) (Z-Library), p.52]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=53&rect=158,302,1289,436|Java设计模式 (刘伟) (Z-Library), p.53]]
### 3.7.3 简单工厂模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=55&rect=155,396,1285,566|Java设计模式 (刘伟) (Z-Library), p.55]]

## 3.8 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=55&rect=152,165,1294,256|Java设计模式 (刘伟) (Z-Library), p.55]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=56&rect=153,971,1296,1858|Java设计模式 (刘伟) (Z-Library), p.56]]

# 4 工厂方法模式(⭐⭐⭐⭐⭐)

> [!NOTE] 工厂方法模式总结
> 一个抽象工厂、多个具体工厂；一个抽象产品、多个具体产品
> 一个具体工厂和一个具体产品关联，根据工厂类型确定创建的产品类型

![[Java设计模式 (刘伟) (Z-Library).pdf#page=60&rect=149,1444,1291,1863|Java设计模式 (刘伟) (Z-Library), p.60]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=60&rect=152,463,1295,1003|Java设计模式 (刘伟) (Z-Library), p.60]]

### 4.7.3 工厂方法模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=70&rect=157,485,1287,824|Java设计模式 (刘伟) (Z-Library), p.70]]

## 4.8 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=70&rect=150,166,1293,340|Java设计模式 (刘伟) (Z-Library), p.70]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=71&rect=149,1163,1292,1861|Java设计模式 (刘伟) (Z-Library), p.71]]

# 5 抽象工厂模式(⭐⭐⭐⭐⭐)

> [!NOTE] 抽象工厂模式总结
> 一个抽象工厂、多个具体工厂；多个产品族（每个产品族包含多个具体产品）
> 一个具体工厂和一个产品族关联，每个工厂可以创建产品族下的多种产品

![[Java设计模式 (刘伟) (Z-Library).pdf#page=75&rect=149,1003,1296,1859|Java设计模式 (刘伟) (Z-Library), p.75]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=76&rect=185,956,1265,1868|Java设计模式 (刘伟) (Z-Library), p.76]]

## 5.5 开闭原则的倾斜性

![[Java设计模式 (刘伟) (Z-Library).pdf#page=84&rect=153,1427,1290,1809|Java设计模式 (刘伟) (Z-Library), p.84]]

### 5.6.3 抽象工厂模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=84&rect=159,163,1287,296|Java设计模式 (刘伟) (Z-Library), p.84]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=85&rect=159,1507,1284,1850|Java设计模式 (刘伟) (Z-Library), p.85]]

## 5.7 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=85&rect=148,397,1299,1366|Java设计模式 (刘伟) (Z-Library), p.85]]

# 6 建造者模式(⭐⭐)

> [!NOTE] 建造者模式总结
> 一个具体产品；一个抽象建造者、多个具体建造者、一个具体指挥者
> 建造者根据实际需要的产品特征创建对应的产品

![[Java设计模式 (刘伟) (Z-Library).pdf#page=89&rect=144,730,1304,1228|Java设计模式 (刘伟) (Z-Library), p.89]]

## 6.2 建造者模式结构与实现

![[Java设计模式 (刘伟) (Z-Library).pdf#page=90&rect=161,1335,1280,1851|Java设计模式 (刘伟) (Z-Library), p.90]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=92&rect=148,387,1291,653|Java设计模式 (刘伟) (Z-Library), p.92]]

### 6.5.3 建造者模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=103&rect=156,235,1289,503|Java设计模式 (刘伟) (Z-Library), p.103]]

## 6.6 本章小结

![[Java设计模式 (刘伟) (Z-Library).pdf#page=104&rect=146,791,1301,1714|Java设计模式 (刘伟) (Z-Library), p.104]]

# 7 原型模式(⭐⭐⭐)

> [!NOTE] 原型模式总结
> 需要复制一个对象的情况下使用

![[Java设计模式 (刘伟) (Z-Library).pdf#page=107&rect=146,637,1298,1364|Java设计模式 (刘伟) (Z-Library), p.107]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=108&rect=156,1373,1288,1845|Java设计模式 (刘伟) (Z-Library), p.108]]

### 7.2.2 浅克隆与深克隆
![[Java设计模式 (刘伟) (Z-Library).pdf#page=108&rect=152,997,1294,1097|Java设计模式 (刘伟) (Z-Library), p.108]]

### 7.5.3 原型模式适用环境

![[Java设计模式 (刘伟) (Z-Library).pdf#page=119&rect=160,1269,1286,1618|Java设计模式 (刘伟) (Z-Library), p.119]]

## 7.6 本章小结

![[Java设计模式 (刘伟) (Z-Library).pdf#page=119&rect=155,170,1288,1127|Java设计模式 (刘伟) (Z-Library), p.119]]

# 8 单例模式(⭐⭐⭐⭐)

> [!NOTE] 单例模式总结
> 整个系统只有一个实例，无法通过自身类以外的方式创建

![[Java设计模式 (刘伟) (Z-Library).pdf#page=122&rect=152,568,1288,947|Java设计模式 (刘伟) (Z-Library), p.122]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=123&rect=161,1464,1280,1845|Java设计模式 (刘伟) (Z-Library), p.123]]

## 8.4 饿汉式单例与懒汉式单例
![[Java设计模式 (刘伟) (Z-Library).pdf#page=127&rect=148,764,1293,1189|Java设计模式 (刘伟) (Z-Library), p.127]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=128&rect=159,1297,1284,1848|Java设计模式 (刘伟) (Z-Library), p.128]]

### 8.5.3 单例模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=131&rect=156,168,1287,382|Java设计模式 (刘伟) (Z-Library), p.131]]

## 8.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=132&rect=156,1186,1287,1712|Java设计模式 (刘伟) (Z-Library), p.132]]

# 结构型模式

![[Java设计模式 (刘伟) (Z-Library).pdf#page=135&rect=155,674,1288,1422|Java设计模式 (刘伟) (Z-Library), p.135]]

# 9 适配器模式(⭐⭐⭐⭐)

> [!NOTE] 适配器模式总结
> 两个类之间无法直接兼容，通过适配器在中间进行转换，使得两个类可以兼容

![[Java设计模式 (刘伟) (Z-Library).pdf#page=136&rect=152,763,1293,1229|Java设计模式 (刘伟) (Z-Library), p.136]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=137&rect=158,789,1290,1857|Java设计模式 (刘伟) (Z-Library), p.137]]

## 9.5 缺省适配器模式
![[Java设计模式 (刘伟) (Z-Library).pdf#page=142&rect=148,341,1289,757|Java设计模式 (刘伟) (Z-Library), p.142]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=143&rect=159,1184,1288,1843|Java设计模式 (刘伟) (Z-Library), p.143]]
## 9.6 双向适配器
![[Java设计模式 (刘伟) (Z-Library).pdf#page=144&rect=148,199,1301,891|Java设计模式 (刘伟) (Z-Library), p.144]]

### 9.7.3 适配器模式
![[Java设计模式 (刘伟) (Z-Library).pdf#page=146&rect=155,917,1285,1134|Java设计模式 (刘伟) (Z-Library), p.146]]

## 9.8 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=146&rect=153,168,1289,776|Java设计模式 (刘伟) (Z-Library), p.146]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=147&rect=155,1382,1285,1855|Java设计模式 (刘伟) (Z-Library), p.147]]


# 10 桥接模式(⭐⭐⭐)
> [!NOTE] 桥接模式总结
> 使用组合的方式取代多层继承关系，能够有效控制系统中类的个数

![[Java设计模式 (刘伟) (Z-Library).pdf#page=150&rect=151,430,1293,1015|Java设计模式 (刘伟) (Z-Library), p.150]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=151&rect=170,1296,1279,1842|Java设计模式 (刘伟) (Z-Library), p.151]]

## 10.4 桥接模式与适配器模式的联用
![[Java设计模式 (刘伟) (Z-Library).pdf#page=159&rect=154,228,1290,945|Java设计模式 (刘伟) (Z-Library), p.159]]

### 10.5.3 桥接模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=160&rect=153,163,1290,594|Java设计模式 (刘伟) (Z-Library), p.160]]

## 10.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=161&rect=152,932,1291,1710|Java设计模式 (刘伟) (Z-Library), p.161]]






# 11 组合模式(⭐⭐⭐⭐)

> [!NOTE] 组合模式总结
> 使用面向对象的方式来处理树形结构，可以一致性地处理整个树结构或者树形结构的一部分

![[Java设计模式 (刘伟) (Z-Library).pdf#page=164&rect=150,252,1293,713|Java设计模式 (刘伟) (Z-Library), p.164]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=165&rect=151,973,1287,1634|Java设计模式 (刘伟) (Z-Library), p.165]]

### 11.5.3 组合模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=175&rect=158,1176,1288,1436|Java设计模式 (刘伟) (Z-Library), p.175]]

## 11.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=175&rect=158,257,1291,1032|Java设计模式 (刘伟) (Z-Library), p.175]]






# 12 装饰模式(⭐⭐⭐)

> [!NOTE] 装饰模式总结
> 一种用于替代继承的技术，通过一种无须定义子类的方式来给对象动态添加职责

![[Java设计模式 (刘伟) (Z-Library).pdf#page=178&rect=157,734,1285,1153|Java设计模式 (刘伟) (Z-Library), p.178]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=179&rect=167,1054,1278,1860|Java设计模式 (刘伟) (Z-Library), p.179]]

### 12.5.3 装饰模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=187&rect=157,169,1285,483|Java设计模式 (刘伟) (Z-Library), p.187]]

## 12.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=188&rect=153,793,1288,1712|Java设计模式 (刘伟) (Z-Library), p.188]]





# 13 外观模式(⭐⭐⭐⭐⭐)

> [!NOTE] 外观模式总结
> 引入外观角色简化客户端与子系统的交互，为复杂子系统调用提供统一入口

![[Java设计模式 (刘伟) (Z-Library).pdf#page=191&rect=152,167,1296,486|Java设计模式 (刘伟) (Z-Library), p.191]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=192&rect=158,1722,1284,1856|Java设计模式 (刘伟) (Z-Library), p.192]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=192&rect=151,837,1288,1500|Java设计模式 (刘伟) (Z-Library), p.192]]

### 13.5.3 外观模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=202&rect=146,1401,1291,1669|Java设计模式 (刘伟) (Z-Library), p.202]]

## 13.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=202&rect=154,401,1287,1263|Java设计模式 (刘伟) (Z-Library), p.202]]




# 14 享元模式(⭐)

> [!NOTE] 享元模式总结
> 系统中存在大量相同或相似对象时，提供用于共享的对象给客户端使用

![[Java设计模式 (刘伟) (Z-Library).pdf#page=205&rect=152,562,1288,901|Java设计模式 (刘伟) (Z-Library), p.205]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=206&rect=151,1404,1289,1850|Java设计模式 (刘伟) (Z-Library), p.206]]

### 14.7.3 享元模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=216&rect=146,570,1293,805|Java设计模式 (刘伟) (Z-Library), p.216]]

## 14.8 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=216&rect=149,165,1293,439|Java设计模式 (刘伟) (Z-Library), p.216]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=217&rect=153,1250,1293,1860|Java设计模式 (刘伟) (Z-Library), p.217]]

# 15 代理模式(⭐⭐⭐⭐)

> [!NOTE] 代理模式总结
> 无法直接访问某对象或访问某对象存在困难时，可以通过代理对象间接访问

![[Java设计模式 (刘伟) (Z-Library).pdf#page=220&rect=147,695,1292,1119|Java设计模式 (刘伟) (Z-Library), p.220]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=221&rect=153,1275,1296,1882|Java设计模式 (刘伟) (Z-Library), p.221]]

### 15.7.3 代理模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=234&rect=152,1264,1293,1714|Java设计模式 (刘伟) (Z-Library), p.234]]

## 15.8 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=234&rect=149,161,1301,1137|Java设计模式 (刘伟) (Z-Library), p.234]]





# 行为型模式
![[Java设计模式 (刘伟) (Z-Library).pdf#page=238&rect=152,222,1290,1459|Java设计模式 (刘伟) (Z-Library), p.238]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=239&rect=156,1304,1284,1819|Java设计模式 (刘伟) (Z-Library), p.239]]

# 16 职责链模式(⭐⭐)

> [!NOTE] 职责链模式总结
> 将请求的发送者和多个接收者解耦，让接收者连成一条链，并沿着这条链传递请求

![[Java设计模式 (刘伟) (Z-Library).pdf#page=240&rect=147,607,1292,1136|Java设计模式 (刘伟) (Z-Library), p.240]]

### 16.6.3 职责链模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=249&rect=146,391,1295,664|Java设计模式 (刘伟) (Z-Library), p.249]]

## 16.7 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=249&rect=154,170,1286,257|Java设计模式 (刘伟) (Z-Library), p.249]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=250&rect=150,906,1294,1854|Java设计模式 (刘伟) (Z-Library), p.250]]

# 17 命令模式(⭐⭐⭐⭐)

> [!NOTE] 命令模式总结
> 将请求的发送者和接收者解耦

![[Java设计模式 (刘伟) (Z-Library).pdf#page=253&rect=154,703,1285,1071|Java设计模式 (刘伟) (Z-Library), p.253]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=254&rect=158,1355,1293,1869|Java设计模式 (刘伟) (Z-Library), p.254]]

### 17.8.3 命令模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=266&rect=150,873,1292,1267|Java设计模式 (刘伟) (Z-Library), p.266]]

## 17.9 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=266&rect=155,172,1287,729|Java设计模式 (刘伟) (Z-Library), p.266]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=267&rect=161,1549,1287,1855|Java设计模式 (刘伟) (Z-Library), p.267]]



# 18 解释器模式(⭐)

> [!NOTE] 解释器模式总结
> 描述如何构成一个简单的语言解释器

![[Java设计模式 (刘伟) (Z-Library).pdf#page=269&rect=153,874,1295,1295|Java设计模式 (刘伟) (Z-Library), p.269]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=271&rect=162,1313,1284,1879|Java设计模式 (刘伟) (Z-Library), p.271]]

### 18.5.3 解释器模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=279&rect=144,171,1291,258|Java设计模式 (刘伟) (Z-Library), p.279]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=280&rect=151,1633,1291,1855|Java设计模式 (刘伟) (Z-Library), p.280]]

## 18.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=280&rect=146,832,1297,1500|Java设计模式 (刘伟) (Z-Library), p.280]]


# 19 迭代器模式(⭐⭐⭐⭐⭐)

> [!NOTE] 迭代器模式总结
> 提供方法能够顺序访问聚合对象中的各个元素

![[Java设计模式 (刘伟) (Z-Library).pdf#page=283&rect=153,666,1294,941|Java设计模式 (刘伟) (Z-Library), p.283]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=284&rect=158,1347,1298,1865|Java设计模式 (刘伟) (Z-Library), p.284]]

### 19.6.3 迭代器模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=296&rect=152,231,1286,506|Java设计模式 (刘伟) (Z-Library), p.296]]

## 19.7 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=297&rect=150,833,1293,1712|Java设计模式 (刘伟) (Z-Library), p.297]]

# 20 中介者模式(⭐⭐)

> [!NOTE] 中介者模式总结
> 中介者可以将原本对象之间的两两交互转化为每个对象和中介者之间的交互，大量运用于GUI

![[Java设计模式 (刘伟) (Z-Library).pdf#page=301&rect=149,1215,1290,1729|Java设计模式 (刘伟) (Z-Library), p.301]]

![[Java设计模式 (刘伟) (Z-Library).pdf#page=301&rect=150,468,1293,916|Java设计模式 (刘伟) (Z-Library), p.301]]

### 20.5.3 中介者模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=313&rect=159,151,1285,390|Java设计模式 (刘伟) (Z-Library), p.313]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=314&rect=156,1767,1289,1859|Java设计模式 (刘伟) (Z-Library), p.314]]

## 20.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=314&rect=159,922,1285,1629|Java设计模式 (刘伟) (Z-Library), p.314]]



# 21 备忘录模式(⭐⭐)

> [!NOTE] 备忘录模式总结
> 提供状态恢复机制，可以方便地回到特定的历史状态

![[Java设计模式 (刘伟) (Z-Library).pdf#page=317&rect=149,910,1299,1344|Java设计模式 (刘伟) (Z-Library), p.317]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=317&rect=156,193,1289,613|Java设计模式 (刘伟) (Z-Library), p.317]]

### 21.5.3 备忘录模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=327&rect=152,165,1292,256|Java设计模式 (刘伟) (Z-Library), p.327]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=328&rect=156,1720,1288,1856|Java设计模式 (刘伟) (Z-Library), p.328]]

## 21.6 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=328&rect=156,969,1291,1584|Java设计模式 (刘伟) (Z-Library), p.328]]


# 22 观察者模式(⭐⭐⭐⭐⭐)

> [!NOTE] 观察者模式总结
> 描述对象间的依赖关系，实现多个对象之间的联动

![[Java设计模式 (刘伟) (Z-Library).pdf#page=331&rect=158,471,1292,941|Java设计模式 (刘伟) (Z-Library), p.331]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=332&rect=163,1053,1278,1852|Java设计模式 (刘伟) (Z-Library), p.332]]

### 22.7.3 观察者模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=343&rect=155,166,1297,264|Java设计模式 (刘伟) (Z-Library), p.343]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=344&rect=159,1640,1291,1857|Java设计模式 (刘伟) (Z-Library), p.344]]

## 22.8 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=344&rect=151,650,1293,1502|Java设计模式 (刘伟) (Z-Library), p.344]]



# 23 状态模式

> [!NOTE] 状态模式总结
> 对象存在多个状态，不同状态间可以相互转换，不同状态下行为不同，具体行为不在对象中定义，而是在状态类中定义，根据状态的类型却确定具体行为。

![[Java设计模式 (刘伟) (Z-Library).pdf#page=347&rect=152,697,1288,973|Java设计模式 (刘伟) (Z-Library), p.347]]
![[Java设计模式 (刘伟) (Z-Library).pdf#page=348&rect=154,1449,1287,1848|Java设计模式 (刘伟) (Z-Library), p.348]]

### 23.6.3 状态模式适用环境
![[Java设计模式 (刘伟) (Z-Library).pdf#page=363&rect=146,1363,1298,1537|Java设计模式 (刘伟) (Z-Library), p.363]]

## 23.7 本章小结
![[Java设计模式 (刘伟) (Z-Library).pdf#page=363&rect=147,398,1296,1224|Java设计模式 (刘伟) (Z-Library), p.363]]


# End

> [!NOTE] 模式总结
> 内容
# 积累的问题
命令模式和中介者模式的区别
中介者和观察者的区别