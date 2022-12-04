# predict-future-sales
Advances in Data Mining Project 2.

## TODO
### 可视化：Seaborn (FS)
- 销量
    - 总销量
    - 商店
    - 城市
    - 商品类别
    - 商店月销量
- 价格异常值

### 特征工程 (LSP / JKT)
- 结构化数据
    - 时间：Year, Month, Week, Day
    - 价格：聚类，用中位数
    - Lag：1, 4, 12 月
- 文本特征：预训练词向量 (LSP) / 翻译成英语 (JKT)
    - 商品类别：聚类作为定类变量
    - 商品名：提取 patterns
    - 商店名：City + Type (TC, SEC, TSC, TK) + Name

### 模型 (LSP / JKT)
- Deep Learning: MLP
- Ensemble Learning: XGBoost + CatBoost + SGDRegressor + Ridge Regression + LGBM
    - 特征重要性评估 / 模型选择

预训练词向量下载：https://fasttext.cc/docs/en/pretrained-vectors.html
