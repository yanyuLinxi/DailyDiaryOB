---
doc_type: hypothesis-highlights
url: >-
  https://github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md
---

# daily-interview/线性回归+逻辑回归.md at master · datawhalechina/daily-interview

## Metadata
- Author: [github.com]()
- Title: daily-interview/线性回归+逻辑回归.md at master · datawhalechina/daily-interview
- Reference: https://github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md
- Category: #article

## Page Notes
## Highlights
- 两种回归均通过在损失函数中引入正则化项 — [Updated on 2022-02-26 23:43:43](https://hyp.is/4GK3kpcaEey_OYNvMDwilg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 其中共有mm个样本点，乘以1/2是为了方便计算。 — [Updated on 2022-02-26 23:43:57](https://hyp.is/6MrC7pcaEeyh-C8fglWqzg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- ElasticNet 回归： 线性回归 + L1正则化 + L2 正则化。 — [Updated on 2022-02-26 23:44:11](https://hyp.is/8RI0PJcaEeyyKttAOKrNXw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 单变量离散化为N个后，每个变量有单独的权重，相当于为模型引入了非线性，能够提升模型表达能力，加大拟合； 离散特征的增加和减少都很容易，易于模型的快速迭代； — [Updated on 2022-02-26 23:46:44](https://hyp.is/TEGVZJcbEeyp02vctVfmxQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 稀疏向量内积乘法运算速度快，计算结果方便存储，容易扩展； — [Updated on 2022-02-26 23:46:49](https://hyp.is/T0JajJcbEeyjeT82nEieSQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 特征离散化以后，起到了简化了逻辑回归模型的作用，降低了模型过拟合的风险。 — [Updated on 2022-02-26 23:47:12](https://hyp.is/XX3QpJcbEeyx_N-QIf3noA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 比如如果对用户年龄离散化，20-30作为一个区间，不会因为一个用户年龄长了一岁就变成一个完全不同的人； — [Updated on 2022-02-26 23:47:18](https://hyp.is/YLDYypcbEeyxr_caPeW_sg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 离散化后的特征对异常数据有很强的鲁棒性：比如一个特征是年龄>30是1，否则0。如果特征没有离散化，一个异常数据“年龄300岁”会给模型造成很大的干扰。 — [Updated on 2022-02-26 23:47:26](https://hyp.is/ZZV9UJcbEeydngP97eDkVQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 逻辑斯特回归为什么要对特征进行离散化。 — [Updated on 2022-02-26 23:47:28](https://hyp.is/Zu3-NJcbEeykHxduuLDCIA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 如果在损失函数最终收敛的情况下，有很多特征高度相关也不会影响分类器的效果。 — [Updated on 2022-02-26 23:48:59](https://hyp.is/nTzkKJcbEeynhzfMbUXVfQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 但是这个特征本身重复了100遍，实质上将原来的特征分成了100份，每一个特征都是原来特征权重值的百分之一 — [Updated on 2022-02-26 23:49:25](https://hyp.is/rGIdLpcbEey-30fEOWowZw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 还是可以认为这100个特征和原来那一个特征扮演的效果一样，只是可能中间很多特征的值正负相消了。 — [Updated on 2022-02-26 23:49:31](https://hyp.is/r--YBJcbEeysWHcwdfyuQg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- Sigmoid也让逻辑回归的损失函数成为凸函数，这也是很好的性质。 — [Updated on 2022-02-26 23:49:36](https://hyp.is/svp5upcbEeymjJuf3DVHRQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 而Sigmoid能够把它映射到[0,1][0,1]之间。正好这个是概率的范围。  — [Updated on 2022-02-26 23:49:43](https://hyp.is/t0sc9JcbEeyh_NeTjSFphA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- LR是参数模型，SVM是非参数模型。 — [Updated on 2022-02-26 23:50:02](https://hyp.is/wkiEXJcbEeykIRsQcgL8Pw/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 区别在于逻辑回归采用的是交叉熵损失函数，SVM采用的是hinge loss — [Updated on 2022-02-26 23:50:06](https://hyp.is/xQW1wJcbEeykIhPwEXmZBg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- SVM的处理方法是只考虑support vectors，也就是和分类最相关的少数点 — [Updated on 2022-02-26 23:50:10](https://hyp.is/x0NCEpcbEey95lPSc0eYMQ/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 逻辑回归相对来说模型更简单，好理解 — [Updated on 2022-02-26 23:50:15](https://hyp.is/yk4R0JcbEeymjUe6ndv5pA/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- 而SVM的理解和优化相对来说复杂一些，SVM转化为对偶问题后,分类只需要计算与少数几个支持向量的距离,这个在进行复杂核函数计算时优势很明显,能够大大简化模型和计算。 — [Updated on 2022-02-26 23:50:22](https://hyp.is/zqTuPpcbEey-YzPqqEf3Ag/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation

- LR能做的 SVM能做，但可能在准确率上有问题，SVM能做的LR有的做不了。 — [Updated on 2022-02-26 23:50:29](https://hyp.is/0ozUEpcbEeyqAc-TCHBWTg/github.com/datawhalechina/daily-interview/blob/master/AI%E7%AE%97%E6%B3%95/machine-learning/%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92%2B%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.md) — Group: #self-notation




