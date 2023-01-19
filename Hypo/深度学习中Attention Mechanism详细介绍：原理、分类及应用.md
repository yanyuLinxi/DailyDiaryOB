---
doc_type: hypothesis-highlights
url: 'https://zhuanlan.zhihu.com/p/78655043'
---

# 深度学习中Attention Mechanism详细介绍：原理、分类及应用

## Metadata
- Author: [zhuanlan.zhihu.com]()
- Title: 深度学习中Attention Mechanism详细介绍：原理、分类及应用
- Reference: https://zhuanlan.zhihu.com/p/78655043
- Category: #article

## Page Notes
## Highlights
- i表示encoder端的第i个词 — [Updated on 2022-03-04 18:48:06](https://hyp.is/kssWDpuoEeyh31e6-s7RVw/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- hj表示encoder端的第j和词的隐向量 — [Updated on 2022-03-04 18:48:18](https://hyp.is/megeWpuoEeytkNdDDzA2Pw/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- 我们之前所描述的传统的Attention Mechanism就是Soft Attention — [Updated on 2022-03-04 19:00:17](https://hyp.is/RvIqDpuqEeysfePzOTf8oA/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- Hard Attention会依概率Si来采样输入端的隐状态一部分来进行计算，而不是整个encoder的隐状态 — [Updated on 2022-03-04 19:03:55](https://hyp.is/yPSSYpuqEeyzWCsR6fM-_Q/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- Global Attention：传统的Attention model一样。所有的hidden state都被用于计算Context vector 的权重 — [Updated on 2022-03-04 19:04:01](https://hyp.is/zBvhZpuqEeyzWXtPoulopA/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- Global Attention有一个明显的缺点就是，每一次，encoder端的所有hidden state都要参与计算，这样做计算开销会比较大，特别是当encoder的句子偏长，比如，一段话或者一篇文章，效率偏低。因此，为了提高效率，Local Attention应运而生 — [Updated on 2022-03-04 19:04:59](https://hyp.is/7pXbhJuqEeyuAyNILnxF7Q/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- 传统的Attention是基于source端和target端的隐变量（hidden state） — [Updated on 2022-03-04 19:13:47](https://hyp.is/KUp8ypusEey6ESsN4hpmsw/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- 它分别在source端和target端进行 — [Updated on 2022-03-04 19:14:00](https://hyp.is/MWyAQpusEeybnf9469CcCg/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- 仅与source input或者target input自身相关的Self Attention — [Updated on 2022-03-04 19:14:04](https://hyp.is/M2Ov4pusEeyItQctqicvYw/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- source端的得到的self Attention加入到target端得到的Attention中 — [Updated on 2022-03-04 19:14:10](https://hyp.is/Nwg59pusEeykvlsRaL9m9A/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation

- 传统的Attention机制忽略了源端或目标端句子中词与词之间的依赖关系 — [Updated on 2022-03-04 19:14:18](https://hyp.is/O_iM1pusEeygvbfxEoXxBQ/zhuanlan.zhihu.com/p/78655043) — Group: #self-notation





