
---   
<div align="center">    
 
# 基于卷积特征提取和递归神经网络的大型视频数据集表情识别

</div>
 
## 声明

该项目仅用于提交机器学习作业使用

## 所需环境

* Python 3.7

* matplotlib 1.12.0

* pandas 1.3.4

* numpy 1.12.0

* tensorflow 2.6.0

* opencv 3.4.6

## 数据集

使用了Aff-Wild2、CK+和JAFFE三个数据集。

## 训练

首先进入config.py中的路径，然后：

* `train_cnn.py` ：训练 CNN 模型；

* 将 config.py 中的 CNN 提取模型路径更改为新路径；

* `extract_features.py`：从裁剪对齐的帧中提取特征；

*  `train_rnn.py` ：在上一步创建的特征上训练 RNN 模型。

## 预测

要使用提供的预训练模型预测表情，先更改“config.py”中的路径，然后运行“predict.py”


```
