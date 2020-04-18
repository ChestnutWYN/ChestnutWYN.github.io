---
layout:     post
title:      BERT for Joint Intent Classification and Slot Filling
subtitle:    论文笔记
date:       2020-04-18
author:     Chestnut
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - NLU
    - joint Model
---

## Note
作者：Qian Chen(Speech Lab, DAMO Academy, Alibaba Group)
论文：《BERT for Joint Intent Classification and Slot Filling》
来源：arXiv:1902.10909（2019-2-28）
[ kami 笔记](https://web.kamihq.com/web/viewer.html?source=filepicker&document_identifier=5c8ff627-57c0-4f45-b512-1832874cdaad&filename=BERT%20for%20Joint%20Intent%20Classification%20and%20Slot%20Filling.pdf)

## Introduce

针对NLU泛化能力差的问题，作者在BERT上将 Intent classification 和 Slot Filling 联合学习（利用BERT的hidden state），进行fine-tuning。

## Joint Intent Classification and Slot Filling

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200418194043305.png)
<p id = "build"></p>
---

## Experiments

Data Sets: ATIS, Snips
指标：Intent classification accuracy, slot filling F1, and sentence-level semantic frame accuracy
对比试验：

![对比试验](https://img-blog.csdnimg.cn/20200418192205926.png)

![探讨Joint和Epoches的影响](https://img-blog.csdnimg.cn/20200418192237740.png)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200418194856679.png)

---


## Others

[一篇很好的论文笔记](https://www.jianshu.com/p/2144cb5b222f?utm_campaign=haruki)



