### 操作系统

### 页面缓存

- [hcache](https://github.com/silenceshell/hcache)

### IO 队列深度

- [azure](https://docs.microsoft.com/zh-cn/azure/virtual-machines/premium-storage-performance#queue-depth)

### 进程 线程

- [多核技术导论之操作系统对多核处理器的支持方法](https://software.intel.com/content/www/cn/zh/develop/articles/book-multicore-multithread-technology_operating_system_support_for_multicore_processors_methods.html)
- [RT-thread线程调度](https://www.bookstack.cn/read/rtthread-manual-doc/3.2.md)
- [死锁检测](https://ivanzz1001.github.io/records/post/cplusplus/2018/11/15/linux-deadlock-detect#41-pstack)
- [llvm 线程安全的分析工具](https://clang.llvm.org/docs/ThreadSafetyAnalysis.html)
- [线程同步策略](https://wyydsb.xin/other/synch.html)
- [linux schedule() 方法浅析](https://my.oschina.net/u/269082/blog/875719)
- [调度器](https://www.cnblogs.com/yangguang-it/p/7267165.html)
- [浅谈linux系统下C开发之(进程) 内存布局](https://zhuanlan.zhihu.com/p/157794925)

### 内存序

- [为什么程序员需要关心顺序一致性（Sequential Consistency）而不是Cache一致性（Cache Coherence？）](http://www.parallellabs.com/2010/03/06/why-should-programmer-care-about-sequential-consistency-rather-than-cache-coherence/)
- [内存序的论文](http://irl.cs.ucla.edu/~yingdi/web/paperreading/whymb.2010.06.07c.pdf)
- [Linux 内核中内存序的文档](https://www.kernel.org/doc/Documentation/memory-barriers.txt)
- [为什么x86中只有storeload可以重排序呢？](https://www.zhihu.com/question/274310265/answer/1271612645)
- [Intel_Reordering_318147.pdf](http://www.cs.cmu.edu/\~410-f10/doc/Intel_Reordering_318147.pdf)
- [缓存一致性](https://en.wikipedia.org/wiki/Cache_coherence)
- [内存一致性模型-TSO](https://zhuanlan.zhihu.com/p/141655129)
- [《现代操作系统 原理与实现》 第十二章：多核与多处理器](https://ipads.se.sjtu.edu.cn/mospi/)

### 计算机架构

- [cpumemory.pdf](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf)
- [高速缓存?](http://igoro.com/archive/gallery-of-processor-cache-effects/)
- [CPUCaches](https://www.aristeia.com/TalkNotes/ACCU2011_CPUCaches.pdf)
- [进程栈 线程栈 内核栈 中断栈](https://blog.csdn.net/yangkuanqaz85988/article/details/52403726)

### 虚拟内存

- [进程如何找到pgd页表，页表的数据结构是什么？](https://www.zhihu.com/question/407985097/answer/1354598494)
- [pagemap.txt](https://www.kernel.org/doc/Documentation/vm/pagemap.txt)
- [如何理解虚拟内存](https://zhuanlan.zhihu.com/p/96098896)
- [phys_to_virt/virt_to_phys](https://blog.csdn.net/weixin_41028621/article/details/104506478)

### 可持久化内存

- [可持久化内存](https://pmem.io/repoindex)

### 异步IO

- [io_uring.pdf](https://kernel.dk/io_uring.pdf)
- [《操作系统与存储：解析Linux内核全新异步IO引擎——io_uring设计与实现》(一)](https://zhuanlan.zhihu.com/p/334658432)
- [how-io_uring-and-ebpf-will-revolutionize-programming-in-linux](https://www.scylladb.com/2020/05/05/how-io_uring-and-ebpf-will-revolutionize-programming-in-linux/)
- [libunifex](https://github.com/facebookexperimental/libunifex)
- [Lord of the io_uring](https://unixism.net/loti/index.html)
- [sun_mengyue/io_uring_coro](https://github.com/CarterLi/liburing4cpp)
- [用 C++20 协程包装 io_uring 读取](https://zhuanlan.zhihu.com/p/357262548)
- [ceph/io_uring.cc](https://github.com/ceph/ceph/blob/master/src/blk/kernel/io_uring.cc)
- [folly/ioUring.cpp](https://github.com/facebook/folly/blob/master/folly/experimental/io/IoUring.cpp)
### 性能测试

- [Flame Graphs](http://www.brendangregg.com/flamegraphs.html)

### 书籍或者网课

- [操作系统的基本原理与简单实现 （清华）](https://github.com/chyyuu/simple_os_book)
- [CSAPP Lab Assignments](http://csapp.cs.cmu.edu/3e/labs.html)
- [现代操作系统 原理与实现 网页版 pdf](https://ipads.se.sjtu.edu.cn/mospi/)
- [上海交通大学 操作系统网课](https://www.cnmooc.org/study/unit/492853.mooc)
- [上海交通大学 操作系统课程](https://ipads.se.sjtu.edu.cn/courses/os/)
- [MIT 6.828 操作系统](https://pdos.csail.mit.edu/6.828/2018/schedule.html)
- [斯坦福 cs124 操作系统](http://users.cms.caltech.edu/~donnie/cs124/lectures/)
- [操作系统实战45讲](https://time.geekbang.org/column/intro/411)
* 《Operating Systems Three Easy pieces》(OSTEP 操作系统导论)
- [深入理解计算机系统（含中文字幕）](https://www.bilibili.com/video/BV1iW411d7hd)

### 自制操作系统

- [Simple kernel](https://github.com/Simple-XX/SimpleKernel)

### Linux 技术

- [/proc 文档](http://lxr.linux.no/linux+v2.6.32/Documentation/filesystems/proc.txt)
- [你管这破玩意叫操作系统源码](https://github.com/sunym1993/flash-linux0.11-talk)

#### futex
- [futex.pdf](https://akkadia.org/drepper/futex.pdf)
- [Requeue-PI: Making Glibc Condvars PI-Aware](https://static.lwn.net/images/conf/rtlws11/papers/proc/p10.pdf)
- [A description of what robust futexes are](https://www.kernel.org/doc/Documentation/robust-futexes.txt)

#### cgroup 和 namespace
- [cgroup-v2](https://www.kernel.org/doc/Documentation/cgroup-v2.txt)
- [intel Namespaces and cgroups](https://netdevconf.info/1.1/proceedings/slides/rosen-namespaces-cgroups-lxc.pdf)
- [Linux kernel Namespaces and cgroups](http://www.haifux.org/lectures/299/netLec7.pdf)
- [cgroups wiki](https://en.wikipedia.org/wiki/Cgroups)
- [chroot](https://www.cnblogs.com/sparkdev/p/8556075.html)

### nonblock
- [nonblock](https://www.remlab.net/op/nonblock.shtml)
- [why-non-blocking-write-to-disk-doesnt-return-eagain-or-ewouldblock](https://stackoverflow.com/questions/28522848/why-non-blocking-write-to-disk-doesnt-return-eagain-or-ewouldblock)
