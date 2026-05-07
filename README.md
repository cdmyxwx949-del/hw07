# HW07 胸部X光肺炎检测实验

## 项目简介
基于Kaggle Chest X-Ray数据集，使用深度学习CNN模型完成肺炎二分类与三分类任务，遵循端到端实验流程。

## 数据集
- 来源：Kaggle Chest X-Ray Images (Pneumonia)
- 划分：从train按8:2重新划分训练集与验证集，未使用原始val文件夹

## 运行方式
1.  在Kaggle新建Notebook，添加Chest X-Ray数据集
2.  开启GPU加速
3.  运行train.ipynb，包含二分类与三分类完整代码

## 依赖环境
- Python 3.8+
- TensorFlow 2.8+
- 安装依赖：`pip install -r requirements.txt`

## 最终结果
- 二分类准确率：0.6667，召回率：0.4744
- 三分类准确率：约0.6
- 所有图表保存在figures/目录

## 参考说明
参考了Kaggle公开baseline思路，自行修改了数据划分方式、模型结构，并增加了医学场景分析与三分类扩展。
