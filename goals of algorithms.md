## 算法设计的目标
### 基本分析方法
#### 流程
和其他学科的研究模式类似，算法的研究，也遵循着“观察-假设-验证的”这一流程。对于多数程序员而言，我们只需要去了解一个算法关于时间的近似，而对于专家来说，则需要对算法的时间复杂度做进一步的细分。
#### 近似的标准
一般在描述的时候，只选取数量级最大的部分，并忽略其他部分。
#### 上限下限
上限值得就是最坏的情况，下限值得是最快的情况。我们希望一个算法能够尽可能稳定，而这样的稳定，表现为算法的上限与下限的**数量级**相同。