# 赛题数据
赛题以预测二手车的交易价格为任务，数据集报名后可见并可下载，该数据来自某交易平台的二手车交易记录，总数据量超过40w，包含31列变量信息，其中15列为匿名变量。为了保证比赛的公平性，将会从中抽取15万条作为训练集，5万条作为测试集A，5万条作为测试集B，同时会对name、model、brand和regionCode等信息进行脱敏。
## 字段表
![](https://picgp.oss-cn-beijing.aliyuncs.com/img/20200503192310.png)
# 评测标准
评价标准为MAE(Mean Absolute Error)。
![](https://picgp.oss-cn-beijing.aliyuncs.com/img/20200503192406.png)
MAE越小，说明模型预测得越准确。
# 结果提交
提交前请确保预测结果的格式与sample_submit.csv中的格式一致，以及提交文件后缀名为csv。

形式如下：
![](https://picgp.oss-cn-beijing.aliyuncs.com/img/20200503192449.png)


