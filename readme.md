Jittor 第四届计图人工智能挑战赛 热身赛 baseline

对已有代码进行补充（TODO部分）即可得到结果

[![result.png](https://i.postimg.cc/Hxtbkpvt/result.png)](https://postimg.cc/ygkDfzHJ)


## 简介

本项目包含了第四届计图挑战赛计图 - 热身赛代码的实现。本项目的特点是：在数字图片数据集 MNIST 上训练 Conditional GAN模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

赛题内容。

## 安装 

本项目可以在linux或者windows环境下运行

#### 运行环境
- python >= 3.7
- jittor >= 1.3.0

#### 安装依赖
执行以下命令安装 python 依赖
```
pip install -r requirements.txt
```

## 训练
直接运行CGAN.py

单卡训练可运行以下命令：

## 推理
修改number得到预期的result.png




## 注意事项

点击项目的“设置”，在Description一栏中添加项目描述，需要包含“jittor”字样。同时在Topics中需要添加jittor。

![image-20220419164035639](https://s3.bmp.ovh/imgs/2022/04/19/6a3aa627eab5f159.png)
