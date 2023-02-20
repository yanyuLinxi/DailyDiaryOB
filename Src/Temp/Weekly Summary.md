---
title: {{title}}
date: {{date:gggg-MM-W}}
tags : [
	"周报",
	"{{date:gggg-MM}}"
]
categories : [
	"{{date:gggg}}年周报"
]
series : []
aliases : []
draft: false
toc: true
---
# 上周完成任务
```tasks
done
has done date
sort by done desc
(done before <% tp.date.now("yyyy-MM-DD", -1, tp.file.title, "gggg年MM月DD-第W周") %>) AND (done after <% tp.date.now("yyyy-MM-DD", -9, tp.file.title, "gggg年MM月DD-第W周")%>)
```

# 上周未完成任务
```tasks
not done
has start date
sort by start desc
(starts before  <% tp.date.now("yyyy-MM-DD", -1, tp.file.title, "gggg年MM月DD-第W周") %>)   AND (starts after <% tp.date.now("yyyy-MM-DD", -9, tp.file.title, "gggg年MM月DD-第W周") %>) 

```


# 本周任务计划

## 三两句话点名核心 ：

## 当周核心TODO:

## 当周其他TODO：



## <% tp.date.now("M月DD日 dddd", -1, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：

## <% tp.date.now("M月DD日 dddd", 0, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：

## <% tp.date.now("M月DD日 dddd", 1, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：

## <% tp.date.now("M月DD日 dddd", 2, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：

## <% tp.date.now("M月DD日 dddd", 3, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：

## <% tp.date.now("M月DD日 dddd", 4, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：

## <% tp.date.now("M月DD日 dddd", 5, tp.file.title, "gggg年MM月DD-第W周") %>  
早上：

中午：

晚上：




