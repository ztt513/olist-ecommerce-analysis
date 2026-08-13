# olist-ecommerce-analysis
Olist巴西电商数据分析，运用统计检验、Kmeans用户分群、逻辑回归挖掘用户满意度影响因素
## 技术栈
Python：Pandas、NumPy、Matplotlib、Seaborn、Scikit-learn、Scipy

## 分析流程
1. 数据预处理：多表关联合并、缺失值/重复值处理、一对多表聚合、业务特征衍生
2. EDA探索性分析：运营趋势、商品品类、物流时效、用户评价、地域支付、下单规律多维度可视化
3. 用户价值分层：适配低复购业务场景，采用 RM 二维模型完成用户分层与画像
## 数据集来源
Kaggle Olist Brazilian E-commerce Dataset
> 原始数据集文件较大，本仓库不存放原始csv，可自行前往Kaggle下载

## 目录结构（持续更新）
- notebook：jupyter分析代码
- output：可视化图表、模型输出结果、分层结果
