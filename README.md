# 基于深度学习的滑坡敏感性分析

## 介绍
- 本质上是多波段图像的二分类问题
- 输入图像的C×H×W为：11×17×17,所以网络结构较浅
- 几乎所有实现均在''train.py''中,包括结果评估，AUC曲线函数绘制

## 必要库安装
- python 3.9
- GDAL   2.4.1
- numpy  1.22.0
- torch  1.9.1+cu111
- torchvision  0.10.1+cu111

