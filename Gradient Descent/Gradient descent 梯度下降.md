# Gradient descent 梯度下降

**梯度下降法是不断去更新参数x以找到解的方法**

一維度的純量**x**的梯度就是算**f(x)**對**x**的微分(就是只有一个x

多維度的向量**x**的梯度就是算**f(x)**對**x**所有元素的偏微分 (有x1,x2...xn

<img src=".\img\2.jpg" style="zoom:50%;" />

​	所以要先隨機產生一組初始參數的「解」，然後根據這組隨機產生的「解」開始算此「解」的梯度方向大小，然後將這個「解」去減去梯度方向大小，得到的「解」就是下一轮迭代的初始「解」

![](.\img\1.jpg)

-  t是第幾次更新參數 (迭代次数

-  γ是學習率(Learning rate)  

  ​									其实就是会变成<img src=".\img\3.jpg" style="zoom: 67%;" />

### 一些关于gradient descent的tip

- #### 调learning rate

  **Adagrad**

  根据update的gradient值来update learning rate

  

  <img src=".\img\4.jpg" style="zoom:80%;" />

  -  𝜎 𝑡 : root mean square of the previous derivatives of parameter w 

    过去所有参数update的结果的均方根

- ###  Stochastic Gradient Descent 

- ###   Feature Scaling 

   Make different features have the same scaling 