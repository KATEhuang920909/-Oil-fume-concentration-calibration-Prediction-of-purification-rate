# -Oil-fume-concentration-calibration-Prediction-of-purification-rate
在线油烟实时监测系统。

目的：监测各个餐厅酒店的油烟排放浓度和净化率，对不达标者进行警示并协助城管和环保局执法，
可以解决现实问题，该系统已上线。

本人工作：负责数据处理部分，负责油烟浓度的校准和净化率的预测两部分，

1.由于单传感器测量的油烟浓度受周围环境如温度和湿度的影响，
因此测得的数据与真实数据存在出入，通过调用神经网络模型输入测量值/温度/湿度来训练模型参数，取得了较好的拟合效果，该模型已嵌入后台进行实时计算。


2.净化率的预测，通过净化率预测未来一段时间的净化效率，调用回归模型，模型的对比结果显示核回归的效果较为理想。
