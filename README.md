# 线性回归

#### 项目介绍
在 Capital Bikeshare（美国 Washington, D.C.的一个共享单车公司）提供的自行车数据上进行回归分析。训练数据为2011年的数据，要求预测2012年每天的单车共享数量。 
 
### 项目需求

1) 训练数据和测试数据分割（将2012年的数据作为测试数据） 
2) 适当的特征工程（及数据探索）
3) 岭回归，并选择最佳的正则参数
4) Lasso，并选择最佳的正则参数
 
### 数据说明 

原始数据集地址：http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

文件说明： day.csv: 按天计的单车共享次数

字段说明：Instant记录号；Dteday：日期；Season：季节 1=春天 2=夏天 3=秋天 4=冬天；yr：年份；mnth：月份；hr：小时；holiday：是否是节假日；weekday：星期；workingday：是否工作日 1=工作日，0=周末；weathersit：天气 1：晴天，多云 2：雾天，阴天 3：小雪，小雨 4：大雨，大雪，大雾；temp：气温摄氏度；atemp：体感温度；hum：湿度；windspeed：风速；casual：非注册用户个数；registered：注册用户个数；cnt：给定日期（天）时间（每小时）总租车人数，响应变量 y ；
 
### 代码说明
Work1
数据探索分析无正则回归结果评估

Work2
岭回归结果评估及可视化结果

Work3
Lasso结果评估
