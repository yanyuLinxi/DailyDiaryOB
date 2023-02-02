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

## 大纲内容
1. 总介绍。
	1. huggingface库的介绍
	2. huggingface网站介绍
2. Bert类模型基础介绍。
	1. [预训练模型的发家史](https://huggingface.co/course/zh-CN/chapter1/4?fw=pt)
	2. 相应的会有编码器模型、解码器模型、翻译模型
3. 代码模板介绍。
	1. 数据输入的标准模板。
		1. 使用Dataset类
		2. 使用pytorch类
	2. 模型构造的模板
		1. 模型更改的模板（使用pytorch更改）
	3. 优化器设置。
	4. 模型微调的模板
		1. 使用trainer
		2. 使用pytorch修改模型并微调
	5. 模型评估
		1. 使用evaluate评估
		2. 使用pytorch进行评估
	6. 模型复用。重新读取模型的方法。
	7. 完整的训练过程。
		1.  一切都尽量使用huggingface的。然后模型修改使用pytorch的。
4. pipeline
	1. pipeline的基础用法汇总
		1. [指定任务。然后输出](https://huggingface.co/course/zh-CN/chapter1/3?fw=pt#:~:text=%E4%BD%BF%E6%88%91%E4%BB%AC%E8%83%BD%E5%A4%9F-,%E9%80%9A%E8%BF%87%E7%9B%B4%E6%8E%A5%E8%BE%93%E5%85%A5%E4%BB%BB%E4%BD%95%E6%96%87%E6%9C%AC%E5%B9%B6%E8%8E%B7%E5%BE%97%E6%9C%80%E7%BB%88%E7%9A%84%E7%AD%94%E6%A1%88%EF%BC%9A,-Copied)
		2. 传入model, tokenizer
	2. pipeline基本构成
	3. [pipeline一共包含哪些任务](https://huggingface.co/docs/transformers/main_classes/pipelines#transformers.pipeline.task)
	4. 如何根据相关任务寻找可用的参数。寻找__call__函数，其输入参数即是对应参数。
5. 模型Model
	1. 模型加载方式：[从头训练(Config类）](https://huggingface.co/course/zh-CN/chapter2/3?fw=pt#:~:text=%E4%BB%8E%E9%BB%98%E8%AE%A4%E9%85%8D%E7%BD%AE%E5%88%9B%E5%BB%BA%E6%A8%A1%E5%9E%8B%E4%BC%9A%E4%BD%BF%E7%94%A8%E9%9A%8F%E6%9C%BA%E5%80%BC%E5%AF%B9%E5%85%B6%E8%BF%9B%E8%A1%8C%E5%88%9D%E5%A7%8B%E5%8C%96%EF%BC%9A)，[加载预训练模型(from_pretrained)](<https://huggingface.co/course/zh-CN/chapter2/3?fw=pt#:~:text=%E6%88%91%E4%BB%AC%E5%8F%AF%E4%BB%A5%E4%BD%BF%E7%94%A8-,from_pretrained(),-%E6%96%B9%E6%B3%95%EF%BC%9A>)
	2. 模型下载方式。可以手动下载。
6. Tokenizer
	1. Tokenizer做了什么事情
		1. [将文本翻译成数字](<https://huggingface.co/course/zh-CN/chapter2/4?fw=pt#:~:text=%E6%96%87%E6%9C%AC%E7%BF%BB%E8%AF%91%E6%88%90%E6%95%B0%E5%AD%97%E8%A2%AB%E7%A7%B0%E4%B8%BA%E7%BC%96%E7%A0%81(encoding).%E7%BC%96%E7%A0%81%E5%88%86%E4%B8%A4%E6%AD%A5%E5%AE%8C%E6%88%90>)
			1. 拆分为单词（以及相关API）
			2. 转为数字（以及相关API）
		2. 处理文本。如padding、truncation、然后添加[注意力遮罩层](https://huggingface.co/course/zh-CN/chapter2/5?fw=pt#:~:text=%E6%9D%A5%E5%AE%9E%E7%8E%B0%E7%9A%84%E3%80%82-,%E6%B3%A8%E6%84%8F%E5%8A%9B%E9%9D%A2%E5%85%B7,-Attention%20masks%E6%98%AF)。
		3. 注意：使用tokenizer(seq)是会自动添加标记的。使用tokenizer.tokenize(seq)是分词。不会添加标记。
	2. Tokenizer的基础代码
	3. 分词器种类：
		1. [子词化分词](<https://huggingface.co/course/zh-CN/chapter2/4?fw=pt#:~:text=subword%20tokenization%E3%80%82-,%E5%AD%90%E8%AF%8D%E6%A0%87%E8%AE%B0%E5%8C%96,-%E5%AD%90%E8%AF%8D%E5%88%86%E8%AF%8D>)
		2. [字符分词](https://huggingface.co/course/zh-CN/chapter2/4?fw=pt#characterbased)
		3. wordpiece
	4. 关键API
		1. tokenizer.tokenize(words) token切片
		2. [~.convert_tokens_to_ids()](https://huggingface.co/course/zh-CN/chapter2/4?fw=pt#token-id) 转为数字
		3. ~.convert_ids_to_tokens 转回文字。
		4. ~.decode() 转为string
7. dataset类
	1. 简单介绍，用于快速导入数据。
		1. 关键：如何组装。如何遍历，如何预处理。如何查看数据。
	2. 关键API介绍
		1. load_dataset
		2. map(tokenize_function, batched=True) 这个结果是缓存的。batched是会分批操作，是加速的关键。num_proc指定进程数量。
		3. [DataCollatorWithPadding](https://huggingface.co/course/zh-CN/chapter3/2?fw=pt#:~:text=transformer%E5%BA%93%E9%80%9A%E8%BF%87-,DataCollatorWithPadding,-%E4%B8%BA%E6%88%91%E4%BB%AC%E6%8F%90%E4%BE%9B) 这个返回一个数据收集器。和tokenizer一样的用法，对字词进行切分。
		4. Dataset.shuffle() 打乱数据集
		5. Dataset.select() 抽取数据。
		6. Dataset.filter()函数。
		7. [train_test_split函数](<https://huggingface.co/course/zh-CN/chapter5/3?fw=pt#:~:text=drug_dataset.reset_format()-,%E5%88%9B%E5%BB%BA%E9%AA%8C%E8%AF%81%E9%9B%86,-%E5%B0%BD%E7%AE%A1%E6%88%91%E4%BB%AC%E6%9C%89>)
		8. save_to_disk
8. Trainer API
	1. Training Arguments示例代码
		1. trainer.train()
		2. trainer.predict()
	2. 相关参数的介绍。
9. evaluate API
	1. compute metrics 函数和用法
10. Accelerate 库。
	1. 简单介绍和基础用法。
		1. 单机多gpu。多机器等。
11. 其他
	1. 设置种子


## TODO
- [ ] 寻找一个 huggingface 完整模板。加载数据、分词、然后 trainer 训练、pytorch 训练模板。
- [ ] 能否使用trainer和accelerate库？