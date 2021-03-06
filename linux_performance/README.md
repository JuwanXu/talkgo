[01 | 如何学习 Linux 性能优化](./01.md)

## 第一阶段（CPU 性能篇）

- [02 | 基础篇：到底应该怎么理解“平均负载”？](./02.md)
- [03 | 基础篇：经常说的 CPU 上下文切换是什么意思？（上）](./03.md)
- [04 | 基础篇：经常说的 CPU 上下文切换是什么意思？（下）](./04.md)
- 05 | 基础篇：某个应用的 CPU 使用率居然达到 100%，我该怎么办？
- 06 | 案例篇：系统的 CPU 使用率很高，但为啥却找不到高 CPU 的应用？
- 07 | 案例篇：系统中出现大量不可中断进程和僵尸进程怎么办？（上）
- 08 | 案例篇：系统中出现大量不可中断进程和僵尸进程怎么办？（下）
- [09 | 基础篇：怎么理解 Linux 软中断？](./09.md)
- 10 | 案例篇：系统的软中断 CPU 使用率升高，我该怎么办？
- 11 | 套路篇：如何迅速分析出系统 CPU 的瓶颈在哪里？
- 12 | 套路篇：CPU 性能优化的几个思路
- 13 | 答疑（一）：无法模拟出 RES 中断的问题，怎么办？
- 14 | 答疑（二）：如何用 perf 工具分析 Java 程序？

## 第二阶段（内存和 I/O 性能篇）

- 15 | 基础篇：Linux 内存是怎么工作的？
- [16 | 基础篇：怎么理解内存中的 Buffer 和 Cache？](./16.md)
- 17 | 案例篇：如何利用系统缓存优化程序的运行效率？
- 18 | 案例篇：内存泄漏了，我该如何定位和处理？
- 19 | 案例篇：为什么系统的 Swap 变高了（上）
- 20 | 案例篇：为什么系统的 Swap 变高了？（下）
- 21 | 套路篇：如何“快准狠”找到系统内存的问题？
- 22 | 答疑（三）：文件系统与磁盘的区别是什么？
- [23 | 基础篇：Linux 文件系统是怎么工作的？](./23.md)
- 24 | 基础篇：Linux 磁盘 I/O 是怎么工作的（上）
- 25 | 基础篇：Linux 磁盘 I/O 是怎么工作的（下）
- 26 | 案例篇：如何找出狂打日志的“内鬼”？
- 27 | 案例篇：为什么我的磁盘 I/O 延迟很高？
- 28 | 案例篇：一个 SQL 查询要 15 秒，这是怎么回事？
- 29 | 案例篇：Redis 响应严重延迟，如何解决？
- 30 | 套路篇：如何迅速分析出系统 I/O 的瓶颈在哪里？
- 31 | 套路篇：磁盘 I/O 性能优化的几个思路
- 32 | 答疑（四）：阻塞、非阻塞 I/O 与同步、异步 I/O 的区别和联系

## 第三阶段（网络 性能篇）

- 33 | 关于 Linux 网络，你必须知道这些（上）
- 34 | 关于 Linux 网络，你必须知道这些（下）
- [35 | 基础篇：C10K 和 C1000K 回顾](./35.md)
- 36 | 套路篇：怎么评估系统的网络性能？
- 37 | 案例篇：DNS 解析时快时慢，我该怎么办？
- 38 | 案例篇：怎么使用 tcpdump 和 Wireshark 分析网络流量？
- 39 | 案例篇：怎么缓解 DDoS 攻击带来的性能下降问题？
- 40 | 案例篇：网络请求延迟变大了，我该怎么办？
- 41 | 案例篇：如何优化 NAT 性能？（上）
- 42 | 案例篇：如何优化 NAT 性能？（下）
- [43 | 套路篇：网络性能优化的几个思路（上）](./43.md)
- [44 | 套路篇：网络性能优化的几个思路（下）](./44.md)
- 45 | 答疑（五）：网络收发过程中，缓冲区位置在哪里？

## 第四阶段（综合实战篇）

- 46 | 案例篇：为什么应用容器化后，启动慢了很多？
- 47 | 案例篇：服务器总是时不时丢包，我该怎么办？（上）
- 48 | 案例篇：服务器总是时不时丢包，我该怎么办？（下）
- 49 | 案例篇：内核线程 CPU 利用率太高，我该怎么办？
- 50 | 案例篇：动态追踪怎么用？（上）
- 51 | 案例篇：动态追踪怎么用？（下）
- 52 | 案例篇：服务吞吐量下降很厉害，怎么分析？
- 53 | 套路篇：系统监控的综合思路
- 54 | 套路篇：应用监控的一般思路
- [55 | 套路篇：分析性能问题的一般步骤](./55.md)
- 56 | 套路篇：优化性能问题的一般方法
- 57 | 套路篇：Linux 性能工具速查
- 58 | 答疑（六）：容器冷启动如何性能分析？
- 加餐（一） | 书单推荐：性能优化和 Linux 系统原理
- 加餐（二） | 书单推荐：网络原理和 Linux 内核实现
- 用户故事 | “半路出家 ”，也要顺利拿下性能优化！
- 用户故事 | 运维和开发工程师们怎么说？
- 结束语 | 愿你攻克性能难关
- 结课测试｜这些 Linux 性能知识你都掌握了吗？
