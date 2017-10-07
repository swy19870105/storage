# 词汇表

- AFA： 全闪存阵列（All Flash Array）
- 强 Hash：
- 弱 Hash：
- [pure storage](http://www.purestorage.com/)： Pure Flash Storage?
- [NVMe](http://baike.sogou.com/v158092014.htm?fromTitle=NVMe)：Non-Volatile Memory express，是一种建立在 M.2 接口上的类似 AHCI 的一种协议，是专门为闪存类存储设计的协议。
- HCI：超融合基础架构，允许将物理存储融合到业界标准 x86 服务器上，从而支持构造块式基础架构部署思路，提供横向扩展能力。
- EC：Erasure Coding，纠删码
- smartctl: 硬盘监控和分析工具
- storcli:  Storage Command Line Tool
- [Purley](https://www.intel.com/content/www/us/en/design/products-and-solutions/processors-and-chipsets/purley/intel-xeon-scalable-processors.html)
- SDS: Software Defined Storage
- CEPH: Ceph是加州大学Santa Cruz分校的Sage Weil（DreamHost的联合创始人）专为博士论文设计的新一代自由软件分布式文件系统。自2007年毕业之后，Sage开始全职投入到Ceph开发之中，使其能适用于生产环境。Ceph的主要目标是设计成基于POSIX的没有单点故障的分布式文件系统，使数据能容错和无缝的复制。2010年3 月，Linus Torvalds将Ceph client合并到内 核2.6.34中。Ceph的架构，它的容错实现和简化海量数据管理的功能。
- FUSE: filesystem in user space，一个用户空间的文件系统框架，允许非特权用户建立功能完备的文件系统，而不需要重新编译内核。fuse模块仅仅提供内核模块的入口，而本身的主要实现代码位于用户空间中。对于读写虚拟文件系统来讲，fuse是个很好的选择。fuse包含包含一个内核模块和一个用户空间守护进程，将大部分的VFS调用都委托一个专用的守护进程来处理。
- Openstack Swift: 提供了弹性可伸缩、高可用的分布式对象存储服务，适合存储大规模非结构化数据。Swift 构筑在比较便宜的标准硬件存储基础设施之上，无需采用 RAID（磁盘冗余阵列），通过在软件层面引入一致性散列技术和数据冗余性，牺牲一定程度的数据一致性来达到高可用性和可伸缩性，支持多租户模式、容器和对象读写操作，适合解决互联网的应用场景下非结构化数据存储问题。
- Lustre: 是HP，Intel，Cluster File System公司联合美国能源部开发的Linux集群并行文件系统。该系统已推出 1.0 的发布版本，是第一个基于对象存储设备的，开源的并行文件系统。
- LFS: Log Structured File System, 是专门针对写操作进行优化的文件系统，这类文件系统的特点是使用日志结构管理数据。最近，LFS成为SSD不可或缺的一部分，因为LFS就是SSD如何管理内部闪存芯片的关键技术。