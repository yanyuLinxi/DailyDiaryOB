---
title: HuggingFace基础教程(一)
date: 2023-01-18
tags : [
	"HuggingFace基础教程",
]
categories : [
	"教程",
]
series : []
aliases : []
draft: false
toc: true
---

# 大纲
如何写这个教程？
自己先学一遍，然后教程的目的：
1. 总结一个基础模板
2. 对tokenizer、trainer、accelerate等有详细的介绍和模板

学习路径：
1. 学习官方教程
2. 学习官方example库。

## 内容
1. pipeline
	1. [pipeline一共包含哪些任务](https://huggingface.co/docs/transformers/main_classes/pipelines#transformers.pipeline.task)
	2. pipeline的基础用法汇总
	3. 如何根据相关任务寻找可用的参数。寻找__call__函数，其输入参数即是对应参数。
2. Bert类模型基础介绍。
	1. [预训练模型的发家史](https://huggingface.co/course/zh-CN/chapter1/4?fw=pt)
	2. 相应的会有编码器模型、解码器模型、翻译模型
3. 