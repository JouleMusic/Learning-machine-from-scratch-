# 正则化

正则化是一系列的方法：


## 正则化的目的是：
* 控制参数幅度，不让模型无法无天
* 限制参数搜索空间；

## 举例说明
线性回归来举例说明：
loss function:

![](https://github.com/bobkentt/Learning-machine-from-scratch-pic/blob/master/alg_base/pic/20170521165348.png)

加入正则化：
![](https://github.com/bobkentt/Learning-machine-from-scratch-pic/blob/master/alg_base/pic/20170521-212109.png)

通常情况下，我们加入的正则化有两种：
* L1正则化：θ平方
* L1正则化：θ局对峙
