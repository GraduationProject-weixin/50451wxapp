# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50451wxapp仓储管理系统_r275i小程序

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1NvtMeFEiw?p=109)


# 第1章 概述
## 1.1课题研究背景
如今互联网发展迅猛，大量的信息都是通过网络这一渠道来传播，所以利用网络渠道来传播信息是非常有前景的。仓储管理系统的主要目的就是及时有效、方便快捷的获取仓储信息，是一个新知识诞生的地方，光靠现有的条件是远远不够的，所以建设仓储管理系统是有必要的，这样能使用户通过仓储管理系统来弥补现有条件的不足，因此开发仓储管理系统迫在眉睫，仓储管理系统的实现有着重大意义。

至今为止，时代的发展趋势一直指向的就是在网络上进行系统管理。这次我所设计的课题是仓储管理系统，正是Internet与用户的紧密关系的体现。

一个好的小程序能够把传统的管理方式，带上一全新的方式，效率、可靠、安全稳定集合一身的系统，带来的体验是传统所没有办法实现的，信息的交流将达到顶峰，用户的沟通将会更加的便捷，有问题实时反馈提交，及时接收重要通知，将仓储管理正规化、合理化、高效化。

由此设计与开发一个仓储管理系统是非常有必要的，java语言是所有语言中的基础，学习好java语言才能去更深入的学习其它语言。java语言有以下特点：绘图能力强、可移植性、有很强的数据处理能力，适用于系统软件的编写、三维和二维图形，还可以编写出动画的效果，所以它是一种高级语言。
## 1.2课题研究意义
当前来说，各种类型小程序应用越来越广泛，然而开发小程序的技术伴随着技术产品的需求，出现了极大的差异性。具体而言，支付宝小程序所运用的是支付宝技术，头条小程序所运用的则是字节跳动公司的技术，在微信小程序中所运用往往是腾讯的WXML、WXSS和JS技术。

除了技术以外，微信用户量十分庞大，而用户基数直接与微信小程序的使用量成正比，选择基于微信小程序的仓储管理系统不仅能够方便用户，也能提高用户的生活效率。21世纪是互联网快时代，与此同时，人们的生活节奏也随之加快。在这快节奏的时代，形形色色的人不断追求着更高层次的生活，从而不断学习“生存技能”。可在这快时代里，线上管理还属于发展阶段。仓储开发微信小程序使得用户能够拥有多种形式去交流，通过小程序可及时与用户联系以及互动，使得用户裂变增加，增强积极性的同时也提高了管理者的管理效率。
## 1.3前期工作
为了使本系统的功能做得更加完美，使用户看上去清晰明了，特意去查找分析了一些相关的系统，了解和分析出其系统的功能和具体功能模块的实现方法，还具体了解了其系统功能的组织结构。最后通过问卷调查的方法进行了实地调查，了解了仓储管理系统的初步的需求，开始初步设计本系统。从问卷调查中得知：该系统在技术上是可行的，在经济上也是可行的，开发成本相对较低。
## 1.4本文的组织结构
本网站利用java技术和的MySQL进行开发，将仓储管理系统推向更安全、技术更强悍的系统信息管理。

仓储主要实现了前台和后台两大模块。通过本网站使管理工作效率提升到另一个层次，还更不容易出错，对数据的查找与存储有更方便等因素； 

对内容的介绍详细阐述如下：

第一章、绪论，对本课题选择的背景以及意义和开发系统前期的工作做了详细的介绍。

第二章、使用的技术相关知识，利用关键技术对系统进行开发。

第三章、对系统进行分析，对系统开发的可行性，系统的流程以及功能进行了探讨。

第四章、系统具体功能的设计，主要是实现前台员工和供应商功能和后台管理员三种身份相应的模块，然后进行整合，分析其结构，然后设计，并进行相对应的数据库的构架与设计。

第五章、本系统的实现，也是系统的核心，主要介绍系统登录页面，系统管理员和、员工和供应商功能模块各异，页面清楚简洁，简单易懂。

最后是总结，主要是对本系统的总结和对后期的展望。


# 第2章开发技术
## 2.1微服务架构
微服务架构(Micro Services Architecture, MSA)最早由软件开发工程师Martin Fowler和James Lewis于2014年正式提出，是一种新兴的软件架构设计风格与组织模式。微服务架构从业务逻辑角度对传统的单体式应用程序进行了严格的拆分，从而得到多个职责单一、可独立部署与运行、开放RESTfuI风格接口的细粒度服务，不同服务之间通过超文本传输协议(Hypertext Transfer Protocol, HTTP)或远程过程调用(Remote ProcedureCall, RPC)机制进行通信，最终形成一个高内聚、低祸合的软件结构体系。
## 2.2微服务架构的优势
`    `相较于SOA等传统应用架构，微服务架构的优势总结如下:

` `(1)开发效率高:微服务架构使得整个系统开发工作的分工更加明确，每个开发团队只需专注于实现自己负责的服务，真正实现了协同、并行开发，大大缩短了开发周期。

` `(2)可拓展性高:当应用程序出现新的功能需求时，可针对各个服务进行独立拓展，快速发布新版本，而不是整体重新发布。

` `(3)低祸合:每个服务高度自治且高度隔离，可独立开发、测试、部署和运维。

` `(4)技术栈灵活:不同服务可根据业务需求自由选择最契合的技术来解决实际问题。

` `(5)可复用性高:每个服务都对外提供RESTfuI风格的接口，专为某项功能所编写的服务模块也可以作为其他功能的构建块，开发人员可以重复利用现有代码以创建新功育旨。

(6)高可用性:得益于微服务治理框架所提供的强大服务治理能力和容错机制，当服务需求激增时也能保持可用性。
## 2.3 JAVA语言
Java 语言是一门受众很广的语言，来自Sun Microsystems公司，Java可运行在很多平台，相较于C++语言，不仅吸收了C++很多优点，还摈弃了里面许多晦涩难懂的概念，Java的优点很多，可面向对象开发，平台多样性以及可移植性很高，目前市面上很多大型网站项目都使用Java编写，由此可知Java的受欢迎程度很高。
## 2.4 springboot框架
Spring Boot是由Pivotal团队提供的轻量级框架，其“开箱即用”及“约定优于配置”的策略可以使开发者全身心的投入到业务逻辑代码的编写中，极大地提高了软件开发项目的效率。相比于Spring框架而言，Spring Boot框架更加能够节省程序员配置XML的时间，Spring Boot项目允许开发者使用它的所有模块和开发功能，此外， Spring Boot内置了服务器，简化了开发者启用服务器的整体流程，Spring Boot还可以自动适配不同类型的数据库以满足用户快速连接后台数据库管理的需求，这极大地方便了用户快速搭建应用程序的实现过程。 2014年4月，Spring Boot 1.0.0发布，截止到2022年2月，发布的Spring Boot版本为Spring Boot 3.0.0-M1。在系统的设计与开发中，为了能够快速搭建软件后台服务的开发环境，从技术实现的难度以及平台开发的成本两个方面考虑，Spring Boot框架能够使开发者更关注平台功能的业务逻辑代码实现，可采用Spring Boot框架搭建系统为前端电子商城App提供数据服务。因此，本案例项目后台开发选择Spring Boot框架。
## 2.5 MYSQL数据库技术
数据库在软件项目中扮演着操作管理数据的角色同时还能够保证数据的独立性、一致性和安全性，并为系统访问数据提供有效方式不仅如此数据库还能大大减少程序员开发程序时间。在日常能够接触实用的一般有两类数据库，一类是以(Oracle，DB2，SQL Server，MySQL )为代表的关系型数据库和以(NoSql、MongeDB)为代表的非关系型数据库，两类数据库各有各的优缺点。其中非关系型数据库又分为网络数据库和层级数据库。-网络数据库是指在计算机网络系统中应用数据库技术然后借助网络技术将存储于数据库中的大量信息及时发布出去；在成熟的数据库技术的帮助下，计算机网络实现了对网络中的各种数据的有效管理，用户与网络中的数据库数据交互也借此得以进行。IMS也是最早研制成功的数据库系统。关系数据结构、关系操作集合、关系完整性约束构成了关系模型。作为数据库另外一种区分方式的存储介质被大家分为磁盘和内存这 两种。例如：关系型数据库就存储在磁盘中，非关系型数据库则存储在内存中。典型的关系型数据库有：Oracle、DB2、Microsoft SQL Server、Microsoft Access、MySQL、SQLite。小型关系型数据库：Microsoft Access，SQLite；中型关系型数据库：SQL Server，Mysql；大型关系型数据库：Oracle，DB2。

大家常用的其他关系形数据库系统大多是MySQL AB公司开发的，其中MySQL也是由这家开发的，所应用的分布式数据库管理系统是客户机/服务器体系结构得益于此结构，而且用这个系统建造的数据库具有很强的适用性，用C和C++编写的系统让他拥有很强的适用性所以他可以在大部分操作系统上使用并能和java结合。不同的API函数针对不同的语言(C,C++,JAVA等)来处理不同数据；为了更好地支持多CPU多线程通过使用核心线程来实现；提供的存储机制分为事务和非事务存储机制；MySQL采用双重许可，不管是从MySQL AB公司获得正式的商业许可又或是许可条款下以免费软件或开放源码软件的方式使用MySQL软件都是被允许的。

MySQL作为数据库拥有很多优点，其中由于是开放源码，所以使用成本特别低，而它体积小的特点决定了速度快的特性。因此，My Sql具有开放性，多线程支持多种API，可跨数据库连接，国际化，数据库体积巨大等特点。简单的来说 ，MySql是一个开放的、快速的、多线程的、多用户的数据库服务器。

选用MySQL作为数据库的其中一个原因就是支持多线程，支持多线程的特点为利用系统资源提供了便捷并因此大大提高了系统运行速度和效率，而且连接数据库的方式多样包括但不局限于TCP/IP、ODBC和JDBC等途径；但是没有东西是完美无缺的，即便MySQL也如此，虽说它有着众多优点但其功能不够强大，规模也相对较小，无法应对大型数据哭的处理。但是对于本系统来说，选用MySQL作为数据库，其功能性能已绰绰有余，如果要进行二次开发的数据库表结构空间的扩展也是完全可行的。综上所述，MySQL是作为本系统数据库的最优选择。
## 2.6 B/S结构简介
使用B/S结构的系统是通过有网络的计算机进行使用，它最大的优点是不需要安装专门的软件，最先，计算机浏览器向服务器发送要求，随后服务器解决要求并将信息回到给计算机浏览器。不用再次计算数据或进行存取，只管负责显示数据来降低要求。与C/S构架对比，B/S构架与C/S架构的较大差别取决于，B/S构架的系统软件以web计算机浏览器为服务平台与消费者实现互动，如下图2-1所显示，而C/S则必须开发专业的运用。

![](/md/blog.007.png)

图2-1  B/S结构图
# 第3章 系统分析
## 3.1系统总体分析
本系统采取了一系列的设计原则，主要目的是为了系统的功能设计，还有管理人员在后期对系统维护时的方便，以及使用户能够简易的操作。最重要的设计原则包括：简单性、针对性、实用性、一致性、先进性。

（1）简单性：在该系统中功能模块实现的同时，让用户操作起来简单明了，很快找到所需资源是最直接的目的。

（2）针对性：该系统是根据设计需求为导向来开发仓储管理系统的设计，所以针对性较强。

（3）实用性：该设计能够满足仓储管理系统的实际的功能需求，能够在实际中让用户真正使用到，具有实际的应用价值。

（4）一致性：系统整体的页面布局，在不同的界面之间，img里的图片的放置位置以及大小都应该有严格的一致性。变量命名规则应该具有统一性。

（5）先进性：本系统采用java作为开发技术、B/C结构和 MySQL作为系统数据库，它们被软件设计者们广泛使用。
## 3.2可行性分析
根据系统所包含其功能的使用情况，通过对经济、技术和管理方式来进行全方面的可行性进行分析，来提供准确的可行性依据。本系统的可行性分析有：

1) 经济可行性

系统采用的是JAVA技术来实现相应的功能的开发，综合就是一个比较基础的系统开发设计，所以所用到的有开源的开发环境所构成。而且可以利用现有的设备，不用进行另外的硬件设备购买。

用户通过使用仓储管理系统，很大程度减小了人员成本，极大提高了管理的效率。目前的由人员管理的方式存在很多不足，首先是人工成本大，并且工作效率比较低，然后是存在着很多信息流失的问题。在结合仓储管理系统的特点，还有一些记录和统计，仓储管理系统杜绝了以上的问题，提高了仓储信息的安全性。

经济可行性是主要计算项目的开发成本，还有项目成功后可能带来的有效收益。很多的项目只有开发成本能控制在企业有可能接受的范围内的情况下，这样的项目才会被批准开发。然而本次系统的开发在上述所有的问题的情况下，是可以完成相关的系统设计。

1) 技术可行性

本管理系统采用JAVA技术和B/S结构进行设计，通过分层分包的方法，有利于日常的维护，同时降低了代码之间的耦合。

1) 管理可行性

本小程序所需要的管理难度低，只需要一个管理员便能进行个人中心、供应商管理、员工管理、商品分类管理、商品信息管理、商品入库管理、商品出库管理、供应商货物管理、货物采购管理、在线沟通管理、系统管理等功能的管理。
## 3.3系统功能分析
系统功能需求包含业务需求、功能需求用户需求，系统功能需求分析是在了解用户习惯、开发人员技术和实力等各个因素的前提下，对其进行深入分析，了解系统基本需求后，基本功能如下：

本课题要求实现优质的仓储管理系统，就一定要包含有前台页面和后端数据库、服务器相联系，从而实现系统的功能运转。系统分为前台员工模块、供应商模块和后台管理员模块三部分；

（1）、员工进入系统可以实现首页、商品信息、供应商货物、我的等功能，在我的页面可以对商品信息、商品入库、商品出库、供应商货物、货物采购、在线沟通、个人中心等进行操作。员工用例如下：

![](/md/blog.008.png)

图3-1 员工用例图

（2）、供应商进入系统可以实现首页、商品信息、供应商货物、我的等功能，在我的页面可以对供应商货物、货物采购、在线沟通、个人中心等进行操作。供应商用例如下：

![](/md/blog.009.png)

图3-2供应商用例图

（3）、管理员主要包括个人中心、、供应商管理、员工管理、商品分类管理、商品信息管理、商品入库管理、商品出库管理、供应商货物管理、货物采购管理、在线沟通管理、系统管理等有关功能进行管理。管理员用例如下：

![](/md/blog.010.png)

图3-3管理员用例图
## 3.4系统流程分析
### 3.4.1登录流程
每个用户都有专属的密码和账号，在输入合法的账号和密码之后即可进入系统。登录流程如图3-4所示：

![登录流程图](/md/blog.011.png)

图3-4登录流程图
### 3.4.2添加信息流程
管理层人员有添加角色功能。添加信息流程如图3-5所示：

![C:\Users\lenovo\AppData\Local\Temp\WeChat Files\da8dfc62fa46238fbebe4d324ba8419.jpg](/md/blog.012.jpeg)

图3-5添加信息流程图
### 3.4.3修改信息流程
管理层人员有修改信息功能。修改信息流程如图3-6所示：

![](/md/blog.013.png)

图3-6修改信息流程图


# 第4章 系统设计
## 4.1系统功能设计
系统的功能设计是整个系统的运行基础，是一个把设计需求替换成以计算机系统的形式表示出来。通过对仓储管理系统的调查、分析和研究，得出了该系统的总体规划，这是开发设计系统的初步核心。如下图所示：

![](/md/blog.014.png)

图4-1总体规划结构图
## 4.2数据库E-R图
关系型数据库是目前使用人数最多的数据库，既是面向对象系统设计，所以它的数据库设计主要是面向对象的。现在主要考虑如何对类进行持久化操作，即如何将对象类映射到关系数据库的二维表。目前可以采用数据库建模工具来实现。

然后根据功能需求来对本系统的e-r图实现分解来得到几种实体—关系模型，以下为部分实体—关系模型。

` `(1) 商品入库实体属性图，如图4-2所示：

![](/md/blog.015.png)图4-2商品入库实体属性图

(2) 商品出库实体属性图，如图4-3所示：

![](/md/blog.016.png)

图4-3商品出库实体属性图

(3) 公告信息实体属性图，如图4-4所示：

![](/md/blog.017.png)

图4-4公告信息实体属性图

(4) 货物盘点实体属性图，如图4-5所示：

![](/md/blog.018.png)

图4-5货物盘点实体属性图

(5) 供应商实体属性图，如图4-6所示：

![](/md/blog.019.png)

图4-6供应商实体属性图
## 4.3数据库表
本系统采用的是MySQL数据库管理数据，系统中使用到的数据表具体展示部分如下所示。

表4-1：商品入库

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|rukubianhao|varchar|200|入库编号|||
|shangpinbianhao|varchar|200|商品编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shangpintupian|longtext|4294967295|商品图片|||
|kucun|int||入库数量|||
|rukudanjia|int||入库单价|||
|rukuzongjia|float||入库总价|||
|rukubeizhu|varchar|200|入库备注|||
|rukuriqi|datetime||入库日期|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||

表4-2：商品分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinfenlei|varchar|200|商品分类|||

表4-3：商品出库

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|chukubianhao|varchar|200|出库编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|kucun|int||出库数量|||
|shangpintupian|longtext|4294967295|商品图片|||
|chukudanjia|int||出库单价|||
|chukujiage|float||出库价格|||
|chukushijian|datetime||出库时间|||
|xiaoshouduixiang|varchar|200|销售对象|||
|beizhu|varchar|200|备注|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||

表4-4：公告信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-5：货物盘点

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|pandianriqi|date||盘点日期|||
|shangpinbianhao|varchar|200|商品编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shengchandi|varchar|200|生产地|||
|shangpinfenlei|varchar|200|商品分类|||
|pandianshuliang|varchar|200|盘点数量|||
|pandianqingkuang|varchar|200|盘点情况|||
|pandianbeizhu|varchar|200|盘点备注|||

表4-6：货物采购

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinfenlei|varchar|200|商品分类|||
|tupian|longtext|4294967295|图片|||
|guige|varchar|200|规格|||
|danjia|float||单价|||
|caigoushuliang|int||采购数量|||
|heji|float||合计|||
|gongyingzhanghao|varchar|200|供应账号|||
|gongyingshang|varchar|200|供应商|||
|gongyingshangshouji|varchar|200|供应商手机|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|yuangongshouji|varchar|200|员工手机|||
|caigoushijian|datetime||采购时间|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-7：供应商货物

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinfenlei|varchar|200|商品分类|||
|tupian|longtext|4294967295|图片|||
|guige|varchar|200|规格|||
|danjia|int||单价|||
|gongyingzhanghao|varchar|200|供应账号|||
|gongyingshang|varchar|200|供应商|||
|gongyingshangshouji|varchar|200|供应商手机|||

表4-8：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-9：供应商

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gongyingzhanghao|varchar|200|供应账号|||
|mima|varchar|200|密码|||
|gongyingshang|varchar|200|供应商|||
|fuzeren|varchar|200|负责人|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|touxiang|longtext|4294967295|头像|||
|gongyingshangshouji|varchar|200|供应商手机|||

表4-10：在线沟通

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinfenlei|varchar|200|商品分类|||
|tupian|longtext|4294967295|图片|||
|guige|varchar|200|规格|||
|gongyingzhanghao|varchar|200|供应账号|||
|gongyingshang|varchar|200|供应商|||
|gongyingshangshouji|varchar|200|供应商手机|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|yuangongshouji|varchar|200|员工手机|||
|zixunshijian|datetime||咨询时间|||
|zixunbiaoti|varchar|200|咨询标题|||
|zixunneirong|longtext|4294967295|咨询内容|||
|shhf|longtext|4294967295|回复内容|||

表4-11：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-12：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-13：员工

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|mima|varchar|200|密码|||
|yuangongxingming|varchar|200|员工姓名|||
|xingbie|varchar|200|性别|||
|nianling|int||年龄|||
|yuangongshouji|varchar|200|员工手机|||
|zhaopian|longtext|4294967295|照片|||

表4-14：关于我们

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|subtitle|varchar|200|副标题|||
|content|longtext|4294967295|内容|||
|picture1|longtext|4294967295|图片1|||
|picture2|longtext|4294967295|图片2|||
|picture3|longtext|4294967295|图片3|||

表4-15：商品信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinbianhao|varchar|200|商品编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shengchandi|varchar|200|生产地|||
|shangpinfenlei|varchar|200|商品分类|||
|kucun|int||库存|||
|shangpintupian|longtext|4294967295|商品图片|||
|shangpinxiangqing|longtext|4294967295|商品详情|||





# 第5章 系统实现
## 5.1小程序前台模块实现
首先双击打开小程序客户端，连上网络之后会显示出本系统的登录界面，这是进入小程序的初始页面“登录”，能成功进入到该登录界面则代表小程序的开启是成功的，接下来就可以操作本系统所带有的其他所有的功能。登录界面如图5-1所示。

![](/md/blog.020.png)

图5-1 登录界面

第一次使用本小程序的使用者，首先是要进行注册，点击“注册”，然后就会进入到注册的页面里面，将员工/供应商信息录入注册表，确认信息正确后，系统才会进入登录界面，员工/供应商登录成功后可使用本小程序所提供的所有功能。员工注册界面如图5-2所示。供应商注册界面如图5-3所示。

![](/md/blog.021.png)

图5-2 员工注册界面

![](/md/blog.022.png)

图5-3供应商注册界面

小程序首页是员工/供应商注册登录后进入的第一个界面，员工/供应商可通过小程序端首页导航栏进入到相应的网页查看信息展示信息进行详细操作。小程序首页界面如图5-4所示。

![](/md/blog.023.png)

图5-4小程序首页界面图
### 5.1.1员工模块实现
员工登录进入系统，点击“我的”，在“我的”页面可以对商品信息、商品入库、商品出库、供应商货物、货物采购、在线沟通、个人中心等功能进行操作；如图5-5所示：

![](/md/blog.024.png)

图5-5员工“我的”界面

员工点击商品信息，在商品信息页面输入商品名称进行搜索，可以查看到商品编号、商品名称、商品分类、库存、生产地和商品详情等信息。如图5-6所示。

![](/md/blog.025.png)

图5-6商品信息详情界面图

员工点击供应商货物，在供应商货物页面输入商品名称进行搜索，可以查看到商品名称、商品分类、单价、供应商、规格、供应账号和供应商手机等信息。如图5-7所示。

![](/md/blog.026.png)

图5-7供应商货物详情界面图
### 5.1.2供应商模块实现
供应商登录进入系统，点击“我的”，在“我的”页面可以对供应商货物、货物采购、在线沟通、个人中心等功能进行操作；如图5-8所示：

![](/md/blog.027.png)

图5-8供应商“我的”界面
## 5.2后台模块实现
后台用户登录，在登录页面正确输入用户名和密码后，进入操作系统进行操作；如图5-9所示。                               

![](/md/blog.028.png)

图5-9后台登录界面
## 5.3管理员模块实现
管理员进入主页面，主要功能包括对个人中心、供应商管理、员工管理、商品分类管理、商品信息管理、商品入库管理、商品出库管理、供应商货物管理、货物采购管理、在线沟通管理、系统管理等进行操作。管理员主界面如图5-10所示：

![](/md/blog.029.png)

图5-10管理员主界面

管理员点击供应商管理。在供应商页面输入供应账号进行查询、新增或删除供应商列表，并根据需要对供应商详情信息进行详情、修改或删除操作；如图5-11所示：

![](/md/blog.030.png)

图5-11供应商管理界面

管理员点击员工管理。在员工页面输入员工工号和员工姓名进行查询、新增或删除员工列表，并根据需要对员工详情信息进行详情、修改或删除操作；如图5-12所示：

![](/md/blog.031.png)

图5-12员工管理界面

管理员点击商品信息管理。在商品信息页面输入商品名称和生产地进行查询、新增或删除商品信息列表，并根据需要对商品详情信息进行详情、修改或删除操作；如图5-13所示：

![](/md/blog.032.png)

图5-13商品信息管理界面

管理员点击商品入库管理。在商品入库页面输入入库编号和商品名称进行查询或删除商品入库列表，并根据需要对商品入库详情信息进行详情、修改或删除操作；如图5-14所示：

![](/md/blog.033.png)

图5-14商品入库管理界面

管理员点击供应商货物管理。在供应商货物页面输入商品名称和选择商品分类进行查询或删除供应商货物列表，并根据需要对供应商货物详情信息进行详情、修改或删除操作；如图5-15所示：

![](/md/blog.034.png)

图5-15供应商货物管理界面

管理员点击在线沟通管理。在在线沟通页面输入商品名称、员工姓名和咨询标题进行查询或删除在线沟通列表，并根据需要对在线沟通详情信息进行回复、详情、修改或删除操作；如图5-16所示：

![](/md/blog.035.png)

图5-16在线沟通管理界面

管理员点击系统管理。在公告信息页面输入标题进行查询、新增或删除公告信息列表，并根据需要对公告详情信息进行详情、修改或删除操作；还可以对关于我们、系统简介和轮播图管理进行详细操作；如图5-17所示：

![](/md/blog.036.png)

图5-17系统管理界面



第6章系统测试

在系统开发上市前都需要经过严格的系统测试。主要测试访问请求的延迟时间，对于一些未知和危险的问题，需要严格的测试和解决方案。
# 










