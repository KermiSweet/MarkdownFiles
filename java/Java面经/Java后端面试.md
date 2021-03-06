## 面试真题

> 下面的面试题是来自百度、京东、新浪微博，我进行了一个总结，希望能帮到大家，划重点的部分表示反复被问到

### 数据结构与算法篇

- B 树和 B+树的区别
- **你了解哪些排序算法？算法的思想、时间复杂度、空间复杂度？**
- LeetCode 第 1 题及第 15 题：两数之和及三数之和问题

### 计算机网络篇

- **TCP 三次握手、四次挥手流程？为什么三次，为什么四次？**
- **TCP 和 UDP 区别，有 TCP 为什么还要有 UDP？**
- TCP 粘包和拆包问题有了解吗？
- TCP 是怎样保持连接的？

### 操作系统篇

- **并发编程中死锁有了解吗？死锁产生的条件是什么？你在项目中是怎样解除避免和解除死锁的？**
- 进程的都有哪些状态？怎么转换的？
- Linux 下文件的操作命令

### 数据库篇

- **数据库范式了解吗？在你的项目中怎么运用的？会出现什么问题？**
- **数据库索引了解吗？MySQL 中索引底层是怎么实现的？**
- MySQL 中存储引擎 InnoDB 和 MyISAM 有什么区别？分别用于什么场景？
- **数据库事务有了解吗？事务的隔离级别？你在项目中使用的隔离级别是什么？**
- SQL 优化有什么思路？
- 项目中使用到外键了吗？外键作用？使用外键要注意些什么问题？
- 除了 MySQL 数据库你还用到哪些数据库？Redis 数据库和 MySQL 数据库的区别？
- 设计一个数据库表

### Java 基础篇

- 类和对象的区别？
- 讲讲 static 关键字和 final 关键字
- **synchronized 关键字是怎么用的？底层实现有了解吗？还有用过其他的锁吗？**
- **BIO、NIO、AIO 区别有哪些？项目中有用到吗？Netty 了解吗？**
- 接口和抽象类的区别？什么时候用接口，什么时候用抽象类？接口可以继承接口吗？
- **HashMap 和 HashTable 的区别是什么？**
- *ConcurrentHashMap*和*HashMap*的区别是什么？*ConcurrentHashMap*为什么线程安全？
- **HashMap 和 HashSet 的区别？HashSet 是如何检查重复的？**
- Java 中线程的状态？join()、yield()方法是干什么？
- Object 类下有哪些方法？
- 字符串"*123*"转换成整型*123*的*API*是什么？整型*123*转换成字符串“*123*”的 API 又是什么？
- **创建线程有几种方式？分别是怎么做的？**
- 线程池用过吗？如何创建一个线程池？其中各个参数的含义是什么？为什么要用线程池？coreSize？
- **synchronized、ReentrantLock 区别？**
- CountDownLatch 和 Semaphore 用过吗？他们的区别是什么？CountDownLatch 应用场景？比如现在要让第 5 个线程等待前 4 个线程执行完毕再执行，具体怎么做？
- 使用 synchronized 来实现单缓冲区的生产者消费者模型？
- JVM 有了解吗？JVM 中参数`–Xms`和`-Xmx`是什么意思？
- **设计模式有了解过哪些？单例设计模式知道哪几种写法？策略设计模式了解吗？你在项目中用到了哪些设计模式？**
- Spring 中依赖注入有几种方式？怎么做的？
- Spring 框架中有哪些组件了解吗？分别做什么的？
- **SpringMVC 的这种 MVC 模式了解吗？他的工作原理是什么？用到了哪些设计模式？（基本每轮面试都被问到）**
- SpringMVC 中要接受用户传来的参数要怎么做？REST 的风格呢？
- Spring 中 bean 的创建过程了解吗？
- SpringBoot 和 SpringMVC 的区别和联系是什么？了解 SpringBoot 的启动流程吗？SpringBoot 自动配置是如何实现的？