#### 对于PCA的理解


#### PCA实现的流程
&emsp; 将数据转换成前N个主成分的伪代码大致如下:
&emsp; &emsp; 去除平均值
&emsp; &emsp; 计算数据集的协方差矩阵
&emsp; &emsp; 计算协方差矩阵的特征值和特征向量
&emsp; &emsp; 将特征值从大到小排序
&emsp; &emsp; 保留上面的前N个特征向量
&emsp; &emsp; 将数据转换到上述N个特征向量构建的新空间中