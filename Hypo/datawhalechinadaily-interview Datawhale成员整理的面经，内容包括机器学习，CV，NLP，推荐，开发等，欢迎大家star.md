---
doc_type: hypothesis-highlights
url: >-
  https://github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md
---

# datawhalechina/daily-interview: Datawhale成员整理的面经，内容包括机器学习，CV，NLP，推荐，开发等，欢迎大家star

## Metadata
- Author: [github.com]()
- Title: datawhalechina/daily-interview: Datawhale成员整理的面经，内容包括机器学习，CV，NLP，推荐，开发等，欢迎大家star
- Reference: https://github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md
- Category: #article

## Page Notes
## Highlights
- 同一类线程共享代码和数据空间，每个线程都有自己独立的运行栈和程序计数器，线程之间切换的开销小 — [Updated on 2022-02-27 10:16:39](https://hyp.is/TCySOJdzEeyVngNdN1NRZA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 每个独立的进程有程序运行的入口、顺序执行序列和程序出口 — [Updated on 2022-02-27 10:16:56](https://hyp.is/VnOipJdzEey9dH_DVfpGAA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多线程程序只要有一个线程崩溃，整个程序就崩溃了，但多进程程序中一个进程崩溃并不会对其它进程造成影响，因为进程有自己的独立地址空间，因此多进程更加健壮。 — [Updated on 2022-02-27 10:17:07](https://hyp.is/XLTp6JdzEeyyvEOO5mZsAg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 协程是一种用户态的轻量级线程，协程的调度完全由用户控制。协程拥有自己的寄存器上下文和栈 — [Updated on 2022-02-27 10:17:23](https://hyp.is/ZmqSRJdzEeyzNre9C0NDfg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- ，直接操作栈则基本没有内核切换的开销，可以不加锁的访问全局变量，所以上下文的切换非常快。 — [Updated on 2022-02-27 10:17:30](https://hyp.is/akspCpdzEey3QN99y9r9DA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 当一个进程获得了除处理机以外的一切所需资源，一旦得到处理机即可运行，则称此进程处于就绪状态。 — [Updated on 2022-02-27 10:17:57](https://hyp.is/eruROpdzEeyYF18-dCASzQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- （例如请求I/O而等待I/O完成等） — [Updated on 2022-02-27 10:18:16](https://hyp.is/heROvJdzEey9dhMXUf7iBg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 消息的链表，存放在内核中并由消息队列标识符标识 — [Updated on 2022-02-27 10:21:03](https://hyp.is/6W8dhpdzEeyuebMvhtcVUg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 共享内存就是映射一段能被其他进程所访问的内存，这段共享内存由一个进程创建，但多个进程都可以访问。共享内存是最快的 IPC 方式， — [Updated on 2022-02-27 10:21:33](https://hyp.is/-1TI3pdzEeyvKGNJVZy_TA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 而父进程并没有调用wait或waitpid获取子进程的状态信息， — [Updated on 2022-02-27 10:22:15](https://hyp.is/FBvHAJd0EeyvKbPgo76EeA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 进程描述符仍然保存在系统中。 — [Updated on 2022-02-27 10:22:21](https://hyp.is/F_REnJd0Eey3Qtew6L6CXA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 个父进程退出，而它的一个或多个子进程还在运行 — [Updated on 2022-02-27 10:22:25](https://hyp.is/GhB9aJd0Eey9eXfMStf1-Q/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 孤儿进程将被init进程(进程号为1)所收养，并由init进程对它们完成状态收集工作。 — [Updated on 2022-02-27 10:22:28](https://hyp.is/G_b4lpd0EeyntX-tQc_ViA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁是指两个或两个以上的进程在执行过程中，由于竞争资源或者由于彼此通信而造成的一种阻塞的现象，若无外力作用，它们都将无法推进下去。 — [Updated on 2022-02-27 10:22:35](https://hyp.is/IC21xpd0Eeyy-PuPkxWoew/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 一个资源每次只能被一个进程使用； — [Updated on 2022-02-27 10:22:39](https://hyp.is/IpTqlpd0Eey4sRfIscZ90g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 一个进程因请求资源而阻塞时，对已获得的资源保持不放； — [Updated on 2022-02-27 10:22:45](https://hyp.is/JkchDpd0Eeyue2e_DtHUJg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 进程已获得的资源，在未使用完之前，不能强行剥夺； — [Updated on 2022-02-27 10:22:50](https://hyp.is/KTgJFJd0Eey3Q1MdNP7x6w/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 若干进程之间形成一种头尾相接的循环等待资源关系。 — [Updated on 2022-02-27 10:22:55](https://hyp.is/K_TjcJd0EeyqjxPJXOkkxw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 但是线程不能独立执行，必须依存在应用程序中 — [Updated on 2022-02-27 18:40:55](https://hyp.is/WDDerpdzEey_Lb9VLPgCaA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation
    - Annotation: 线程不能独立运行，必须存在一个进程中。进程是资源调度的基本单位。
- 段是信息的逻辑单位 — [Updated on 2022-02-27 19:44:27](https://hyp.is/nlpdmJfCEeysHVsN5WccAg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 页是信息的物理单位，是为了管理主存的方便而划分的 — [Updated on 2022-02-27 19:44:29](https://hyp.is/n5llKJfCEey1UpdHXvcpvw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 段的大小不固定，由它所完成的功能决定；页的大小固定，由系统决定 — [Updated on 2022-02-27 19:44:34](https://hyp.is/oiAx3JfCEey4L89GgiM8bw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 段向用户提供二维地址空间；页向用户提供的是一维地址空间 — [Updated on 2022-02-28 10:28:52](https://hyp.is/qNvQnpfCEeyTIde1umwS_A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation
    - Annotation: 由于每个段的长度不一，因此虽然数据段、代码段的段号是连续的，但是数据段的最后一个地址和代码段的第一个地址是不连续，因此分段机制中的地址不是一维的，而是二维的。
- 软中断是一些对I/O的请求 — [Updated on 2022-02-28 10:30:45](https://hyp.is/buSXWpg-Eeyn2oNFyrxDWQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- ​ 	软中断并不会直接中断CPU。也只有当前正在运行的代码（或进程）才会产生软中断 — [Updated on 2022-02-28 10:31:12](https://hyp.is/fyWd-Jg-Eey6tH93TPrwgA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 它们仅仅是由当前正在运行的进程所产生的 — [Updated on 2022-02-28 10:38:42](https://hyp.is/ixUrvpg_EeyrtK-gz_Lo4g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 这种中断是一种需要内核为正在运行的进程去做一些事情 — [Updated on 2022-02-28 10:41:13](https://hyp.is/5UHMPJg_EeyhSuPAEtp5Gg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 轮询 — [Updated on 2022-02-28 10:41:21](https://hyp.is/6g1yZpg_EeyKRNPrCR-oxg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation




