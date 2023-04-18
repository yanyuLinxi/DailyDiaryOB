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


要弄清楚几个问题：
1. gpt模型是如何发展起来的，近几年来的深度学习究竟在如何发展？是不是真的深度学习就是换个模型就可以了？
2. GPT模型的炼成。
	1. 大模型
	2. 强化学习
4. 生成模型发展这么多年，发展出了哪些分支？
	1. gpt
	2. bert
	3. clip等（zero shot）
5. 未来gpt可能往哪方面发展，可能存在的发展方向
	1. 大模型指导小模型
	2. hugginggpt，用chatgpt来连接万物模型。
	3. 往efficient上做（PEFT）
	4. 使用已经有的模型（Existing stuff，pretrained model 选择新的方向）
	5. 设计plug and play 即插即用的模块
	6. 做数据集、评价指标、survey
	7. prompt是什么。
6. 低成本可训练的gpt的炼成（实操）。llama，PaLM，Chinchilla。

整个文章组织架构：
1. 介绍llm的timeline（结合实验室发表的文章。杨佳的两篇。洪瑶的论文、江帅的论文、自己的论文）介绍路径就是模型容量和问题容量。问题容量就是目标函数。模型+数据=》问题。模型和数据就是一个桶的两个板。只有两者匹配的时候，才能得到模型空间，去匹配问题空间
2. 介绍gpt后时代的一些经典论文。gpt模型的改进和变化。
3. 介绍未来研究方向（自己觉得感兴趣的研究方向，和代码安全相结合的方向）
4. 介绍一个实践llama


组织结构：
1. LLM的timeline
	1. 深度学习的发展史（一部问题容量和模型容量互相对抗的发展史）
		1. 阐述：模型容量指的是模型拟合各种函数的能力。模型容量由几个因素共同影响短板理论（非线性能力、参数量、数据量）当模型容量大于问题容量时，问题是可解的。当模型容量小于问题容量时，需要增大模型容量。（引入先验知识，使用更多的数据）
		3. 第一阶段（参数量较少）：支持向量机。（模型容量够不上问题容量，此时提升数据也无法提升模型效能，大家在提升模型的能力=》高斯核等等）
		4. 第二阶段：CNN图卷积出来后（模型能力可以往上升了，数据的作用提升出来了，但仍然出现瓶颈：无法进一步提升参数量，即使将模型容量增加，任务效果也做不上去）
			1. 限制：
				1. CNN的瓶颈是什么？模型大小，长距离依赖=》残差模型
				2. RNN的瓶颈是什么？长距离依赖。=》注意力机制（global、local）
			2. 做法：
				1. 中间任务的兴起（通过引入先验知识来帮助模型理解，通过提升数据，
				2. 来使得模型达到问题容量）引入多任务、划分明显网络结构=》举例
				3. 引入数据先验知识，进行人工嵌入层的划分。
				4. 变更网络结构，加强对数据的理解。
		5. 第三阶段：新的模型架构的出现，模型容量进一步提升。残差结构、注意力机制。最终结合成了Trm结构，所做的目的，就是为了让整个模型有加深的能力。Trm结构。attention、残差、norm的结合。**此时模型容量可以无限上升**。这一阶段就变成了如何去扩充问题容量了。所以针对任务做了更多的细分。
			1. 限制：为了要增大模型
			2. 做法：残差、注意力机制、batchnorm
			3. 影响：
				1. 中间任务的消融。End2End模型的建立。
				2. 越来越大的模型。
				3. 预训练模型的兴起（模型容量已经能涵盖众多问题了）
		6. 第四阶段：问题类型的统一（将生成任务、判别任务统一成了一种任务=》prompt。 T5模型。）做zero shot prompting任务，gpt模型效果更好。chain of thought的效果。
			1. encoder、decoder的区别以及时间线。
			2. 后来的发展方向（关键成果介绍）：
				1. GPT1、GPT2、GPT3的区别联系。
				2. CLIP
				3. InstructGPT
				4. llama
	2. llm定义
	3. LLM未来的发展方向。（大模型成为趋势，如何将大模型应用到各行各业）
3. llama的搭建、实验细节。
4. finetune的基本理论。

几个点：
1. thoght step by step是哪一步提出来的？
2. 




资料：
1. [# 从Word Embedding到Bert模型—自然语言处理中的预训练技术发展史](https://zhuanlan.zhihu.com/p/49271699)
2. [# 乘风破浪的PTM：两年来预训练模型的技术进展](https://zhuanlan.zhihu.com/p/254821426)
3. [由Chatgpt归纳的LLM技术精要](https://mp.weixin.qq.com/s/gR9YsYjFVhViuANWFw59fg)
4. [李沐：gpt时代下的AI怎么做](https://www.bilibili.com/video/BV1fg4y1s7qv/)
5. [李沐：大模型时代下如何做科研](https://www.bilibili.com/video/BV1oX4y1d7X6/)
6. [李沐：gpt发展史](https://www.bilibili.com/video/BV1AF411b7xQ/)
7. [李沐：迁移学习](https://www.bilibili.com/video/BV1bq4y1y7tg/)
8. [gpt1,2,3区别和对比](https://zhuanlan.zhihu.com/p/350017443)
9. [大模型综述](https://mp.weixin.qq.com/s/7HRr55Md2Wl6EHQMGioumw)
10. [chatgpt成长史](https://mp.weixin.qq.com/s/qiNzCQFieIkZFzox8F-FBw)

论文：
读论文时，弄清楚改进。

1. On the Role of Bidirectionality in Language Model Pre-Training。gpt和bert模型的比较。
2. A comprehensive survey on pretrained foundation Models: A history from bert to chatgpt
3. Rethinking the Role of Demonstrations: What Makes In-Context Learning Work? 分析incontext-learning 的有效性。

# TODO
- [x] 弄清楚要看哪些论文 🛫 2023-04-13 ✅ 2023-04-14
- [x] 整体描述框架的搭建 🛫 2023-04-14 ✅ 2023-04-14
- [x] 使用飞书来记录。确定框架。然后确定要读的论文。速速读完。 🛫 2023-04-17 ✅ 2023-04-18
- [ ] 看完Codex、thought by chain、Tamer等论文。前期准备资料已经完成。下面开始行文。
- [ ] 看视频CLIP🛫 2023-04-12 
- [ ] 调研llmam的可行性🛫 2023-04-12 
- [x] 弄清楚GPT1、2、3的区别 🛫 2023-04-13 ✅ 2023-04-14
- [ ] instructgpt模型 🛫 2023-04-13 
- [ ] t5等模型🛫 2023-04-12 