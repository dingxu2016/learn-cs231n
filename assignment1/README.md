Details about this assignment can be found [on the course webpage](http://cs231n.github.io/), under Assignment #1 of Spring 2017.

## 一些代码注释
### knn

- ``` python
 from __future__ import print_function  
```
    - python3为了兼容python2的而导入，比如这个print函数的用法

- ```python
 np.flatnonzero( y_train == y) 
```
    - 该函数的作用对象是一个数组， 其返回该数组不为0的元素的**下标**（即索引index）
    - (y_train == y) 返回了一个 0和1组成的数组， 0表示label不是y对应的，1表示是对应的
    
- ```python
np.random.choice(a,size=None,replace=True,p=None)
```
    - 主要说明还是见numpy官方吧，这里主要说一下replace的意思，replace=True表示a中的元素可以被重复选取，replace=False表示不能重复选取
    
- ```python
 plt.subplot(raw, column, index, **kwargs)
 ```
     - 当然主要还是官方说明，这里简要说明：参数依次是子图的行，列，小图块的索引。 空间被划分成 **行*列** 个子图，index按**行major**来排序
     

