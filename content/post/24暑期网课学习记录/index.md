---
title: 24暑期网课学习记录
description:  记录一下24暑期上过的网课
slug: 网课学习记录
date: 2024-08-24 00:00:00+0000
categories:
    - Study
tags:
    - 学习
    - 网课
---

~~大二暑假是弯道超车的好时候~~

我不是一个太能闲的住的人，所以总想着给自己找点事情做。所以就会想着，为什么不学一点自己喜欢的东西的呢？这些东西可能对我以后的学习和生活没有太多帮助，或者说不需要如此系统性的学习，但是学这些东西这件事本身就给我带来了很多乐趣，于我而言，那就足够了。

去年学了很多C++相关的知识，今年本想强化一下的，奈何没有找到合适的课程。今年的重点是数据与机器学习，其实很多是我在平时学习时随手点开的课程，觉得很有趣，但是没有在课余时间学完，最后都囤到了暑假。

自学是磨人的，你没有ddl和GPA的压力，所以学的会很随性，学的会很浮躁。所以我在学完一遍后都会再过一遍，找一些补充资料。

我坚信三分钟热度有三分钟收获。哪怕你只是知道这件事是什么，也是足够的。你所要做的，只是找到合适自己的自学办法，然后认真学习并坚持下去。

感谢csdiy，让我知道有这么多有趣的课程。感谢设计这些课程并将其开源的老师、学校以及各种学习者，让我有机会接触世界上各种精彩的课程。我不批判本科所学的课程，在其中我还是学到很多东西，但我知道与这些课程相比，我们仍有一段路要走。

愿我们在学习路上有所收获，所念皆得。


## UCS CS70 discrete Math and probability theory
课程网址：[CS70](http://www.eecs70.org/)

伯克利的离散数学入门课程。内容包括逻辑证明，基础数论，图论，多项式，概率论和随机过程（主要是马克洛夫链）。课程内容丰富且生动形象，对于一门入门课而言深度和广度都是足够的。

> 具体的理论与算法的对应关系列举如下：
> 
> - 逻辑证明：稳定匹配算法
> - 图论：网络拓扑设计
> - 基础数论：RSA 算法
> - 多项式环：纠错码设计
> - 概率论：哈希表设计、负载均衡等等
> 
> (源自csdiy的介绍)

课程的Notes写的非常棒，第一次感受到读数学相关的资料是一件很快乐的事情，比大多教科书写的好多了，感觉自学把notes看懂就行，里面的公式建议自己推导一下（尤其是数论和图论那一部分）。

每周有对应的Homework和Discussion，隔一两周会公布答案，作业偏难但是一定要好好做作业！



## MIT 18.S191 Computational Thinking
课程网址：[Computational Thinking](https://computationalthinking.mit.edu/)

一门由Alan Edelman, David P. Sanders 和 Charles E. Leiserson三位教授开设的计算思维入门课，内容涵盖了图像处理、社会科学与数据科学、气候学建模三个主题。在这三个主题的带领下来指引学生理解算法、数据解算法、数学建模、数据分析、交互设计、图例展示，让学生体验计算与科学的美妙结合，很适合作为一门数值分析或者数据分析处理的入门课。

~~可以看到Alan教授家超级可爱的狗~~

![](image.png)

Lectures的Notes非常棒，是由Julia的Pluto库生成的交互式文本（类似于Jupyter Notebook），不仅外观赏心悦目，而且内容丰富有趣，Alan教授一直希望我们能够"play fun with it"。课程作业也是在Pluto里完成的，作业内容类似于Lab，基本上是按照课内所学知识完成的，后面会有一个传染病模型的建模，很有趣。

lectures的videos也附在课程网址里，前两个topics的视频可以在B站上找到，后一个topic的视频可能要到油管上看，videos一般是教授讲解并操作notes，我后面基本上只看notes没有看videos了.

课程使用的语言是[Julia](https://julialang.org/)，是由MIT研发的一款科学计算编程软件，按照MIT的说法是希望到达Python一样好写，C语言一样快的效果。个人感觉语法和MATLAB类似，运行速度虽然快但是需要长时间的预编译。

## MIT 18.065 Matrix Methods in Data Analysis, Signal Processing, and Machine Learning

课程网址：[Matrix Methods in Data Analysis, Signal Processing, and Machine Learning](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/)

![](18.065.jpg)

由Gilbert Strang教授主讲的线性代数的内容，算是18.06的拓展，偏在机器学习方面的应用。课程内容从线性代数出发，涵盖概率论和数理统计、优化方法和深度学习，内容很丰富，教授讲述的时候主要用板书，会举例子辅助讲解。但是内容太多，很多东西都是以介绍为主，需要课后查一下资料补充相关知识。

有一本教材，内容会比课程上多，但是知识点更加细致。但是和这门课一样，很多内容只是以介绍为主没有太多拓展。所以个人认为不一定需要。

~~个人很多没听懂~~

如果有志于机器学习或者想在线性代数的应用有更多了解的话可以尝试听这门课。

感谢Gilbert Strang拯救我的线性代数于水生火热之中。在此祝Gilbert Strang退休快乐，顺心顺意。

## UCB Data100

课程网址：[Data100](https://ds100.org/)

UCB数据科学课程，内容包括数据处理、数据可视化、特征处理、传统机器学习方法等。也会讲授Pandas, Numpy, Matplotlib 等数据科学常用工具包。如果你对数据科学感兴趣的话，真心推荐这门课程！

课程有video但都是讲解PPT的内容，PPT做的很好，我是直接看PPT自学的！

![Data Science Lifecycle](<pasted image 0.png>)

这门课是用python语言，lab和homework都是在Jupyter Notebook上实现的，但是网站上lab和homework都需要UCB的学生账号，github上有人备份了[作业代码](https://github.com/DS-100)。同时，为了实现作业内置的评分系统，你需要安装otter包和在每份lab/hw的test文件夹里面评分代码的前面加上`OK_FORMAT = True`（每份都要）。

lab和homework质量非常高！

