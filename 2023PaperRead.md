# 2023PaperRead
## 人工智能本构计算
### 1. Learning composite constitutive laws via coupling Abaqus and deep neural network
#### 摘要
这篇论文的创新点在于将商业有限元代码Abaqus与深度神经网络模型相结合，形成了Abaqus-DNN力学系统，用于学习复合材料的本构定律。该系统允许数据在Abaqus和DNN模型之间进行通信，从而使DNN能够以无形式的方式学习本构定律。此外，所学结果自动满足平衡和运动方程，确保所学本构定律的准确性。这种方法可以利用Abaqus的多功能有限元分析能力和DNN强大的机器学习能力，从而提高了复合材料本构定律的准确性和效率。
#### 论文创新点及实现方法
![alt 属性文本](/img/2021Learning_Fig3.png "算法流程图")