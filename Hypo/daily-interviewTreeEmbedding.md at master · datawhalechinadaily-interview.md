---
doc_type: hypothesis-highlights
url: >-
  https://github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md
---

# daily-interview/TreeEmbedding.md at master · datawhalechina/daily-interview

## Metadata
- Author: [github.com]()
- Title: daily-interview/TreeEmbedding.md at master · datawhalechina/daily-interview
- Reference: https://github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md
- Category: #article

## Page Notes
## Highlights
- 每次建树特征个数随机选择 — [Updated on 2022-02-26 19:53:55](https://hyp.is/xi-RYpb6Eey3LifBWmjVNQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 每次建树样本个数随机选择 — [Updated on 2022-02-26 19:53:56](https://hyp.is/xyojIJb6Eeypg8cjirnc7g/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 样本扰动，还来自属性扰动，这就使得最终集成得泛化性能可通过个体学习器之间差异度得增加而进一步提升。使得模型更加鲁棒。 — [Updated on 2022-02-26 19:54:05](https://hyp.is/zFXU1Jb6Eey1YDfCfWNQXA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 本轮迭代找到决策树，要让样本的损失尽量变得更小。GBDT本轮迭代只需拟合当前模型的残差。 — [Updated on 2022-02-26 19:54:29](https://hyp.is/2n7EJpb6EeysGPd0FWjBxw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 行采样和列采样技术 — [Updated on 2022-02-26 20:00:35](https://hyp.is/tLnqspb7EeyYp7u_HRjwMQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 更好的降低模型的方差 — [Updated on 2022-02-26 20:00:46](https://hyp.is/u2ElGpb7Eey2CoMXHvwgYg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 在回归的使用是使用的k个树的平均。可以看出来rf的训练和预测过程都可以进行并行处理。 — [Updated on 2022-02-26 20:00:57](https://hyp.is/wfq2epb7EeywXwfyP2TiAA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 随机森林对异常值不敏感，GBDT对异常值非常敏感 — [Updated on 2022-02-26 20:01:21](https://hyp.is/0BuPrpb7EeypiDdzXKF99A/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 因此可能得到更快的速度 — [Updated on 2022-02-26 20:01:27](https://hyp.is/0878HJb7EeythEuWqPEJWA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 数值连续特征使用的最小均方误差 — [Updated on 2022-02-26 20:02:08](https://hyp.is/7Ak6cpb7EeymJHMH7izRLg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 离散值使用的gini指数 — [Updated on 2022-02-26 20:02:11](https://hyp.is/7haekJb7Eey1rPP5CJzyjA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- GDBT的做法是采用一对多的策略也就是说，对每个类别训练M个分类器。假设有K个类别，那么训练完之后总共有M*K颗树。 — [Updated on 2022-02-26 20:02:40](https://hyp.is/_3y4Ipb7EeyUAaOA_WjHZQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 也就是说，K个类别都拟合完第一颗树之后才开始拟合第二颗树，不允许先把某一个类别的M颗树学习完，再学习另外一个类别。 — [Updated on 2022-02-26 20:02:51](https://hyp.is/BfYUeJb8EeyxFFPz6fE3Rg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 这个时候xgboost相当于带L1和L2正则化项的逻辑斯蒂回归（分类问题）或者线性回归（回归问题）。 — [Updated on 2022-02-26 20:04:17](https://hyp.is/OUmJrpb8EeyFbOc60xHihA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 代价函数里加入了正则项 — [Updated on 2022-02-26 20:04:29](https://hyp.is/QAIQzJb8Eey74jOmNlppOQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 数进行了二阶泰勒展开 — [Updated on 2022-02-26 20:04:31](https://hyp.is/QU8qgpb8Eey2C19NEL5j3w/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 列抽样 — [Updated on 2022-02-26 20:04:40](https://hyp.is/RsVyMpb8Eey2DONcFu4YUA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- xgboost工具支持并行。 — [Updated on 2022-02-26 20:04:43](https://hyp.is/SFfQBJb8EeylxDuQyjCV4g/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 可并行的近似直方图算法 — [Updated on 2022-02-26 20:04:46](https://hyp.is/SqCEAJb8Eey-9QONzgb-mQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 可并行的近似直方图算法。 — [Updated on 2022-02-26 20:05:18](https://hyp.is/XVYaOJb8Eeyx53d1KOZsyQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- xgb为什么使用二阶梯度信息， — [Updated on 2022-02-26 20:05:25](https://hyp.is/Ya68SJb8EeylxVPIxMzqhQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 从泰勒展开的角度来看展开的次数越多越能更精准的表示损失函数的值，但是如果我们使用二阶梯度就要要求损失函数二阶可导，如果使用n阶展开就要求损失函数n阶可导，但是有很多损失函数不是n阶可导的， — [Updated on 2022-02-26 20:05:37](https://hyp.is/aK0xyJb8Eey2DW9BxouItw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 直方图算法 — [Updated on 2022-02-26 20:05:42](https://hyp.is/a31Q_pb8EeypqcuO_jjXuw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 在训练决策树计算切分点的增益时，预排序需要对每个样本的切分位置计算，所以时间复杂度是O(#data)而LightGBM则是计算将样本离散化为直方图后的直方图切割位置的增益即可，时间复杂度为O(#bins), — [Updated on 2022-02-26 20:05:47](https://hyp.is/buqkWJb8Eey-80tRgsNA4g/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 直方图做差进一步提高效率 — [Updated on 2022-02-26 20:05:50](https://hyp.is/cFKEjJb8Eey1aqsjKOy1MA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 节省内存 — [Updated on 2022-02-26 20:05:54](https://hyp.is/cuKYrpb8Eey-9EdFTEtj-g/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 稀疏特征优化、直接支持类别特征、网络通信优化 — [Updated on 2022-02-26 20:05:56](https://hyp.is/dEAgGJb8EeymSmv8tcwFTw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- RF可能出现过拟合? GBDT没有任何改变? — [Updated on 2022-02-26 20:06:06](https://hyp.is/eg-0Dpb8Eey9oDsVECN5Ig/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 前面的树往往起到决定性的作用，如何改进这个问题 — [Updated on 2022-02-26 20:06:36](https://hyp.is/jDQpCJb8Eeyx-4tekHD9NQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation

- 一般使用缩减因子对每棵树进行降权，可以使用带有dropout的GBDT算法 — [Updated on 2022-02-26 20:06:39](https://hyp.is/jbHyVpb8Eeyj4LNWueFPTQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/TreeEmbedding.md) — Group: #self-notation




