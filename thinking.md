# Thinking1	XGBoost与GBDT的区别是什么？ #

答：XGboost为GBDT的工程版本，在GBDT的基础上加入了很多工程类优化
（1）xgboost将损失函数泰勒展开到了二阶。保留了更多有关目标函数的信息，对提升效果有帮助。
（2）xgboost加入了L2正则化项，目的在于惩罚复杂模型，防止过拟合，泛化性能好。
（3）XGBoost利用近似贪心算法等，对分裂节点进行优化，获取最优的分割节点。
（4）支持特征并行计算，速度快，效果好，但是参数相较于GBDT多，调参比较复杂。



# thinking2 3 发布了博客，请移驾CSDN #
https://blog.csdn.net/weixin_41579119/article/details/108877227
