# Regression

### 线性回归可以用于 :

- 股票市场预测

  ![](.\img\1.jpg)

- 自动驾驶方向盘角度

  ![](.\img\2.jpg)

- 推荐系统

  ![](.\img\3.jpg)

**我理解为 就是输入一些特征 会得到一个output这样 这个output就是可以是股票预测的结果/购买可能性等等**

### Linear model

![](.\img\4.jpg)

线性模型长这样

### Loss function(how bad it is -> error 越小越好)

![](.\img\6.jpg)

**怎么找到loss function的最优解?**

用 Gradient descent法

### Gradient descent

这里要有几个概念

1. 步长(learning rate)
2. 损失函数(loss function)
3. 预测函数(线性回归函数)

做法

1. 随机选取一个起始点w0
2. 在w0点对它进行求导 求导后乘learning rate 表示这一步梯度下降步长有多大
3. 多次迭代

![](.\img\7.jpg)

![8](.\img\8.jpg)

### 用线性回归做预测的过程

1. step1: 选择linear model 就是上面那个式子 

2. step2: 找到最好的function![image-20200729114148709](.\img\5)

3. 梯度下降

   使用梯度下降法 找出最佳参数 (error最低的参数

### Overfitting 

### Regularization

