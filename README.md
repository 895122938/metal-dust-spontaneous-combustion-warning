# 金属粉尘自燃预警算法 (Metal Dust Spontaneous Combustion Warning Algorithm)

## 项目简介
本项目旨在开发一套基于机器学习的金属粉尘自燃预警算法系统，通过实时监测环境温度、湿度、粉尘浓度、氧气含量等关键参数，预测金属粉尘发生自燃的风险。

## 主要功能
- 自燃风险评估：基于多参数融合的自燃概率预测
- 实时监测：支持多传感器数据实时采集与处理
- 多级预警：低、中、高风险三级预警机制
- 趋势分析：历史数据趋势分析与可视化

## 技术栈
- Python 3.9+
- scikit-learn, TensorFlow/PyTorch
- pandas, numpy
- matplotlib, plotly
- Docker, Flask/FastAPI

## 项目结构
```
├── data/              # 数据集
├── models/            # 训练好的模型
├── src/               # 源代码
├── notebooks/         # Jupyter notebooks
├── tests/             # 单元测试
├── config/            # 配置文件
└── requirements.txt   # 依赖包
```

## 许可证
MIT License
