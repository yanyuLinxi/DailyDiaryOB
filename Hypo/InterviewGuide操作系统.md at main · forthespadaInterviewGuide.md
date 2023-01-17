---
doc_type: hypothesis-highlights
url: >-
  https://github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md
---

# InterviewGuide/操作系统.md at main · forthespada/InterviewGuide

## Metadata
- Author: [github.com]()
- Title: InterviewGuide/操作系统.md at main · forthespada/InterviewGuide
- Reference: https://github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md
- Category: #article

## Page Notes
## Highlights
- 对于线程，我认为弄清以下两点非常重要： — [Updated on 2022-02-24 11:31:22](https://hyp.is/PP2xqpUiEeysMw-IIlh1zw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 线程之间有无先后访问顺序（线程依赖关系） — [Updated on 2022-02-24 11:31:24](https://hyp.is/Pggi4pUiEeymEyeevO7u0g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多个线程共享访问同一变量（同步互斥问题） — [Updated on 2022-02-24 11:31:26](https://hyp.is/P2QHbpUiEeyzUgN3hlj6Gg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 除了标识线程的tid，每个线程还有自己独立的栈空间，线程彼此之间是无法访问其他线程栈上内容的。 — [Updated on 2022-02-24 11:31:38](https://hyp.is/RmnIyJUiEeyL8QcVxXp8SQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 保存线程栈、寄存器数据和PC即可 — [Updated on 2022-02-24 11:31:45](https://hyp.is/Sn6cXpUiEey1XT81dNVNHg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 代码段是静态的二进制代码，多个程序可以共享。 — [Updated on 2022-02-24 11:36:56](https://hyp.is/A8q73pUjEey-_hcjkcjxfg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 子进程在读写数据时会通过写时复制机制将公共的数据重新拷贝一份，之后在拷贝出的数据上进行操作。 — [Updated on 2022-02-24 11:44:02](https://hyp.is/Aiq-kJUkEey8t7Ne-bN7Jw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- execv()函数重新加载新的代码段，之后就和父进程独立开了。 — [Updated on 2022-02-24 11:44:06](https://hyp.is/BHpphJUkEeymI99u66F88Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 虚拟地址空间 — [Updated on 2022-02-24 15:19:03](https://hyp.is/C17bfJVCEeyeo5-iYw3Uiw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 进程有两种创建方式，一种是操作系统创建的一种是父进程创建的 — [Updated on 2022-02-24 15:20:48](https://hyp.is/SekuGpVCEeyxVjcUnZO7vg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- ./program执行可执行文件时，所有创建的进程都是shell进程的子进程 — [Updated on 2022-02-24 15:21:09](https://hyp.is/VlxxepVCEey9cm_eL8m8vA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 常情况下代码运行在用户态（使用0x00000000 ~ 0xC00000000的用户地址空间） — [Updated on 2022-02-24 15:23:13](https://hyp.is/oNEdPJVCEeyo28_AzUrw3g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 当发生系统调用、进程切换等操作时CPU控制寄存器设置模式位，进入内和模式，在该状态（超级用户模式）下进程可以访问全部存储器位置和执行全部指令。 — [Updated on 2022-02-24 15:23:30](https://hyp.is/qpcm_pVCEey2XgvL-7ncKA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 通用寄存器、浮点寄存器、状态寄存器、程序计数器、用户栈和内核数据结构（页表、进程表、文件表） — [Updated on 2022-02-24 15:24:08](https://hyp.is/wSbCxpVCEey9dZt9KZrJCw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 一次完整的上下文切换通常是进程原先运行于用户态，之后因系统调用或时间片到切换到内核态执行内核指令，完成上下文切换后回到用户态，此时已经切换到进程B。 — [Updated on 2022-02-24 15:24:51](https://hyp.is/2wubOpVCEeyxJ4NLXuoF0Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 当时间片用完时，由计时器发出时钟中断，调度程序便停止该进程的执行，并将它送往就绪队列的末尾，同时继续把 CPU 时间分配给队首的进程。 — [Updated on 2022-02-24 15:26:33](https://hyp.is/F8zBFpVDEeykptet2UvcFQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多级反馈队列 — [Updated on 2022-02-24 15:27:17](https://hyp.is/Me_XzJVDEey_6IeUUfrECw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 每个队列时间片大小都不同 — [Updated on 2022-02-24 15:27:28](https://hyp.is/OF3HmpVDEey3pcfRuynQqg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 进程在第一个队列没执行完，就会被移到下一个队列。 — [Updated on 2022-02-24 15:27:31](https://hyp.is/OldJkJVDEey9f5Ph8VUtjQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 管道是一种半双工的通信方式，数据只能单向流动 — [Updated on 2022-02-24 15:28:10](https://hyp.is/UctUVJVDEeyp3iNd8y614Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 共享内存是最快的IPC方式 — [Updated on 2022-02-24 15:28:35](https://hyp.is/YF5H7JVDEey9d3sR94nF9Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 这段共享内存由一个进程创建，但多个进程都可以访问。 — [Updated on 2022-02-24 15:28:38](https://hyp.is/YnN6rJVDEeyqaeNnoGbVZg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 消息队列是有消息的链表 — [Updated on 2022-02-24 15:28:51](https://hyp.is/aern1JVDEey3p5_85JXwuw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 套接字：适用于不同机器间进程通信 — [Updated on 2022-02-24 15:29:08](https://hyp.is/dB2Z_pVDEey3qA9gcycisQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 信号：用于通知接收进程某个事件已经发生 — [Updated on 2022-02-24 15:29:17](https://hyp.is/eXS-UJVDEey2ZMvPoy7cfA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 信号量：信号量是一个计数器，可以用来控制多个进程对共享资源的访问。它常作为一种锁机制，实现进程、线程的对临界区的同步及互斥访问。 — [Updated on 2022-02-24 15:29:24](https://hyp.is/fdioCJVDEeyg5Fe49Yt8gw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 调度：线程是调度的基本单位（PC，状态码，通用寄存器，线程栈及栈指针）；进程是拥有资源的基本单位（打开文件，堆，静态区，代码段等）。 — [Updated on 2022-02-24 15:29:52](https://hyp.is/jmrs5JVDEey5JseFmFF1Kw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 线程和进程的区别？ — [Updated on 2022-02-24 15:30:29](https://hyp.is/pK8xBJVDEeykqcfaTfjy2w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多个线程可以共享隶属进程的资源 — [Updated on 2022-02-24 15:30:42](https://hyp.is/rFNIqpVDEeyuqhOSv4hF5w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 总结 — [Updated on 2022-02-24 15:32:03](https://hyp.is/3EZsaJVDEeyMvf8-de5ToA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多个进程能在同一个处理器上并发执行使用了时分复用技术 — [Updated on 2022-02-24 15:32:16](https://hyp.is/4_Qh2pVDEeyeqkNLNCxYVw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 阻塞状态（waiting）：等待资源 — [Updated on 2022-02-24 15:32:43](https://hyp.is/9EuE4pVDEey_6u8CUhBBxw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 只有就绪态和运行态可以相互转换，其它的都是单向转换 — [Updated on 2022-02-24 15:33:00](https://hyp.is/_pjsbpVDEeyuq0_JUij8-A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- （1）预编译 — [Updated on 2022-02-24 15:33:35](https://hyp.is/E4oaOpVEEeys9COnStTLHg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 主要处理源代码文件中的以“#”开头的预编译指令 — [Updated on 2022-02-24 15:33:39](https://hyp.is/FaHx2pVEEeyc9P-OyKiYZA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- （2）编译  — [Updated on 2022-02-24 15:33:42](https://hyp.is/F2zwoJVEEeyeu2cCrLWzmA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 把预编译之后生成的xxx.i或xxx.ii文件，进行一系列词法分析、语法分析、语义分析及优化后，生成相应的汇编代码文件。 — [Updated on 2022-02-24 15:33:47](https://hyp.is/GneGtpVEEeyiMX_NetJlHg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- （3）汇编 — [Updated on 2022-02-24 15:33:50](https://hyp.is/HEiicpVEEeyarydKHPJv2w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- （4）链接 — [Updated on 2022-02-24 15:33:52](https://hyp.is/HXONYJVEEeyfsA-LJfbn2g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 保留所有的#pragma 编译器指令 — [Updated on 2022-02-24 15:34:09](https://hyp.is/J7b9mJVEEeyevItYwkCuuw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 词法分析：利用类似于“有限状态机”的算法 — [Updated on 2022-02-24 15:34:49](https://hyp.is/PycW3pVEEeyV5489xsJGIA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 语法分析：语法分析器对由扫描器产生的记号，进行语法分析，产生语法树 — [Updated on 2022-02-24 15:34:59](https://hyp.is/RX1-JJVEEey7ENsrpQnOVA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 语义分析器则对表达式是否有意义进行判断，其分析的语义是静态语义 — [Updated on 2022-02-24 15:35:14](https://hyp.is/TlhhMJVEEeyr82vYHue1IA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 语义分析 — [Updated on 2022-02-24 15:36:11](https://hyp.is/cH-A9JVEEeyxMFNZKzZ2KA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 优化 — [Updated on 2022-02-24 15:36:34](https://hyp.is/fbk90pVEEeyunnPD47L0xQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 目标代码生成 — [Updated on 2022-02-24 15:36:35](https://hyp.is/fpLOEpVEEeyr9TOdD6X4lQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 目标代码优化 — [Updated on 2022-02-24 15:36:37](https://hyp.is/f4i5spVEEeyerg-3vPbnCQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 将汇编代码转变成机器可以执行的指令(机器码文件) — [Updated on 2022-02-24 15:36:51](https://hyp.is/iFbKFpVEEey86M8sy7llOw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 产生目标文件(与可执行文件格式几乎一样)xxx.o(Linux下)、xxx.obj(Windows下)。 — [Updated on 2022-02-24 15:37:03](https://hyp.is/j0vnKpVEEey56APkvECabA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 链接分为静态链接和动态链接： — [Updated on 2022-02-24 15:37:34](https://hyp.is/oaMc1pVEEeyJAw90vQpnOw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 函数和数据被编译进一个二进制文件 — [Updated on 2022-02-24 15:38:34](https://hyp.is/xX_LhpVEEey3J2d-VQY89w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 静态链接 — [Updated on 2022-02-24 15:38:36](https://hyp.is/xo0X9JVEEey3qwPfqcORgw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 库中复制这些函数和数据并把它们和应用程序的其它模块组合起来创建最终的可执行文件 — [Updated on 2022-02-24 15:38:48](https://hyp.is/za4pupVEEey3KJtyeyJaDw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 空间浪费 — [Updated on 2022-02-24 15:38:56](https://hyp.is/0r10xJVEEeyMwUeKa3zNQQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 更新困难 — [Updated on 2022-02-24 15:38:58](https://hyp.is/06WIcpVEEeykr9f2JFmP4A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 运行速度快：但是静态链接的优点就是 — [Updated on 2022-02-24 15:39:09](https://hyp.is/2k5xcJVEEey9fl8cmE0iJg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 在程序运行时才将它们链接在一起形成一个完整的程序 — [Updated on 2022-02-24 15:39:19](https://hyp.is/4FjmkJVEEey5LEvSSEGf1A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 性能损耗 — [Updated on 2022-02-24 15:39:41](https://hyp.is/7ajT3JVEEeyr-SMCl1UxGQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 更新方便： — [Updated on 2022-02-24 15:39:43](https://hyp.is/7mY4PJVEEeyqcAtgvLf1HQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 共享库 — [Updated on 2022-02-24 15:39:46](https://hyp.is/8HmVLpVEEeyiN0NY2b8qUA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 在编译期能分期的语义 — [Updated on 2022-02-24 15:51:15](https://hyp.is/iuwE7JVGEey877tliVyRKQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 添加行号和文件标识，便于编译时编译器产生调试用的行号信息， — [Updated on 2022-02-24 15:51:25](https://hyp.is/kO1ZaJVGEeywLF_Nu_wm1A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 互斥访问临界资源 — [Updated on 2022-02-24 15:53:51](https://hyp.is/5_kVWJVGEey_87eY8-i5LQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 同步：多个进程因为合作产生的直接制约关系，使得进程有一定的先后执行关系。 — [Updated on 2022-02-24 15:54:03](https://hyp.is/73NgrpVGEeyc_FOKMpytqQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 互斥：多个进程在同一时刻只有一个进程能进入临界区。 — [Updated on 2022-02-24 15:54:12](https://hyp.is/9IhjCpVGEeym-nvG9VmLgw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 可以对其执行 down 和 up 操作，也就是常见的 P 和 V 操作 — [Updated on 2022-02-24 15:54:18](https://hyp.is/-Fh_apVGEeyewndQLlmwxA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- down : 如果信号量大于 0 ，执行 -1 操作；如果信号量等于 0，进程睡眠，等待信号量大于 0； — [Updated on 2022-02-24 15:54:33](https://hyp.is/AOTe0JVHEeyqeqPHEaNiIw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- up ：对信号量执行 +1 操作，唤醒睡眠的进程让其完成 down 操作。 — [Updated on 2022-02-24 15:54:36](https://hyp.is/AryJ4pVHEeyrW-PwD8JMVw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 通常的做法是在执行这些操作的时候屏蔽中断。 — [Updated on 2022-02-24 15:54:49](https://hyp.is/Co-0WpVHEeypqFcbCW2tdw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 不可分割 — [Updated on 2022-02-24 15:54:54](https://hyp.is/Dbel8pVHEey9g0NT0J5Qwg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 0 表示临界区已经加锁，1 表示临界区解锁。 — [Updated on 2022-02-24 15:55:12](https://hyp.is/GCcBuJVHEey8XssRSJ6vkw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 使用一个缓冲区来保存物品，只有缓冲区没有满，生产者才可以放入物品；只有缓冲区不为空，消费者才可以拿走物品 — [Updated on 2022-02-24 15:57:21](https://hyp.is/ZQZleJVHEey8YL9nV2MxPg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- mutex 来控制对缓冲区的互斥访问 — [Updated on 2022-02-24 15:57:56](https://hyp.is/eiYQDJVHEeyldYcp0ADa8A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 不能先执行 down(mutex) 再执行 down(empty)。 — [Updated on 2022-02-24 15:58:08](https://hyp.is/gVhX_pVHEey2RHNHXrCp0A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 管程 — [Updated on 2022-02-24 16:00:13](https://hyp.is/y78lKpVHEey3198T26dppw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 而管程把控制的代码独立出来 — [Updated on 2022-02-24 16:00:37](https://hyp.is/2eBrtJVHEeyir5PDep6DAw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 操作系统在对内存进行管理的时候需要做些什么? — [Updated on 2022-02-24 16:01:10](https://hyp.is/7bQAupVHEey3uo-3LSgQSA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 管道(pipe) — [Updated on 2022-02-24 16:03:36](https://hyp.is/RI4TRJVIEeyMzIuHGUMarA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 命名管道(FIFO) — [Updated on 2022-02-24 16:03:37](https://hyp.is/RaKfjpVIEeyvxJMemOFVuQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 内存映射(mapped memory) — [Updated on 2022-02-24 16:04:32](https://hyp.is/ZeUdipVIEey2R680GEaaVg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 通过把一个共享的文件映射到自己的进程地址空间来实现它 — [Updated on 2022-02-24 16:04:45](https://hyp.is/beVwZpVIEeyJE_Ms3Wga_A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 虚拟内存的目的是什么？ 虚拟内存的目的是为了让物理内存扩充成更大的逻辑内存，从而让程序获得更多的可用内存。 — [Updated on 2022-02-24 16:06:51](https://hyp.is/uTDrXpVIEeyuV4cvHING8A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 必须同时拿起左右两根筷子； 只有在两个邻居都没有进餐的情况下才允许进餐。 — [Updated on 2022-02-24 16:08:37](https://hyp.is/-A-9FJVIEey0QlMQWYCakg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 操作系统经典问题之读者-写者问题 允许多个进程同时对数据进行读操作，但是不允许读和写以及写和写操作同时发生。 — [Updated on 2022-02-24 16:09:07](https://hyp.is/CkouzpVJEeyp-ROrbJEnbA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 读写锁 — [Updated on 2022-02-24 16:22:14](https://hyp.is/3uIjKpVKEeyuXQNhtjvWYw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 互斥锁 — [Updated on 2022-02-24 16:22:16](https://hyp.is/4ISHNpVKEeyWAn-C4g-Bww/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 一次只能一个线程拥有互斥锁，其他线程只有等待 — [Updated on 2022-02-24 16:22:21](https://hyp.is/41mDEpVKEeyWA8cG6Q6lLw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 主动放弃CPU进入睡眠状态直到锁的状态改变时再唤醒 — [Updated on 2022-02-24 16:22:31](https://hyp.is/6VEW9JVKEeyexocti8et_A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 操作系统负责线程调度，为了实现锁的状态发生改变时唤醒阻塞的线程或者进程，需要把锁交给操作系统管理 — [Updated on 2022-02-24 16:23:13](https://hyp.is/AnXjdpVLEeyWBHvxPaXnMQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 总的来说互斥锁是线程间互斥的机制，条件变量则是同步机制。 — [Updated on 2022-02-24 16:23:56](https://hyp.is/G7yatJVLEeyxP4PdEahlzg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 进线程不会立刻放弃CPU时间片，而是一直循环尝试获取锁，直到获取为止 — [Updated on 2022-02-24 16:25:03](https://hyp.is/Q_jANJVLEey0SUsj1mBotg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 那么自旋就是在浪费CPU做无用功，但是自旋锁一般应用于加锁时间很短的场景，这个时候效率比较高 — [Updated on 2022-02-24 16:25:09](https://hyp.is/R38RaJVLEeyq5m-vXEjiyg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 你知道哪几种线程锁（POSIX） — [Updated on 2022-02-24 16:25:37](https://hyp.is/WDw-VJVLEey7L1u-ULP5PQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 相对地址又称逻辑地址，绝对地址又称物理地址。 — [Updated on 2022-02-24 16:25:52](https://hyp.is/YTLEdJVLEeyM23cY47XeAw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 等待线程结束 — [Updated on 2022-02-24 16:34:23](https://hyp.is/kZYMJJVMEeyxdGefBVliQg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 结束线程 — [Updated on 2022-02-24 16:34:29](https://hyp.is/lYk7npVMEeydDruF8oD1MQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 子线程执行， — [Updated on 2022-02-24 16:34:34](https://hyp.is/mANVOpVMEeytE8cuQ1svqw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 分离线程 — [Updated on 2022-02-24 16:34:40](https://hyp.is/nAN5gJVMEeyuYodMOT3tCg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 因此可以把用户空间分成为一个固定区和若干个覆盖区。将经常活跃的部分放在固定区，其余部分按照调用关系分段，首先将那些即将要访问的段放入覆盖区，其他段放在外存中，在需要调用前，系统将其调入覆盖区，替换覆盖区中原有的段。 — [Updated on 2022-02-24 16:35:28](https://hyp.is/uF0_7pVMEeytFHcqPRFBTg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 内存交换 — [Updated on 2022-02-24 16:36:15](https://hyp.is/1IFSZJVMEey3yXt7VEvOkQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 把外存中某些已具备运行条件的进程换入内存(进程在内存与磁盘间动态调度) — [Updated on 2022-02-24 16:36:24](https://hyp.is/2gS-BpVMEeyuZGe5sbFu-w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 换入：把准备好竞争CPU运行的程序从辅存移到内存 — [Updated on 2022-02-24 16:36:30](https://hyp.is/3Y4obpVMEeywRCvnfpXFIA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

-  换出：把处于等待状态（或CPU调度原则下被剥夺运行权力）的程序从内存移到辅存，把内存空间腾出来。 — [Updated on 2022-02-24 16:36:34](https://hyp.is/36Ld_JVMEey8ca80wWkn1w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 什么时候会进行内存的交换？ — [Updated on 2022-02-24 16:36:54](https://hyp.is/65JMVpVMEeykxpthN4RlOQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 如何让进程后台运行 — [Updated on 2022-02-24 16:37:14](https://hyp.is/927Y3JVMEeypuXt9ZzT9pg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 指在后台运行的，没有控制终端与之相连的进程。它独立于控制终端，周期性地执行某种任务。Linux的大多数服务器就是用守护进程的方式实现的，如web服务器进程http等 — [Updated on 2022-02-24 16:37:56](https://hyp.is/EF4beJVNEeyvz8P7BrOVYA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 孤儿进程 如果父进程先退出，子进程还没退出，那么子进程的父进程将变为init进程 — [Updated on 2022-02-24 16:38:42](https://hyp.is/K_uldpVNEeydEKuJL5z4Nw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 僵尸进程 如果子进程先退出，父进程还没退出，那么子进程必须等到父进程捕获到了子进程的退出状态才真正结束，否则这个时候子进程就成为僵尸进程。 — [Updated on 2022-02-24 16:39:02](https://hyp.is/ODlttJVNEeyWBw_T-f1sdw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 时间局部性:如果执行了程序中的某条指令，那么不久后这条指令很有可能再次执行;如果某个数据被访问过，不久之后该数据很可能再次被访问。(因为程序中存在大量的循环) 空间局部性:一旦程序访问了某个存储单元，在不久之后，其附近的存储单元也很有可能被访问。(因为很多数据在内存中都是连续存放的，并且程序的指令也是顺序地在内存中存放的) — [Updated on 2022-02-24 16:40:25](https://hyp.is/aaCLspVNEey2VcOVVrg4og/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 由fork创建的新进程被称为子进程（child process）。该函数被调用一次，但返回两次。两次返回的区别是子进程的返回值是0，而父进程的返回值则是新进程（子进程）的进程 id — [Updated on 2022-02-24 16:41:24](https://hyp.is/jOT_NpVNEeyf1Kc-zNpQ1A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 是因为它随时可以调用getpid()来获取自己的pid；也可以调用getppid()来获取父进程的id。(进程id 0总是由交换进程使用，所以一个子进程的进程id不可能为0 ) — [Updated on 2022-02-24 16:44:11](https://hyp.is/8GdWOpVNEeylhYOyV2TlpQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 这2个进程共享代码空间，但是数据空间是互相独立的，子进程数据空间中的内容是父进程的完整拷贝，指令指针也完全相同，子进程拥有父进程当前运行到的位置 — [Updated on 2022-02-24 16:44:34](https://hyp.is/_gGt_pVNEey8dScVrxraWw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- shell可以运行一个前台作业和任意多个后台作业，这称为作业控制 — [Updated on 2022-02-24 16:49:06](https://hyp.is/oAMlzpVOEeye3eNWruT73A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 如果作业中的某个进程有创建了子进程，则该子进程是不属于该作业的。 一旦作业运行结束，shell就把自己提到前台（子进程还存在，但是子进程不属于作业），如果原来的前台进程还存在（这个子进程还没有终止），他将自动变为后台进程组 — [Updated on 2022-02-24 16:49:32](https://hyp.is/r5R3XpVOEeyiS1skY1jcPg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 会话（Session）是一个或多个进程组的集合 — [Updated on 2022-02-24 16:50:02](https://hyp.is/wVzW8pVOEeyeyJvu24Bo1w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- Linux中异常和中断的区别 — [Updated on 2022-02-24 16:50:07](https://hyp.is/xDieiJVOEeyrdctjCDUOXw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 中断是由硬件设备产生的，而它们从物理上说就是电信号，之后，它们通过中断控制器发送给CPU，接着CPU判断收到的中断来自于哪个硬件设备（这定义在内核中），最后，由CPU发送给内核，有内核处理中断 — [Updated on 2022-02-24 16:50:20](https://hyp.is/zEfneJVOEeyazq-LsI8s_A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 异常是由CPU产生的，同时，它会发送给内核，要求内核处理这些异常 — [Updated on 2022-02-24 16:50:37](https://hyp.is/1mo21JVOEeyxf9dVo6l8Mw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 最后都是由CPU发送给内核，由内核去处理 — [Updated on 2022-02-24 16:50:46](https://hyp.is/265oLJVOEey9mgu9Lc76Pg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 处理程序的流程设计上是相似的 — [Updated on 2022-02-24 16:50:50](https://hyp.is/3fFjbpVOEeyiTKtN1VFxSA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 产生源不相同，异常是由CPU产生的，而中断是由硬件设备产生的 — [Updated on 2022-02-24 16:50:52](https://hyp.is/3zkALpVOEeyhB__8X0_Z1w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 中断不是时钟同步的，这意味着中断可能随时到来；异常由于是CPU产生的，所以它是时钟同步的 — [Updated on 2022-02-24 16:50:58](https://hyp.is/4vBE1JVOEey9qCvG68Nnqw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 内核需要根据是异常还是中断调用不同的处理程序 — [Updated on 2022-02-24 16:51:03](https://hyp.is/5fLUOpVOEey36OuYeYzidw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 当处理中断时，处于中断上下文中；处理异常时，处于进程上下文中 — [Updated on 2022-02-24 16:51:06](https://hyp.is/54EGoJVOEey7PY8ErBVgHg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 栈区（stack）— 地址向下增长，由编译器自动分配释放，存放函数的参数值，局部变量的值等。其操作方式类似于数据结构中的队列，先进后出。 — [Updated on 2022-02-24 16:51:25](https://hyp.is/8rNr5JVOEey7Pq8j9jZycg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 堆区（heap）— 地址向上增长，一般由程序员分配释放，若程序员不释放，程序结束时可能由OS回收。注意它与数据结构中的堆是两回事，分配方式倒是类似于链表。 — [Updated on 2022-02-24 16:51:38](https://hyp.is/-os8ZpVOEeyhCe_bktMPkA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 全局区（静态区）（static） — [Updated on 2022-02-24 16:51:43](https://hyp.is/_U81zpVOEeyekR-1vO83aQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 文字常量区 —常量字符串就是放在这里的。程序结束后由系统释放 — [Updated on 2022-02-24 16:51:45](https://hyp.is/_t0uUJVOEeyWDZ-4pmJwug/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 程序代码区(text)—存放函数体的二进制代码。 — [Updated on 2022-02-24 16:51:47](https://hyp.is/ABBJupVPEeypAxtB6Sx-yA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 常见的几种磁盘调度算法 — [Updated on 2022-02-24 16:52:41](https://hyp.is/IEcKDJVPEeypxJtA8w8yTQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 1. 先来先服务 — [Updated on 2022-02-24 16:52:43](https://hyp.is/IQqQnpVPEeyWDifMQEnI0g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 2. 最短寻道时间优先 — [Updated on 2022-02-24 16:52:44](https://hyp.is/Idyd0pVPEeyu0_sXN_PvYg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 3. 电梯扫描算法 — [Updated on 2022-02-24 16:52:47](https://hyp.is/I3TffpVPEey9qZsIiyZWAw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 系统并发和并行，分得清吗？ 并发是指宏观上在一段时间内能同时运行多个程序，而并行则指同一时刻能运行多个指令。 并行需要硬件支持，如多流水线、多核处理器或者分布式计算系统。 操作系统通过引入进程和线程，使得程序能够并发运行。 — [Updated on 2022-02-24 16:53:17](https://hyp.is/NZAUipVPEeyxgq8aWAuziw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁相关问题大总结，超全！ — [Updated on 2022-02-24 16:53:50](https://hyp.is/SQPuEJVPEeyWEIeE4lfNrw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 语句1和语句2表示线程A先锁资源1，再锁资源2，语句3和语句4表示线程B先锁资源2再锁资源1，具备死锁产生的条件。 — [Updated on 2022-02-24 16:54:23](https://hyp.is/XSVWcpVPEey7QTdXAeHvkg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- ​ 保证上锁的顺序一致。 — [Updated on 2022-02-24 16:54:25](https://hyp.is/XiiLwJVPEeyiTRdV1QgOVA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁必要条件 — [Updated on 2022-02-24 16:54:34](https://hyp.is/Y6W2DpVPEeyiTgcEoWb0dQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 鸵鸟策略 — [Updated on 2022-02-24 16:54:40](https://hyp.is/Zt-K3pVPEey2jpeBI2HpHw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 把头埋在沙子里，假装根本没发生问题。 — [Updated on 2022-02-24 16:54:42](https://hyp.is/aBMnspVPEey3RdfuKp__Kg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 处理死锁问题的办法仅仅是忽略它。 — [Updated on 2022-02-24 16:54:53](https://hyp.is/brnd9JVPEey2XN95bqv8TA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 不试图阻止死锁，而是当检测到死锁发生时，采取措施进行恢复 — [Updated on 2022-02-24 17:01:31](https://hyp.is/XDT2cpVQEey3SKO8JcaxXg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁恢复 利用抢占恢复 利用回滚恢复 通过杀死进程恢复 — [Updated on 2022-02-24 17:01:39](https://hyp.is/YL1lHJVQEeya1ecsPX7QSA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁预防 — [Updated on 2022-02-24 17:02:01](https://hyp.is/bfW8XJVQEeywS4O3F2Z7yw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 破坏循环请求等待 ​ 给资源统一编号，进程只能按编号顺序来请求资源。 — [Updated on 2022-02-24 17:02:14](https://hyp.is/dZbfQJVQEeyqEWdHOCr8KQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 破坏不剥夺条件 — [Updated on 2022-02-24 17:02:18](https://hyp.is/eE7ApJVQEeyv4YNWemsQfA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 破坏请求和保持条件 — [Updated on 2022-02-24 17:02:20](https://hyp.is/eSqSjJVQEeyuwkePqhr48g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 破坏互斥条件 — [Updated on 2022-02-24 17:02:21](https://hyp.is/efEQVpVQEeyhE9duUxa8Fg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 冯诺依曼结构有哪几个模块？分别对应现代计算机的哪几个部分？（百度安全一面） — [Updated on 2022-02-24 17:02:43](https://hyp.is/hrNORJVQEeyhFVuNyXQsyA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多进程和多线程的区别是什么？换句话说，什么时候该用多线程，什么时候该用多进程？ — [Updated on 2022-02-24 17:02:45](https://hyp.is/iFkj9JVQEey2kiPkekM8Yw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 多分布：可能要扩展到多机分布的用多进程，多核分布的用多线程 — [Updated on 2022-02-24 17:03:33](https://hyp.is/pPyN8pVQEeyf2av5zZP8lQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 频繁修改 — [Updated on 2022-02-24 17:03:43](https://hyp.is/qqOviJVQEeysFnMZ54iv2Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 计算量 — [Updated on 2022-02-24 17:03:44](https://hyp.is/q3L3PpVQEey5T8sIuQ_t5Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 相关性 — [Updated on 2022-02-24 17:03:46](https://hyp.is/rD5UkpVQEeyf24cOJFRS0A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 应用数据与静态资源分离  — [Updated on 2022-02-24 17:04:18](https://hyp.is/v3zDuJVQEeyq8o8TS29uZg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 客户端缓存 — [Updated on 2022-02-24 17:04:25](https://hyp.is/w_zUqpVQEeyf3fdTOo9bQA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 集群和分布式 （集群是所有的服务器都有相同的功能，请求哪台都可以，主要起分流作用） （分布式是将不同的业务放到不同的服务器中，处理一个请求可能需要使用到多台服务器，起到加快请求处理的速度。） 可以使用服务器集群和分布式架构，使得原本属于一个服务器的计算压力分散到多个服务器上。同时加快请求处理的速度。 — [Updated on 2022-02-24 17:04:40](https://hyp.is/zPQaAJVQEeyiUeNT1Tkqvg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 反向代理 在访问服务器的时候，服务器通过别的服务器获取资源或结果返回给客户端。 — [Updated on 2022-02-24 17:04:51](https://hyp.is/01DEApVQEeyrfVd2loNEMw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁避免 — [Updated on 2022-02-27 10:48:47](https://hyp.is/yXy_Kpd3EeyrQhOaWRwiVA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 死锁预防 — [Updated on 2022-02-27 10:48:49](https://hyp.is/ykM0opd3EeywFEvYu1o4xw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 动态分区分配算法有哪几种？可以分别说说吗 — [Updated on 2022-02-27 10:57:09](https://hyp.is/9Kopypd4EeyvN_fmHR4ekQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 首次适应算法 — [Updated on 2022-02-27 10:57:11](https://hyp.is/9cQQMpd4EeyVsXt8WfuZoQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 每次都从低地址开始查找，找到第–个能满足大小的空闲分区 — [Updated on 2022-02-27 10:57:16](https://hyp.is/-NO18pd4EeyzoDtOIsasEQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 最佳适应算法 — [Updated on 2022-02-27 10:57:20](https://hyp.is/-taXcJd4Eey43YuXLgw9BA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 可以尽可能多地留下大片的空闲区,即，优先使用更小的空闲 — [Updated on 2022-02-27 11:00:01](https://hyp.is/Wsn1jJd5EeyVsn9UsHrQVg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 算法思想:为了解决最佳适应算法的问题—即留下太多难以利用的小碎片，可以在每次分配时优先使用最大的连续空闲区，这样分配后剩余的空闲区就不会太小，更方便使用。 — [Updated on 2022-02-27 11:00:10](https://hyp.is/YKnmLpd5Eey6bc__JGPN8g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 首次适应算法每次都从链头开始查找的。这可能会导致低地址部分出现很多小的空闲分区，而每次分配查找时，都要经过这些分区，因此也增加了查找的开销。如果每次都从上次查找结束的位置开始检索，就能解决上述问题。 — [Updated on 2022-02-27 11:00:29](https://hyp.is/bAKV8pd5EeyVs2tZKDE0sg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 虚拟内存使用了空分复用技术，它将物理内存抽象为地址空间，每个进程都有各自的地址空间。地址空间的页被映射到物理内存，地址空间的页并不需要全部在物理内存中，当使用到一个没有在物理内存的页时，执行页面置换算法，将该页置换到内存中 — [Updated on 2022-02-27 11:00:57](https://hyp.is/fD-Xxpd5Eeyo7PMxKxDVoA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 时（时间）分复用技术和空（空间）分复用技术。 — [Updated on 2022-02-27 11:01:21](https://hyp.is/ioU0Tpd5EeyHATsIAxOQkQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 可能是最全的页面置换算法总结了 — [Updated on 2022-02-27 11:01:49](https://hyp.is/mzB28Jd5Eey276fvWZWW3Q/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 最佳置换算法(OPT，Optimal) :每次选择淘汰的页面将是以后永不使用，或者在最长时间内不再被访问的页面，这样可以保证最低的缺页率。 — [Updated on 2022-02-27 11:02:09](https://hyp.is/pzj4yJd5Eey6by9U1Pa-KQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 只有在进程执行的过程中才能知道接下来会访问到的是哪个页面。操作系统无法提前预判页面访问序列。因此，最佳置换算法是无法实现的 — [Updated on 2022-02-27 11:03:22](https://hyp.is/0xxVtpd5EeySWmPHU-jzWQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 先进先出置换算法(FIFO) :每次选择淘汰的页面是最早进入内存的页面 实现方法:把调入内存的页面根据调入的先后顺序排成一个队列，需要换出页面时选择队头页面队列的最大长度取决于系统为进程分配了多少个内存块。 — [Updated on 2022-02-27 11:03:34](https://hyp.is/2dAtppd5EeyecwNPoWTgSg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- Belady异常—当为进程分配的物理块数增大时，缺页次数不减反增的异常现象。 只有FIFO算法会产生Belady异常，而LRU和OPT算法永远不会出现Belady异常。 — [Updated on 2022-02-27 11:03:59](https://hyp.is/6J4LZJd5EeyfBUPeH_nZOg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 因为较早调入的页往往是经常被访问的页，这些页在FIFO算法下被反复调入和调出，并且有Belady现象。所谓Belady现象是指：采用FIFO算法时，如果对—个进程未分配它所要求的全部页面，有时就会出现分配的页面数增多但缺页率反而提高的异常现象。 — [Updated on 2022-02-27 11:05:00](https://hyp.is/DQjdJpd6EeyaUPusJXOApw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 最近最久未使用置换算法(LRU，least recently used) :每次淘汰的页面是最近最久未使用的页面  — [Updated on 2022-02-27 11:05:07](https://hyp.is/EVS1dpd6EeyaUe-LwwY1Xg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 用访问字段记录该页面自.上次被访问以来所经历的时间t — [Updated on 2022-02-27 11:05:18](https://hyp.is/F-4WcJd6EeyjejvnGd8IGw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 虽然算法性能好，但是实现困难，开销大 — [Updated on 2022-02-27 11:05:22](https://hyp.is/GqWA9pd6Eey_5l8iKBxUuQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- LRU是堆栈类算法，理论上可以证明，堆栈类算法不可能出现Belady异常。 — [Updated on 2022-02-27 11:05:43](https://hyp.is/JuBxtJd6EeyYLhMe0Yg0eg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 时钟置换算法(CLOCK) — [Updated on 2022-02-27 11:05:50](https://hyp.is/KvZQ8pd6EeyqpYP-q0Ysug/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 最佳置换算法性OPT能最好，但无法实现；先进先出置换算法实现简单，但算法性能差；最近最久未使用置换算法性能好，是最接近OPT算法性能的，但是实现起来需要专门的硬件支持，算法开销大。 — [Updated on 2022-02-27 11:05:59](https://hyp.is/MET7Opd6EeytpFdbYctIYA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 最近未用算法 — [Updated on 2022-02-27 11:06:10](https://hyp.is/Nxamtpd6Eeyx_VP8Xz8xPQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 再将内存中的页面都通过链接指针链接成一个循环队列。当某页被访问时，其访问位置为1 — [Updated on 2022-02-27 11:06:26](https://hyp.is/QFyVyJd6Eey9iacrbkwg0g/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 当需要淘汰-一个页面时，只需检查页的访问位。如果是0，就选择该页换出;如果是1，则将它置为0，暂不换出，继续检查下一个页面，若第- - ~轮扫描中所有页面都是1，则将这些页面的访问位依次置为0后，再进行第二轮扫描(第二轮扫描中一定会有访问位为0的页面，因此简单的CLOCK算法选择–个淘汰页面最多会经过两轮扫描) — [Updated on 2022-02-27 11:06:42](https://hyp.is/Sj6JDJd6Eey0oruJOi2OJg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 如果被淘汰的页面没有被修改过,就不需要执行I/O操作写回外存。只有被淘汰的页面被修改过时，才需要写回外存。 — [Updated on 2022-02-27 11:07:10](https://hyp.is/WwpaLJd6EeyzCVcSJcbG8A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 应优先淘汰没有修改过的页面，避免I/O操作。这就是改进型的时钟置换算法的思想。修改位=0，表示页面没有被修改过;修改位=1，表示页面被修改过。 — [Updated on 2022-02-27 11:07:22](https://hyp.is/YhF7IJd6Eey9irMULb7REQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- (访问位，修改位)的形式表示各页面状态。如(1, 1)表示一个页面近期被访问过，且被修改过。 — [Updated on 2022-02-27 11:07:31](https://hyp.is/ZwpyCJd6Eeyo3-urd7S3wA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 本轮将所有扫描过的帧访问位设为0 — [Updated on 2022-02-27 11:09:02](https://hyp.is/nZHTPpd6Eeyo8YvWyVtDRg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

-  第二轮 — [Updated on 2022-02-27 11:09:07](https://hyp.is/oJ3hnpd6EeyzcJNIjtyccw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 第一轮 — [Updated on 2022-02-27 11:09:10](https://hyp.is/ogLQxpd6Eeyll9MfuO1eZw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 第三轮 — [Updated on 2022-02-27 11:09:13](https://hyp.is/o73u5pd6EeyrZgNokLCK7A/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 这些页被映射到物理内存，但不需要映射到连续的物理内存，也不需要所有页都必须在物理内存中 — [Updated on 2022-02-27 19:04:54](https://hyp.is/F46fGJe9Eeye4y9zFo0kwA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 当程序引用到不在物理内存中的页时，由硬件执行必要的映射，将缺失的部分装入物理内存并重新执行失败的指令。 — [Updated on 2022-02-27 19:48:30](https://hyp.is/L0dnTJfDEeybHnv2l8nFiQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 协程是用户态的轻量级线程，线程内部调度的基本单位 — [Updated on 2022-02-28 10:34:52](https://hyp.is/Af05jpg_EeyxuYPOAkqbUQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 堆、全局变量、静态变量、指针，引用、文件等 — [Updated on 2022-02-28 10:35:19](https://hyp.is/EmC6xpg_EeyiUlMg548r4w/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 外中断是指由 CPU 执行指令以外的事件引起，如 I/O 完成中断，表示设备输入/输出处理已经完成，处理器能够发送下一个输入/输出请求。此外还有时钟中断、控制台中断等。 — [Updated on 2022-02-28 10:35:53](https://hyp.is/JihRzJg_Eeyqwmsgbi8PYw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 处理机调度的最小单位 — [Updated on 2022-02-28 10:41:30](https://hyp.is/75LLUJg_EeyiWHNMuZ3rAA/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 每个程序拥有自己的地址空间，这个地址空间被分割成多个块，每一块称为一页 — [Updated on 2022-02-28 10:49:59](https://hyp.is/EfyP7Je9Eey4IwNZb-ZxAQ/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation
    - Annotation: 这个是指程序的地址空间。每个程序拥有自己的地址空间。这些地址空间划分成页。然后映射到物理内存中。这些映射可以是不连续的。意味着程序可以在执行的时候再将需要的页文件调入内存。这也伴随着一些内存页置换算法。
- 内核对子进程的结束不关心，由内核回收 — [Updated on 2022-02-28 11:02:13](https://hyp.is/1F2kiJhCEeyNCdMe9DPUYw/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation

- 表示父进程忽略SIGCHLD信号，该信号是子进程退出的时候向父进程发送的 — [Updated on 2022-02-28 11:02:25](https://hyp.is/25gx8JhCEey6O2sT0ET7Wg/github.com/forthespada/InterviewGuide/blob/main/Doc/Knowledge/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md) — Group: #self-notation




