# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0647springboot大学生体质测试管理系统--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=4)


﻿
**本科生毕业设计**



**大学生体质测试管理系统**





![](/md/blog.001.png)学生姓名 

![](/md/blog.002.png)学    号 

![](/md/blog.003.png)指导教师 

![](/md/blog.004.png)所在学院 

![](/md/blog.005.png)专业名称 

![](/md/blog.006.png)班    级 
**


**摘要**

大学生体质测试管理系统提供给用户一个简单方便体质测试管理信息，通过留言区互动更方便。本系统采用了B/S体系的结构，使用了java技术以及MYSQL作为后台数据库进行开发。系统主要分为系统管理员、教师和用户三个部分，系统管理员主要功能包括首页、个人中心、用户管理、教师管理、体质测试管理、测试报告管理、测试成绩管理、留言板、系统管理；基本上实现了整个大学生体质测试管理系统信息管理的过程。

**关键词：**大学生体质测试管理系统； java技术；MYSQL数据库；

**Abstract**

College students physique test management system provides users with a simple and convenient physique test management information, more convenient interaction through the message area. This system adopts the STRUCTURE of B/S system, using Java technology and MYSQL as the background database for development. The system is mainly divided into three parts: system administrator, teacher and user. The main functions of system administrator include home page, personal center, user management, teacher management, physical test management, test report management, test result management, message board, system management; Basically realized the entire college students physical test management system information management process.

**Key words:** college students physical test management system; Java technology; MYSQL database;






# **目录**
[目录	1](#_Toc98330750)

[1 绪 论	2](#_Toc98330751)

[1.1系统背景介绍	2](#_Toc98330752)

[1.2课题研究的目的和意义	2](#_Toc98330753)

[1.3系统的研究现状	2](#_Toc98330754)

[1.4系统实现的功能	3](#_Toc98330755)

[1.5系统的特点	3](#_Toc98330756)

[2 开发工具和技术	4](#_Toc98330757)

[2.1 B/S体系结构	4](#_Toc98330758)

[2.2 Java语言简介	4](#_Toc98330759)

[2.3 SpringBoot框架	5](#_Toc98330760)

[2.4 MySQL简介	5](#_Toc98330761)

[3 系统需求分析	5](#_Toc98330762)

[3.1 系统可行性分析及目的	5](#_Toc98330763)

[3.1.1 系统设计目的	5](#_Toc98330764)

[3.1.2 技术可行性	5](#_Toc98330765)

[3.1.3 操作可行性	5](#_Toc98330766)

[3.1.4 运行可行性	5](#_Toc98330767)

[3.1.5 时间可行性	6](#_Toc98330768)

[3.2 性能需求分析	6](#_Toc98330769)

[3.3系统功能需求	6](#_Toc98330770)

[3.4系统流程分析	7](#_Toc98330771)

[3.4.1操作流程	7](#_Toc98330772)

[3.4.2添加信息流程	7](#_Toc98330773)

[3.4.3删除信息流程	8](#_Toc98330774)

[4  系统总体设计	9](#_Toc98330775)

[4.1 系统体系结构	9](#_Toc98330776)

[4.2数据库设计	10](#_Toc98330777)

[4.2.1 数据库概念结构设计	10](#_Toc98330778)

[4.2.2数据库逻辑结构设计	11](#_Toc98330779)

[5 系统详细设计	17](#_Toc98330780)

[5.1系统功能模块	17](#_Toc98330781)

[5.2管理员功能模块	18](#_Toc98330782)

[5.3用户功能模块	22](#_Toc98330783)

[5.3教师功能模块	23](#_Toc98330784)

[6 系统测试	26](#_Toc98330785)

[总 结	27](#_Toc98330786)

[参考文献	28](#_Toc98330787)

[致 谢	29](#_Toc98330788)


























# **1 绪 论**
## **1.1系统背景介绍**
近几年来,网络事业，特别是Internet发展速度之快是任何人都始料不及的。目前，由于Internet表现出来的便捷，快速等诸多优势，已经使它成为社会各行各业，甚至是平民大众工作，生活不可缺少的一个重要组成部分。

随着社会的发展线下管理的方式已经不可避免的显示出它在时间与空间等方面的局限性，广大的人民群众迫切的需要打破这种局限性。在这种要求下，大学生体质测试管理系统产生了。它的出现不但解决了传统管理方式的缺点，而且给了广大用户更大的选择空间，促进了大学生体质测试信息的优化管理，有效的避免了大学生体质测试的管理缭乱的局面。所以像大学生体质测试管理系统这种电子商务的发展壮大也是不可避免的。

大学生体质测试管理系统作为一种典型的办公系统也迅速的发展并深入人们的日常生活中，它使用户足不出户就可以管理自己的大学生体质测试的测试信息等，最大化减缩了用户的管理时间，提高了管理效率。
## **1.2课题研究的目的和意义**
人们现在的生活方式因为网络的普及发生了巨大变化，由于网络管理在人们的视野中出现,人们对网络管理额外的关注。人们只要在有网络的地方足不出户查看到世界各地的各类。目前的挑战是前台界面的设计，要把顾客的眼球吸引住，选则比较人性化的界面设计，要更直观的表现，让用户能更多的了解大学生体质测试管理系统的作用和功效。

本系统的主要意义在于，全力以赴为用户提供一个操作方便，界面简洁，信息直观的大学生体质测试管理系统。使用该系统的用户，可以先浏览到公司介绍,产品信息，并可以注册成为本网站的用户。
## **1.3系统的研究现状**
现如今用户大多也改用网站平台的形式来管理信息动态，传统的信息交流时代正慢慢离我们远去。大学生体质测试管理系统采用了一些平台软件来管理公司，但是如何让我们的管理效率更高呢？

网络时代成为大学生体质测试管理系统的大势所趋，因为我们国家的互联网相比外国的起步晚了一点，因此我们国家的大学生体质测试的办公管理网站做的也不早。但是在现实的需求与IT人才辛苦的设计后，网站类大学生体质测试管理系统发展的速度很快，各种功能也做的尽善尽美。
## **1.4系统实现的功能**
本次设计任务是要设计一个大学生体质测试管理系统，通过这个系统能够满足大学生体质测试管理系统功能。系统的主要功能包括首页、个人中心、用户管理、教师管理、体质测试管理、测试报告管理、测试成绩管理、留言板、系统管理等功能。

管理员可以根据系统给定的账号进行登录，登录后可以进入大学生体质测试管理系统对大学生体质测试所有模块进行管理。包括查看和修改自己的个人信息以及登录密码，用户信息等。

该系统为每一个用户都分配了一个用户账号，用户通过账号的登录可以在系统中查看大学生体质测试信息及对个人信息进行修改等功能。
## **1.5系统的特点**
大学生体质测试管理系统充分利用网络技术和网络信息资源，提高阅读效率，和平常的一些网络系统比较，更注重大学生体质测试的办公动态这一个重要环节。大学生体质测试管理系统研究与设计主要表现出内容方式丰富、方便用户互动交流功能齐全等方面的特点。
# **2 开发工具和技术**
## **2.1 B/S体系结构**
B/S的系统是通过能上网的电脑就可以使用，它最大的优点是不需要安装专门的软件，首先浏览器向服务器发出请求，然后服务器处理请求把信息再返回给浏览器。不需要再次对数据进行存取与计算数据，只要负责显示数据来降低要求，如果说客户端像个“瘦子”，而服务器会越来越“胖”。B/S体系结构与C/S体系结构相比，最大的不同是：B/S体系的应用软件使用网络浏览器作为与用户交互的平台，而C/S则需要开发专用的应用程序。

![2009318052962238](/md/blog.007.png)

图2-1 B/S结构图
## **2.2 Java语言简介**
Java是由SUN公司推出，该公司于2010年被oracle公司收购。Java本是印度尼西亚的一个叫做爪洼岛的英文名称，也因此得来java是一杯正冒着热气咖啡的标识。Java语言在移动互联网的大背景下具备了显著的优势和广阔的前景，它是面向对象的，分布式的，动态的，具有平台无关性、安全性、健壮性。Java语言的基本语句语法和C++一样，但是它面向对象的技术更加彻底，因为Java要求将所有的内容都必须封装成类，把类作为程序的基本单位。由于不允许类外有变量、方法。 Java语言的分布式体现在数据分布和操作分布，它是面向网络的语言，可以处理TCP/IP协议，它也支持客户机/服务器的计算模式。Java语言的动态性是指类在运行时是动态安装的，使得Java可以动态的维护程序。Java不支持指针，对内存访问的所有操作都是通过对象实例化实现的，这样就避免了指针操作中易产生的错误，同时也预防了病毒对系统的破坏和威胁。

Java语言的编程风格与C语言非常接近，它继承了C++面向对象技术的核心，它面世之后发展迅速，非常流行，对高级C语言形成了很大的冲击。业内人士称之为“一次编译、到处执行”。当然java也有缺点，在每次执行编译后，字节码都需要消耗一定的时间，在某些程度上降低了性能。但是这并不影响java成为此次设计语言的选择。Java语言简单易学，使用它的编程时间短，功能性强，开发者学习起来更简便、更快。Java的主要特性有以下几个：

1.面向对象

面向对象有四个特点：封装、继承、多态、抽象。抽象是指忽略一个问题中的次要部分，关注主要部分。多态是指对同一种消息做出的不同反应。继承是指在原有的父类方法基础上增加自己独有的方法，而不改变原来父类。

2.平台无关性、

Java编译出来的是字节码，直接由虚拟机执行。在任何平台上，只要有Java虚拟机，Java代码都能运行。

3.可靠性和安全性

Java对内存的访问都必须通过对象的实例变量来实现，避免了指针中出现的错误。

\4. 多线程	

Java提供了多线程功能，利用编程实现同一时间同时工作的功能。
## **2.3 SpringBoot框架**
SpringBoot是一个全新开源的轻量级框架。基于Spring4.0设计，其不仅继承了Spring框架原来有的优秀特性，而且还通过简化配置文件来进一步简化了Spring应用的整个搭建以及开发过程。另外在原本的Spring中由于随着项目的扩大导入的jar包数量越来越大，随之出现了jar包版本之间的兼容性问题，而此时SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性问题得到了很好的解决。

SpringBoot可以看做是Spring的加强版本，但实质上都是Spring的相关技术，有了这些优秀的开源框架，程序员在开发过程中将事半功倍。
## **2.4 MySQL简介**
数据库(Database)是按照数据结构来组织、存储和管理数据的建立在计算机存储设备上的仓库。简单来讲，存储粮食的仓库叫粮仓存储数据的仓库就叫数据库。数据库在软件项目中扮演着操作管理数据的角色同时还能够保证数据的独立性、一致性和安全性，并为系统访问数据提供有效方式不仅如此数据库还能大大减少程序员开发程序时间。在日常能够接触实用的一般有两类数据库，一类是以(Oracle，DB2，SQL Server，MySQL )为代表的关系型数据库和以(NoSql、MongeDB)为代表的非关系型数据库，两类数据库各有各的优缺点。其中非关系型数据库又分为网络数据库和层级数据库。-网络数据库是指在计算机网络系统中应用数据库技术然后借助网络技术将存储于数据库中的大量信息及时发布出去；在成熟的数据库技术的帮助下，计算机网络实现了对网络中的各种数据的有效管理，用户与网络中的数据库数据交互也借此得以进行。作为最成功的典型层次模型数据库系统，IMS是最早研制成功的数据库系统。1970年由埃德加·科德于首先提出的关系模型融合了“科德十二定律”。现如今即使很多人仍旧不看好这个模型，但它依旧是数据存储的传统标准。关系数据结构、关系操作集合、关系完整性约束构成了关系模型。作为数据库另外一种区分方式的存储介质被大家分为磁盘和内存这 两种。例如：关系型数据库就存储在磁盘中，非关系型数据库则存储在内存中。典型的关系型数据库有：Oracle、DB2、Microsoft SQL Server、Microsoft Access、MySQL、SQLite。小型关系型数据库：Microsoft Access，SQLite；中型关系型数据库：SQL Server，Mysql；大型关系型数据库：Oracle，DB2。

大家常用的其他关系形数据库系统大多是MySQL AB公司开发的，其中MySQL也是由这家开发的，所应用的分布式数据库管理系统是客户机/服务器体系结构得益于此结构，而且用这个系统建造的数据库具有很强的适用性，用C和C++编写的系统让他拥有很强的适用性所以他可以在大部分操作系统上使用并能和php结合。不同的API函数针对不同的语言(C,C++,JAVA等)来处理不同数据；为了更好地支持多CPU多线程通过使用核心线程来实现；提供的存储机制分为事务和非事务存储机制；MySQL采用双重许可，不管是从MySQL AB公司获得正式的商业许可又或是许可条款下以免费软件或开放源码软件的方式使用MySQL软件都是被允许的。

MySQL作为数据库拥有很多优点，其中由于是开放源码，所以使用成本特别低，而它体积小的特点决定了速度快的特性。因此，My Sql具有开放性，多线程支持多种API，可跨数据库连接，国际化，数据库体积巨大等特点。简单的来说 ，MySql是一个开放的、快速的、多线程的、多用户的数据库服务器。

选用MySQL作为数据库的其中一个原因就是支持多线程，支持多线程的特点为利用系统资源提供了便捷并因此大大提高了系统运行速度和效率，而且连接数据库的方式多样包括但不局限于TCP/IP、ODBC和JDBC等途径；但是没有东西是完美无缺的，即便MySQL也如此，虽说它有着众多优点但其功能不够强大，规模也相对较小，无法应对大型数据哭的处理。但是对于本系统来说，选用MySQL作为数据库，其功能性能已绰绰有余，如果要进行二次开发的数据库表结构空间的扩展也是完全可行的。综上所述，MySQL是作为本系统数据库的最优选择。

![](/md/blog.008.png)

图2-2 数据库管理系统和接口的原理

#
# **3 系统需求分析**
#

## **3.1 系统可行性分析及目的**
### 3.1.1 系统设计目的
如今我们已经越来越离不开互联网给我们带来的生活便利，希望大学生体质测试管理系统也能通过活泼、清新的界面给用户提供简单的与互动的网站。方便用户在平时利用有限的时间对测试信息进行查看，对个人中心、用户管理、教师管理、体质测试管理、测试报告管理、测试成绩管理等信息进行操作。
### 3.1.2 技术可行性
本系统开发选择java技术，它被研究的目的就是在于能够为网页创建等可以看到的信息。随着移动互联网技术的不断发展和创新，java俨然已成为下一代互联网的Web标准。所以设计选择使用MYSQL,数据库主要用来的建立和维护信息。对于前台开发要求应具备功能完善、易于操作等优点，后台数据库的要求则是能够建立和维护数据信息的统一性和完整性。
### 3.1.3 操作可行性
现在随着科技的飞速发展，计算机早已经进入了人们的日常生活中，人们的工作环境也不像以前有那么多的要求，需要用户一定要到公司办公，有的工作在家也可以完成。这使得人们的工作效益有了很大的提高。操作的多样性也变高了。因此，管理的计算机化，智能化是社会发展而带来的必然趋势，各种智能的软件层出不穷，不同的软件能完成用户不同的需求，这不仅提高了工作效率还能完成一些客户特定的一些需求。本系统不仅界面简洁明了还采用可视化界面，用户只要用鼠标和键盘就可以完成对相关信息的修改，删除，添加等操作。因为这个系统的操作十分简单，方便上手，对于第一次使用系统的人，只需要很少的时间就可以上手操作。由此可见，本系统在操作上是可行的。
### 3.1.4 运行可行性
本系统作为以java作为开发语言的系统，而且选用B/S结构则决定了要操作本系统仅需要占用很小的资源，并没有过多地硬件配置要求，目前市面上只要能正常运行浏览器的个人电脑都可以正常运行使用该系统。
### 3.1.5 时间可行性
从时间上看，在大四的最后一个学期，在实习工作与完成毕设两件大事相交叉的时间里，结合之前学习的相关知识，并开发系统，时间上是有点紧，但是也不是完全没可能实现，通过这段时间的努力功能基本实现。

经过总结，本系统在操作方面、技术方面、运行方面和时间方面的条件都得以满足，为此系统的开发具备了可行性条件。

## **3.2 性能需求分析**
对系统的性能，从（功能、运行、界面、安全）等方面进行，下面我们逐一进行分析；

\1. 系统的功能是否完整进行分析：系统的功能，能对应设计出原始代码和算法，以表格同文字的形式进行详细介绍个人信息保证功能完整；

\2. 系统的运行是否通畅进行分析：系统的每个功能都有编写数据的关系和应对的代码，通过需求分析和可行性分析进行分析和显示系统的物理数据，保证其进行通畅；

\3. 系统的界面设计进行分析：对系统中的软件进行处理与分析的方式是由不同代码来进行的；从而使界面容易操作。

\4. 系统的安全性进行分析：这样才可以每个角色的不同对应的信息也就不同，在登录系统务必使用自己的账号，密码登录，账号与密码错误自然就登录失败了。登录成功可以对自己的信息进行操作，不能对别人的账号的信息进行查看等操作，这样自然保证系统的安全性。
## **3.3系统功能需求**
功能需求分析的任务是通过详细调查大学生体质测试的测试信息管理系统要处理的所有对象，通过充分了解大学生体质测试管理系统的工作流程，明确使用者的各种需求，充分思考之后可能扩充和改变的情况，然后在这个基础上来设计数据库。
## **3.4系统流程分析**
### 3.4.1操作流程
系统登录流程图，如图所示：

![](/md/blog.009.png)

图3-1登录流程图
### 3.4.2添加信息流程
添加信息流程图，如图所示：

![](/md/blog.010.png)

图3-2添加信息流程图
### 3.4.3删除信息流程
删除信息流程图，如图所示：

![](/md/blog.011.png)

图3-3删除信息流程图



# **4  系统总体设计**
## **4.1 系统体系结构**
大学生体质测试管理系统的结构图4-1所示：

网

络

管理员

服务器和程序

用户

教师

![](/md/blog.012.png)

图4-1 系统结构

模块包括首页、个人中心、用户管理、教师管理、体质测试管理、测试报告管理、测试成绩管理、留言板、系统管理等进行相应的操作。

登录系统结构图，如图4-2所示：

大学生体质测试的办公管理系统登录

用户登录

密码正确

管理员界面

用户界面

教师界面

![](/md/blog.013.png)

图4-2 登录结构图

这些功能可以充分满足大学生体质测试管理系统的需求。此系统功能较为全面如下图系统功能结构如图4-3所示。

![](/md/blog.014.png)

图4-3系统功能结构图
## **4.2数据库设计**
本系统使用MYSQL 作为系统的数据库，设计用户注册表、文件上传的表等等。
### 4.2.1 数据库概念结构设计
概念结构设计是根据用户需求形成的。用最常的E-R方法描述数据模型进行数据库的概念设计，首先设计局部的E-R模式，最后各局部ER模式综合成一个全局模式。然后再把概念模式转换成逻辑模式。将概念设计从设计过程中独立开来，设计复杂程度降低，不受特定DBMS的限制。

1.所有实体和属性的定义如下所示。

体质测试实体属性图如图4-4所示。

![](/md/blog.015.png)

图4-4体质测试实体属性图

个人中心实体属性图如图4-5所示。

![](/md/blog.016.png)

图4-5个人中心实体属性图
### 4.2.2数据库逻辑结构设计
根据E-R得出数据库包涵了以下几张数据表来实现了对数据库的存储、调用。以下分别列出数据表的每个字段名、数据类型、主外键及备注。

表4-1：token表

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

表4-2：体质测试

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|ceshibianhao|varchar|200|测试编号|||
|ceshimingcheng|varchar|200|测试名称|||
|ceshiwenjian|varchar|200|测试文件|||
|tupian|varchar|200|图片|||
|faburiqi|datetime||发布日期|||
|ceshishuoming|longtext|4294967295|测试说明|||
|ceshineirong|longtext|4294967295|测试内容|||
|jiaoshigonghao|varchar|200|教师工号|||
|jiaoshixingming|varchar|200|教师姓名|||

表4-3：公告资讯

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||

表4-4：留言板

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||留言人id|||
|username|varchar|200|用户名|||
|content|longtext|4294967295|留言内容|||
|cpicture|varchar|200|留言图片|||
|reply|longtext|4294967295|回复内容|||
|rpicture|varchar|200|回复图片|||

表4-5：教师

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jiaoshigonghao|varchar|200|教师工号|||
|mima|varchar|200|密码|||
|jiaoshixingming|varchar|200|教师姓名|||
|xingbie|varchar|200|性别|||
|zhicheng|varchar|200|职称|||
|lianxidianhua|varchar|200|联系电话|||
|touxiang|varchar|200|头像|||

表4-6：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||
表4-7：测试成绩

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|ceshibianhao|varchar|200|测试编号|||
|ceshimingcheng|varchar|200|测试名称|||
|jiaoshigonghao|varchar|200|教师工号|||
|jiaoshixingming|varchar|200|教师姓名|||
|ceshipingfen|int||测试评分|||
|ceshipingji|varchar|200|测试评级|||
|pingfenshijian|date||评分时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|banji|varchar|200|班级|||
|ceshipingjia|longtext|4294967295|测试评价|||


表4-8：测试报告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|ceshibianhao|varchar|200|测试编号|||
|ceshimingcheng|varchar|200|测试名称|||
|jiaoshigonghao|varchar|200|教师工号|||
|jiaoshixingming|varchar|200|教师姓名|||
|baogaowenjian|varchar|200|报告文件|||
|tijiaoriqi|date||提交日期|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|banji|varchar|200|班级|||
|beizhu|longtext|4294967295|备注|||

表4-9：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|xingbie|varchar|200|性别|||
|banji|varchar|200|班级|||
|lianxifangshi|varchar|200|联系方式|||
|touxiang|varchar|200|头像|||

表4-10：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

















# **5 系统详细设计**
## **5.1系统功能模块**
大学生体质测试管理系统，在系统首页可以查看首页、体质测试、公告资讯、留言板、个人中心、后台管理等内容进行详细操作，如图5-1所示。

![](/md/blog.017.png)

图5-1系统首页界面图

体质测试，在体质测试页面可以查看测试名称、测试编号、测试说明、测试文件、发布日期、教师工号等内容进行测试等操作，如图5-2所示。

![](/md/blog.018.png)

图5-2体质测试界面图

用户注册，通过填写用户账号、密码、确认密码、用户姓名、班级、联系方式等内容进行注册等操作，如图5-3所示。

![](/md/blog.019.png)

图5-3用户注册界面图

个人中心，在个人中心页面通过填写用户账号、密码、用户姓名、性别、班级、联系方式、图片等内容进行更新信息等操作；如图5-4所示。

![](/md/blog.020.png)

图5-4个人中心界面图

## **5.2管理员功能模块**
管理员登录，管理员通过输入用户，密码，选择角色等信息进行系统登录，如图5-5所示。

![](/md/blog.021.png)

图5-5管理员登录界面图

管理员登录进入大学生体质测试管理系统可以查看首页、个人中心、用户管理、教师管理、体质测试管理、测试报告管理、测试成绩管理、留言板、系统管理等内容进行详细操作，如图5-6所示。

![](/md/blog.022.png)

图5-6管理员功能界面图

用户管理，在用户管理页面可以对索引、用户账号、用户姓名、性别、班级、联系方式、头像等内容详情、修改或删除等操作，如图5-7所示。

![](/md/blog.023.png)

图5-7用户管理界面图

体质测试管理，在体质测试管理页面可以对索引、测试编号、测试名称、测试文件、图片、发布日期、教师工号、教师姓名等内容进行详情、修改或删除等操作，如图5-8所示。

![](/md/blog.024.png)

图5-8体质测试管理界面图

教师管理，在教师管理页面可以对教师工号、教师姓名、性别、职称、联系电话、头像等内容进行详情、修改或删除等操作，如图5-9所示。

![](/md/blog.025.png)

图5-9教师管理界面图

测试报告管理，在测试报告管理页面可以对索引、测试编号、测试名称、教师工号、教师姓名、报告文件、提交日期、用户账号、用户姓名、班级等内容进行详情、修改或删除等详细的操作，如图5-10所示。

![](/md/blog.026.png)

图5-10测试报告管理界面图

测试成绩管理，在测试成绩管理页面可以对索引、测试编号、、测试名称、教师工号、教师姓名、测试评分、测试评级、评分时间、用户账号、用户姓名、班级等内容进行详情、修改或删除等详细的操作，如图5-11所示。

![](/md/blog.027.png)

图5-11测试成绩管理界面图

留言板，在留言板页面可以对索引、用户名、留言内容、留言图片、回复内容、回复图片等内容进行详情、修改、回复或删除等操作，如图5-12所示。

![](/md/blog.028.png)

图5-12留言板界面图

系统管理，在公告资讯页面中可以对索引、标题、图片等内容进行详情、修改或删除等操作，也可以对轮播图管理进行相应的操作，如图5-13所示。

![](/md/blog.029.png)

图5-13系统管理界面图

## **5.3用户功能模块**
用户进入大学生体质测试管理系统可以查看首页、个人中心、测试报告管理、测试成绩管理等内容进行详细操作，如图5-14所示。

![](/md/blog.030.png)

图5-14用户功能界面图

测试报告管理，在测试报告管理页面中可以对索引、测试编号、测试名称、教师工号、教师姓名、报告文件、提交日期、用户账号、用户姓名、班级等内容进行详情或删除等详细的操作，如图5-15所示。

![](/md/blog.031.png)

图5-15测试报告管理界面图

## **5.3教师功能模块**
教师注册，通过填写教师工号、密码、确认密码、教师姓名、职称、联系电话等内容进行注册，如图5-16所示。

![](/md/blog.032.png)

图5-16教师注册界面图


进入教师页面中可以查看首页、个人中心、体质测试管理、测试报告管理、测试成绩管理等内容进行相应的操作，如图5-17所示。

![](/md/blog.033.png)

图5-17教师功能界面图

体质测试管理，在体质测试管理页面中可以对索引、测试编号、测试名称、测试文件、图片、发布日期、教师工号、教师姓名等内容进行详细等操作，如图5-18所示。

![](/md/blog.034.png)

图5-18体质测试管理界面图

测试报告管理，在测试报告管理页面中可以对索引、测试编号、测试名称、教师工号、教师姓名、报告文件、提交日期、用户账号、用户姓名、班级等内容进行详细等操作，如图5-19所示。

![](/md/blog.035.png)

图5-19测试报告管理界面图














# **6 系统测试**

测试软件系统的过程就是通过自动的手段或者使用人工方法的过程，测试是为了尽可能的少发生错误，但是过程就是要创造一些条件，让错误发生就能及早的修改完善系统。是提高系统软件质量和可靠性的有效手段。

系统测试有两大类分别是静态测试与动态测试，黑盒与白盒测试根据用例方法的不同是属于动态测试类的。最考验细心度的静态测试不依靠计算机运行，需要人工检测代码、静态结构分析。现在通过运行程序发现错误一般的测试大多是动态测试。黑盒测试也叫功能测试。把程序当成一个看不见里面是什么的黑盒子，不管程序如何都放入测试只是了解输入与输出间的关系，黑盒测试也算是根据程序的功能说明来设计测试用例的。白盒测试就把软件当成透明的盒子，也是非常复杂的一个测试方法。

本系统使用功能测试运行程序，模拟用户输入相应的测试用例，检查预期结果与实际结果的差异，判定实际结果是否满足需求设计。

# **总 结**
四个多月的毕业设计，最终完成了大学生体质测试管理系统。网站的功能勉强达到了最初设想的结果，完成了最简单的需求。系统界面虽然看起来有些多，但都是简单的功能页面，用户操作容易上手能完成。感觉第一次独自设计一个网站是从头再学习的过程，在此期间也巩固了所学的书本知识。

在界面上运用了自己熟练的软件设计首页的图片，颜色采用统一的色调让整体看起来更加整洁，拍摄的背景显得格外清新。后台采用了三种活泼的亮色调，CSS简单统一背景及字体颜色。

在这次大学生体质测试管理系统的设计过程中有一些还没有解决的地方。首先要设计网站就要明确目标，理清大体的思路。对于我而言还是较有难度的，俗话说万事开头难。第一步总是最关键的，花了一个月的时间在图书馆里寻找相关的书籍、在网上浏览一些大学生体质测试的测试信息类的网站。有些功能还不完善。


# **参考文献**
[1]孔波,邹有,卢红兵,杨华武,庹苏行.基于Web的色质数据解析平台设计与开发[J].计算机技术与发展,2019,29(12):198-204.

[2]闫朝阳.基于Web的大数据分析平台交互设计研究[J].设计,2019,32(17):94-97.

[3]胡念祖,林晓焕,肖新帅.基于嵌入式Web服务器的远程温度采集系统设计[J].舰船电子工程,2019,39(09):113-117+182.

[4]谭卫,阳晓霞.基于移动Web技术的高校思想品德教育工作评价系统设计与研究[J].信息与电脑(理论版),2019(15):101-104.

[5]宋丽芳.网站建设中网页设计的安全缺陷及对策分析[J].信息通信,2019(08):113-114.

[6]吴城.跨境电商网站系统的设计与分析[J].商场现代化,2019(15):37-38.

[7]蔡振海,张静.基于python的网络爬虫系统的设计与实现[J].电脑知识与技术,2019,15(23):36-37.

[8]黄绍涵.“HZD”校友圈社交网站设计与开发研究——就业模块设计[J].电声技术,2019,43(08):29-32.

[9]李翔宇.基于Web前端开发技术的儿童教育网站设计与实现[J].中国新通信,2019,21(15):196.

[10]曾婷,凌财进.基于HTML5的计算机一级考试模拟Web APP的设计与实现[J].办公自动化,2019,24(15):60-62.

[11]王立强.HTML5:电商网站设计与实现[J].营销界,2019(30):152-157.

[12]黄安.基于PHP+Mysql技术的网站设计与实现——以美食网站系统的设计为例[J].轻纺工业与技术,2019,48(07):168-170.

[13]张欢.服务类网站设计与经营模式的实例研究[J].科技经济导刊,2019,27(21):207+197.

[14]王瑞,徐方晨.开放共享实验室的Web平台设计与实现[J].工业控制计算机,2019,32(07):120-122.

[15]苏思雨,陈汝倩.长白山体验式旅游日文网站的设计与建设[J].数字技术与应用,2019,37(07):139-140.

[16]NastitiAndini,DaehaKim,JongAhnChun.Operationalsoilmoisturemodelingusingamulti-stageapproachbasedonthegeneralizedcomplementaryprinciple[J].AgriculturalWaterManagement,2020,231.

[17]A.D.Titisari,D.Phillips,I.W.Warmada,Hartono,A.Idrus.40Ar/39ArgeochronologyofthePongkorlowsulfidationepithermalgoldmineralisation,WestJava,Indonesia[J].OreGeologyReviews,2020,119.

[18]FranciscoOrtin,OscarRodriguez-Prieto,NicolasPascual,MiguelGarcia.HeterogeneoustreestructureclassificationtolabelJavaprogrammersaccordingtotheirexpertiselevel[J].FutureGenerationComputerSystems,2020,105.





# **致 谢**
在有限的几个月里，从一开始的不知所措到现在把毕业论文与设计写完。这要感谢我的导师给我的帮助。由于我的实习工作把设计网站的时间排到了周一到周五的晚上以及周末，也给老师的周末增加了工作量，然而老师还能在网上给我一些远程的指导以及一些建议，心里十分感激。老师性格开朗、为人也十分平易近人。想起四月份那会儿我错过了交中期报告的时间，老师遇到我笑嘻嘻提醒我：“是不是忘了什么没有交呀？”。当时我就红着脸非常不好意思，其中有点不会写中期报告的原因，更多的是自己的拖延症毛病又犯了。最后在老师细心疏导下才把报告通过了检测。老师后来又多次提醒我注意毕业设计的进度，最好可以面对面沟通这样对我更有帮助。由于我的专业水平不是很好，遇到很多问题请教了老师。毕业设计可以勉强完成，在此表示深深地谢意。

同时，在即将结束的大学生活中，也得到了很多同学的协助，即使他们也有很重要的毕业设计在完善中，但是对我的疑问总是有求必应。他们在我做毕业设计的这些日子里表现出的热情与悉心的指导，让我很感动。

最后，也向在百忙之中抽出时间对本人的论文进行审阅、评议和参加论文答辩的老师们表示由衷的感谢！

#












