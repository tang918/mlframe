# mlframe

项目结构：
mlframe
|--data
|   |--predictions  #用来预测的数据
|   |--raw          #未作修改的原始数据
|   |--staging      #经过数据处理后的数据
|   |--transformed  #已经准备好输入进模型的数据(包含特征和标签的数据集)
|--ml_skeleton      #模型的逻辑曾
|   |--etl          #清洗数据，划分数据的逻辑
|   |--model        #算法模型
|
|--models           #保存序列化后的模型
|
|--reports          #保存一些可视化文件
|
|--scripts          #调用ml_skeleton模块，比如编写训练方法
