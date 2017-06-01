# js-detail-onclick
详解element.onclick是个什么数据类型，如何准确赋值

测试不同的赋值方式，即返回值接收，分析数据类型对其影响。看起来不起眼的问题，在做案子的时候踩过很多坑。这里详细总结一下，避免以后不再踩到类似的坑。
总的来说：
1 element.onclick是个object数据类型，且不可更改数据类型无效，不可更改；
2 element.onclick=function(){} 可以看作一个赋值表达式。

详细的分析见代码
