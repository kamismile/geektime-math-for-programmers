## 概率和统计：编程为什么需要概率和统计

### 概率和统计里有哪些需要掌握的概念
- 概率（Probability）就是描述这种可能性的一个数值
- 随机变量（Random Variable）来描述事件所有可能出现的状态
  - 连续型随机变量（Continuous Random Variable）
  - 离散型随机变量（Discrete Random Variable）
- 概率分布（Probability Distribution）来描述每个状态出现的可能性
- 边缘概率（Marginal Probability）

对于多个随机变量，还有一个很重要的概念是条件概率，其实概率论研究的就是这些概率之间相互转化的关系，比如联合概率、条件概率和边缘概率。
通过这些关系，概率论中产生了著名的贝叶斯定理（Bayes’ theorem）。加上变量的独立性，我们就可以构建朴素贝叶斯（Naive Bayes）分类算法

基于概率发展而来的信息论，提出了很多重要的概率，例如信息熵（Entropy）/ 香农熵（Shannon Entropy）、信息增益（Information Gain）、基尼指数（Gini）等。这些概念都被运用到了决策树（Decision Tree）的算法中

概率和统计其实是互逆的：概率论是对数据产生的过程进行建模，然后研究某种模型所产生的数据有什么特性。而统计学正好相反，它需要通过已知的数据，来推导产生这些数据的模型是怎样的。因此统计特别关注数据的各种分布、统计值及其对应的统计意义

### 小结
概率中的概念看起来很多，但是，其实最重要就是你耳熟能详的这几个：随机变量、概率分布、联合概率、条件概率和边缘概率。通过这些概念之间的相互推导，我们可以得到贝叶斯定理，这是朴素贝叶斯等系列算法的核心。
而在概率基础之上发展而来的信息论，定义了信息熵、信息增益和基尼指数等，构成了决策树等系列算法的核心。

- 概率可以帮助我们进行更精准的复杂度分析
- 概率统计更多的是用在机器学习和大数据分析中
- 概率统计还可以用在各种机器学习的算法中