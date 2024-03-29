# Deep Learning Topics with 5 modules in Chinese 

## 1. 深度学习背景
```
1 深度学习引爆 5
1.1 谷歌Alpha GO 2.0 – 围棋. . . . . . . . . . . . . . . . . . . . . . . . . . . 5
1.2 谷歌Alpha GO – 围棋. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6
1.3 微软Skype – 语音翻译. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
1.4 Facebook DeepFace – 人脸识别. . . . . . . . . . . . . . . . . . . . . . . . 8
1.5 典型深度学习神经网络. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9

2 深度学习简史 21
2.1 代表人物：三巨头. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
2.2 人工智能到深度学习. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
2.3 为什么深度学习会成功. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51

3 神经网络基础和数学基础 71
3.1 神经网络模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 71
3.2 导数工具. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 78
3.3 经验风险最小和梯度下降. . . . . . . . . . . . . . . . . . . . . . . . . . . 92
3.4 反向传播BP 算法. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 97

4 数学上直观理解三大网络 151
4.1 卷积神经网络CNN 的数学类比. . . . . . . . . . . . . . . . . . . . . . . . 151
4.2 递归神经网络RNN 的数学类比. . . . . . . . . . . . . . . . . . . . . . . . 164
4.3 自动编码器AE 的数学类比. . . . . . . . . . . . . . . . . . . . . . . . . . 178
```



## 2. 深度学习基础知识
```
1 深度神经网络理论   30
1.1 卷积神经网络CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30
1.2 递归神经网络RNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40
1.3 玻尔兹曼机BM . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50
1.4 自动编码器AE . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 57
1.5 生成对抗网络GAN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 69

2 卷积神经网络CNN 核心概念   75
2.1卷积层Convolution . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 75
2.2 池化层Pooling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 83
2.3 CNN 的BP . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 86

3 卷积神经网络CNN 训练技巧   96
3.1 激活函数Activation Functions . . . . . . . . . . . . . . . . . . . . . . . . 96
3.2 数据预处理. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 115
3.3 权重初始化. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 118
3.4 批标准化Batch Normalization . . . . . . . . . . . . . . . . . . . . . . . . 131
3.5 学习率Learning Rate . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 140
3.6 正则化. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 144
3.7 数据增强Data Augmentation . . . . . . . . . . . . . . . . . . . . . . . . . 158
3.8 迁移学习Transfer Learning . . . . . . . . . . . . . . . . . . . . . . . . . . 164
3.9 梯度检查. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 166
3.10 训练技巧举例. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 167

4 卷积神经网络CNN 主流架构  169
4.1 LeNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170
4.2 AlexNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 171
4.3 ZFNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 179
4.4 VGGNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 183
4.5 GoogLeNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 192
4.6 ResNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 203
4.7 NiN、改进ResNet、超越ResNet . . . . . . . . . . . . . . . . . . . . . . . 217
4.8 CNN 深度网络对比. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 229

```


## 3. 深度学习经典模块
```
1 递归神经网络RNN 4
2 玻尔兹曼机BM 69
3 自动编码器AE 157
4 生成对抗网络GAN 188

```


## 4. 自然语言处理
```
1 自然语言处理简介 6
1.1 Seq2Seq 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
1.2 RNN Encoder-Decoder 模型. . . . . . . . . . . . . . . . . . . . . . . . . . 12
1.3 Encoder-Decoder 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
1.4 NNLM 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
1.5 Log-Linear 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
1.6 嵌入词模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
1.7 向量空间模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30
1.8 词袋BoW 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37
1.9 N-Gram 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40

2 数学基础 46
2.1 概率统计. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 46
2.2 频率派. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 48
2.3 Fisher 派. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52
2.4 贝叶斯派. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59
2.5 K 分类最大相互熵推导Softmax . . . . . . . . . . . . . . . . . . . . . . . . 65

3 词嵌入模型 70
3.1 词-文上下文Word-Document . . . . . . . . . . . . . . . . . . . . . . . . . 70
3.2 词上下文Word-Neighboring Word . . . . . . . . . . . . . . . . . . . . . . 78
3.3 Softmax 近似计算. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 116

4 语言模型 123
4.1 从概率模型到神经网络模型. . . . . . . . . . . . . . . . . . . . . . . . . . 123
4.2 从神经网络模型到RNN 模型. . . . . . . . . . . . . . . . . . . . . . . . . 140
4.3 从RNN 模型到Encoder-Decoder 模型. . . . . . . . . . . . . . . . . . . . 147
4.4 Attention 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 164
4.5 Seq2Seq 模型：端到端. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 184
4.6 翻译输出. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 192
4.7 替代和增强RNN 模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 194
4.8 其他应用. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 207

```


## 5. 图像视频处理
```
图像视频处理模型 41
2.1 R-CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
2.2 MR-CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 47
2.3 OverFeat . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51
2.4 SPPNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64
2.5 Fast R-CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 74
2.6 Faster R-CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 86
2.7 R-FCN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 95
2.8 YOLO . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 101
2.9 YOLO2 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 113
2.10 SSD . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 122
2.11 DSSD . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 131
2.12 AttentionNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 136
2.13 AttractioNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 147
2.14 G-CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 155
2.15 ION . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 161
2.16 FPN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 166
2.17 Mask R-CNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 173
2.18 图像视频处理小结. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 195

```
