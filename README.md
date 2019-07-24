# Java Core Problems  
  
## 1 数据结构与算法基础  
1.1 說一下几种常见的排序算法和分别的复杂度  
1.2 用 Java 写一个冒泡排序算法  
1.3 描述一下链式存储的结构  
1.4 如何遍历一棵二叉树  
1.5 倒排一个 LinkedList  
1.6 用 Java 写一个递归遍历目录下面所有的文件  
  
## 2 Java 基础  
2.1 接口和抽象类的区别  
2.2 Java 中的异常有哪几类？ 分别怎么使用？  
2.3 常用的集合类有哪些？比如 List 如何排序？  
2.4 ArrayList 和 LinkedList 内部的实现大至是什么样子? 他们之间的区别和优缺点？  
2.5 内存溢出是怎么回事？ 请举一个栗子  
2.6 == 和 equals 的区别  
2.7 hashCode 方法的作用？  
2.8 NIO 是什么？ 用于何种场景？  
2.9 HashMap 实现原理， 如何保证 HashMap 的线程安全？  
2.10 JVM 内存结构， 为什么需要GC？  
2.11 NIO 模型, select/epoll 的区别， 多路复用的原理  
2.12 Java 中一个字符占多少个字节， 扩展再问int, long, double 占多少个字节  
2.13 创建一个类的实例都有哪些方法？  
2.14 final/finally/finalize 的区别  
2.15 Session/Cookie 的区别  
2.16 String/StringBuffer/StringBuilder 的区别， 扩展再问他们的实现？  
2.17 Servlet 的生命周期  
2.18 如何用Java 分配一段连续的 1G 的内存空间？ 需要注意什么？  
2.19 Java 有自己的内存回收机制， 但为什么还存在内存泄露的问题？  
2.20 什么是 Java 序列化， 如何实现 Java 序列化？（写一个实例）？  
2.21 String s = new String("abc"); 创建了几个 String Object  
  
## 3 JVM  
3.1 JVM 堆的基本结构  
3.2 JVM 的垃圾算法有哪几种？ CMS 垃圾回收的基本流程  
3.3 JVM 有哪些常用的启动参数可以调整， 描述几个？  
3.4 如何查看 JVM 的内存使用情况？  
3.5 Java 程序是否会内训溢出，内存泄露情况的发生？ 举几个例子  
3.6 你常用的 JVM 配置和调优的参数有哪些？ 分别什么作用？  
3.7 JVM 的内存结构  
3.8 常用的GC策略， 什么时候会触发 YGC， 什么时候触发 FGC  
  
## 4 多线程/并发  
4.1 如何创建线程？ 如何保证线程安全  
4.2 如何实现一个线程安全的数据结构  
4.3 如何避免死锁  
4.4 Volatile 关键字的作用  
4.5 HashMap 再多线程环境下使用需要注意些什么？ 为什么？  
4.6 Java 线程中 run() 和 start() 的区别  
4.7 什么是守护线程？ 有什么作用  
4.8 什么是死锁？ 如何避免  
4.9 线程和进程的区别  
4.10 Java 中 ThreadLocal 作用和实现原理  
4.11 ConcurrentHashMap 的实现原理是什么？  
4.12 sleep 和 wait 的区别？  
4.13 notify 和 notifyAll 的区别，  
4.14 两个线程如何串行执行  
4.15 上下文切换是什么含义？  
4.16 可以运行 kill 一个线程吗？  
4.17 什么是条件锁、读写锁、自旋锁、可重入锁？  
4.18 线程池 ThreadPoolExecutor 的实现原理？  
  
## 5 Linux 使用与问题分析排查  
5.1 使用两种命令创建一个文件  
5.2 硬链接和软链接的区别？  
5.3 Linux 常用命令有哪些?  
5.4 怎么看一个Java 线程的资源消耗  
5.5 Load 过高可能性有哪些  
5.6 /etc/hosts 文件作用  
5.7 如何快速的將一个文本中所有的abc替换成xyz  
5.8 如何在log文件中搜索找出error的日志？  
5.9 发现磁盘空间不够用， 如何快速找出找出占用空间大的文件  
5.10 Java 服务端问题排查 OOM CPU 高 Load高， 类冲突  
5.11 Java 常用问题排查工具及用法 top, iostat,vmstat, sar, tcpdump, jvisualvm, jmap, jconsole  
5.12 Thread dump 文件如何分析 Runnable, 锁， 代码栈， 操作系统线程ID关联  
5.13 如何查看Java应用的线程信息  
  
## 6 框架使用  
6.1 描述一下 Hibernate 的三个状态  
6.2 Spring Bean 的生命周期  
6.3 SpringMVC 处理请求的流程  
6.4 SpringAOP 解决了什么问题， 怎么实现？  
6.5 Spring 事务的传播属性是怎么回事， 它会有什么影响？  
6.6 Spring 中 BeanFactory 和 FactoryBean有什么区别  
6.7 Spring 依赖注入有哪几种方式?  
6.8 Spring IOC 原理是什么？  
6.9 用Spring如何实现一个切面  
6.10 Spring 如何实现数据库事务  
6.11 mybatis 如何实现批量提交  
  
## 7 数据库相关  
7.1 Mysql InnoDB、Mysaim的特点  
7.2 乐观锁和悲观锁的区别  
7.3 数据库的隔离级别是什么？ 有什么作用  
7.4 Mysql 主备同步的基本原理   
7.5 select * from table t where size > 10 group by size order by size 的sql语句执行顺序  
7.6 如何优化数据库性能（索引、分库分表、批量操作、分页算法、升级硬盘、业务优化、主从部署、读写分离）  
7.7 SQL 什么情况下不会使用索引（不包含、不等于、函数）  
7.8 一般在什么字段上建索引（过滤数据最多的字段上）  
7.9 如何从一张表中查出 name 字段不包含 “XYZ" 的所有行  
7.10 MySQL B+索引实现、行锁实现、SQL优化  
7.11 Redis， RDB， AOF 如何做高可用、集群  
7.12 如何解决高并发减库存问题  
7.13 mysql 存储引擎中的实现机制  
7.14 数据库事务的几种颗粒度  
7.15 行锁、表锁、乐观锁、悲观锁  
  
## 8 网络协议和网络编程  
8.1 TCP 建立连接的过程  
8.2 TCP 断开连接的过程  
8.3 浏览器发生302跳转背后的逻辑  
8.4 Http 协议的交互流程， Http 和 Https 的差异， SSL 的交互流程  
8.5 TCP的滑动窗口协议有什么用？讲讲原理  
8.6 Http 协议都有哪些方法  
8.7 交换机和路由器的区别  
8.8 Socket 交互的基本流程  
8.9 Http 协议（报文结构，断电续传，多线程下载， 什么是长连接）  
8.10 tcp 协议（建立过程，慢启动，滑动窗口，七层模型）  
8.11 webservice 协议（wsdl/soap格式， 与rest协议的区别）  
8.12 NIO 的好处， Netty 线程模型， 什么是零拷贝  
  
## 9 Redis 等缓存系统/中间件/NoSQL/一致性Hash等  
9.1 列举一个常用的Redis客户端的并发模型  
9.2 HBase 如何实现模糊查询  
9.3 列举一个常用的消息中间件， 如果消息要保序如何实现？  
9.4 如何实现一个HashTable？你的设计如何考虑Hash冲突？ 如何优化  
9.5 分布式缓存， 一致性Hash  
9.6 LRU算法， slab分配， 如何减少内存碎片  
9.7 如何解决缓存单机热点问题  
9.8 什么是布隆过滤器， 实现原理是什么？ False positive指的是什么  
9.9 memcache 与 redis 的区别  
9.10 zookeeper 有什么功能， 选举算法如何进行  
9.11 map/reduce 过程， 如何用 map/reduce实现两个数据源的联合统计  
  
## 10 设计模式与重构  
10.1 列举几个常见的设计模式  
10.2 你在设计一个工厂的包的时候会遵守的哪些原则  
10.3 你能列举一个使用了Visitor/Decoraor模式的开源项目/庫吗  
10.4 你在编码的时候最常用的设计模式有哪些？在什么场景下使用  
10.5 如何实现一个单例  
10.6 代理模式（动态代理）  
10.7 单例模式（懒汉模式，并发初始化如何解决， volatile 与 lock的使用）  
10.8 JDK源码里面有什么让你印象深刻的设计模式， 举例看看）
