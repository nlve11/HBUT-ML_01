# HBUT-ML# 人工智能开发技术实验 01

Python 机器学习基本流程与结果分析。

## 实验内容

使用 scikit-learn 内置二分类数值数据集，完成数据检查、分层划分、逻辑回归与决策树训练、指标评价、混淆矩阵与错误样本分析，并保存最佳模型后在新进程重载验证。

## 目录说明

- `data_utils.py`：数据加载、标签转换和分层划分
- `models.py`：逻辑回归与决策树 Pipeline
- `evaluation.py`：Accuracy、Precision、Recall、F1、混淆矩阵和错误样本
- `training.py`：训练两个模型并保存逐模型结果
- `run_experiment.py`：主训练脚本，选择并保存最佳模型
- `verify_saved_model.py`：重载模型并验证预测一致性
- `outputs/`：指标、混淆矩阵、错误样本、图片、环境与运行摘要
- `models/best_pipeline.joblib`：按 F1 选出的最佳模型文件
- `student_identity.json`：学号与身份校验信息

## 运行结果

最佳模型为 `logistic_regression`，测试集 F1 约为 0.964。
