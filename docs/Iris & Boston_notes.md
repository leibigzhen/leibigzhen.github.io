> 尝试用Markdown记笔记，熟悉基本语法，养成代码性习惯！

# Iris & Boston

## 学习中的一些tips：

- score不同，按照 **highest** 排名来分析data与model的匹配度，选择合适的类型、模型和评分方法
- 在参数化建模时，避免用 **二级参数** 的不同组合可以描述同一组模型，用 **一级参数** 更佳，防止结果对冲
- 训练集的评分接近1.0，而预测集较低，则为 **过拟合** 现象，需要对 **超参数** 调参，官网查询它各个属性
- 评估回归模型的Metric (e.g. mse, rmse, mas, r2)，数值从0到正无穷，表示离散程度，误差值越小越准
- **API** 是多软件协同工作术语，从GH→python→sklearn，需要通过调用的方法，搭接模块和传输数据
- PKL模型是文件类型，属于pytorch深度学习包的文件，sklearn是机器学习包，numpy是科学分析工具
- [机器学习 | 四大常用机器学习Python库介绍](https://cloud.tencent.com/developer/article/1800222) 分别是：[Scikit-learn](https://scikit-learn.org/stable/)，[Keras](https://keras.io/zh/)，[TensorFlow](https://tensorflow.google.cn/)，[PyTorch](https://pytorch.org/)  