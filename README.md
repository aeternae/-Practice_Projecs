# Practice_Projecs
## Zhixiang Wang

机器学习与数据挖掘个人基础练习项目，在实践中运用并掌握ML算法与框架，打下坚实的基础。<br>

* 数据分析处理过程
![](./pic/process.jpg)<br>

    * 1.数据分析
      * 下载并加载数据
      * 了解每列数据的含义,数据的格式等，观察每个变量特征的意义以及对于问题的重要程度
      * 数据初步分析,通过绘图:初步了解数据之间的相关性,为构造特征工程以及模型建立做准备

    * 2.特征工程
      * 将特征转换为模型可以辨别的类型(如处理缺失值,异常值处理，处理文本进行等)

    * 3.模型选择
      * 根据目标函数确定学习类型,是无监督学习还是监督学习,是分类问题还是回归问题等选择合适的模型
      * 比较各个模型的分数,取效果较好的模型作为基础模型

    * 4.集成学习——模型融合
      * 训练多个模型，然后按照一定的方法集成多个模型，应为它容易理解、实现也简单，同时效果也很好
      * 包括bagging，Boosting两种思想的方法

    * 5.修改特征和模型参数
      * 可以通过添加或者修改特征,提高模型的上限
      * 通过修改模型的参数,使模型逼近上限


#### Titanic生存预测
Kaggle基础项目，数据特征包含乘客的信息特征，如姓名、年龄、性别、票价等，与是否获救的label（二分类，1 or 0），运用Python和机器学习的相关模型来预测哪些乘客幸免于难。

#### 20Newsgroups
20newsgroups数据集是用于文本分类、文本挖据和信息检索研究的国际标准数据集之一。数据集收集了大约20,000左右的新闻组文档，均匀分为20个不同主题的新闻组集合。
