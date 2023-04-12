---
title: LLM调研
date: 2023-04-12
tags : [
	"LLM调研",
]
categories : [
	"教程",
]
series : []
aliases : []
draft: false
toc: true
---
LLM（大语言模型）的背景调研：
1. LLM的timeline
	1. 深度学习的发展史（一部问题容量和模型容量互相对抗的发展史）
		1. 决定效果好坏的几个因素（数据、模型容量、问题容量）
		2. 支持向量机。（模型容量够不上问题容量，此时提升数据也无法提升模型效能，大家在提升模型的能力=》高斯核等等）
		3. CNN图卷积出来后（模型能力可以往上升了，数据的作用提升出来了，但仍然出现瓶颈）
			1. 中间任务的兴起（通过引入先验知识来帮助模型理解，通过提升数据，来使得模型达到问题容量）=》举例
			2. CNN的瓶颈是什么？模型大小，长距离依赖=》残差模型
			3. RNN的瓶颈是什么？长距离依赖。=》注意力机制（global、local）
		4. Trm结构。attention、残差、norm的结合。
		5. encoder、decoder的区别以及时间线。
	2. llm定义
	3. 为什么LLM成功了。成功的必要条件
		1. 注意力机制=》突破了模型理论上限
		2. 残差机制=》
		3. batchnorm
	4. LLM未来的发展方向。（大模型成为趋势，如何将大模型应用到各行各业）
3. llama的搭建、实验细节。
4. finetune的基本理论。

要弄清楚几个问题：
1. gpt模型是如何发展起来的，近几年来的深度学习究竟在如何发展？是不是真的深度学习就是换个模型就可以了？
2. GPT模型的炼成。
	1. 大模型
	2. 强化学习
4. 生成模型发展这么多年，发展出了哪些分支？
	1. gpt
	2. bert
	3. clip等
5. 未来gpt可能往哪方面发展，可能存在的发展方向
	1. 大模型指导小模型
	2. hugginggpt，用chatgpt来连接万物模型。
6. 低成本可训练的gpt的炼成（实操）。llama，PaLM，Chinchilla。



资料：
1. [# 从Word Embedding到Bert模型—自然语言处理中的预训练技术发展史](https://zhuanlan.zhihu.com/p/49271699)
2. [# 乘风破浪的PTM：两年来预训练模型的技术进展](https://zhuanlan.zhihu.com/p/254821426)
3. [由Chatgpt归纳的LLM技术精要](https://mp.weixin.qq.com/s/gR9YsYjFVhViuANWFw59fg)
4. [李沐：gpt时代下的AI怎么做](https://www.bilibili.com/video/BV1fg4y1s7qv/)
5. [李沐：大模型时代下如何做科研](https://www.bilibili.com/video/BV1oX4y1d7X6/)
6. [李沐：gpt发展史](https://www.bilibili.com/video/BV1AF411b7xQ/)
7. [李沐：迁移学习](https://www.bilibili.com/video/BV1bq4y1y7tg/)