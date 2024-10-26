# 关注秀才！学习最热门web3技术+go语言！学习方向不迷路！
**视频都在抖音上,搜索@跟着秀才学编程，进入java学go语言双向就业合集观看学习！**</br>
**【超全golang面试题合集+golang学习指南+golang知识图谱+成长路线】一份涵盖大部分golang程序员所需要掌握的核心知识。</br>**
https://camo.githubusercontent.com/14ae0ae04052757a75e9f3790912ca4fde5d606e4c02d3f96c5f985fed3b4a56/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f7869616f626169546563682f696d6167652f2545352539302538452545372541422541462545362538382539302545392539352542462545382542372541462545372542412542462e706e67


**后续文章和内容会不断更新到 github项目 中，欢迎关注。</br>**
**大家好，我是秀才。大家知道，我一直以来都是golang的忠实粉丝，**</br>
**在学习和参与面试的过程中遇到过很多golang的问题。**</br>
**最近花了些时间整理了一下后端程序员成长路线和高频面试题，**</br>
**这是一份涵盖大部分后端程序员所需要掌握的核心知识。**</br>

### 最后</br>

**不满足于看八股文，可以尝试拿着岗位要求来进行AI押题。**</br>
**基础不牢，缺乏实战项目，想快速成为中大厂Go/Java工程师？</br>
加入秀才web3+go训练营！实现双向远程就业！**</br>

## 基础入门
### 新手

### Golang开发新手常犯的50个错误
#### 数据类型
1. 连nil切片和空切片一不一样都不清楚？</br>那BAT面试官只好让你回去等通知了。</br>
2. golang面试题：字符串转成byte数组，会发生内存拷贝吗？</br>
3. golang面试题：翻转含有中文、数字、英文字母的字符串</br>
4. golang面试题：拷贝大切片一定比小切片代价大吗？</br>
5. map不初始化使用会怎么样</br>
6. map不初始化长度和初始化长度的区别</br>
7. map承载多大，大了怎么办</br>
8. map的iterator是否安全？</br>能不能一边delete一边遍历？</br>
9. 字符串不能改，那转成数组能改吗，怎么改</br>
10. 怎么判断一个数组是否已经排序</br>
11. 普通map如何不用锁解决协程安全问题</br>
12. array和slice的区别</br>
13. golang面试题：json包变量不加tag会怎么样？</br>
14. golang面试题：reflect（反射包）如何获取字段tag？</br>
15. 为什么json包不能导出私有变量的tag？</br>
16. 零切片、空切片、nil切片是什么</br>
17. slice深拷贝和浅拷贝</br>
18. map触发扩容的时机，满足什么条件时扩容？</br>
19. map扩容策略是什么</br>
20. 自定义类型切片转字节切片和字节切片转回自动以类型切片</br>
21. make和new什么区别</br>
22. slice ，map，chanel创建的时候的几个参数什么含义</br>
23. slice，len，cap，共享，扩容</br>
24. 线程安全的map怎么实现</br>
25. go slice 和 array 区别</br>
26. go struct能不能比较？</br>
27. map如何顺序读取？</br>
28. go中怎么实现set</br>
29. map 的扩容机制是什么？</br>
30. 使用值为 nil 的 sice、map 会发生什么？</br>
31. Golang 有没有 this 指针？</br>
32. Golang 语言中局部变量和全局变量的缺省值是什么</br>
33. Golang 中的引用类型包含哪些?</br>
34. 使用range 迭代 map 是有序的吗?</br>
35. slice 的扩容机制是什么？</br>
36. Golang 中指针运算有哪些?
37. 类型的值可以修改吗？</br>
38. 解析 JSON 数据时，默认将数值当做哪种类型
39. array 类型的值作为函数参数是引用传递还是值传递？</br>

#### 流程控制
1. 昨天那个在for循环里append元素的同事，今天还在么？</br>

2. golang面试官：for select时，如果通道已经关闭会怎么样？</br>如果只有一个case呢？</br>
3. go defer（for defer）
4. select可以用于什么？</br>
5. context包的用途？</br>
6. select 可以用于实现哪些功能？</br>
7. 在循杯内执行 defer 语句会发生什么?</br>
8. switch 中如何强制执行下一个 case 代码块?</br>
9. 如何从 panic 中恢复?</br>

## 进阶

### 包管理
学go mod就够了！</br>

### 优化
1. golang面试题：怎么避免内存逃逸？</br>

2. golang面试题：简单聊聊内存逃逸？</br>
3. 给大家丢脸了，用了三年golang，我还是没答对这道内存泄漏题</br>
4. 内存碎片化问题</br>
5. chan相关的goroutine泄露的问题</br>
6. string相关的goroutine泄露的问题</br>
7. 你一定会遇到的内存回收策略导致的疑似内存泄漏的问题</br>
8. sync.Pool的适用场景</br>
9. go1.13sync.Pool对比go1.12版本优化点</br>

### 并发编程
1. golang面试题：对已经关闭的的chan进行读写，会怎么样？</br>为什么？</br>

2. golang面试题：对未初始化的的chan进行读写，会怎么样？</br>为什么？</br>
3. sync.map 的优缺点和使用场景</br>
4. sync.Map的优化点</br>
5. 主协程如何等其余协程完再操作</br>
6. 有缓存的channel和没有缓存的channel区别是什么？</br>
7. 协程通信方式有哪些？</br>
8. channel底层实现</br>
9. 读写锁底层是怎么实现的？</br>
10. 请你说说golang的CSP思想</br>
11. channel 是怎么保证线程安全？</br>

### 高级特性
1. golang面试题：能说说uintptr和unsafe.Pointer的区别吗？</br>

2. golang 面试题：reflect（反射包）如何获取字段 tag？</br>为什么 json 包不能导出私有变量的 tag？</br>
3. 协程和线程的差别</br>
4. 垃圾回收的过程是怎么样的？</br>
5. 什么是写屏障、混合写屏障，如何实现？</br>
6. 开源库里会有一些类似下面这种奇怪的用法：var _ io.Writer = (*myWriter)(nil)，是为什么？</br>

### GMP模型

1. 动图图解，GMP里为什么要有P</br>

2. 协程之间是怎么调度的</br>
3. gc的stw是怎么回事</br>
4. 利用golang特性，设计一个QPS为500的服务器</br>
5. 为什么gc会让程序变慢</br>
6. 开多个线程和开多个协程会有什么区别</br>
7. 两个interface{} 能不能比较</br>
8. 必须要手动对齐内存的情况</br>
9. go栈扩容和栈缩容，连续栈的缺点</br>
10. golang怎么做代码优化</br>
11. golang隐藏技能:怎么访问私有成员</br>
12. 协程可以自己主动让出 CPU 吗？</br>
13. 断言时会发生拷贝吗</br>
14. 接口是怎么实现的？</br>
15. 协程与进程，线程的区别是什么？协程有什么优势？</br>
16. 为什么小对象多了会造成 gc 压力?</br>
17. 一个协程能保证绑定在一个内核线程上吗？</br>
18. 闭包怎么实现的,闭包的主要应用场景</br>
19. 两次 GC 周期重叠会引发什么问题，GC 触发机制是什么样的？</br>
20. Goroutinue 什么时候会被挂起？</br>
21. Data Race 问题怎么检测？怎么解决?</br>
22. Golang 触发异常的场景有哪些?</br>
23. net/http包中client如何实现长连接？</br>
24. net/http怎么做连接池和长链接？</br>

## golang进阶面试题
### 问题排查
trace</br>
pprof</br>
什么是 goroutine 泄漏?</br>
当go服务部署到线上了，发现有内存泄露，该怎么处理</br>

### 源码阅读
1. sync.map</br>

2. net/http</br>
3. i/o timeout ， 希望你不要踩到这个net/http包的坑</br>
4. mutex</br>
5. channel</br>
6. context</br>
7. select实现原理</br>
8. main函数背后的启动过程</br>
9. 内存管理</br>
10. GC垃圾回收</br>
11. timer</br>

### 实践常用工具
mysql建表语句转golang struct</br>
json转golang struct</br>
toml转golang struct</br>
yaml转golang struct</br>


### 图解网络基础
1. 漫画图解HTTP知识点+面试题</br>

2. TCP粘包 数据包：我只是犯了每个数据包都会犯的错</br>
3. 30张图带你搞懂！路由器，集线器，交换机，网桥，光猫有啥区别？</br>
4. 既然IP层会分片，为什么TCP层也还要分段？</br>
5. 断网了，还能ping通 127.0.0.1 吗？为什么？</br>
6. 连接一个 IP 不存在的主机时，握手过程是怎样的？</br>
7. 动图图解！代码执行send成功后，数据就发出去了吗？</br>
8. 活久见！TCP两次挥手，你见过吗？那四次握手呢？</br>
9. 动图图解！收到RST，就一定会断开TCP连接吗？</br>
10. 动图图解！没有accept，能建立TCP连接吗？</br>
11. HTTP 是无状态的吗？需要保持状态的场景应该怎么做？</br>
12. 粘包如何解决?</br>
13. RestFul 是什么？RestFul 请求的 URL 有什么特点？</br>
14. 一次url访问会经历哪些过程</br>
15. TCP 三次握手以及四次挥手的流程。为什么需要三次握手以及四次挥手？</br>
16. TCP的拥塞控制具体是怎么实现的？</br>UDP有拥塞控制吗？</br>
17. 是否了解中间人劫持原理</br>
18. TCP 与 UDP 在网络协议中的哪一层，他们之间有什么区别？</br>
19. HTTP 与 HTTPS 有哪些区别？</br>
20. select和epoll区别</br>
21. TCP 如何实现数据有序性？</br>
22. TCP长连接和短连接有那么不同的使用场景？</br>
23. TIME_WAIT时长，为什么？</br>
24. 什么是零拷贝？</br>
25. HTTP 简述 HTTP 的 keepalive 的原理和使用场景</br>
26. Cookie 和 Session 的关系和区别是什么？</br>
27. DNS 查询服务器的基本流程是什么？</br>DNS 劫持是什么？</br>
28. libevent结构，内部实现</br>
29. 简述对称与非对称加密的概念</br>
30. epoll中的ET和LT模式</br>
31. JWT 的原理和校验机制</br>
32. TCP 怎么保证可靠传输？</br>
33. 介绍下proactor和reactor</br>
34. Accept发生在三次握手哪个阶段</br>
35. RPC 的调用过程</br>
36. tcp的可靠性体现在哪里</br>
37. 如何解决 TCP 传输丢包问题？</br>
38. 什么是 ARP 协议？简述其使用场景</br>
39. http和https区别</br>
40. DDOS 攻击原理，如何防范它？</br>
41. 如何防止传输内容被篡改？</br>
42. 介绍下滑动窗口</br>
43. 三次握手四次握手详细过程，越详细越好</br>
44. 什么是中间人攻击？如何防止攻击？</br>
45. TCP 半连接发生场景</br>
46. reactor的组成</br>
47. udp包长度</br>
48. IP为什么要分片</br>
49. OSI 七层模型，TCP，IP 属于哪一层？</br>
50. 数据包乱序会处理？</br>
51. 什么是 SYN flood，如何防止这类攻击？</br>
52. WebSocket 是如何进行传输的</br>
53. 为什么需要序列化？有什么序列化的方式？</br>
54. 有chunked的时候contentlength是什么样子</br>
55. 如何设计一个可靠的udp</br>
56. TCP 中常见的拥塞控制算法有哪些？</br>
57. 如何设置非阻塞</br>
58. 什么是跨域，什么情况下会发生跨域请求？</br>
59. Udp的接收缓冲区和发送缓冲区和tcp的区别</br>
60. 什么时候需要TCP四次挥手？</br>
61. traceroute 有什么作用？</br>
62. HTTP 的方法有哪些？</br>
63. TIME_WAIT危害</br>
64. select什么情况返回0</br>
65. 半连接在哪个阶段</br>
66. TCP 的 keepalive 了解吗？</br>说一说它和 HTTP 的 keepalive 的区别？</br>
67. 简述常见的 HTTP 状态码的含义（30从系统层面上，UDP 如何保证尽量可靠？</br>
68. 指针与引用的区别</br>
69. iPv4 和 iPv6 的区别</br>
70. 项目中说用到线程池，开多大，为什么运用线程池？</br>
71. 如何设计 API 接口使其实现幂等性？</br>
72. TCP 的 TIME_WAIT 和 CLOSE_WAIT</br>
73. HTTP 报文头部的组成结构</br>
74. RestFul 与 RPC 的区别是什么？RestFul 的优点在哪里？</br>
75. 从输入 URL 到展现页面的全过程</br>
76. 什么是 TCP 粘包和拆包？</br>
77. HTTP 中 GET 和 POST 区别</br>
78. 讲一下拥塞控制和流量控制</br>
79. TCP 协议的延迟 ACK 和累计应答</br>
80. TCP 挥手时出现大量 CLOSE_WAIT 或 TIME_WAIT 怎么解决？</br>
81. ARP协议工作流程</br>
82. tcp与udp的区别以及应用场景</br>
83. HTTPS 的加密与认证过程</br>
84. TCP 中 SYN 攻击是什么？如何防止？</br>
85. HTTP 短链接与长链接的区别</br>
86. TCP 的报文头部结构</br>
87. http长连接与短连接的区别</br>
88. TCP 滑动窗口以及重传机制</br>
89. seq为1000，发送了1000个数据，下一个seq是多少?</br>
90. chunked块了解？介绍下</br>
91. BGP 协议和 OSPF 协议的区别</br>
92. 简述在四层和七层网络协议中负载均衡的原理</br>
93. http协议格式，几种方法，功能是什么</br>
94. syn如果丢了，重传多少次</br>
95. epoll可读情况有哪些</br>

### 操作系统
1. 创建线程有多少种方式？</br>

2. 如何调试服务器内存占用过高的问题？</br>
3. 简述操作系统如何进行内存管理</br>
4. 简述创建进程的流程</br>
5. 简述操作系统中 malloc 的实现原理</br>
6. 简述僵尸进程和孤儿进程及其危害和处理</br>
7. 两个线程交替打印一个共享变量</br>
8. 进程通信中的管道实现原理是什么？</br>
9. 简述同步与异步的区别，阻塞与非阻塞的区别</br>
10. malloc 创建的对象在堆还是栈中？</br>
11. 死锁产生的条件、死锁避免方法</br>
12. 进程的三状态模型、五状态模型、七状态模型</br>
13. 什么情况下，进程会进行切换？</br>
14. Linux 系统态与用户态，什么时候会进入系统态？</br>
15. Linux 下如何查看端口被哪个进程占用？</br>
16. 共享内存是如何实现的？</br>
17. 进程有多少种状态？</br>
18. 线程间有哪些通信方式？</br>
19. Linux 下如何排查 CPU 以及 内存占用过多？</br>
20. 操作系统中，虚拟地址与物理地址之间如何映射？</br>
21. CPU L1, L2缓存是什么</br>
22. 信号量是如何实现的？</br>
23. 什么时候会由用户态陷入内核态？</br>
24. Linux 如何查看实时的滚动日志？</br>
25. Linux 进程调度的算法</br>
26. 简述分页与分段，分页与分段的区别</br>
27. Linux 虚拟内存的页面置换算法</br>
28. Linux 中虚拟内存和物理内存有什么区别？有什么优点？</br>
29. traceroute 命令的原理</br>
30. 操作系统是通过什么机制触发系统调用的？</br>
31. Linux 零拷贝的原理</br>
32. 系统调用的过程是怎样的？</br>
33. Linux 的 IO模型有哪些</br>
34. 简述自旋锁与互斥锁的使用场景</br>
35. 多线程和多进程的区别是什么？</br>
36. 简述几个常用的 Linux 命令以及他们的功能</br>
37. 进程空间从高位到低位都有些什么？</br>
38. 简述缓冲区溢出及其危害</br>
39. mmap 的使用场景以及原理</br>
40. BIO、NIO 有什么区别？</br>怎么判断写文件时 Buffer 已经写满？</br>
41. 线程有多少种状态，状态之间如何转换</br>
42. 简述操作系统中的缺页中断</br>
43. Linux 下如何查看 CPU 荷载，正在运行的进程，某个端口对应的进程？</br>
44. 进程和线程之间有什么区别？</br>
45. 进程间有哪些通信方式？</br>
46. 为什么进程切换慢，线程切换快？</br>
47. 线程从进程继承了哪些资源？</br>线程独享哪些资源？</br>
48. Linux 页大小是多少？</br>
49. select, poll, epoll 的使用场景以及区别，epoll 中水平触发以及边缘触发有什么不同？</br>

### 数据库
1. 数据库三大范式是什么</br>

2. mysql有关权限的表都有哪几个</br>
3. MySQL的binlog有有几种录入格式？分别有什么区别？</br>
4. mysql有哪些数据类型</br>
5. MySQL存储引擎MyISAM与InnoDB区别</br>
6. MyISAM索引与InnoDB索引的区别？</br>
7. InnoDB引擎的4大特性</br>
8. 存储引擎选择</br>
9. 什么是索引？</br>
10. 索引有哪些优缺点？</br>
11. **索引使用场景（重点）**</br>
12. 索引有哪几种类型？</br>
13. 索引的数据结构（b树，hash）</br>
14. 索引的基本原理</br>
15. 索引算法有哪些？</br>
16. 索引设计的原则？</br>
17. 创建索引的原则</br>
18. 创建索引的三种方式，删除索引</br>
19. 创建索引时需要注意什么？</br>
20. 使用索引查询一定能提高查询的性能吗？为什么</br>
21. 百万级别或以上的数据如何删除</br>
22. 前缀索引</br>
23. 什么是最左前缀原则？什么是最左匹配原则</br>
24. B树和B+树的区别</br>
25. 使用B树的好处</br>
26. 使用B+树的好处</br>
27. Hash索引和B+树所有有什么区别或者说优劣呢?</br>
28. 数据库为什么使用B+树而不是B树</br>
29. B+树在满足聚簇索引和覆盖索引的时候不需要回表查询数据，</br>
30. 什么是聚簇索引？</br>何时使用聚簇索引与非聚簇索引</br>
31. 非聚簇索引一定会回表查询吗？</br>
32. 联合索引是什么？</br>为什么需要注意联合索引中的顺序？</br>
33. 什么是数据库事务？</br>
34. 事物的四大特性(ACID)介绍一下?
35. 什么是脏读？</br>幻读？</br>不可重复读？</br>
36. 什么是事务的隔离级别？</br>MySQL的默认隔离级别是什么？</br>
37. 对MySQL的锁了解吗</br>
38. 隔离级别与锁的关系</br>
39. 按照锁的粒度分数据库锁有哪些？锁机制与InnoDB锁算法</br>
40. 从锁的类别上分MySQL都有哪些锁呢？像上面那样子进行锁定岂不是有点阻碍并发效率了</br>
41. MySQL中InnoDB引擎的行锁是怎么实现的？</br>
42. InnoDB存储引擎的锁的算法有三种</br>
43. 什么是死锁？</br>怎么解决？</br>
44. 数据库的乐观锁和悲观锁是什么？怎么实现的？</br>
45. 为什么要使用视图？</br>什么是视图？</br>
46. 视图有哪些特点？</br>
47. 视图的使用场景有哪些？</br>
48. 视图的优点</br>
49. 视图的缺点</br>
50. 什么是游标？</br>
51. 存储过程与函数</br>
52. 什么是存储过程？</br>有哪些优缺点？</br>
53. 什么是触发器？</br>触发器的使用场景有哪些？</br>
54. MySQL中都有哪些触发器？</br>
55. 常用SQL语句</br>
56. SQL语句主要分为哪几类</br>
57. 超键、候选键、主键、外键分别是什么？</br>
58. SQL 约束有哪几种？</br>
59. 六种关联查询</br>
60. 什么是子查询</br>
61. 子查询的三种情况</br>
62. mysql中 in 和 exists 区别</br>
63. varchar与char的区别</br>
64. varchar(50)中50的涵义</br>
65. int(20)中20的涵义</br>
66. mysql为什么这么设计</br>
67. mysql中int(10)和char(10)以及varchar(10)的区别</br>
68. FLOAT和DOUBLE的区别是什么？</br>
69. drop、delete与truncate的区别</br>
70. UNION与UNION ALL的区别？</br>
71. 如何定位及优化SQL语句的性能问题？创建的索引有没有被使用到?或者说怎么才可以知道这条语句运行很慢的原因？</br>
72. SQL的生命周期？</br>
73. 大表数据查询，怎么优化
74. 超大分页怎么处理？</br>
75. mysql 分页怎么实现</br>
76. 慢查询日志怎么看</br>
77. 关心过业务系统里面的sql耗时吗？统计过慢查询吗？对慢查询都怎么优化过？</br>
78. 为什么要尽量设定一个主键？</br>
79. 主键使用自增ID还是UUID？</br>
80. 字段为什么要求定义为not null？</br>
81. 如果要存储用户的密码散列，应该使用什么字段进行存储？</br>
82. 优化查询过程中的数据访问</br>
83. 优化长难的查询语句</br>
84. 优化特定类型的查询语句</br>
85. 优化关联查询</br>
86. 优化子查询</br>
87. 优化LIMIT分页</br>
88. 优化UNION查询</br>
89. 优化WHERE子句</br>

### 数据库优化
1. 为什么要优化</br>

2. 数据库结构优化</br>
3. MySQL数据库cpu飙升到500%的话他怎么处理？</br>
4. 大表怎么优化？某个表有近千万数据，CRUD比较慢，如何优化？分库分表了是怎么做的？分表分库了有什么问题？</br>有用到中间件么？他们的原理知道么？</br>
5. 垂直分表适用场景</br>
6. 水平分表适用场景</br>
7. 水平切分的缺点</br>
8. MySQL的复制原理以及流程</br>
9. 读写分离有哪些解决方案？</br>
10. 备份计划，mysqldump以及xtranbackup的实现原理</br>
11. 数据表损坏的修复方式有哪些？</br>


## 常用官方包说明
常用第三方包说明</br>
常用框架</br>
完整标准库列表</br>
优秀的第三方库</br>
音频和音乐</br>
数据结构:Go中的通用数据结构和算法</br>
分布式系统:Go中的通用数据结构和算法</br>
电子邮件:实现电子邮件创建和发送的库和工具</br>
嵌入式脚本语言:在go代码中嵌入其他语言</br>
错误处理</br>
处理文件和文件系统的库</br>
金融:会计和财务软件包</br>
游戏开发:游戏开发相关库</br>
地理位置:地理相关的位置信息和工具库</br>
编译器相关:转到其他语言</br>
Goroutines:用于管理和使用Goroutines的工具</br>
图形界面:用于构建GUI应用程序的库</br>
图片:用于处理图像的库</br>
物联网:物联网设备编程库</br>
JSON格式:用于处理JSON的库</br>
机器学习:常用机器学习库</br>
微软办公软件</br>
自然语言处理</br>
网络:与网络各层配合使用的库</br>
视频:用于处理视频的库</br>



## 其他
### 1.常用包
**常用包	说明**</br>
fmt	实现格式化的输入输出操作，其中的fmt.Printf()和fmt.Println()是开发者使用最为频繁的函数。  </br>
io	实现了一系列非平台相关的IO相关接口和实现，比如提供了对os中系统相关的IO功能的封装。我们在进行流式读写（比如读写文件）时，通常会用到该包。  </br>
bufio	它在io的基础上提供了缓存功能。在具备了缓存功能后， bufio可以比较方便地提供ReadLine之类的操作。  </br>
strconv	提供字符串与基本数据类型互转的能力。  </br>
os	本包提供了对操作系统功能的非平台相关访问接口。接口为Unix风格。提供的功能包括文件操作、进程管理、信号和用户账号等。  </br>
sync	它提供了基本的同步原语。在多个goroutine访问共享资源的时候，需要使用sync中提供的锁机制。</br>  
flag	它提供命令行参数的规则定义和传入参数解析的功能。绝大部分的命令行程序都需要用到这个包。  </br>
encoding/json	JSON目前广泛用做网络程序中的通信格式。本包提供了对JSON的基本支持，比如从一个对象序列化为JSON字符串，或者从JSON字符串反序列化出一个具体的对象等。  </br>
http	通过http包，只需要数行代码，即可实现一个爬虫或者一个Web服务器，这在传统语言中是无法想象的。</br>


### 2. 常用第三方包

**包	地址**</br>
数据库操作	github.com/jinzhu/gorm</br>
github.com/go-xorm/xorm</br>
搜索es	github.com/olivere/elastic</br>
rocketmq操作	github.com/apache/rocketmq-client-go/v2</br>
rabbitmq 操作	github.com/streadway/amqp</br>
redis 操作	github.com/go-redis/redis</br>
etcd 操作	github.com/coreos/etcd/clientv3</br>
kafka	https://github.com/Shopify/sarama https://github.com/bsm/sarama-cluster</br>
excel 操作	github.com/360EntSecGroup-Skylar/excelize</br>
ppt 操作	golang.org/x/tools/cmd/present</br>
go-svg 操作	https://github.com/ajstarks/svgo</br>
go 布隆过滤器实现	https://github.com/AndreasBriese/bbloom</br>
json相关	https://github.com/bitly/go-simplejson
LRU Cache实现	https://github.com/bluele/gcache https://github.com/hashicorp/golang-lru</br>
go运行时函数替换	https://github.com/bouk/monkey</br>
toml	https://github.com/toml-lang/toml https://github.com/naoina/toml</br>
yaml	https://github.com/go-yaml/yaml</br>
viper	https://github.com/spf13/viper</br>
go key/value存储	https://github.com/etcd-io/bbolt</br>
基于ringbuffer的无锁golang workpool	https://github.com/Dai0522/workpool</br>
轻量级的协程池	https://github.com/ivpusic/grpool</br>
打印go的详细数据结构	https://github.com/davecgh/go-spew</br>
基于ringbuffer实现的队列	https://github.com/eapache/queue</br>
拼音	https://github.com/go-ego/gpy</br>
分词	https://github.com/go-ego/gse</br>
搜索	https://github.com/go-ego/riot</br>
windows COM	https://github.com/go-ego/cedar</br>
session	https://github.com/gorilla/sessions</br>
路由	https://github.com/gorilla/mux</br>
websocket	https://github.com/gorilla/websocket</br>
Action handler	https://github.com/gorilla/handlers</br>
csrf	https://github.com/gorilla/csrf</br>
context	https://github.com/gorilla/context</br>
过滤html标签	https://github.com/grokify/html-strip-tags-go</br>
可配置的HTML标签过滤	https://github.com/microcosm-cc/bluemonday</br>
根据IP获取地理位置信息	https://github.com/ipipdotnet/ipdb-go</br>
html转markdown	https://github.com/jaytaylor/html2text</br>
goroutine 本地存储	https://github.com/jtolds/gls</br>
彩色输出	https://github.com/mgutz/ansi</br>
表格打印	https://github.com/olekukonko/tablewriter</br>
reflect 更高效的反射API	https://github.com/modern-go/reflect2</br>
msgfmt (格式化字符串，将%更换为变量名)	https://github.com/modern-go/msgfmt</br>
可取消的goroutine	https://github.com/modern-go/concurrent</br>
深度拷贝	https://github.com/mohae/deepcopy</br>
安全的类型转换包	https://github.com/spf13/cast</br>
从文本中提取链接	https://github.com/mvdan/xurls</br>
字符串格式处理（驼峰转换）	https://godoc.org/github.com/naoina/go-stringutil</br>
文本diff实现	https://github.com/pmezard/go-difflib</br>
uuid相关	https://github.com/satori/go.uuid https://github.com/snluu/uuid</br>
去除UTF编码中的BOM	https://github.com/ssor/bom</br>
图片缩放	https://github.com/nfnt/resize</br>
生成 mock server	https://github.com/otokaze/mock</br>
go 性能上报到influxdb	https://github.com/rcrowley/go-metrics</br>
go zookeeper客户端	https://github.com/samuel/go-zookeeper</br>
go thrift	https://github.com/samuel/go-thrift</br>
MQTT 客户端	https://github.com/shirou/mqttcli</br>
hbase	https://github.com/tsuna/gohbase</br>
go 性能上报到influxdb	https://github.com/rcrowley/go-metrics</br>
go 性能上报到prometheus	https://github.com/deathowl/go-metrics-prometheus</br>
ps utils	https://github.com/shirou/gopsutil</br>
小数处理	https://github.com/shopspring/decimal</br>
结构化日志处理(json)	https://github.com/sirupsen/logrus</br>
命令行程序框架 cli	https://github.com/urfave/cli</br>
命令行程序框架 cobra	https://github.com/spf13/cobra</br>


### 3. 必看项目
**项目	地址	说明**</br>
gin	github.com/gin-gonic/gin	轻量级web框架，很多公司都是基于它进行魔改</br>
beego	github.com/beego/beego	也是web框架，比较全能</br>
kratos	github.com/go-kratos/kratos	bilibili开源的微服务框架，b站出品必属于精品</br>
TiDB	github.com/pingcap/tidb	见识过mysql性能瓶颈之后你会想要选择的一款数据库</br>


### 4. 完整标准库列表
**包	子包	说明**</br>
bufio	bytes	提供了对字节切片操作的函数</br>
crypto	收集了常见的加密常数</br>
errors	实现了操作错误的函数</br>
Expvar	为公共变量提供了一个标准的接口，如服务器中的运算计数器</br>
flag	实现了命令行标记解析</br>
fmt	实现了格式化输入输出</br>
hash	提供了哈希函数接口</br>
html	实现了一个HTML5兼容的分词器和解析器</br>
image	实现了一个基本的二维图像库</br>
io	提供了对I/O原语的基本接口</br>
log	它是一个简单的记录包，提供最基本的日志功能</br>
math	提供了一些基本的常量和数学函数</br>
mine	实现了部分的MIME规范</br>
net	提供了一个对UNIX网络套接字的可移植接口，包括TCP/IP、 UDP域名解析和UNIX域套接字</br>
os	为操作系统功能实现了一个平台无关的接口</br>
path	实现了对斜线分割的文件名路径的操作</br>
reflect	实现了运行时反射，允许一个程序以任意类型操作对象</br>
regexp	实现了一个简单的正则表达式库</br>
runtime	包含与Go运行时系统交互的操作，如控制goroutine的函数</br>
sort	提供对集合排序的基础函数集</br>
strconv	实现了在基本数据类型和字符串之间的转换</br>
strings	实现了操作字符串的简单函数</br>
sync	提供了基本的同步机制，如互斥锁</br>
syscall	包含一个低级的操作系统原语的接口</br>
testing	提供对自动测试Go包的支持</br>
time	提供测量和显示时间的功能</br>
unicode	Unicode编码相关的基础函数</br>
archive	tar	实现对tar压缩文档的访问</br>
zip	提供对ZIP压缩文档的读和写支持</br>
compress	bzip2	实现了bzip2解压缩</br>
flate	实现了RFC 1951中所定义的DEFLATE压缩数据格式</br>
gzip	实现了RFC 1951中所定义的gzip格式压缩文件的读和写</br>
lzw	实现了 Lempel-Ziv-Welch编码格式的压缩的数据格式</br>
zlib	实现了RFC 1950中所定义的zlib格式压缩数据的读和写</br>
container	heap	提供了实现heap.Interface接口的任何类型的堆操作</br>
lsit	实现了一个双链表</br>
ring	实现了对循环链表的操作</br>
crypto	aes	实现了AES加密（以前的Rijndael）</br>
cipher	实现了标准的密码块模式，该模式可包装进低级的块加密实现中</br>
des	实现了数据加密标准（ Data Encryption Standard，DES）和三重数据加密算法（ TripleData Encryption Algorithm， TDEA）</br>
dsa	实现了FIPS 186-3所定义的数据签名算法（ Digital Signature Algorithm）</br>
ecdsa	实现了FIPS 186-3所定义的椭圆曲线数据签名算法（ Elliptic Curve Digital SignatureAlgorithm）</br>
elliptic	实现了素数域上几个标准的椭圆曲线</br>
hmac	实现了键控哈希消息身份验证码（ Keyed-Hash Message Authentication Code，HMAC）</br>
md5	实现了RFC 1321中所定义的MD5哈希算法</br>
rand	实现了一个加密安全的伪随机数生成器</br>
rc4	实现了RC4加密，其定义见Bruce Schneier的应用密码学（ Applied Cryptography）</br>
rsa	实现了PKCS#1中所定义的RSA加密</br>
sha1	实现了RFC 3174中所定义的SHA1哈希算法</br>
sha256	实现了FIPS 180-2中所定义的SHA224和SHA256哈希算法</br>
sha512	实现了FIPS 180-2中所定义的SHA384和SHA512哈希算法</br>
subtle	实现了一些有用的加密函数，但需要仔细考虑以便正确应用它们</br>
tls	部分实现了RFC 4346所定义的TLS 1.1协议</br>
x509	可解析X.509编码的键值和证书</br>
x509/pkix	包含用于对X.509证书、 CRL和OCSP的ASN.1解析和序列化的共享的、低级的结构</br>
database	sql	围绕SQL提供了一个通用的接口</br>
sql/driver	定义了数据库驱动所需实现的接口，同sql包的使用方式</br>
debug	dwarf	提供了对从可执行文件加载的DWARF调试信息的访问，这个包对于实现Go语言的调试器非常有价值</br>
elf	实现了对ELF对象文件的访问。 ELF是一种常见的二进制可执行文件和共享库的文件格式。 Linux采用了ELF格式</br>
gosym	访问Go语言二进制程序中的调试信息。对于可视化调试很有价值</br>
macho	实现了对Mach-O对象文件的访问</br>
pe	实现了对PE（ Microsoft Windows Portable Executable）文件的访问</br>
encoding	ascii85	实现了ascii85数据编码，用于btoa工具和Adobe’s PostScript以及PDF文档格式</br>
asn1	实现了解析DER编码的ASN.1数据结构，其定义见ITU-T Rec X.690</br>
base32	实现了RFC 4648中所定义的base32编码</br>
base64	实现了RFC 4648中所定义的base64编码</br>
binary	实现了在无符号整数值和字节串之间的转化，以及对固定尺寸值的读和写</br>
csv	可读和写由逗号分割的数值（ csv）文件</br>
gob	管理gob流——在编码器（发送者）和解码器（接收者）之间进行二进制值交换</br>
hex	实现了十六进制的编码和解码</br>
json	实现了定义于RFC 4627中的JSON对象的编码和解码</br>
pem	实现了PEM（ Privacy Enhanced Mail）数据编码</br>
xml	实现了一个简单的可理解XML名字空间的XML 1.0解析器</br>
go	ast	声明了用于展示Go包中的语法树类型</br>
build	提供了构建Go包的工具</br>
doc	从一个Go AST（抽象语法树）中提取源代码文档</br>
parser	实现了一个Go源文件解析器</br>
printer	实现了对AST（抽象语法树）的打印</br>
scanner	实现了一个Go源代码文本的扫描器</br>
token	定义了代表Go编程语言中词法标记以及基本操作标记（ printing、 predicates）的常量</br>
hash	adler32	实现了Adler-32校验和</br>
crc32	实现了32位的循环冗余校验或CRC-32校验和</br>
crc64	实现了64位的循环冗余校验或CRC-64校验和</br>
fnv	实现了Glenn Fowler、 Landon Curt Noll和Phong Vo所创建的FNV-1和FNV-1a未加密哈希函数</br>
html	template	它自动构建HTML输出，并可防止代码注入</br>
image	color	实现了一个基本的颜色库</br>
draw	提供一些做图函数</br>
gif	实现了一个GIF图像解码器</br>
jpeg	实现了一个JPEG图像解码器和编码器</br>
png	实现了一个PNG图像解码器和编码器</br>
index	suffixarray	通过构建内存索引实现的高速字符串匹配查找算法</br>
io	ioutil	实现了一些实用的I/O函数</br>
log	syslog	提供了对系统日志服务的简单接口</br>
math	big	实现了多精度的算术运算（大数）</br>
cmplx	为复数提供了基本的常量和数学函数</br>
rand	实现了伪随机数生成器</br>
mime	multipart	实现了在RFC 2046中定义的MIME多个部分的解析</br>
net	http	提供了HTTP客户端和服务器的实现</br>
mail	实现了对邮件消息的解析</br>
rpc	提供了对一个来自网络或其他I/O连接的对象可导出的方法的访问</br>
smtp	实现了定义于RFC 5321中的简单邮件传输协议（ Simple Mail Transfer Protocol)</br>
textproto	实现了在HTTP、 NNTP和SMTP中基于文本的通用的请求/响应协议</br>
url	解析URL并实现查询转义</br>
http/cgi	实现了定义于RFC 3875中的CGI（通用网关接口）</br>
http/fcgi	实现了FastCGI协议</br>
http/httptest	提供了一些HTTP测试应用</br>
http/httputil	提供了一些HTTP应用函数，这些是对net/http包中的东西的补充，只不过相对不太常用</br>
http/pprof	通过其HTTP服务器运行时提供性能测试数据，该数据的格式正是pprof可视化工具需要的</br>
rpc/jsonrpc	为rpc包实现了一个JSON-RPC ClientCodec和ServerCodec</br>
os	exec	可运行外部命令</br>
user	通过名称和id进行用户账户检查</br>
path	filepath	实现了以与目标操作系统定义文件路径相兼容的方式处理文件名路径</br>
regexp	syntax	将正则表达式解析为语法树</br>
runtime	debug	包含当程序在运行时调试其自身的功能</br>
pprof	以pprof可视化工具需要的格式写运行时性能测试数据</br>
sync	atomic	提供了低级的用于实现同步算法的原子级的内存机制</br>
testing	iotest	提供一系列测试目的的类型，实现了Reader和Writer标准接口</br>
quick	实现了用于黑箱测试的实用函数</br>
script	帮助测试使用通道的代码</br>
text	scanner	为UTF-8文本提供了一个扫描器和分词器</br>
tabwriter	实现了一个写筛选器（ tabwriter.Writer），它可将一个输入的tab分割的列翻译为适当对齐的文本</br>
template	数据驱动的模板引擎，用于生成类似HTML的文本输出格式</br>
template/parse	为template构建解析树</br>
unicode/utf16	实现了UTF-16序列的的编码和解码</br>
unicode/utf8	实现了支持以UTF-8编码的文本的函数和常数</br>


### 5. 其他优秀的开源工具分类
**音频和音乐**</br>
包	说明</br>
EasyMIDI	EasyMidi是一个简单可靠的库，用于处理标准Midi文件（SMF）。</br>
flac	支持FLAC流的Native Go FLAC编码器/解码器。</br>
gaad	本机Go AAC比特流解析器。</br>
go-sox	用于go的libsox绑定。</br>
go_mediainfo	用于go的libmediainfo绑定。</br>
gosamplerate	用于go的libsamplerate绑定。</br>
id3v2	用于Go的快速，稳定的ID3解析和编写库。</br>
malgo	迷你音频库。</br>
minimp3	轻量级MP3解码器库。</br>
mix	为音乐应用程序基于序列转到本地音频混合器。</br>
mp3	Native Go MP3解码器。</br>
music-theory	Go中的音乐理论模型。</br>
Oto	在多个平台上播放声音的低级库。</br>
PortAudio	用于PortAudio音频I / O库的绑定。</br>
portmidi	绑定PortMidi。</br>
taglib	为taglib绑定。</br>
vorbis	“本机” Go Vorbis解码器（使用CGO，但没有依赖项）。</br>
waveform	Go程序包，能够从音频流生成波形图像。</br>

## 数据结构

**包	说明**</br>
algorithms	算法和数据结构。CLRS研究。</br>
binpacker	二进制打包程序和解包程序可帮助用户构建自定义二进制流。</br>
bit	具有额外的位旋转功能的Golang设置数据结构。</br>
bitset	实现位集的Go包。</br>
bloom	在Go中实现的Bloom过滤器。</br>
bloom	Golang Bloom过滤器实现。</br>
boomfilters	用于处理连续无界流的概率数据结构。</br>
concurrent-writer	高并发直接替换bufio.Writer。</br>
conjungo	一个小型，强大而灵活的合并库。</br>
count-min-log	执行Count-Min-Log草图：使用近似计数器进行近似计数（类似于Count-Min草图，但使用较少的内存）。</br>
crunch	Go包实现了用于轻松处理各种数据类型的缓冲区。</br>
cuckoofilter	Cuckoo过滤器：是Go中实现的计数布隆过滤器的很好替代。</br>
deque	高度优化的双端队列。</br>
deque	快速的环形缓冲区双端队列（双端队列）。</br>
dict	Go的类似Python的字典（dict）。</br>
encoding	Go的整数压缩库。</br>
go-adaptive-radix-tree	自适应基数树的 Go实现。</br>
go-datastructures	有用，高性能和线程安全的数据结构的集合。</br>
go-ef	Elias-Fano编码的Go实现。</br>
go-geoindex	内存中的地理索引。</br>
go-mcache	快速内存键：值存储/缓存库。指针缓存。</br>
go-rquad	具有有效点定位和邻居发现功能的区域四叉树。</br>
gocache	具有多个存储（内存，memcache，redis等），可链接，可加载，指标缓存等的完整Go缓存库。</br>
goconcurrentqueue	并发FIFO队列。</br>
gods	数据结构。容器，集合，列表，堆栈，地图，BidiMap，树，HashSet等。</br>
gofal	Go的小数api。</br>
golang-set	Go的线程安全和非线程安全高性能集。</br>
goset	Go的有用的Set集合实现。</br>
goskiplist	Go中的跳过列表实现。</br>
gota	Go的数据框，序列和数据整理方法的实现。</br>
hide	ID类型，将其编组进/出哈希以防止将ID发送给客户端。</br>
hilbert	Go程序包，用于在空间填充曲线（例如Hilbert和Peano曲线）之间映射值。</br>
hyperloglog	HyperLogLog实施，具有稀疏，LogLog-Beta偏差校正和TailCut空间减少功能。</br>
iter	C ++ STL迭代器和算法的实现。</br>
levenshtein	Levenshtein距离和相似性度量标准，具有可自定义的编辑费用和通用前缀的类似于Winkler的奖金。</br>
levenshtein	在Go中计算levenshtein距离的实现。</br>
mafsa	具有最小完美散列的MA-FSA实现。</br>
merkletree	merkle树的实现，可对数据结构的内容进行有效且安全的验证。</br>
mspm	用于信息检索的多字符串模式匹配算法。</br>
null	可空转到类型，可以被编组/解组到/从JSON。</br>
parsefields	用于解析类似JSON的日志的工具，以收集唯一的字段和事件。</br>
pipeline	具有扇入和扇出的管线的实现。</br>
ptrie	前缀树的实现。</br>
remember-go	缓存慢速数据库查询的通用接口（由redis，memcached，ristretto或内存支持）。</br>
ring	围棋实现了高性能，线程安全的布隆过滤器。</br>
roaring	实施压缩位集的软件包。</br>
set	使用LinkedHashMap的围棋设置简单的数据结构实现。</br>
skiplist	非常快的Go Skiplist实施。</br>
skiplist	Go中的跳过列表实现。</br>
timedmap	具有过期的键/值对的地图。</br>
treap	使用树堆的持久快速排序的地图。</br>
trie	Go中的Trie实现。</br>
ttlcache	内存中的LRU字符串接口{}映射，其中包含golang的到期时间。</br>
typ	空类型，安全的原始类型转换和从复杂结构中获取值。</br>
willf/bloom	Go包实现Bloom过滤器。</br>

## 分布式系统

**包	说明**</br>
celeriac	用于在Go中添加支持以交互和监视Celery工作者，任务和事件的库。</br>
consistent	具有受限负载的一致哈希</br>
dht	BitTorrent Kademlia DHT实施。</br>
digota	grpc电子商务微服务。</br>
dot	使用操作转换/ OT进行分布式同步。</br>
doublejump	改进后的Google的跳转一致性哈希。</br>
dragonboat	Go中功能齐全的高性能多组Raft库。</br>
drmaa	基于DRMAA标准的集群调度程序的作业提交库。</br>
dynamolock	DynamoDB支持的分布式锁定实现。</br>
dynatomic	将DynamoDB用作原子计数器的库。</br>
emitter-io	使用MQTT，Websockets和love构建的高性能，分布式，安全和低延迟的发布-订阅平台。</br>
flowgraph	基于流的编程包。</br>
gleam	用纯围棋和Luajit快速和可扩展的分布式的map / reduce系统，具有Luajit的高性能结合Go的高并发，单独运行或分发。</br>
glow	易于使用的可扩展的分布式大数据处理，Map-Reduce，DAG执行，全部在纯Go中进行。</br>
go-health	health-用于在服务中启用异步依赖项运行状况检查的库。</br>
go-jump	Google的“ Jump”一致性哈希函数的端口。</br>
go-kit	支持服务发现，负载平衡，可插拔传输，请求跟踪等的微服务工具包</br>
go-sundheit	建立用于支持为golang服务定义异步服务运行状况检查的库。</br>
gorpc	简单，快速和可扩展的RPC库，可实现高负载。</br>
grpc-go	gRPC的Go语言实现。基于HTTP / 2的RPC。</br>
hprose	十分新颖的RPC库，现在支持25种以上的语言。</br>
jsonrpc	jsonrpc软件包可帮助实现JSON-RPC 2.0。</br>
jsonrpc	JSON-RPC 2.0 HTTP客户端实现。</br>
KrakenD	具有中间件的超高性能API网关框架。</br>
liftbridge	NATS的轻量级，容错消息流。</br>
micro	可插拔的microService工具箱和分布式系统平台。</br>
NATS	用于微服务，IoT和云本机系统的轻量级高性能消息传递系统。</br>
outboxer	Outboxer是一个实现库模式的go库。</br>
pglock	PostgreSQL支持的分布式锁定实现。</br>
raft	HashiCorp的Raft共识协议的Golang实现。</br>
raft	ETCD中实现的Raft协议。</br>
rain	BitTorrent客户端和库。</br>
redis-lock	使用Redis的简化分布式锁定实现。</br>
resgate	用于构建REST，实时和RPC API的实时API网关，其中所有客户端都可以无缝同步。</br>
ringpop-go	Go应用程序的可扩展，容错应用程序层分片。</br>
rpcx	分布式可插拔RPC服务框架，例如阿里巴巴Dubbo。</br>
sleuth	用于在HTTP服务之间进行无主p2p自动发现和RPC的库（ZeroMQ）。</br>
tendermint	高性能中间件，用于使用Tendermint共识和区块链协议将以任何编程语言编写的状态机转换为拜占庭容错复制状态机。</br>
torrent	BitTorrent客户端软件包。</br>

## 电子邮件

**包	说明**</br>
chasquid	用Go编写的SMTP服务器。</br>
douceur	CSS内衬为您的HTML电子邮件。</br>
email	用于Go的强大而灵活的电子邮件库。</br>
go-dkim	DKIM库，用于签名和验证电子邮件。</br>
go-imap	用于客户端和服务器的IMAP库。</br>
go-message	Internet消息格式和邮件消息的流库。</br>
go-premailer	Go中HTML邮件的内联样式。</br>
go-simple-mail	使用SMTP保持活动状态和两个超时发送电子邮件的非常简单的程序包：连接和发送。</br>
Hectane	提供HTTP API的轻型SMTP客户端。</br>
hermes	Golang软件包，可生成干净的响应式HTML电子邮件。</br>
mailchain	将加密的电子邮件发送到用Go编写的区块链地址。</br>
mailgun-go	Go库，用于使用Mailgun API发送邮件。</br>
MailHog	通过Web和API界面进行电子邮件和SMTP测试。</br>
SendGrid	SendGrid的Go库，用于发送电子邮件。</br>
smtp	SMTP服务器协议状态机。</br>

## 嵌入式脚本语言

**包	说明</br>**
anko	用Go语言编写的可编写脚本的解释器。</br>
binder	转到基于gopher-lua的 Lua绑定库。</br>
cel-go	具有渐进式输入功能的快速，便携式，非图灵完整表达评估。</br>
expr	可以评估表达式的引擎。</br>
gentee	可嵌入的脚本编程语言。</br>
gisp	Go中的简单LISP。</br>
go-duktape	Go的Duktape JavaScript引擎绑定。</br>
go-lua	Lua 5.2 VM到纯Go的端口。</br>
go-php	Go的PHP绑定。</br>
go-python	与CPython C-API的幼稚go绑定。</br>
golua	Lua C API的绑定。</br>
gopher-lua	用Go编写的Lua 5.1 VM和编译器。</br>
gval	用Go编写的高度可定制的表达语言。</br>
ngaro	可嵌入的Ngaro VM实现，支持在Retro中编写脚本。</br>
otto	用Go编写的JavaScript解释器。</br>
purl	Go中嵌入的Perl 5.18.2。</br>
tengo	用于Go的字节码编译脚本语言。</br>

## 错误处理

**包	说明</br>**
emperror	Go库和应用程序的错误处理工具和最佳实践。</br>
errlog	可破解的软件包，用于确定错误的负责任的源代码（以及其他一些快速调试功能）。可插入任何现成的记录器。</br>
errors	下拉更换为标准库的错误包和github.com/pkg/errors。提供各种错误处理原语。</br>
errors	提供简单错误处理原语的软件包。</br>
errors	简单golang错误处理与分类元。</br>
errorx	具有堆栈跟踪，错误组成等的功能丰富的错误包。</br>
Falcon	一个简单但功能强大的错误处理软件包。</br>
go-multierror	Go（golang）软件包，用于将错误列表表示为单个错误。</br>
tracerr	带有堆栈跟踪和源代码片段的Golang错误。</br>
werr	错误包装程序为Go中的错误类型创建了一个包装程序，该包装程序捕获了调用它的文件，行和堆栈。</br>

## 文件

**包	说明</br>**
afero	Go的文件系统抽象系统。</br>
afs	Go的抽象文件存储（mem，scp，zip，tar，云：s3，gs）。</br>
bigfile	文件传输系统，支持使用http api，rpc调用和ftp客户端管理文件。</br>
checksum	计算大型文件的消息摘要，例如MD5和SHA256。</br>
flop	文件操作库，旨在与GNU cp镜像功能奇偶校验。</br>
go-csv-tag	tag-使用标签加载csv文件。</br>
go-decent-copy	复制human文件。</br>
go-exiftool	ExifTool的Go绑定，这是众所周知的库，用于从文件（图片，PDF，office，...）提取尽可能多的元数据（EXIF，IPTC等）。</br>
go-gtfs	在go中加载gtfs文件。</br>
notify	具有简单API的文件系统事件通知库，类似于os / signal。</br>
opc	为Go加载Open Packaging Conventions（OPC）文件。</br>
parquet	读取和写入 parquet文件。</br>
pdfcpu	PDF 处理器。</br>
skywalker	一种软件包，允许一个人轻松地同时通过文件系统。</br>
stl	读取和写入STL（立体光刻）文件的模块。并发读取算法。</br>
tarfs	tar文件FileSystem interface接口的实现。</br>
vfs	跨多种文件系统类型（例如os，S3和GCS）的Go的一组可插拔，可扩展且自以为是的文件系统功能。</br>

## 金融

**包	说明**</br>
accounting	golang的货币和货币格式。</br>
currency	高性能和准确的货币计算包。</br>
decimal	任意精度定点十进制数字。</br>
go-finance	Go中的综合金融市场数据。</br>
go-finance	金融功能库，用于货币时间价值（年金），现金流量，利率转换，债券和折旧计算。</br>
go-finance	获取汇率，通过VIES检查增值税号和检查IBAN银行帐号的模块。</br>
go-money	Fowler的Money模式的实现。</br>
ofxgo	查询OFX服务器和/或解析响应（使用示例命令行客户端）。</br>
orderbook	匹配引擎的限价订单在Golang。</br>
techan	具有高级市场分析和交易策略的技术分析库。</br>
transaction	以多线程模式运行的嵌入式帐户嵌入式事务数据库。</br>
vat	增值税号验证和欧盟增值税率。</br>

## 游戏开发

**包	说明**</br>
Azul3D	用Go语言编写的3D游戏引擎。</br>
Ebiten	Go中死的简单2D游戏库。</br>
engo	Engo是用Go语言编写的开源2D游戏引擎。它遵循实体组件系统范式。</br>
g3n	Go 3D游戏引擎。</br>
GarageEngine	用Go语言编写的2D游戏引擎，可在OpenGL上使用。</br>
glop	Glop（权力游戏库）是一个相当简单的跨平台游戏库。</br>
go-astar	A 路径查找算法的Go实现。</br>
go-collada	Go包，用于Collada文件格式。</br>
go-sdl2	Simple DirectMedia Layer的 Go绑定。</br>
go3d	用于Go的面向性能的2D/3D数学软件包。</br>
gonet	使用golang实现的游戏服务器框架。</br>
goworld	可扩展的游戏服务器引擎，具有空间实体框架和热插拔功能。</br>
Leaf	轻量级游戏服务器框架。</br>
nano	重量轻，设备，高性能的基于golang游戏服务器架构。</br>
Oak	Pure Go游戏引擎。</br>
Pitaya	可扩展的游戏服务器框架，具有群集支持和通过C SDK的iOS，Android，Unity等客户端库。</br>
Pixel	Go中的手工制作2D游戏库。</br>
raylib-go	去绑定raylib，简单和易于使用的库，以了解电子游戏编程。</br>
termloop	Go的基于终端的游戏引擎，建立在Termbox之上。</br>

## 地理位置

**包	说明</br>**
geocache	适用于基于地理位置的应用程序的内存中缓存。</br>
geoserver	geoserver是Go软件包，用于通过GeoServer REST API操纵GeoServer实例。</br>
gismanager	将 GIS数据（矢量数据）发布到PostGIS和Geoserver。</br>
osm	用于读取，编写和使用OpenStreetMap数据和API的库。</br>
pbf	OpenStreetMap PBF golang编码器/解码器。</br>
S2 geometry	Go中的S2几何库。</br>
Tile38	具有空间索引和实时地理围栏的地理位置数据库。</br>
WGS84	库坐标转换和变换（ETRS89，OSGB36，NAD83，RGF93，网络墨卡托UTM）。</br>

## 编译器

**包	说明**</br>
c4go	将C代码转换为Go代码。</br>
f4go	将FORTRAN 77代码转换为Go代码。</br>
gopherjs	从Go到JavaScript的编译器。</br>
llgo	Go的基于LLVM的编译器。</br>
tardisgo	Golang转换为CPP / CSharp / Java / JavaScript转译器。</br>

## Goroutines

**包	说明**</br>
ants	用于golang的高性能goroutine池。</br>
artifex	Golang使用基于工作程序的分派的简单内存中作业队列。</br>
async	一种异步执行功能的安全方法，以防万一。</br>
breaker	使执行流程可中断的灵活机制。</br>
cyclicbarrier	用于golang的CyclicBarrier。</br>
go-floc	轻松编排goroutine。</br>
go-flow	控制goroutine的执行顺序。</br>
go-tools/multithreading	使用带有简单API的轻量级库管理goroutine池。</br>
go-trylock	支持Golang的读写锁的TryLock。</br>
go-waitgroup	sync.WaitGroup与错误处理和并发控制类似。</br>
gohive	Go的高性能和易于使用的Goroutine池。</br>
gollback	异步简单函数实用程序，用于管理闭包和回调的执行。</br>
GoSlaves	简单和异步Goroutine池库。</br>
goworker	goworker是基于Go的后台工作者。</br>
gowp	gowp是并发限制goroutine池。</br>
gpool	管理可调整大小的上下文感知goroutine池以绑定并发。</br>
grpool	轻巧的Goroutine池。</br>
Hunch	预感提供功能，如：All，First，Retry，Waterfall等等，这使得异步流控制更加直观。</br>
oversight	监督是Erlang监督树的完整实现。</br>
parallel-fn	并行运行功能。</br>
pool	有限的消费者goroutine池或无限制的goroutine池，以便更轻松地处理和取消goroutine。</br>
queue	为您提供sync.WaitGroup类似的队列组可访问性。帮助您节流和限制goroutine，等待所有goroutine结束等等。</br>
routine	具有上下文和支持的例程控制：Main，Go，Pool和一些有用的Executors。</br>
semaphore	基于通道和上下文的具有锁定/解锁操作超时的信号量模式实现。</br>
semaphore	基于CAS的快速可调整大小的信号量实现（比基于通道的信号量实现更快）。</br>
stl	基于软件交易内存（STM）并发控制机制的软件交易锁。</br>
threadpool	Golang线程池实现。</br>
tunny	线程池golang。</br>
worker-pool	goworker是一个简单的Go异步工作池。</br>
workerpool	Goroutine池，它限制了任务执行的并发性，而不是排队的任务数。</br>

## 图形界面

**包	说明**</br>
app	打包以使用GO，HTML和CSS创建应用的程序。支持：MacOS，Windows正在开发中。</br>
fyne	为Go设计的跨平台本机GUI，使用EFL呈现。支持：Linux，macOS，Windows。</br>
go-astilectron	使用GO和HTML / JS / CSS（由Electron支持）构建跨平台GUI应用。</br>
go-gtk	GTK的绑定。</br>
go-sciter	Go绑定：用于现代桌面UI开发的可嵌入HTML / CSS / script引擎。跨平台。</br>
gotk3	GTK3的绑定。</br>
gowd	使用GO，HTML，CSS和NW.js进行快速简单的桌面UI开发。跨平台。</br>
qt	Go的Qt绑定（支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi）。</br>
ui	Go的平台本地GUI库。跨平台。</br>
Wails	使用内置OS HTML渲染器的HTML UI的Mac，Windows，Linux桌面应用程序。</br>
walk	Go的Windows应用程序库工具包。</br>
webview	具有简单双向JavaScript绑定的跨平台Webview窗口（Windows / macOS / Linux）。</br>
go-appindicator	libappindicator3 C库的Go绑定。</br>
gosx-notifier	Go的OSX桌面通知库。</br>
mac-activity-tracker	OSX库，用于通知计算机上的任何（可插入）活动。</br>
mac-sleep-notifier	golang中的OSX睡眠/唤醒通知。</br>
robotgo	Go本机跨平台GUI系统自动化。控制鼠标，键盘等。</br>
systray	跨平台的Go库，用于在通知区域中放置图标和菜单。</br>
trayhost	跨平台的Go库，用于在主机操作系统的任务栏中放置一个图标。</br>

## 图片

**包	说明**</br>
bild 	纯Go中图像处理算法的集合。</br>
bimg 	使用libvips进行快速有效的图像处理的小包装。</br>
cameron 	Go的头像生成器。</br>
canvas 	将矢量图形转换为PDF，SVG或光栅图像。</br>
darkroom 	具有可变存储后端的图像代理和侧重于速度和弹性的图像处理引擎。</br>
geopattern 	从字符串创建漂亮的生成图像图案。</br>
gg 	纯Go中的2D渲染。</br>
gift 	图像处理过滤器的包装。</br>
gltf 	高效，强大的glTF 2.0读取器，写入器和验证器。</br>
go-cairo 	用于cairo图形库的绑定。</br>
go-gd 	GD库的Go绑定。</br>
go-nude 	Go的裸露检测。</br>
go-opencv 	用于OpenCV的绑定。</br>
go-webcolors 	webcolors库的端口，从Python到Go。</br>
gocv 	使用OpenCV 3.3+进行计算机视觉的Go软件包。</br>
goimagehash 	Go感知图像哈希包。</br>
goimghdr 	imghdr模块确定Go文件中包含的图像类型。</br>
govatar 	用于生成有趣头像的库和CMD工具。</br>
image2ascii 	将图像转换为ASCII。</br>
imagick 	绑定到ImageMagick的MagickWand C API。</br>
imaginary 	用于图像大小调整的快速，简单的HTTP微服务。</br>
imaging 	简单的Go图像处理包。</br>
img 	选择图像处理工具。</br>
ln 	Go中的3D线条艺术渲染。</br>
mergi 	用于图像处理（合并，裁切，调整大小，水印，动画）的Tool＆Go库。</br>
mort 	用Go编写的存储和图像处理服务器。</br>
mpo 	用于MPO 3D照片的解码器和转换工具。</br>
picfit 	用Go编写的图像大小调整服务器。</br>
pt 	用Go语言编写的路径跟踪引擎。</br>
resize 	使用常见的插值方法为Go 调整图像大小。</br>
rez 	在纯Go和SIMD中调整图像大小。</br>
smartcrop 	查找适合任何图像和尺寸的优质作物。</br>
steganography 	用于LSB隐写术的Pure Go库。</br>
stegify 	用于LSB隐写术的Go工具，能够隐藏图像中的任何文件。</br>
svgo 	用于SVG生成的Go语言库。</br>
tga 	软件包tga是TARGA图像格式的解码器/编码器。</br>
photo-translate 	图片翻译。</br>

## 物联网

**包	说明**</br>
connectordb 	量化自我和物联网的开源平台。</br>
devices 	IoT设备库套件，针对x / exp / io进行实验。</br>
eywa 	Project Eywa本质上是一个连接管理器，用于跟踪连接的设备。</br>
flogo 	Project Flogo是一个用于IoT Edge应用和集成的开源框架。</br>
gatt 	盖特是一个围棋包构建低功耗蓝牙外设。</br>
gobot 	Gobot是机器人技术，物理计算和物联网的框架。</br>
huego 	适用于Go的飞利浦Hue扩展客户端库。</br>
iot 	IoT是用于实现Google IoT Core设备的简单框架。</br>
mainflux 	工业物联网消息和设备管理服务器。</br>
periph 	外设I / O与低级别的主板设备接口。</br>
sensorbee 	用于物联网的轻量级流处理引擎。</br>

## JSON格式

**包	说明**</br>
ajson 	具有JSONPath支持的golang的抽象JSON。</br>
gjo 	用于创建JSON对象的小型实用程序。</br>
GJSON 	使用一行代码获取JSON值。</br>
go-jsonerror 	Go-JsonError可让我们轻松创建遵循JsonApi规范的json响应错误。</br>
go-respond 	Go包，用于处理常见的HTTP JSON响应。</br>
gojq 	Golang中的 JSON查询。</br>
gojson 	从示例JSON自动生成Go（golang）结构定义。</br>
JayDiff 	用Go编写的JSON diff实用程序。</br>
jettison 	用于Go的高性能，无反射JSON编码器。</br>
JSON-to-Go 	将JSON转换为Go结构。</br>
json2go 	高级JSON到Go结构转换。提供可以解析多个JSON文档并创建适合所有JSON的结构的包。</br>
jsonapi-errors 	根据JSON API错误参考进行绑定。</br>
jsonf 	突出显示格式和获取JSON的结构查询的控制台工具。</br>
jsongo 	Fluent API，可以更轻松地创建Json对象。</br>
jsonhal 	简单的Go包，用于将自定义结构编组为HAL兼容的JSON响应。</br>
kazaam 	用于JSON文档的任意转换的API。</br>
mp 	简单的cli电子邮件解析器。当前，它使用标准输入并输出JSON。</br>

## 机器学习

**包	说明**</br>
bayesian 	贝叶斯分类为Golang天真。</br>
CloudForest 	快速，灵活，多线程的决策树集合，用于纯Go中的机器学习。</br>
eaopt 	进化优化库。</br>
evoli 	遗传算法和粒子群优化库。</br>
fonet 	用Go编写的深度神经网络库。</br>
go-cluster 	k模式和k-原型聚类算法的Go实现。</br>
go-deep 	Go中功能丰富的神经网络库</br>
go-fann 	快速人工神经网络（FANN）库的Go绑定。</br>
go-galib 	用Go / golang编写的遗传算法库。</br>
go-pr 	Go lang中的模式识别包。</br>
gobrain 	用go语言编写的神经网络</br>
godist 	各种概率分布及相关方法。</br>
goga 	Go的遗传算法库。</br>
GoLearn 	用于Go的通用机器学习库。</br>
golinear 	Go的liblinear绑定。</br>
GoMind 	Go中的简单神经网络库。</br>
goml 	Go中的在线机器学习。</br>
Goptuna 	用于Go语言编写的黑盒函数的贝叶斯优化框架。一切都会被优化。</br>
goRecommend 	用Go编写的推荐算法库。</br>
gorgonia 	基于图形的计算库，例如Theano for Go，它提供了用于构建各种机器学习和神经网络算法的原语。</br>
gorse 	基于Go编写的协作过滤的离线推荐系统后端。</br>
goscore 	用于PMML的Go Scoring API。</br>
gosseract 	使用Tesseract C ++库的OCR（光学字符识别）软件包。</br>
libsvm 	基于LIBSVM 3.14 libsvm的golang版本衍生作品。</br>
neat 	用于增强拓扑神经演化（NEAT）的即插即用，并行Go框架。</br>
neural-go 	go-在Go中实现的多层感知器网络，通过反向传播进行训练。</br>
ocrserver 	一个简单的OCR API服务器，非常容易被Docker和Heroku部署。</br>
onnx-go 	转到开放神经网络交换（ONNX）的接口。</br>
probab 	概率分布函数。贝叶斯推断。用纯Go语言编写。</br>
regommend 	建议和协作过滤引擎。</br>
shield 	贝叶斯文本分类器，具有灵活的标记器和Go的存储后端。</br>
tfgo 	易于使用的Tensorflow绑定：简化了官方Tensorflow Go绑定的使用。在Go中定义计算图，加载并执行经过Python训练的模型。</br>
Varis 	Golang神经网络。</br>

## 金融

**包	说明**</br>
unioffice 	Pure Go库，用于创建和处理Office Word（.docx），Excel（.xlsx）和Powerpoint（.pptx）文档。</br>
excelize 	Golang库用于读取和写入Microsoft Excel™（XLSX）文件。</br>
go-excel 	一个简单而轻便的阅读器，可以将类似于related-db的excel读取为表格。</br>
goxlsxwriter 	libxlsxwriter的Golang绑定，用于编写XLSX（Microsoft Excel）文件。</br>
xlsx 	用于简化在Go程序中读取Microsoft Excel最新版本使用的XML格式的库。</br>
xlsx 	在Go程序中快速/安全地读取/更新您现有的Microsoft Excel文件的方法。</br>

## 自然语言处理

**包	说明**</br>
getlang 	快速自然语言检测程序包。</br>
go-i18n 	用于处理本地化文本的软件包和一个随附工具。</br>
go-mystem 	CGo与Yandex.Mystem的绑定-俄罗斯形态分析仪。</br>
go-nlp 	用于处理离散概率分布的实用程序和其他可用于执行NLP工作的工具。</br>
go-pinyin 	CN Hanzi至Hanyu拼音转换器。</br>
go-stem 	搬运程序阻止算法的实现。</br>
go-unidecode 	Unicode文本的ASCII音译。</br>
go2vec 	用于word2vec嵌入的阅读器和实用程序功能。</br>
gojieba 	这是一个围棋实施解霸其中中国分词算法。</br>
golibstemmer 	雪球库libstemmer库的绑定，包括porter 2。</br>
gotokenizer 	基于字典和Goram语言的Bigram语言模型的标记器。（现在仅支持中文细分）</br>
gounidecode 	Go的Unicode音译器（也称为unidecode）。</br>
gse 	进行有效的文本分割；支持英语，中文，日语等。</br>
icu 	CGO结合为ICU4C C库检测和转换功能。保证与版本50.1兼容。</br>
kagome 	用纯Go语言编写的JP形态分析仪。</br>
libtextcat 	libtextcat C库的Cgo绑定。保证与2.2版兼容。</br>
MMSEGO 	这是MMSEG的GO实现，它是中文分词算法。</br>
nlp 	从字符串中提取值，并用nlp填充您的结构。</br>
nlp 	支持LSA（潜在语义分析）的自然语言处理库。</br>
paicehusk 	Paice / Husk提取算法的Golang实现。</br>
petrovich 	彼得罗维奇（Petrovich）是库，在给定的语法情况下使用俄语名称。</br>
porter 	这是Martin Porter的Porter干算法的C实现的相当简单的移植。</br>
porter2 	非常快的Porter 2 提取器。</br>
prose 	用于文本处理的库，支持标记化，词性标记，命名实体提取等。仅限英语。</br>
RAKE.go 	快速自动关键字提取算法（RAKE）的Go端口。</br>
segment 	用于执行Unicode标准附件＃29中所述的Unicode文本分段的Go库</br>
sentences 	句子标记器：将文本转换为句子列表。</br>
shamoji 	shamoji是用Go编写的单词过滤程序包。</br>
snowball 	Go的雪球茎端口（cgo包装器）。提供单词词干提取功能Snowball本机。</br>
stemmer 	用于Go编程语言的Stemmer软件包。包括英语和德语词干。</br>
textcat 	Go软件包，用于基于n-gram的文本分类，并支持utf-8和原始文本。</br>
whatlanggo 	Go的自然语言检测程序包。支持84种语言和24种脚本（书写系统，例如拉丁语，西里尔字母等）。</br>
when 	自然EN和RU语言日期/时间分析器具有可插拔的规则。</br>

## 网络

**包	说明**</br>
arp 	包arp实现ARP协议，如RFC 826中所述。</br>
buffstreams 	通过TCP流化协议缓冲区数据变得容易。</br>
canopus 	CoAP客户端/服务器实施（RFC 7252）。</br>
cidranger 	Go的快速IP到CIDR查找。</br>
dhcp6 	软件包dhcp6实现了DHCPv6服务器，如RFC 3315中所述。</br>
dns 	使用DNS的Go库。</br>
ether 	用于发送和接收以太网帧的跨平台Go软件包。</br>
ethernet 	程序包ethernet实施IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的封送处理。</br>
fasthttp 	软件包fasthttp是Go的一种快速HTTP实现，比net / http快10倍。</br>
fortio 	负载测试库和命令行工具，高级回显服务器和Web UI。允许指定设置的每秒查询负载，并记录延迟直方图和其他有用的统计数据并对其进行图形化。Tcp，Http，gRPC。</br>
ftp	 程序包ftp实现RFC 959中所述的FTP客户端。</br>
gev 	gev是基于Reactor模式的轻量级，快速，无阻塞的TCP网络库。</br>
gmqtt 	Gmqtt是一个灵活的高性能MQTT代理库，它完全实现了MQTT协议V3.1.1。</br>
gnet 	gnet是一个高性能的，用纯围棋轻便，非阻塞，事件循环网络库。</br>
gNxI 	使用gNMI和gNOI协议的网络管理工具的集合。</br>
go-getter 	Go库，用于使用URL从各种来源下载文件或目录。</br>
go-powerdns 	Golang的 PowerDNS API绑定。</br>
go-stun 	STUN客户端的Go实现（RFC 3489和RFC 5389）。</br>
gobgp 	使用Go编程语言实现的BGP。</br>
golibwireshark 	软件包golibwireshark使用libwireshark库来解码pcap文件并分析解剖数据。</br>
gopacket 	Go库，用于使用libpcap绑定进行数据包处理。</br>
gopcap 	libpcap的包装器。</br>
goshark 	软件包goshark使用tshark解码IP数据包并创建数据结构以分析数据包。</br>
gosnmp 	用于执行SNMP操作的本机Go库。</br>
gosocsvr 	套接字服务器变得简单。</br>
gotcp 	用于快速编写tcp应用程序的Go软件包。</br>
grab 	用于管理文件下载的软件包。</br>
graval 	实验性FTP服务器框架。</br>
HTTPLab 	HTTPLabs可让您检查HTTP请求并伪造响应。</br>
iplib 	受python ipaddress和ruby ipaddr启发而使用IP地址（net.IP，net.IPNet）的库</br>
jazigo 	Jazigo是用Go语言编写的工具，用于检索多个网络设备的配置。</br>
kcp-go 	KCP-快速可靠的ARQ协议。</br>
kcptun 	基于KCP协议的极其简单和快速的udp隧道。</br>
lhttp 	强大的websocket框架，可更轻松地构建IM服务器。</br>
linkio 	用于读取器/写入器接口的网络链接速度模拟。</br>
llb 	这是代理服务器的非常简单但快速的后端。对于零内存分配和快速响应的快速重定向到预定义域很有用。</br>
mdns 	Golang中的简单mDNS（多播DNS）客户端/服务器库。bSockets连接到MQTT代理。</br>
NFF-Go 	用于快速开发云和裸机（以前的YANFF）的高性能网络功能的框架。</br>
packet 	通过TCP和UDP发送数据包。如果需要，它可以缓冲消息和热交换连接。</br>
peerdiscovery 	Pure Go库，用于使用UDP多播的跨平台本地对等发现。</br>
portproxy 	简单的TCP代理，它将不支持它的API添加到CORS支持中。</br>
publicip 	软件包publicip返回您的面向公众的IPv4地址（互联网出口）。</br>
quic-go 	在纯Go中实现QUIC协议。</br>
raw 	包raw允许在设备驱动程序级别为网络接口读取和写入数据。</br>
sftp 	程序包sftp实现SSH文件传输协议，如https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt</br>
ssh 	用于构建SSH服务器的高级API（包装crypto / ssh）。</br>
sslb 	这是一个超级简单的负载均衡器，只是一个实现某种性能的小项目。</br>
stun 	实施RFC 5389 STUN协议。</br>
tcp_server 	用于更快地构建tcp服务器的Go库。</br>
tspool 	TCP库使用工作池来提高性能并保护您的服务器。</br>
utp 	围棋UTP微传输协议的实现。</br>
water 	简单的TUN / TAP库。</br>
webrtc 	WebRTC API的纯Go实现。</br>
winrm 	进入WinRM客户端以在Windows计算机上远程执行命令。</br>
xtcp 	具有同步全双工通信，安全关闭，自定义协议的TCP Server Framework。</br>

## 视频

**包	说明**</br>
go-astisub 	在GO中处理字幕（.srt，.stl，.ttml，.webvtt，.ssa / .ass，图文电视，.smi等）。</br>
go-astits 	在GO中本地解析和解复用MPEG传输流（.ts）。</br>
go-m3u8 	Apple m3u8播放列表的解析器和生成器库。</br>
goav 	FFmpeg的综合Go绑定。</br>
gst 	GStreamer的绑定。</br>
libgosubs 	go的字幕格式支持。支持.srt，.ttml和.ass。</br>
libvlc-go 	libvlc 2.X / 3.X / 4.X的绑定（由VLC媒体播放器使用）。</br>
m3u8 	Apple HLS的M3U8播放列表的解析器和生成器库。</br>
v4l 	用Go编写的Linux视频捕获库。</br>



## 开源书籍

**书籍名	推荐理由</br>**
Go palyground	不用搭建本地 Go 环境，在线就编写 Go 的代码</br>
Go实战开发	作者是著名的 Go 开源项目 beego 的作者，他的最佳实践非常值得阅读</br>
Go Web 编程	跟前面一本书作者是同一位，讲的是web开发</br>
Go语言标准库	对标准库的介绍</br>
Go入门指南	比较适合新手，内容相对基础一些</br>
Go语言圣经	书如其名</br>
Go语言中文网	找对圈子，学的更快</br>
菜鸟教程	这个网站非常适合快速上手某门语言</br>
Go语言高级编程	内容适合进阶</br>
go语言原本	欧神出品，虽然号称进度只有9.9%/100%，但不妨碍它的优秀，值得一看</br>
golang设计模式	设计模式 Golang实现，《研磨设计模式》的golang实现</br>
Go语言四十二章经	可以对比查漏补缺</br>
