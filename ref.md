


```
个性化推荐系统一般由日志系统、推荐算法、内容展示UI三部分组成。

日志系统：这是推荐系统的输入源，是一个推荐系统所有信息的源头。
推荐算法：这是推荐系统的核心，根据输入数据得出最终的推荐结果的具体过程就在这里。
内容展示UI：对于推荐结果如何展示，也是一个值得权衡的地方。以更好地满足推荐系统的目标，并能更好的收集用户的行为信息等。
其中，个性化推荐中最为核心的推荐算法，目前比较流行的有以下几种：

基于内容的推荐：根据内容本身的属性(特征向量)所作的推荐。
基于关联规则的推荐：“啤酒与尿布”的方式，是一种动态的推荐，能够实时对用户的行为作出推荐。是基于物品之间的特征关联性所做的推荐，在某种情况下会退化为物品协同过滤推荐。
协同过滤推荐：与基于关联规则的推荐相比是一种静态方式的推荐，是根据用户已有的历史行为作分析的基础上做的推荐。可分为物品协同过滤、用户协同过滤、基于模型的协同过滤。其中，基于模型的协同又可以分为以下几种类型：基于距离的协同过滤；基于矩阵分解的协同过滤，即Latent Factor Model(SVD)；基于图模型协同，即Graph，也叫社会网络图模型。
```
