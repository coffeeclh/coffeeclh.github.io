---
layout: post
title:  "Can a Conversation Paint a Picture? Mining Requirements in Software Forums""An in-depth study of the promises and perils of mining GitHub"
date:   2019-12-22 21:25:45 +1300
categories: paper reading
---

##### Can a Conversation Paint a Picture? Mining Requirements in Software Forums

Part I: Introduction

存在问题：手动分析难以从大量的文本中提取出新的需求（requirements）

已有研究：已有研究大多是针对App Store和Twitter上的评论来获取产品开发新需求的

本文特点：本文致力于从Software Forums的数据入手进行研究分析

数据：分析两个软件产品的论坛，the VLC media player 和 Firefox browser



本文的三大贡献：

（1）描述了软件产品论坛中包含的信息，对论坛中的文本做了跟细粒度的分类

（2）应用了之前用于分析App Store数据的工具，ARdoc，发现其在分析论坛数据上的不足性

（3）提取了针对论坛的新特征，然后用机器学习的方法构建分类器，发现比App Store tool效果好（特征工程+机器学习）



Part III: Research Setting

从5个方面对两个产品进行介绍：product,people,organisation,market以及process

数据收集，包括the title, the author(s), the content, the post date, the number of views and the URL



##### An in-depth study of the promises and perils of mining GitHub

github数据挖掘存在的一些挑战：（1）大量项目是私有的或者不活跃；（2）almost 40 % of all pull requests do not appear as merged even though they were;（3）近一半的github注册用户没有公开活动（public activity）

本文针对软件工程研究者提出了一些挖掘github数据的建议

