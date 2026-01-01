# Pytorch版本 0.4 
```c
#includec<stdio.h>
int main(){
}
```

## 要求
1.    什么是深度学习框架
2.    学会看文档

## 课程目标
* 如何用pytorch实现一个学习系统
* 理解神经网络和深度学习的目标

## requirements
* Linear Algebra(线性代数) + Probability(概率论与数理统计)
    * 了解随机变量，分布之间的关系
* Python
    * 了解面向对象，class，
    * 了解magic methods(魔法方法)

## 什么是人类智能
Q: 中午吃什么？
快速决策
根据外部有的信息进行推理，
有外部信息输入
你的经济 + 你的偏好 -> 你吃什么

Q: 今天穿什么
information -> infer(推断)

这些都是有 input -> 推理


**预测**
照片 -> 抽象概念
Image -> Prediction

什么是Machine Learning
推理的大脑 -> 用算法来实现推断  => 人工智能
用算法替代人脑来处理

基本使用的都是监督学习
有Label的数据，监督学习

ML中的算法和平常的算法课有什么区别
* 算法课： 人工设计的一种思想
* 机器学习(ML)中： 来源于数据训练
    * 基于统计的方法


### 算法思想
1. 穷举
2. 贪心 (ML梯度下降)
3. 分治 (快排)
4. 动态规划

机器学习中，算法不是人为设计出来的，而是从一个数据集，从数据集中，把想要的算法找出来
怎么从data中提取出算法
有数据集 -> 提一个模型 -> 拿数据去做训练 -> 好用的话就直接部署



> AI > Machine Learning > Deep learning

## Rule-based system
input ->  **Hand-designed program** -> Output
手动地设计程序来得到输出
## classic machine learning
input ->  Hand-designed features -> **Mapping from features** -> Output
## 表示学习中(Present Learning)
input ->  Features -> **Mapping from features** -> Output
features也可以学习提取
## Deep Learning
input ->  Simple Features -> Additional layers of more abstract features -> **Mapping from features** -> Output
End-to-End 端到端的训练过程

## 维度诅咒
维度(特征)越多，对数据要求越多，采样越多，满足大数定律，满足原始数据的分布

所以有降维需求

Manifold, 流刑


> What is magic methods 
>    * 定义 
>        * 是 Python 中一组内置的、以双下划线开头和双下划线结尾（格式：__xxx__）的特殊方法，也被称为「dunder methods」

![Sklearn学习路线图](assets\imgs\SkLearn_path.png "Sklearn学习路线图")

<img src="assets\imgs\SkLearn_path.png" alt="Sklearn学习路线图" title="网站logo" width="200" height="auto" align="center">


![](assets\imgs\SVM_challenge.png "SVM挑战")


## 神经网络
* 来源介绍
    * 神经科学 -> 数学和工程学

![](assets\imgs\Neural_networks.png "分层神经网络")

* back propagation 反向传播
    * 核心：计算图

![](assets\imgs\back_propagation.png)

