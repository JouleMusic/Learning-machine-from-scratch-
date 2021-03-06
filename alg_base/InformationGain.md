

## 信息增益（Information Gain）

信息增益是按某属性分裂前的熵与按该属性分裂后的熵的差值。

### 公式

```

gain()=infobeforeSplit()–infoafterSplit()

```
![公式](http://latex.codecogs.com/gif.latex?infoGain%5Cleft&space;(&space;S,&space;A&space;%5Cright&space;)=Entropy%5Cleft&space;(&space;S&space;%5Cright&space;)-%5Csum&space;_%7BV%5Cin&space;Value%5Cleft&space;(&space;A&space;%5Cright&space;)%7D%5Cfrac%7B%5Cleft&space;%7C&space;S_V&space;%5Cright&space;%7C%7D%7B%5Cleft&space;%7C&space;S&space;%5Cright&space;%7C%7DEntropy%5Cleft&space;(&space;S_V&space;%5Cright&space;))

信息增益选择方法有一个很大的缺陷，它总是会倾向于选择属性值多的属性，如果训练集中加一个姓名属性，假设14条记录中的每个人姓名不同，那么信息增益就会选择姓名作为最佳属性，因为按姓名分裂后，每个组只包含一条记录，而每个记录只属于一类（要么购买电脑要么不购买），因此纯度最高，以姓名作为测试分裂的结点下面有14个分支。但是这样的分类没有意义，它没有任何泛化能力。增益比率对此进行了改进，它引入一个分裂信息：


