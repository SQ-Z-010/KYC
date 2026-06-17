# KYC 客户风险等级评分系统

基于机器学习的 KYC（Know Your Customer）客户风险等级评分与合规分析项目。

## 项目简介

本项目利用机器学习算法对金融机构客户进行风险等级评分，帮助识别高风险客户，满足反洗钱（AML）和合规要求。基于多维度特征（交易行为、信用记录、人口统计信息）构建分类模型，输出客户风险等级。

## 功能特性

- **多维度特征分析**：34 个特征变量，覆盖交易行为、信用、人口统计等维度
- **完整数据科学流程**：数据探索 → 缺失值处理 → 特征工程 → 异常值处理 → 建模评估
- **丰富的数据可视化**：数值/分类/文本变量的全面探索性分析
- **机器学习建模**：多种分类模型对比，选择最优方案

## 数据集

`data/kyc_data.csv`：包含客户风险等级数据，字段包括：
- 人口统计特征（年龄、职业、教育等）
- 交易行为特征（交易频率、金额、时间模式等）
- 信用特征（信用评分、历史违约等）
- 目标变量：风险等级（低/中/高）

## 技术栈

- Python 3.9+
- `pandas`：数据处理
- `numpy`：数值计算
- `matplotlib` / `seaborn`：可视化
- `scikit-learn`：机器学习建模
- `Jupyter Notebook`：交互式分析

## 安装依赖

```bash
pip install -r requirements.txt
```

## 使用方式

打开 Jupyter Notebook：`ML_demo_kyc_eval.ipynb`，按顺序执行即可。

## 项目结构

```
kyc-risk-scoring/
├── ML_demo_kyc_eval.ipynb    # 主分析 Notebook（EDA + 预处理 + 建模）
├── data/
│   └── kyc_data.csv            # 数据集
├── requirements.txt
├── README.md
└── .gitignore
```

## 作者

- GitHub：[SQ-Z-010](https://github.com/SQ-Z-010)
- 项目用途：金融风控数据分析作品集 / 机器学习学习参考

## License

MIT
