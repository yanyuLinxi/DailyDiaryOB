---
doc_type: hypothesis-highlights
url: 'https://zhuanlan.zhihu.com/p/412351920'
---

# GPT系列论文阅读笔记

## Metadata
- Author: [zhuanlan.zhihu.com]()
- Title: GPT系列论文阅读笔记
- Reference: https://zhuanlan.zhihu.com/p/412351920
- Category: #article

## Page Notes
## Highlights
- 该论文用的是可学习的位置矩阵来表征位置信息 — [Updated on 2022-06-11 16:31:36](https://hyp.is/6BNVlOlgEey-AE-bWaU2gA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 并且他是生成式(Generative)的无监督方式预训练(Pre-Train)模型 — [Updated on 2022-06-11 16:31:42](https://hyp.is/7AezPulgEeyPv68syfK8Hw/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 因为虽然他的效果十分惊人并且开始了新的学界范式，但在未出名时这个框架给人的感觉便是创新性不足，犹如一个简单的缝合怪。但真理和科学往往便是这样前进的。 — [Updated on 2022-06-11 16:32:04](https://hyp.is/-PuaaulgEey-AUv_j2mCVQ/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 模型框架 — [Updated on 2022-06-11 16:32:12](https://hyp.is/_gzrHOlgEeyQFD-YhA_FBQ/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 加一个简单的线性层做映射，最后以SOFTMAX转化为概率形式 — [Updated on 2022-06-11 16:32:38](https://hyp.is/DTv20ulhEeyuGJOJz408bg/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 如果想要对下游任务做更好的优化，往往需要更复杂的做法 — [Updated on 2022-06-11 16:32:50](https://hyp.is/FHkBdOlhEey6G0eC-Xk2gA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 是个多层堆叠的Transformer里的解码器 — [Updated on 2022-06-11 16:44:01](https://hyp.is/pDozaOliEeySg8ddgyQmpg/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 遍历式的单项文本(traversal style) — [Updated on 2022-06-11 16:44:58](https://hyp.is/xlY7LOliEeyEQa9857ZvRA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 文章发现模型的泛化能力与模型堆叠的解码器层数直接相关 — [Updated on 2022-06-11 16:45:15](https://hyp.is/0HOTSOliEeyIRMdxdNehIg/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 最主要的就是OPENAI自己，从GPT1的几亿参数到GPT2的十倍参数到GPT3的1750亿参数 — [Updated on 2022-06-11 16:45:28](https://hyp.is/2BV2yuliEeyu5uu6PRK9hw/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 章测试了不做任何微调（zero-shot）的情况下 — [Updated on 2022-06-11 16:46:41](https://hyp.is/A5I3KuljEey74k-5wyYXlA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 并且lstm的高方差显示了其架构的归纳偏置不如transformer. — [Updated on 2022-06-11 16:47:43](https://hyp.is/KHG0bOljEeyG2N8GA3XpoA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 作者发现在抛弃第一阶段的预训练后，模型表现大幅下降 — [Updated on 2022-06-11 16:47:59](https://hyp.is/MmeoAOljEeyEQud4V5iL3A/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 其次用LSTM模型所取得的结果全面逊色于用transformer的结果。 — [Updated on 2022-06-11 16:48:04](https://hyp.is/NUjx-uljEey91DNOr2yWQA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 即预训练，提示(PROMPT)加预测 — [Updated on 2022-06-11 16:48:24](https://hyp.is/QTAuDOljEeyR9__R9svnkg/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 其中一个便是模型在ZERO-SHOT的设定下，模型的表现与堆叠的解码器层数有直接的正相关性。 — [Updated on 2022-06-11 16:54:10](https://hyp.is/DzECVOlkEeygbIc704ILuw/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 大规模语料下的生成式预训练模型为什么对下游任务有帮助 — [Updated on 2022-06-11 16:54:23](https://hyp.is/FuvHrulkEeyxkAesbKTWeA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 单任务单领域的训练是模型缺乏泛化能力的主要原因 — [Updated on 2022-06-11 16:56:18](https://hyp.is/W-nEUOlkEey9xndvpYFgzQ/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 能不能有一种模型完全不需要对下游任务进行适配就可以表现优异 — [Updated on 2022-06-11 16:56:31](https://hyp.is/Y4URBulkEeygbb_bFsE6dg/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 首先模型运用了更大规模的新数据集 — [Updated on 2022-06-11 16:58:16](https://hyp.is/oh9rZOlkEeyxkresn-pdPA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 具体来说层归一化 — [Updated on 2022-06-11 16:58:24](https://hyp.is/pr5XeulkEey0EYMHc9YH_g/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 层归一化 — [Updated on 2022-06-11 16:58:30](https://hyp.is/qgsdKOlkEeyMA3c8sEjDsA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 前置层归一化和后置层归一化，对于模型预训练的稳定性和微调有着重要区别） — [Updated on 2022-06-11 16:58:39](https://hyp.is/r-XFGOlkEeyIJ-MEPcMiTw/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 仅靠预训练+提示+预测就在8/9个任务里达到了SOTA. — [Updated on 2022-06-11 16:59:13](https://hyp.is/xBFDvulkEeysrWeMDoopXQ/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- 只重点考察了在ZERO-SHOT(只有任务描述） — [Updated on 2022-06-11 17:02:32](https://hyp.is/OpZBYOllEeySiOeJsAPycA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation

- ONE-SHOT（任务描述+单个例子）和FEW-SHOT(任务描述+多个例子) — [Updated on 2022-06-11 17:02:35](https://hyp.is/PEjEpullEeyPxPsvrnBcQA/zhuanlan.zhihu.com/p/412351920) — Group: #self-notation





