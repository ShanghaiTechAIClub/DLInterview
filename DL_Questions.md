

## 1. CNN
### CNN为什么可以在CV/NLP/Speech等领域都可以使用？
* 输入数据的局部相关性
* 权值共享是因为输入数据的局部特征具有平移不变性，即在不同位置具有共性的局部特征。
* 权值共享能够降低参数量，而且降低了网络的训练难度。
-----------
### 什么样的数据适合Deep learning?
* 数据要有局部相关性，像表格类数据就不适合

+ ### CNN卷积
    - #### 卷积的时间复杂度

+ ### BP
    * #### 梯度消失,爆炸的原因

    * #### 梯度消失

    * #### 为什么梯度相反的方向是函数下降最快的方向？
        https://math.oregonstate.edu/home/programs/undergrad/CalculusQuestStudyGuides/vcalc/grad/grad.html
    
## 过拟合
### 何为共线性，跟过拟合有啥关联
多变量线性回归中，变量之间由于存在高度相关关系而使回归估计不准确。

共线性会造成冗余，导致过拟合。

解决方法：排除变量的相关性／加入权重正则。

### Overfitting如何解决
* Data augmentation
* regularization such as dropout, BN, weight decay
* ensembling


+ ### Loss
#### 交叉熵和相对熵（KL散度）？
#### L1,L2 regularization的原理




### 为什么神经网络的损失函数是非凸的