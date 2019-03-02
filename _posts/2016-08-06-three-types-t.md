---

layout: post
title: 关于推论统计的三种t统计量
date: 2016-08-06
categories: blog
tags: [统计学,t统计]
---

# 关于推论统计的三种t统计量

**t统计量**用来对未知总体的均值和均值差异做推论。在日常的数据中，关于数据总体的许多信息都是未知的。当使用t统计量时，首先面临的问题就是选用哪种方法。

t统计量的三种方法：
1. 单样本t检验
2. 独立测量的t检验
3. 重复测量的t检验


 ![三种t统计量-001](http://o9m8cmsd5.bkt.clouddn.com/%E4%B8%89%E7%A7%8Dt%E7%BB%9F%E8%AE%A1%E9%87%8F-001.jpg)





如图所示，在单样本t检验和重复测量t检验中，都只有一组数据。不同的是，后者会进行两种不同的处理。得到两次的**差异值**，计算差值的平均数和方差。检验用样本差异值的均值和方差，检验关于总体均值差异的假设。而单样本则是用**唯一**的样本均值和样本方差，检验未总体均值的假设。在独立测量t检验中则有两组分数，因此则有两个均值和方差。通过计算**合并方差**，通过t检验用两个样本均值的差异检验两个总体均值差异的假设。



![pic](http://o9m8cmsd5.bkt.clouddn.com/2016-07-26-poem.jpg)
