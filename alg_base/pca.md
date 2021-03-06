# 主成分分析

## 基本概念
主成分分析（Principal Component Analysis，PCA）， 是一种统计方法。通过正交变换将一组可能存在相关性的变量转换为一组线性不相关的变量，转换后的这组变量叫主成分。

在实际课题中，为了全面分析问题，往往提出很多与此有关的变量（或因素），因为每个变量都在不同程度上反映这个课题的某些信息。

主成分分析首先是由K.皮尔森（Karl Pearson）对非随机变量引入的，尔后H.霍特林将此方法推广到随机向量的情形。信息的大小通常用离差平方和或方差来衡量。

> [来源于百度百科](https://baike.baidu.com/item/%E4%B8%BB%E6%88%90%E5%88%86%E5%88%86%E6%9E%90/829840?fr=aladdin)

## 基本原理
主成份分析是最经典的基于线性分类的分类系统。这个分类系统的最大特点就是利用线性拟合的思路把分布在多个维度的高维数据投射到几个轴上。如果每个样本只有两个数据变量，这种拟合就是 其中和分别是样本的两个变量，而和则被称为loading,计算出的P值就被称为主成份。实际上，当一个样本只有两个变量的时候，主成份分析本质上就是做一个线性回归。公式本质上就是一条直线。

![](http://images2015.cnblogs.com/blog/1036042/201610/1036042-20161016092028608-179450736.png)

> [转自博文](http://www.cnblogs.com/SCUJIN/p/5965946.html)

# pca原理

> [参考博文](http://blog.jobbole.com/109015/)

