# 23 文本分类：如何区分特定类型的新闻？

- 采集训练样本
- 预处理自然语言,让计算机能够理解文本
- 训练模型就是算法通过训练数据进行模型拟合的过程。对于朴素贝叶斯方法而言，训练的过程就是要获取每个分类的先验概率、每个属性的先验概率以及给定某个分类时，出现某个属性的条件概率。
- 实时分类预测，对于朴素贝叶斯方法而言，分类预测的过程就是根据训练阶段所获得的先验概率和条件概率，来预估给定一系列属性的情况下属于某个分类的后验概率。

### 基于自然语言的预处理 / 找关键词
-  分词 1.基于字符串匹配。 2. 基于统计和机器学习。
- 取词干和归一化，讲一次相近的词统一化  am，is，are，was，were全部转换为be。。。
- 停用词，无论何种语言，都会存在一些不影响（或基本不影响）相关性的词。有的时候干脆可以指定一个叫停用词（stop word）的字典，直接将这些词过滤，不予以考虑。
- 同义词和扩展词， 

##### 最后运用朴素贝叶斯模型讲这些条件带入进行计算分类
##### 思考题 能否计算一下“美国电影”属于政治、军事、财经、体育和娱乐分类的概率，分别是多少？
    P(政治|美国电影)
    = P(政治|美国) · P(政治|电影)
    = [ P(美国|政治) · P(政治) / P(美国) ] · [ P(电影|政治) · P(政治) / P(电影) ]




