# 关注秀才！学习最热门web3技术！学习方向不迷路！
**视频都在抖音上,搜索@跟着秀才学编程，进入java学go语言双向就业合集观看学习！**
【超全golang面试题合集+golang学习指南+golang知识图谱+成长路线】
一份涵盖大部分golang程序员所需要掌握的核心知识。

后续文章和内容会不断更新到 github项目 中，欢迎关注。
**大家好，我是秀才。大家知道，我一直以来都是golang的忠实粉丝，**
**在学习和参与面试的过程中遇到过很多golang的问题。**
**最近花了些时间整理了一下后端程序员成长路线和高频面试题，**
**这是一份涵盖大部分后端程序员所需要掌握的核心知识。**

最后
不满足于看八股文，可以尝试拿着岗位要求来进行ai押题。押题宝
**基础不牢，缺乏实战项目，想快速成为中大厂Go/Java工程师？秀才web3+go训练营了解一下。**
**秀才web3+go训练营介绍文档**

## 基础入门
### 新手

### Golang开发新手常犯的50个错误
#### 数据类型
连nil切片和空切片一不一样都不清楚？那BAT面试官只好让你回去等通知了。
golang面试题：字符串转成byte数组，会发生内存拷贝吗？
golang面试题：翻转含有中文、数字、英文字母的字符串
golang面试题：拷贝大切片一定比小切片代价大吗？
map不初始化使用会怎么样
map不初始化长度和初始化长度的区别
map承载多大，大了怎么办
map的iterator是否安全？能不能一边delete一边遍历？
字符串不能改，那转成数组能改吗，怎么改
怎么判断一个数组是否已经排序
普通map如何不用锁解决协程安全问题
array和slice的区别
golang面试题：json包变量不加tag会怎么样？
golang面试题：reflect（反射包）如何获取字段tag？为什么json包不能导出私有变量的tag？
零切片、空切片、nil切片是什么
slice深拷贝和浅拷贝
map触发扩容的时机，满足什么条件时扩容？
map扩容策略是什么
自定义类型切片转字节切片和字节切片转回自动以类型切片
make和new什么区别
slice ，map，chanel创建的时候的几个参数什么含义
slice，len，cap，共享，扩容
线程安全的map怎么实现
go slice 和 array 区别
go struct能不能比较？
map如何顺序读取？
go中怎么实现set
map 的扩容机制是什么？
使用值为 nil 的 sice、map 会发生什么？
Golang 有没有 this 指针？
Golang 语言中局部变量和全局变量的缺省值是什么
Golang 中的引用类型包含哪些?
使用range 迭代 map 是有序的吗?
slice 的扩容机制是什么？
Golang 中指针运算有哪些?
类型的值可以修改吗？
解析 JSON 数据时，默认将数值当做哪种类型
array 类型的值作为函数参数是引用传递还是值传递？
#### 流程控制
昨天那个在for循环里append元素的同事，今天还在么？
golang面试官：for select时，如果通道已经关闭会怎么样？如果只有一个case呢？
go defer（for defer）
select可以用于什么？
context包的用途？
select 可以用于实现哪些功能？
在循杯内执行 defer 语句会发生什么?
switch 中如何强制执行下一个 case 代码块?
如何从 panic 中恢复?

## 进阶

### 包管理
学go mod就够了！

### 优化
golang面试题：怎么避免内存逃逸？
golang面试题：简单聊聊内存逃逸？
给大家丢脸了，用了三年golang，我还是没答对这道内存泄漏题
内存碎片化问题
chan相关的goroutine泄露的问题
string相关的goroutine泄露的问题
你一定会遇到的内存回收策略导致的疑似内存泄漏的问题
sync.Pool的适用场景
go1.13sync.Pool对比go1.12版本优化点

### 并发编程
golang面试题：对已经关闭的的chan进行读写，会怎么样？为什么？
golang面试题：对未初始化的的chan进行读写，会怎么样？为什么？
sync.map 的优缺点和使用场景
sync.Map的优化点
主协程如何等其余协程完再操作
有缓存的channel和没有缓存的channel区别是什么？
协程通信方式有哪些？
channel底层实现
读写锁底层是怎么实现的？
请你说说golang的CSP思想
channel 是怎么保证线程安全？

### 高级特性
golang面试题：能说说uintptr和unsafe.Pointer的区别吗？
golang 面试题：reflect（反射包）如何获取字段 tag？为什么 json 包不能导出私有变量的 tag？
协程和线程的差别
垃圾回收的过程是怎么样的？
什么是写屏障、混合写屏障，如何实现？
开源库里会有一些类似下面这种奇怪的用法：var _ io.Writer = (*myWriter)(nil)，是为什么？

GMP模型
动图图解，GMP里为什么要有P
协程之间是怎么调度的
gc的stw是怎么回事
利用golang特性，设计一个QPS为500的服务器
为什么gc会让程序变慢
开多个线程和开多个协程会有什么区别
两个interface{} 能不能比较
必须要手动对齐内存的情况
go栈扩容和栈缩容，连续栈的缺点
golang怎么做代码优化
golang隐藏技能:怎么访问私有成员
协程可以自己主动让出 CPU 吗？
断言时会发生拷贝吗
接口是怎么实现的？
协程与进程，线程的区别是什么？协程有什么优势？
为什么小对象多了会造成 gc 压力?
一个协程能保证绑定在一个内核线程上吗？
闭包怎么实现的,闭包的主要应用场景
两次 GC 周期重叠会引发什么问题，GC 触发机制是什么样的？
Goroutinue 什么时候会被挂起？
Data Race 问题怎么检测？怎么解决?
Golang 触发异常的场景有哪些?
net/http包中client如何实现长连接？
net/http怎么做连接池和长链接？

## golang进阶面试题
### 问题排查
trace
pprof
什么是 goroutine 泄漏?
当go服务部署到线上了，发现有内存泄露，该怎么处理

### 源码阅读
sync.map
net/http
i/o timeout ， 希望你不要踩到这个net/http包的坑
mutex
channel
context
select实现原理
main函数背后的启动过程
内存管理
GC垃圾回收
timer

### 实践常用工具
mysql建表语句转golang struct
json转golang struct
toml转golang struct
yaml转golang struct


### 图解网络基础
漫画图解HTTP知识点+面试题
TCP粘包 数据包：我只是犯了每个数据包都会犯的错
30张图带你搞懂！路由器，集线器，交换机，网桥，光猫有啥区别？
既然IP层会分片，为什么TCP层也还要分段？
断网了，还能ping通 127.0.0.1 吗？为什么？
连接一个 IP 不存在的主机时，握手过程是怎样的？
动图图解！代码执行send成功后，数据就发出去了吗？
活久见！TCP两次挥手，你见过吗？那四次握手呢？
动图图解！收到RST，就一定会断开TCP连接吗？
动图图解！没有accept，能建立TCP连接吗？
来了来了！小白图解网络电子书和博客都来啦！
HTTP 是无状态的吗？需要保持状态的场景应该怎么做？
粘包如何解决?
RestFul 是什么？RestFul 请求的 URL 有什么特点？
一次url访问会经历哪些过程
TCP 三次握手以及四次挥手的流程。为什么需要三次握手以及四次挥手？
TCP的拥塞控制具体是怎么实现的？UDP有拥塞控制吗？
是否了解中间人劫持原理
TCP 与 UDP 在网络协议中的哪一层，他们之间有什么区别？
HTTP 与 HTTPS 有哪些区别？
select和epoll区别
TCP 如何实现数据有序性？
TCP长连接和短连接有那么不同的使用场景？
TIME_WAIT时长，为什么？
什么是零拷贝？
HTTP 简述 HTTP 的 keepalive 的原理和使用场景
Cookie 和 Session 的关系和区别是什么？
DNS 查询服务器的基本流程是什么？DNS 劫持是什么？
libevent结构，内部实现
简述对称与非对称加密的概念
epoll中的ET和LT模式
JWT 的原理和校验机制
TCP 怎么保证可靠传输？
介绍下proactor和reactor
Accept发生在三次握手哪个阶段
RPC 的调用过程
tcp的可靠性体现在哪里
如何解决 TCP 传输丢包问题？
什么是 ARP 协议？简述其使用场景
http和https区别
DDOS 攻击原理，如何防范它？
如何防止传输内容被篡改？
介绍下滑动窗口
三次握手四次握手详细过程，越详细越好
什么是中间人攻击？如何防止攻击？
TCP 半连接发生场景
reactor的组成
udp包长度
IP为什么要分片
OSI 七层模型，TCP，IP 属于哪一层？
数据包乱序会处理？
什么是 SYN flood，如何防止这类攻击？
WebSocket 是如何进行传输的
为什么需要序列化？有什么序列化的方式？
有chunked的时候contentlength是什么样子
如何设计一个可靠的udp
TCP 中常见的拥塞控制算法有哪些？
如何设置非阻塞
什么是跨域，什么情况下会发生跨域请求？
Udp的接收缓冲区和发送缓冲区和tcp的区别
什么时候需要TCP四次挥手？
traceroute 有什么作用？
HTTP 的方法有哪些？
TIME_WAIT危害
select什么情况返回0
半连接在哪个阶段
TCP 的 keepalive 了解吗？说一说它和 HTTP 的 keepalive 的区别？
简述常见的 HTTP 状态码的含义（30从系统层面上，UDP 如何保证尽量可靠？
指针与引用的区别
iPv4 和 iPv6 的区别
项目中说用到线程池，开多大，为什么运用线程池？
如何设计 API 接口使其实现幂等性？
TCP 的 TIME_WAIT 和 CLOSE_WAIT
HTTP 报文头部的组成结构
RestFul 与 RPC 的区别是什么？RestFul 的优点在哪里？
从输入 URL 到展现页面的全过程
什么是 TCP 粘包和拆包？
HTTP 中 GET 和 POST 区别
讲一下拥塞控制和流量控制
TCP 协议的延迟 ACK 和累计应答
TCP 挥手时出现大量 CLOSE_WAIT 或 TIME_WAIT 怎么解决？
ARP协议工作流程
tcp与udp的区别以及应用场景
HTTPS 的加密与认证过程
TCP 中 SYN 攻击是什么？如何防止？
HTTP 短链接与长链接的区别
TCP 的报文头部结构
http长连接与短连接的区别
TCP 滑动窗口以及重传机制
seq为1000，发送了1000个数据，下一个seq是多少?
chunked块了解？介绍下
BGP 协议和 OSPF 协议的区别
简述在四层和七层网络协议中负载均衡的原理
http协议格式，几种方法，功能是什么
syn如果丢了，重传多少次
epoll可读情况有哪些

### 操作系统
创建线程有多少种方式？
如何调试服务器内存占用过高的问题？
简述操作系统如何进行内存管理
简述创建进程的流程
简述操作系统中 malloc 的实现原理
简述僵尸进程和孤儿进程及其危害和处理
两个线程交替打印一个共享变量
进程通信中的管道实现原理是什么？
简述同步与异步的区别，阻塞与非阻塞的区别
malloc 创建的对象在堆还是栈中？
死锁产生的条件、死锁避免方法
进程的三状态模型、五状态模型、七状态模型
什么情况下，进程会进行切换？
Linux 系统态与用户态，什么时候会进入系统态？
Linux 下如何查看端口被哪个进程占用？
共享内存是如何实现的？
进程有多少种状态？
线程间有哪些通信方式？
Linux 下如何排查 CPU 以及 内存占用过多？
操作系统中，虚拟地址与物理地址之间如何映射？
CPU L1, L2缓存是什么
信号量是如何实现的？
什么时候会由用户态陷入内核态？
Linux 如何查看实时的滚动日志？
Linux 进程调度的算法
简述分页与分段，分页与分段的区别
Linux 虚拟内存的页面置换算法
Linux 中虚拟内存和物理内存有什么区别？有什么优点？
traceroute 命令的原理
操作系统是通过什么机制触发系统调用的？
Linux 零拷贝的原理
系统调用的过程是怎样的？
Linux 的 IO模型有哪些
简述自旋锁与互斥锁的使用场景
多线程和多进程的区别是什么？
简述几个常用的 Linux 命令以及他们的功能
进程空间从高位到低位都有些什么？
简述缓冲区溢出及其危害
mmap 的使用场景以及原理
BIO、NIO 有什么区别？怎么判断写文件时 Buffer 已经写满？
线程有多少种状态，状态之间如何转换
简述操作系统中的缺页中断
Linux 下如何查看 CPU 荷载，正在运行的进程，某个端口对应的进程？
进程和线程之间有什么区别？
进程间有哪些通信方式？
为什么进程切换慢，线程切换快？
线程从进程继承了哪些资源？线程独享哪些资源？
Linux 页大小是多少？
select, poll, epoll 的使用场景以及区别，epoll 中水平触发以及边缘触发有什么不同？

### 数据库
数据库三大范式是什么
mysql有关权限的表都有哪几个
MySQL的binlog有有几种录入格式？分别有什么区别？
mysql有哪些数据类型
MySQL存储引擎MyISAM与InnoDB区别
MyISAM索引与InnoDB索引的区别？
InnoDB引擎的4大特性
存储引擎选择
什么是索引？
索引有哪些优缺点？
索引使用场景（重点）
索引有哪几种类型？
索引的数据结构（b树，hash）
索引的基本原理
索引算法有哪些？
索引设计的原则？
创建索引的原则
创建索引的三种方式，删除索引
创建索引时需要注意什么？
使用索引查询一定能提高查询的性能吗？为什么
百万级别或以上的数据如何删除
前缀索引
什么是最左前缀原则？什么是最左匹配原则
B树和B+树的区别
使用B树的好处
使用B+树的好处
Hash索引和B+树所有有什么区别或者说优劣呢?
数据库为什么使用B+树而不是B树
B+树在满足聚簇索引和覆盖索引的时候不需要回表查询数据，
什么是聚簇索引？何时使用聚簇索引与非聚簇索引
非聚簇索引一定会回表查询吗？
联合索引是什么？为什么需要注意联合索引中的顺序？
什么是数据库事务？
事物的四大特性(ACID)介绍一下?
什么是脏读？幻读？不可重复读？
什么是事务的隔离级别？MySQL的默认隔离级别是什么？
对MySQL的锁了解吗
隔离级别与锁的关系
按照锁的粒度分数据库锁有哪些？锁机制与InnoDB锁算法
从锁的类别上分MySQL都有哪些锁呢？像上面那样子进行锁定岂不是有点阻碍并发效率了
MySQL中InnoDB引擎的行锁是怎么实现的？
InnoDB存储引擎的锁的算法有三种
什么是死锁？怎么解决？
数据库的乐观锁和悲观锁是什么？怎么实现的？
为什么要使用视图？什么是视图？
视图有哪些特点？
视图的使用场景有哪些？
视图的优点
视图的缺点
什么是游标？
存储过程与函数
什么是存储过程？有哪些优缺点？
什么是触发器？触发器的使用场景有哪些？
MySQL中都有哪些触发器？
常用SQL语句
SQL语句主要分为哪几类
超键、候选键、主键、外键分别是什么？
SQL 约束有哪几种？
六种关联查询
什么是子查询
子查询的三种情况
mysql中 in 和 exists 区别
varchar与char的区别
varchar(50)中50的涵义
int(20)中20的涵义
mysql为什么这么设计
mysql中int(10)和char(10)以及varchar(10)的区别
FLOAT和DOUBLE的区别是什么？
drop、delete与truncate的区别
UNION与UNION ALL的区别？
如何定位及优化SQL语句的性能问题？创建的索引有没有被使用到?或者说怎么才可以知道这条语句运行很慢的原因？
SQL的生命周期？
大表数据查询，怎么优化
超大分页怎么处理？
mysql 分页怎么实现
慢查询日志怎么看
关心过业务系统里面的sql耗时吗？统计过慢查询吗？对慢查询都怎么优化过？
为什么要尽量设定一个主键？
主键使用自增ID还是UUID？
字段为什么要求定义为not null？
如果要存储用户的密码散列，应该使用什么字段进行存储？
优化查询过程中的数据访问
优化长难的查询语句
优化特定类型的查询语句
优化关联查询
优化子查询
优化LIMIT分页
优化UNION查询
优化WHERE子句

### 数据库优化
为什么要优化
数据库结构优化
MySQL数据库cpu飙升到500%的话他怎么处理？
大表怎么优化？某个表有近千万数据，CRUD比较慢，如何优化？分库分表了是怎么做的？分表分库了有什么问题？有用到中间件么？他们的原理知道么？
垂直分表适用场景
水平分表适用场景
水平切分的缺点
MySQL的复制原理以及流程
读写分离有哪些解决方案？
备份计划，mysqldump以及xtranbackup的实现原理
数据表损坏的修复方式有哪些？


## 常用官方包说明
常用第三方包说明
常用框架
完整标准库列表
优秀的第三方库
音频和音乐
数据结构:Go中的通用数据结构和算法
分布式系统:Go中的通用数据结构和算法
电子邮件:实现电子邮件创建和发送的库和工具
嵌入式脚本语言:在go代码中嵌入其他语言
错误处理
处理文件和文件系统的库
金融:会计和财务软件包
游戏开发:游戏开发相关库
地理位置:地理相关的位置信息和工具库
编译器相关:转到其他语言
Goroutines:用于管理和使用Goroutines的工具
图形界面:用于构建GUI应用程序的库
图片:用于处理图像的库
物联网:物联网设备编程库
JSON格式:用于处理JSON的库
机器学习:常用机器学习库
微软办公软件
自然语言处理
网络:与网络各层配合使用的库
视频:用于处理视频的库



## 其他
### 1.常用包
常用包	说明
fmt	实现格式化的输入输出操作，其中的fmt.Printf()和fmt.Println()是开发者使用最为频繁的函数。  
io	实现了一系列非平台相关的IO相关接口和实现，比如提供了对os中系统相关的IO功能的封装。我们在进行流式读写（比如读写文件）时，通常会用到该包。  
bufio	它在io的基础上提供了缓存功能。在具备了缓存功能后， bufio可以比较方便地提供ReadLine之类的操作。  
strconv	提供字符串与基本数据类型互转的能力。  
os	本包提供了对操作系统功能的非平台相关访问接口。接口为Unix风格。提供的功能包括文件操作、进程管理、信号和用户账号等。  
sync	它提供了基本的同步原语。在多个goroutine访问共享资源的时候，需要使用sync中提供的锁机制。  
flag	它提供命令行参数的规则定义和传入参数解析的功能。绝大部分的命令行程序都需要用到这个包。  
encoding/json	JSON目前广泛用做网络程序中的通信格式。本包提供了对JSON的基本支持，比如从一个对象序列化为JSON字符串，或者从JSON字符串反序列化出一个具体的对象等。  
http	通过http包，只需要数行代码，即可实现一个爬虫或者一个Web服务器，这在传统语言中是无法想象的。


### 2. 常用第三方包

包	地址
数据库操作	github.com/jinzhu/gorm
github.com/go-xorm/xorm
搜索es	github.com/olivere/elastic
rocketmq操作	github.com/apache/rocketmq-client-go/v2
rabbitmq 操作	github.com/streadway/amqp
redis 操作	github.com/go-redis/redis
etcd 操作	github.com/coreos/etcd/clientv3
kafka	https://github.com/Shopify/sarama https://github.com/bsm/sarama-cluster
excel 操作	github.com/360EntSecGroup-Skylar/excelize
ppt 操作	golang.org/x/tools/cmd/present
go-svg 操作	https://github.com/ajstarks/svgo
go 布隆过滤器实现	https://github.com/AndreasBriese/bbloom
json相关	https://github.com/bitly/go-simplejson
LRU Cache实现	https://github.com/bluele/gcache https://github.com/hashicorp/golang-lru
go运行时函数替换	https://github.com/bouk/monkey
toml	https://github.com/toml-lang/toml https://github.com/naoina/toml
yaml	https://github.com/go-yaml/yaml
viper	https://github.com/spf13/viper
go key/value存储	https://github.com/etcd-io/bbolt
基于ringbuffer的无锁golang workpool	https://github.com/Dai0522/workpool
轻量级的协程池	https://github.com/ivpusic/grpool
打印go的详细数据结构	https://github.com/davecgh/go-spew
基于ringbuffer实现的队列	https://github.com/eapache/queue
拼音	https://github.com/go-ego/gpy
分词	https://github.com/go-ego/gse
搜索	https://github.com/go-ego/riot
windows COM	https://github.com/go-ego/cedar
session	https://github.com/gorilla/sessions
路由	https://github.com/gorilla/mux
websocket	https://github.com/gorilla/websocket
Action handler	https://github.com/gorilla/handlers
csrf	https://github.com/gorilla/csrf
context	https://github.com/gorilla/context
过滤html标签	https://github.com/grokify/html-strip-tags-go
可配置的HTML标签过滤	https://github.com/microcosm-cc/bluemonday
根据IP获取地理位置信息	https://github.com/ipipdotnet/ipdb-go
html转markdown	https://github.com/jaytaylor/html2text
goroutine 本地存储	https://github.com/jtolds/gls
彩色输出	https://github.com/mgutz/ansi
表格打印	https://github.com/olekukonko/tablewriter
reflect 更高效的反射API	https://github.com/modern-go/reflect2
msgfmt (格式化字符串，将%更换为变量名)	https://github.com/modern-go/msgfmt
可取消的goroutine	https://github.com/modern-go/concurrent
深度拷贝	https://github.com/mohae/deepcopy
安全的类型转换包	https://github.com/spf13/cast
从文本中提取链接	https://github.com/mvdan/xurls
字符串格式处理（驼峰转换）	https://godoc.org/github.com/naoina/go-stringutil
文本diff实现	https://github.com/pmezard/go-difflib
uuid相关	https://github.com/satori/go.uuid https://github.com/snluu/uuid
去除UTF编码中的BOM	https://github.com/ssor/bom
图片缩放	https://github.com/nfnt/resize
生成 mock server	https://github.com/otokaze/mock
go 性能上报到influxdb	https://github.com/rcrowley/go-metrics
go zookeeper客户端	https://github.com/samuel/go-zookeeper
go thrift	https://github.com/samuel/go-thrift
MQTT 客户端	https://github.com/shirou/mqttcli
hbase	https://github.com/tsuna/gohbase
go 性能上报到influxdb	https://github.com/rcrowley/go-metrics
go 性能上报到prometheus	https://github.com/deathowl/go-metrics-prometheus
ps utils	https://github.com/shirou/gopsutil
小数处理	https://github.com/shopspring/decimal
结构化日志处理(json)	https://github.com/sirupsen/logrus
命令行程序框架 cli	https://github.com/urfave/cli
命令行程序框架 cobra	https://github.com/spf13/cobra


### 3. 必看项目
项目	地址	说明
gin	github.com/gin-gonic/gin	轻量级web框架，很多公司都是基于它进行魔改
beego	github.com/beego/beego	也是web框架，比较全能
kratos	github.com/go-kratos/kratos	bilibili开源的微服务框架，b站出品必属于精品
TiDB	github.com/pingcap/tidb	见识过mysql性能瓶颈之后你会想要选择的一款数据库


### 4. 完整标准库列表
包	子包	说明
bufio	bytes	提供了对字节切片操作的函数
crypto	收集了常见的加密常数
errors	实现了操作错误的函数
Expvar	为公共变量提供了一个标准的接口，如服务器中的运算计数器
flag	实现了命令行标记解析
fmt	实现了格式化输入输出
hash	提供了哈希函数接口
html	实现了一个HTML5兼容的分词器和解析器
image	实现了一个基本的二维图像库
io	提供了对I/O原语的基本接口
log	它是一个简单的记录包，提供最基本的日志功能
math	提供了一些基本的常量和数学函数
mine	实现了部分的MIME规范
net	提供了一个对UNIX网络套接字的可移植接口，包括TCP/IP、 UDP域名解析和UNIX域套接字
os	为操作系统功能实现了一个平台无关的接口
path	实现了对斜线分割的文件名路径的操作
reflect	实现了运行时反射，允许一个程序以任意类型操作对象
regexp	实现了一个简单的正则表达式库
runtime	包含与Go运行时系统交互的操作，如控制goroutine的函数
sort	提供对集合排序的基础函数集
strconv	实现了在基本数据类型和字符串之间的转换
strings	实现了操作字符串的简单函数
sync	提供了基本的同步机制，如互斥锁
syscall	包含一个低级的操作系统原语的接口
testing	提供对自动测试Go包的支持
time	提供测量和显示时间的功能
unicode	Unicode编码相关的基础函数
archive	tar	实现对tar压缩文档的访问
zip	提供对ZIP压缩文档的读和写支持
compress	bzip2	实现了bzip2解压缩
flate	实现了RFC 1951中所定义的DEFLATE压缩数据格式
gzip	实现了RFC 1951中所定义的gzip格式压缩文件的读和写
lzw	实现了 Lempel-Ziv-Welch编码格式的压缩的数据格式
zlib	实现了RFC 1950中所定义的zlib格式压缩数据的读和写
container	heap	提供了实现heap.Interface接口的任何类型的堆操作
lsit	实现了一个双链表
ring	实现了对循环链表的操作
crypto	aes	实现了AES加密（以前的Rijndael）
cipher	实现了标准的密码块模式，该模式可包装进低级的块加密实现中
des	实现了数据加密标准（ Data Encryption Standard，DES）和三重数据加密算法（ TripleData Encryption Algorithm， TDEA）
dsa	实现了FIPS 186-3所定义的数据签名算法（ Digital Signature Algorithm）
ecdsa	实现了FIPS 186-3所定义的椭圆曲线数据签名算法（ Elliptic Curve Digital SignatureAlgorithm）
elliptic	实现了素数域上几个标准的椭圆曲线
hmac	实现了键控哈希消息身份验证码（ Keyed-Hash Message Authentication Code，HMAC）
md5	实现了RFC 1321中所定义的MD5哈希算法
rand	实现了一个加密安全的伪随机数生成器
rc4	实现了RC4加密，其定义见Bruce Schneier的应用密码学（ Applied Cryptography）
rsa	实现了PKCS#1中所定义的RSA加密
sha1	实现了RFC 3174中所定义的SHA1哈希算法
sha256	实现了FIPS 180-2中所定义的SHA224和SHA256哈希算法
sha512	实现了FIPS 180-2中所定义的SHA384和SHA512哈希算法
subtle	实现了一些有用的加密函数，但需要仔细考虑以便正确应用它们
tls	部分实现了RFC 4346所定义的TLS 1.1协议
x509	可解析X.509编码的键值和证书
x509/pkix	包含用于对X.509证书、 CRL和OCSP的ASN.1解析和序列化的共享的、低级的结构
database	sql	围绕SQL提供了一个通用的接口
sql/driver	定义了数据库驱动所需实现的接口，同sql包的使用方式
debug	dwarf	提供了对从可执行文件加载的DWARF调试信息的访问，这个包对于实现Go语言的调试器非常有价值
elf	实现了对ELF对象文件的访问。 ELF是一种常见的二进制可执行文件和共享库的文件格式。 Linux采用了ELF格式
gosym	访问Go语言二进制程序中的调试信息。对于可视化调试很有价值
macho	实现了对Mach-O对象文件的访问
pe	实现了对PE（ Microsoft Windows Portable Executable）文件的访问
encoding	ascii85	实现了ascii85数据编码，用于btoa工具和Adobe’s PostScript以及PDF文档格式
asn1	实现了解析DER编码的ASN.1数据结构，其定义见ITU-T Rec X.690
base32	实现了RFC 4648中所定义的base32编码
base64	实现了RFC 4648中所定义的base64编码
binary	实现了在无符号整数值和字节串之间的转化，以及对固定尺寸值的读和写
csv	可读和写由逗号分割的数值（ csv）文件
gob	管理gob流——在编码器（发送者）和解码器（接收者）之间进行二进制值交换
hex	实现了十六进制的编码和解码
json	实现了定义于RFC 4627中的JSON对象的编码和解码
pem	实现了PEM（ Privacy Enhanced Mail）数据编码
xml	实现了一个简单的可理解XML名字空间的XML 1.0解析器
go	ast	声明了用于展示Go包中的语法树类型
build	提供了构建Go包的工具
doc	从一个Go AST（抽象语法树）中提取源代码文档
parser	实现了一个Go源文件解析器
printer	实现了对AST（抽象语法树）的打印
scanner	实现了一个Go源代码文本的扫描器
token	定义了代表Go编程语言中词法标记以及基本操作标记（ printing、 predicates）的常量
hash	adler32	实现了Adler-32校验和
crc32	实现了32位的循环冗余校验或CRC-32校验和
crc64	实现了64位的循环冗余校验或CRC-64校验和
fnv	实现了Glenn Fowler、 Landon Curt Noll和Phong Vo所创建的FNV-1和FNV-1a未加密哈希函数
html	template	它自动构建HTML输出，并可防止代码注入
image	color	实现了一个基本的颜色库
draw	提供一些做图函数
gif	实现了一个GIF图像解码器
jpeg	实现了一个JPEG图像解码器和编码器
png	实现了一个PNG图像解码器和编码器
index	suffixarray	通过构建内存索引实现的高速字符串匹配查找算法
io	ioutil	实现了一些实用的I/O函数
log	syslog	提供了对系统日志服务的简单接口
math	big	实现了多精度的算术运算（大数）
cmplx	为复数提供了基本的常量和数学函数
rand	实现了伪随机数生成器
mime	multipart	实现了在RFC 2046中定义的MIME多个部分的解析
net	http	提供了HTTP客户端和服务器的实现
mail	实现了对邮件消息的解析
rpc	提供了对一个来自网络或其他I/O连接的对象可导出的方法的访问
smtp	实现了定义于RFC 5321中的简单邮件传输协议（ Simple Mail Transfer Protocol)
textproto	实现了在HTTP、 NNTP和SMTP中基于文本的通用的请求/响应协议
url	解析URL并实现查询转义
http/cgi	实现了定义于RFC 3875中的CGI（通用网关接口）
http/fcgi	实现了FastCGI协议
http/httptest	提供了一些HTTP测试应用
http/httputil	提供了一些HTTP应用函数，这些是对net/http包中的东西的补充，只不过相对不太常用
http/pprof	通过其HTTP服务器运行时提供性能测试数据，该数据的格式正是pprof可视化工具需要的
rpc/jsonrpc	为rpc包实现了一个JSON-RPC ClientCodec和ServerCodec
os	exec	可运行外部命令
user	通过名称和id进行用户账户检查
path	filepath	实现了以与目标操作系统定义文件路径相兼容的方式处理文件名路径
regexp	syntax	将正则表达式解析为语法树
runtime	debug	包含当程序在运行时调试其自身的功能
pprof	以pprof可视化工具需要的格式写运行时性能测试数据
sync	atomic	提供了低级的用于实现同步算法的原子级的内存机制
testing	iotest	提供一系列测试目的的类型，实现了Reader和Writer标准接口
quick	实现了用于黑箱测试的实用函数
script	帮助测试使用通道的代码
text	scanner	为UTF-8文本提供了一个扫描器和分词器
tabwriter	实现了一个写筛选器（ tabwriter.Writer），它可将一个输入的tab分割的列翻译为适当对齐的文本
template	数据驱动的模板引擎，用于生成类似HTML的文本输出格式
template/parse	为template构建解析树
unicode/utf16	实现了UTF-16序列的的编码和解码
unicode/utf8	实现了支持以UTF-8编码的文本的函数和常数


### 5. 其他优秀的开源工具分类
音频和音乐
包	说明
EasyMIDI	EasyMidi是一个简单可靠的库，用于处理标准Midi文件（SMF）。
flac	支持FLAC流的Native Go FLAC编码器/解码器。
gaad	本机Go AAC比特流解析器。
go-sox	用于go的libsox绑定。
go_mediainfo	用于go的libmediainfo绑定。
gosamplerate	用于go的libsamplerate绑定。
id3v2	用于Go的快速，稳定的ID3解析和编写库。
malgo	迷你音频库。
minimp3	轻量级MP3解码器库。
mix	为音乐应用程序基于序列转到本地音频混合器。
mp3	Native Go MP3解码器。
music-theory	Go中的音乐理论模型。
Oto	在多个平台上播放声音的低级库。
PortAudio	用于PortAudio音频I / O库的绑定。
portmidi	绑定PortMidi。
taglib	为taglib绑定。
vorbis	“本机” Go Vorbis解码器（使用CGO，但没有依赖项）。
waveform	Go程序包，能够从音频流生成波形图像。

## 数据结构

包	说明
algorithms	算法和数据结构。CLRS研究。
binpacker	二进制打包程序和解包程序可帮助用户构建自定义二进制流。
bit	具有额外的位旋转功能的Golang设置数据结构。
bitset	实现位集的Go包。
bloom	在Go中实现的Bloom过滤器。
bloom	Golang Bloom过滤器实现。
boomfilters	用于处理连续无界流的概率数据结构。
concurrent-writer	高并发直接替换bufio.Writer。
conjungo	一个小型，强大而灵活的合并库。
count-min-log	执行Count-Min-Log草图：使用近似计数器进行近似计数（类似于Count-Min草图，但使用较少的内存）。
crunch	Go包实现了用于轻松处理各种数据类型的缓冲区。
cuckoofilter	Cuckoo过滤器：是Go中实现的计数布隆过滤器的很好替代。
deque	高度优化的双端队列。
deque	快速的环形缓冲区双端队列（双端队列）。
dict	Go的类似Python的字典（dict）。
encoding	Go的整数压缩库。
go-adaptive-radix-tree	自适应基数树的 Go实现。
go-datastructures	有用，高性能和线程安全的数据结构的集合。
go-ef	Elias-Fano编码的Go实现。
go-geoindex	内存中的地理索引。
go-mcache	快速内存键：值存储/缓存库。指针缓存。
go-rquad	具有有效点定位和邻居发现功能的区域四叉树。
gocache	具有多个存储（内存，memcache，redis等），可链接，可加载，指标缓存等的完整Go缓存库。
goconcurrentqueue	并发FIFO队列。
gods	数据结构。容器，集合，列表，堆栈，地图，BidiMap，树，HashSet等。
gofal	Go的小数api。
golang-set	Go的线程安全和非线程安全高性能集。
goset	Go的有用的Set集合实现。
goskiplist	Go中的跳过列表实现。
gota	Go的数据框，序列和数据整理方法的实现。
hide	ID类型，将其编组进/出哈希以防止将ID发送给客户端。
hilbert	Go程序包，用于在空间填充曲线（例如Hilbert和Peano曲线）之间映射值。
hyperloglog	HyperLogLog实施，具有稀疏，LogLog-Beta偏差校正和TailCut空间减少功能。
iter	C ++ STL迭代器和算法的实现。
levenshtein	Levenshtein距离和相似性度量标准，具有可自定义的编辑费用和通用前缀的类似于Winkler的奖金。
levenshtein	在Go中计算levenshtein距离的实现。
mafsa	具有最小完美散列的MA-FSA实现。
merkletree	merkle树的实现，可对数据结构的内容进行有效且安全的验证。
mspm	用于信息检索的多字符串模式匹配算法。
null	可空转到类型，可以被编组/解组到/从JSON。
parsefields	用于解析类似JSON的日志的工具，以收集唯一的字段和事件。
pipeline	具有扇入和扇出的管线的实现。
ptrie	前缀树的实现。
remember-go	缓存慢速数据库查询的通用接口（由redis，memcached，ristretto或内存支持）。
ring	围棋实现了高性能，线程安全的布隆过滤器。
roaring	实施压缩位集的软件包。
set	使用LinkedHashMap的围棋设置简单的数据结构实现。
skiplist	非常快的Go Skiplist实施。
skiplist	Go中的跳过列表实现。
timedmap	具有过期的键/值对的地图。
treap	使用树堆的持久快速排序的地图。
trie	Go中的Trie实现。
ttlcache	内存中的LRU字符串接口{}映射，其中包含golang的到期时间。
typ	空类型，安全的原始类型转换和从复杂结构中获取值。
willf/bloom	Go包实现Bloom过滤器。

## 分布式系统

包	说明
celeriac	用于在Go中添加支持以交互和监视Celery工作者，任务和事件的库。
consistent	具有受限负载的一致哈希
dht	BitTorrent Kademlia DHT实施。
digota	grpc电子商务微服务。
dot	使用操作转换/ OT进行分布式同步。
doublejump	改进后的Google的跳转一致性哈希。
dragonboat	Go中功能齐全的高性能多组Raft库。
drmaa	基于DRMAA标准的集群调度程序的作业提交库。
dynamolock	DynamoDB支持的分布式锁定实现。
dynatomic	将DynamoDB用作原子计数器的库。
emitter-io	使用MQTT，Websockets和love构建的高性能，分布式，安全和低延迟的发布-订阅平台。
flowgraph	基于流的编程包。
gleam	用纯围棋和Luajit快速和可扩展的分布式的map / reduce系统，具有Luajit的高性能结合Go的高并发，单独运行或分发。
glow	易于使用的可扩展的分布式大数据处理，Map-Reduce，DAG执行，全部在纯Go中进行。
go-health	health-用于在服务中启用异步依赖项运行状况检查的库。
go-jump	Google的“ Jump”一致性哈希函数的端口。
go-kit	支持服务发现，负载平衡，可插拔传输，请求跟踪等的微服务工具包
go-sundheit	建立用于支持为golang服务定义异步服务运行状况检查的库。
gorpc	简单，快速和可扩展的RPC库，可实现高负载。
grpc-go	gRPC的Go语言实现。基于HTTP / 2的RPC。
hprose	十分新颖的RPC库，现在支持25种以上的语言。
jsonrpc	jsonrpc软件包可帮助实现JSON-RPC 2.0。
jsonrpc	JSON-RPC 2.0 HTTP客户端实现。
KrakenD	具有中间件的超高性能API网关框架。
liftbridge	NATS的轻量级，容错消息流。
micro	可插拔的microService工具箱和分布式系统平台。
NATS	用于微服务，IoT和云本机系统的轻量级高性能消息传递系统。
outboxer	Outboxer是一个实现库模式的go库。
pglock	PostgreSQL支持的分布式锁定实现。
raft	HashiCorp的Raft共识协议的Golang实现。
raft	ETCD中实现的Raft协议。
rain	BitTorrent客户端和库。
redis-lock	使用Redis的简化分布式锁定实现。
resgate	用于构建REST，实时和RPC API的实时API网关，其中所有客户端都可以无缝同步。
ringpop-go	Go应用程序的可扩展，容错应用程序层分片。
rpcx	分布式可插拔RPC服务框架，例如阿里巴巴Dubbo。
sleuth	用于在HTTP服务之间进行无主p2p自动发现和RPC的库（ZeroMQ）。
tendermint	高性能中间件，用于使用Tendermint共识和区块链协议将以任何编程语言编写的状态机转换为拜占庭容错复制状态机。
torrent	BitTorrent客户端软件包。

## 电子邮件

包	说明
chasquid	用Go编写的SMTP服务器。
douceur	CSS内衬为您的HTML电子邮件。
email	用于Go的强大而灵活的电子邮件库。
go-dkim	DKIM库，用于签名和验证电子邮件。
go-imap	用于客户端和服务器的IMAP库。
go-message	Internet消息格式和邮件消息的流库。
go-premailer	Go中HTML邮件的内联样式。
go-simple-mail	使用SMTP保持活动状态和两个超时发送电子邮件的非常简单的程序包：连接和发送。
Hectane	提供HTTP API的轻型SMTP客户端。
hermes	Golang软件包，可生成干净的响应式HTML电子邮件。
mailchain	将加密的电子邮件发送到用Go编写的区块链地址。
mailgun-go	Go库，用于使用Mailgun API发送邮件。
MailHog	通过Web和API界面进行电子邮件和SMTP测试。
SendGrid	SendGrid的Go库，用于发送电子邮件。
smtp	SMTP服务器协议状态机。

## 嵌入式脚本语言

包	说明
anko	用Go语言编写的可编写脚本的解释器。
binder	转到基于gopher-lua的 Lua绑定库。
cel-go	具有渐进式输入功能的快速，便携式，非图灵完整表达评估。
expr	可以评估表达式的引擎。
gentee	可嵌入的脚本编程语言。
gisp	Go中的简单LISP。
go-duktape	Go的Duktape JavaScript引擎绑定。
go-lua	Lua 5.2 VM到纯Go的端口。
go-php	Go的PHP绑定。
go-python	与CPython C-API的幼稚go绑定。
golua	Lua C API的绑定。
gopher-lua	用Go编写的Lua 5.1 VM和编译器。
gval	用Go编写的高度可定制的表达语言。
ngaro	可嵌入的Ngaro VM实现，支持在Retro中编写脚本。
otto	用Go编写的JavaScript解释器。
purl	Go中嵌入的Perl 5.18.2。
tengo	用于Go的字节码编译脚本语言。

## 错误处理

包	说明
emperror	Go库和应用程序的错误处理工具和最佳实践。
errlog	可破解的软件包，用于确定错误的负责任的源代码（以及其他一些快速调试功能）。可插入任何现成的记录器。
errors	下拉更换为标准库的错误包和github.com/pkg/errors。提供各种错误处理原语。
errors	提供简单错误处理原语的软件包。
errors	简单golang错误处理与分类元。
errorx	具有堆栈跟踪，错误组成等的功能丰富的错误包。
Falcon	一个简单但功能强大的错误处理软件包。
go-multierror	Go（golang）软件包，用于将错误列表表示为单个错误。
tracerr	带有堆栈跟踪和源代码片段的Golang错误。
werr	错误包装程序为Go中的错误类型创建了一个包装程序，该包装程序捕获了调用它的文件，行和堆栈。

## 文件

包	说明
afero	Go的文件系统抽象系统。
afs	Go的抽象文件存储（mem，scp，zip，tar，云：s3，gs）。
bigfile	文件传输系统，支持使用http api，rpc调用和ftp客户端管理文件。
checksum	计算大型文件的消息摘要，例如MD5和SHA256。
flop	文件操作库，旨在与GNU cp镜像功能奇偶校验。
go-csv-tag	tag-使用标签加载csv文件。
go-decent-copy	复制human文件。
go-exiftool	ExifTool的Go绑定，这是众所周知的库，用于从文件（图片，PDF，office，...）提取尽可能多的元数据（EXIF，IPTC等）。
go-gtfs	在go中加载gtfs文件。
notify	具有简单API的文件系统事件通知库，类似于os / signal。
opc	为Go加载Open Packaging Conventions（OPC）文件。
parquet	读取和写入 parquet文件。
pdfcpu	PDF 处理器。
skywalker	一种软件包，允许一个人轻松地同时通过文件系统。
stl	读取和写入STL（立体光刻）文件的模块。并发读取算法。
tarfs	tar文件FileSystem interface接口的实现。
vfs	跨多种文件系统类型（例如os，S3和GCS）的Go的一组可插拔，可扩展且自以为是的文件系统功能。

## 金融

包	说明
accounting	golang的货币和货币格式。
currency	高性能和准确的货币计算包。
decimal	任意精度定点十进制数字。
go-finance	Go中的综合金融市场数据。
go-finance	金融功能库，用于货币时间价值（年金），现金流量，利率转换，债券和折旧计算。
go-finance	获取汇率，通过VIES检查增值税号和检查IBAN银行帐号的模块。
go-money	Fowler的Money模式的实现。
ofxgo	查询OFX服务器和/或解析响应（使用示例命令行客户端）。
orderbook	匹配引擎的限价订单在Golang。
techan	具有高级市场分析和交易策略的技术分析库。
transaction	以多线程模式运行的嵌入式帐户嵌入式事务数据库。
vat	增值税号验证和欧盟增值税率。

## 游戏开发

包	说明
Azul3D	用Go语言编写的3D游戏引擎。
Ebiten	Go中死的简单2D游戏库。
engo	Engo是用Go语言编写的开源2D游戏引擎。它遵循实体组件系统范式。
g3n	Go 3D游戏引擎。
GarageEngine	用Go语言编写的2D游戏引擎，可在OpenGL上使用。
glop	Glop（权力游戏库）是一个相当简单的跨平台游戏库。
go-astar	A 路径查找算法的Go实现。
go-collada	Go包，用于Collada文件格式。
go-sdl2	Simple DirectMedia Layer的 Go绑定。
go3d	用于Go的面向性能的2D/3D数学软件包。
gonet	使用golang实现的游戏服务器框架。
goworld	可扩展的游戏服务器引擎，具有空间实体框架和热插拔功能。
Leaf	轻量级游戏服务器框架。
nano	重量轻，设备，高性能的基于golang游戏服务器架构。
Oak	Pure Go游戏引擎。
Pitaya	可扩展的游戏服务器框架，具有群集支持和通过C SDK的iOS，Android，Unity等客户端库。
Pixel	Go中的手工制作2D游戏库。
raylib-go	去绑定raylib，简单和易于使用的库，以了解电子游戏编程。
termloop	Go的基于终端的游戏引擎，建立在Termbox之上。
地理位置
包	说明
geocache	适用于基于地理位置的应用程序的内存中缓存。
geoserver	geoserver是Go软件包，用于通过GeoServer REST API操纵GeoServer实例。
gismanager	将 GIS数据（矢量数据）发布到PostGIS和Geoserver。
osm	用于读取，编写和使用OpenStreetMap数据和API的库。
pbf	OpenStreetMap PBF golang编码器/解码器。
S2 geometry	Go中的S2几何库。
Tile38	具有空间索引和实时地理围栏的地理位置数据库。
WGS84	库坐标转换和变换（ETRS89，OSGB36，NAD83，RGF93，网络墨卡托UTM）。

## 编译器

包	说明
c4go	将C代码转换为Go代码。
f4go	将FORTRAN 77代码转换为Go代码。
gopherjs	从Go到JavaScript的编译器。
llgo	Go的基于LLVM的编译器。
tardisgo	Golang转换为CPP / CSharp / Java / JavaScript转译器。

## Goroutines

包	说明
ants	用于golang的高性能goroutine池。
artifex	Golang使用基于工作程序的分派的简单内存中作业队列。
async	一种异步执行功能的安全方法，以防万一。
breaker	使执行流程可中断的灵活机制。
cyclicbarrier	用于golang的CyclicBarrier。
go-floc	轻松编排goroutine。
go-flow	控制goroutine的执行顺序。
go-tools/multithreading	使用带有简单API的轻量级库管理goroutine池。
go-trylock	支持Golang的读写锁的TryLock。
go-waitgroup	sync.WaitGroup与错误处理和并发控制类似。
gohive	Go的高性能和易于使用的Goroutine池。
gollback	异步简单函数实用程序，用于管理闭包和回调的执行。
GoSlaves	简单和异步Goroutine池库。
goworker	goworker是基于Go的后台工作者。
gowp	gowp是并发限制goroutine池。
gpool	管理可调整大小的上下文感知goroutine池以绑定并发。
grpool	轻巧的Goroutine池。
Hunch	预感提供功能，如：All，First，Retry，Waterfall等等，这使得异步流控制更加直观。
oversight	监督是Erlang监督树的完整实现。
parallel-fn	并行运行功能。
pool	有限的消费者goroutine池或无限制的goroutine池，以便更轻松地处理和取消goroutine。
queue	为您提供sync.WaitGroup类似的队列组可访问性。帮助您节流和限制goroutine，等待所有goroutine结束等等。
routine	具有上下文和支持的例程控制：Main，Go，Pool和一些有用的Executors。
semaphore	基于通道和上下文的具有锁定/解锁操作超时的信号量模式实现。
semaphore	基于CAS的快速可调整大小的信号量实现（比基于通道的信号量实现更快）。
stl	基于软件交易内存（STM）并发控制机制的软件交易锁。
threadpool	Golang线程池实现。
tunny	线程池golang。
worker-pool	goworker是一个简单的Go异步工作池。
workerpool	Goroutine池，它限制了任务执行的并发性，而不是排队的任务数。

## 图形界面

包	说明
app	打包以使用GO，HTML和CSS创建应用的程序。支持：MacOS，Windows正在开发中。
fyne	为Go设计的跨平台本机GUI，使用EFL呈现。支持：Linux，macOS，Windows。
go-astilectron	使用GO和HTML / JS / CSS（由Electron支持）构建跨平台GUI应用。
go-gtk	GTK的绑定。
go-sciter	Go绑定：用于现代桌面UI开发的可嵌入HTML / CSS / script引擎。跨平台。
gotk3	GTK3的绑定。
gowd	使用GO，HTML，CSS和NW.js进行快速简单的桌面UI开发。跨平台。
qt	Go的Qt绑定（支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi）。
ui	Go的平台本地GUI库。跨平台。
Wails	使用内置OS HTML渲染器的HTML UI的Mac，Windows，Linux桌面应用程序。
walk	Go的Windows应用程序库工具包。
webview	具有简单双向JavaScript绑定的跨平台Webview窗口（Windows / macOS / Linux）。
go-appindicator	libappindicator3 C库的Go绑定。
gosx-notifier	Go的OSX桌面通知库。
mac-activity-tracker	OSX库，用于通知计算机上的任何（可插入）活动。
mac-sleep-notifier	golang中的OSX睡眠/唤醒通知。
robotgo	Go本机跨平台GUI系统自动化。控制鼠标，键盘等。
systray	跨平台的Go库，用于在通知区域中放置图标和菜单。
trayhost	跨平台的Go库，用于在主机操作系统的任务栏中放置一个图标。

## 图片

包	说明
bild 	纯Go中图像处理算法的集合。
bimg 	使用libvips进行快速有效的图像处理的小包装。
cameron 	Go的头像生成器。
canvas 	将矢量图形转换为PDF，SVG或光栅图像。
darkroom 	具有可变存储后端的图像代理和侧重于速度和弹性的图像处理引擎。
geopattern 	从字符串创建漂亮的生成图像图案。
gg 	纯Go中的2D渲染。
gift 	图像处理过滤器的包装。
gltf 	高效，强大的glTF 2.0读取器，写入器和验证器。
go-cairo 	用于cairo图形库的绑定。
go-gd 	GD库的Go绑定。
go-nude 	Go的裸露检测。
go-opencv 	用于OpenCV的绑定。
go-webcolors 	webcolors库的端口，从Python到Go。
gocv 	使用OpenCV 3.3+进行计算机视觉的Go软件包。
goimagehash 	Go感知图像哈希包。
goimghdr 	imghdr模块确定Go文件中包含的图像类型。
govatar 	用于生成有趣头像的库和CMD工具。
image2ascii 	将图像转换为ASCII。
imagick 	绑定到ImageMagick的MagickWand C API。
imaginary 	用于图像大小调整的快速，简单的HTTP微服务。
imaging 	简单的Go图像处理包。
img 	选择图像处理工具。
ln 	Go中的3D线条艺术渲染。
mergi 	用于图像处理（合并，裁切，调整大小，水印，动画）的Tool＆Go库。
mort 	用Go编写的存储和图像处理服务器。
mpo 	用于MPO 3D照片的解码器和转换工具。
picfit 	用Go编写的图像大小调整服务器。
pt 	用Go语言编写的路径跟踪引擎。
resize 	使用常见的插值方法为Go 调整图像大小。
rez 	在纯Go和SIMD中调整图像大小。
smartcrop 	查找适合任何图像和尺寸的优质作物。
steganography 	用于LSB隐写术的Pure Go库。
stegify 	用于LSB隐写术的Go工具，能够隐藏图像中的任何文件。
svgo 	用于SVG生成的Go语言库。
tga 	软件包tga是TARGA图像格式的解码器/编码器。
photo-translate 	图片翻译。

## 物联网

包	说明
connectordb 	量化自我和物联网的开源平台。
devices 	IoT设备库套件，针对x / exp / io进行实验。
eywa 	Project Eywa本质上是一个连接管理器，用于跟踪连接的设备。
flogo 	Project Flogo是一个用于IoT Edge应用和集成的开源框架。
gatt 	盖特是一个围棋包构建低功耗蓝牙外设。
gobot 	Gobot是机器人技术，物理计算和物联网的框架。
huego 	适用于Go的飞利浦Hue扩展客户端库。
iot 	IoT是用于实现Google IoT Core设备的简单框架。
mainflux 	工业物联网消息和设备管理服务器。
periph 	外设I / O与低级别的主板设备接口。
sensorbee 	用于物联网的轻量级流处理引擎。
JSON格式
包	说明
ajson 	具有JSONPath支持的golang的抽象JSON。
gjo 	用于创建JSON对象的小型实用程序。
GJSON 	使用一行代码获取JSON值。
go-jsonerror 	Go-JsonError可让我们轻松创建遵循JsonApi规范的json响应错误。
go-respond 	Go包，用于处理常见的HTTP JSON响应。
gojq 	Golang中的 JSON查询。
gojson 	从示例JSON自动生成Go（golang）结构定义。
JayDiff 	用Go编写的JSON diff实用程序。
jettison 	用于Go的高性能，无反射JSON编码器。
JSON-to-Go 	将JSON转换为Go结构。
json2go 	高级JSON到Go结构转换。提供可以解析多个JSON文档并创建适合所有JSON的结构的包。
jsonapi-errors 	根据JSON API错误参考进行绑定。
jsonf 	突出显示格式和获取JSON的结构查询的控制台工具。
jsongo 	Fluent API，可以更轻松地创建Json对象。
jsonhal 	简单的Go包，用于将自定义结构编组为HAL兼容的JSON响应。
kazaam 	用于JSON文档的任意转换的API。
mp 	简单的cli电子邮件解析器。当前，它使用标准输入并输出JSON。

## 机器学习

包	说明
bayesian 	贝叶斯分类为Golang天真。
CloudForest 	快速，灵活，多线程的决策树集合，用于纯Go中的机器学习。
eaopt 	进化优化库。
evoli 	遗传算法和粒子群优化库。
fonet 	用Go编写的深度神经网络库。
go-cluster 	k模式和k-原型聚类算法的Go实现。
go-deep 	Go中功能丰富的神经网络库
go-fann 	快速人工神经网络（FANN）库的Go绑定。
go-galib 	用Go / golang编写的遗传算法库。
go-pr 	Go lang中的模式识别包。
gobrain 	用go语言编写的神经网络
godist 	各种概率分布及相关方法。
goga 	Go的遗传算法库。
GoLearn 	用于Go的通用机器学习库。
golinear 	Go的liblinear绑定。
GoMind 	Go中的简单神经网络库。
goml 	Go中的在线机器学习。
Goptuna 	用于Go语言编写的黑盒函数的贝叶斯优化框架。一切都会被优化。
goRecommend 	用Go编写的推荐算法库。
gorgonia 	基于图形的计算库，例如Theano for Go，它提供了用于构建各种机器学习和神经网络算法的原语。
gorse 	基于Go编写的协作过滤的离线推荐系统后端。
goscore 	用于PMML的Go Scoring API。
gosseract 	使用Tesseract C ++库的OCR（光学字符识别）软件包。
libsvm 	基于LIBSVM 3.14 libsvm的golang版本衍生作品。
neat 	用于增强拓扑神经演化（NEAT）的即插即用，并行Go框架。
neural-go 	go-在Go中实现的多层感知器网络，通过反向传播进行训练。
ocrserver 	一个简单的OCR API服务器，非常容易被Docker和Heroku部署。
onnx-go 	转到开放神经网络交换（ONNX）的接口。
probab 	概率分布函数。贝叶斯推断。用纯Go语言编写。
regommend 	建议和协作过滤引擎。
shield 	贝叶斯文本分类器，具有灵活的标记器和Go的存储后端。
tfgo 	易于使用的Tensorflow绑定：简化了官方Tensorflow Go绑定的使用。在Go中定义计算图，加载并执行经过Python训练的模型。
Varis 	Golang神经网络。

## 金融

包	说明
unioffice 	Pure Go库，用于创建和处理Office Word（.docx），Excel（.xlsx）和Powerpoint（.pptx）文档。
excelize 	Golang库用于读取和写入Microsoft Excel™（XLSX）文件。
go-excel 	一个简单而轻便的阅读器，可以将类似于related-db的excel读取为表格。
goxlsxwriter 	libxlsxwriter的Golang绑定，用于编写XLSX（Microsoft Excel）文件。
xlsx 	用于简化在Go程序中读取Microsoft Excel最新版本使用的XML格式的库。
xlsx 	在Go程序中快速/安全地读取/更新您现有的Microsoft Excel文件的方法。

## 自然语言处理

包	说明
getlang 	快速自然语言检测程序包。
go-i18n 	用于处理本地化文本的软件包和一个随附工具。
go-mystem 	CGo与Yandex.Mystem的绑定-俄罗斯形态分析仪。
go-nlp 	用于处理离散概率分布的实用程序和其他可用于执行NLP工作的工具。
go-pinyin 	CN Hanzi至Hanyu拼音转换器。
go-stem 	搬运程序阻止算法的实现。
go-unidecode 	Unicode文本的ASCII音译。
go2vec 	用于word2vec嵌入的阅读器和实用程序功能。
gojieba 	这是一个围棋实施解霸其中中国分词算法。
golibstemmer 	雪球库libstemmer库的绑定，包括porter 2。
gotokenizer 	基于字典和Goram语言的Bigram语言模型的标记器。（现在仅支持中文细分）
gounidecode 	Go的Unicode音译器（也称为unidecode）。
gse 	进行有效的文本分割；支持英语，中文，日语等。
icu 	CGO结合为ICU4C C库检测和转换功能。保证与版本50.1兼容。
kagome 	用纯Go语言编写的JP形态分析仪。
libtextcat 	libtextcat C库的Cgo绑定。保证与2.2版兼容。
MMSEGO 	这是MMSEG的GO实现，它是中文分词算法。
nlp 	从字符串中提取值，并用nlp填充您的结构。
nlp 	支持LSA（潜在语义分析）的自然语言处理库。
paicehusk 	Paice / Husk提取算法的Golang实现。
petrovich 	彼得罗维奇（Petrovich）是库，在给定的语法情况下使用俄语名称。
porter 	这是Martin Porter的Porter干算法的C实现的相当简单的移植。
porter2 	非常快的Porter 2 提取器。
prose 	用于文本处理的库，支持标记化，词性标记，命名实体提取等。仅限英语。
RAKE.go 	快速自动关键字提取算法（RAKE）的Go端口。
segment 	用于执行Unicode标准附件＃29中所述的Unicode文本分段的Go库
sentences 	句子标记器：将文本转换为句子列表。
shamoji 	shamoji是用Go编写的单词过滤程序包。
snowball 	Go的雪球茎端口（cgo包装器）。提供单词词干提取功能Snowball本机。
stemmer 	用于Go编程语言的Stemmer软件包。包括英语和德语词干。
textcat 	Go软件包，用于基于n-gram的文本分类，并支持utf-8和原始文本。
whatlanggo 	Go的自然语言检测程序包。支持84种语言和24种脚本（书写系统，例如拉丁语，西里尔字母等）。
when 	自然EN和RU语言日期/时间分析器具有可插拔的规则。

## 网络

包	说明
arp 	包arp实现ARP协议，如RFC 826中所述。
buffstreams 	通过TCP流化协议缓冲区数据变得容易。
canopus 	CoAP客户端/服务器实施（RFC 7252）。
cidranger 	Go的快速IP到CIDR查找。
dhcp6 	软件包dhcp6实现了DHCPv6服务器，如RFC 3315中所述。
dns 	使用DNS的Go库。
ether 	用于发送和接收以太网帧的跨平台Go软件包。
ethernet 	程序包ethernet实施IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的封送处理。
fasthttp 	软件包fasthttp是Go的一种快速HTTP实现，比net / http快10倍。
fortio 	负载测试库和命令行工具，高级回显服务器和Web UI。允许指定设置的每秒查询负载，并记录延迟直方图和其他有用的统计数据并对其进行图形化。Tcp，Http，gRPC。
ftp	 程序包ftp实现RFC 959中所述的FTP客户端。
gev 	gev是基于Reactor模式的轻量级，快速，无阻塞的TCP网络库。
gmqtt 	Gmqtt是一个灵活的高性能MQTT代理库，它完全实现了MQTT协议V3.1.1。
gnet 	gnet是一个高性能的，用纯围棋轻便，非阻塞，事件循环网络库。
gNxI 	使用gNMI和gNOI协议的网络管理工具的集合。
go-getter 	Go库，用于使用URL从各种来源下载文件或目录。
go-powerdns 	Golang的 PowerDNS API绑定。
go-stun 	STUN客户端的Go实现（RFC 3489和RFC 5389）。
gobgp 	使用Go编程语言实现的BGP。
golibwireshark 	软件包golibwireshark使用libwireshark库来解码pcap文件并分析解剖数据。
gopacket 	Go库，用于使用libpcap绑定进行数据包处理。
gopcap 	libpcap的包装器。
goshark 	软件包goshark使用tshark解码IP数据包并创建数据结构以分析数据包。
gosnmp 	用于执行SNMP操作的本机Go库。
gosocsvr 	套接字服务器变得简单。
gotcp 	用于快速编写tcp应用程序的Go软件包。
grab 	用于管理文件下载的软件包。
graval 	实验性FTP服务器框架。
HTTPLab 	HTTPLabs可让您检查HTTP请求并伪造响应。
iplib 	受python ipaddress和ruby ipaddr启发而使用IP地址（net.IP，net.IPNet）的库
jazigo 	Jazigo是用Go语言编写的工具，用于检索多个网络设备的配置。
kcp-go 	KCP-快速可靠的ARQ协议。
kcptun 	基于KCP协议的极其简单和快速的udp隧道。
lhttp 	强大的websocket框架，可更轻松地构建IM服务器。
linkio 	用于读取器/写入器接口的网络链接速度模拟。
llb 	这是代理服务器的非常简单但快速的后端。对于零内存分配和快速响应的快速重定向到预定义域很有用。
mdns 	Golang中的简单mDNS（多播DNS）客户端/服务器库。
mqttPaho 	Paho Go客户端提供了一个MQTT客户端库，用于通过TCP，TLS或WebSockets连接到MQTT代理。
NFF-Go 	用于快速开发云和裸机（以前的YANFF）的高性能网络功能的框架。
packet 	通过TCP和UDP发送数据包。如果需要，它可以缓冲消息和热交换连接。
peerdiscovery 	Pure Go库，用于使用UDP多播的跨平台本地对等发现。
portproxy 	简单的TCP代理，它将不支持它的API添加到CORS支持中。
publicip 	软件包publicip返回您的面向公众的IPv4地址（互联网出口）。
quic-go 	在纯Go中实现QUIC协议。
raw 	包raw允许在设备驱动程序级别为网络接口读取和写入数据。
sftp 	程序包sftp实现SSH文件传输协议，如https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt
ssh 	用于构建SSH服务器的高级API（包装crypto / ssh）。
sslb 	这是一个超级简单的负载均衡器，只是一个实现某种性能的小项目。
stun 	实施RFC 5389 STUN协议。
tcp_server 	用于更快地构建tcp服务器的Go库。
tspool 	TCP库使用工作池来提高性能并保护您的服务器。
utp 	围棋UTP微传输协议的实现。
water 	简单的TUN / TAP库。
webrtc 	WebRTC API的纯Go实现。
winrm 	进入WinRM客户端以在Windows计算机上远程执行命令。
xtcp 	具有同步全双工通信，安全关闭，自定义协议的TCP Server Framework。

## 视频

包	说明
go-astisub 	在GO中处理字幕（.srt，.stl，.ttml，.webvtt，.ssa / .ass，图文电视，.smi等）。
go-astits 	在GO中本地解析和解复用MPEG传输流（.ts）。
go-m3u8 	Apple m3u8播放列表的解析器和生成器库。
goav 	FFmpeg的综合Go绑定。
gst 	GStreamer的绑定。
libgosubs 	go的字幕格式支持。支持.srt，.ttml和.ass。
libvlc-go 	libvlc 2.X / 3.X / 4.X的绑定（由VLC媒体播放器使用）。
m3u8 	Apple HLS的M3U8播放列表的解析器和生成器库。
v4l 	用Go编写的Linux视频捕获库。



## 开源书籍

书籍名	推荐理由
Go palyground	不用搭建本地 Go 环境，在线就编写 Go 的代码
Go实战开发	作者是著名的 Go 开源项目 beego 的作者，他的最佳实践非常值得阅读
Go Web 编程	跟前面一本书作者是同一位，讲的是web开发
Go语言标准库	对标准库的介绍
Go入门指南	比较适合新手，内容相对基础一些
Go语言圣经	书如其名
Go语言中文网	找对圈子，学的更快
菜鸟教程	这个网站非常适合快速上手某门语言
Go语言高级编程	内容适合进阶
go语言原本	欧神出品，虽然号称进度只有9.9%/100%，但不妨碍它的优秀，值得一看
golang设计模式	设计模式 Golang实现，《研磨设计模式》的golang实现
Go语言四十二章经	可以对比查漏补缺