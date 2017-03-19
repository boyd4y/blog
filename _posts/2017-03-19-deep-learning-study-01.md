---
layout: post
title:  "Deep Learning Study 01"
date:   2017-03-19 22:36:47 +0800
categories: blog
---

![神经网络的抽象过程]({{ site.url }}/{{ site.baseurl }}/assets/dl_002.jpeg){:class="img-responsive"}

深度学习(DL)源于人工神经网络的研究，自下而上通过组合低层特征形成更加抽象的高层特征. 

传统神经网络采用BP算法，随机设定初始值，不断向label收敛。BP算法存在的问题如下：
* 梯度稀疏
* 依赖label

DL的训练过程（Wake-Sleep）是在非监督数据集上建立多层神经网络，主要分为两步：
* 逐层构建单层神经元
* Wake-Sleep调优

参考文档：
* http://www.leiphone.com/news/201608/7lwVZCXnScbQb6cJ.html
