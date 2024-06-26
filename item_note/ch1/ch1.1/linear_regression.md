# 线性回归（linear regression）

## 什么是线性回归

### 什么是回归
回归：探究自变量和因变量的关系
回归用于预测就是通过历史数据（训练数据）来找到“套路”，然后根据套路来预测未知

### 线性回归
探究因变量和自变量的线性关系

$$
f(x) = \kappa x + b
$$

训练数据(x0,y0),(x1,y1),(x2,y2)……(xn,yn)
使用这些训练数据来训练参数，即k和b，训练完成k和b变成常数
在预测中，已知一个x，代入公式就能求得y

## 怎么训练
训练数据量往往比较大，所以大概率这些数据不能用一条直线完美的拟合
那我们就要尽可能的让更多的点或者更靠近这些个点
**那么怎么来量化呢？**
量化就要使用数学公式来体现，更多的点不太好体现，那么更靠近这些点可以实现
定义损失：$ loss = \sum(f(x)-y)^2 $

