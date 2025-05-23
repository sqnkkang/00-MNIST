# 00-MNIST

## 1 >> 依赖环境

本项目因为是作者手写的 CNN，所以没有用到 GPU，因为本身手写字识别就是一个很简单的分类问题，所以网络结构设计的也非常的简单，直接使用 CPU 进行训练的。

主要用到了一些简单的 numpy 库函数，来代替手写的 for 循环，不让代码看着过于的冗杂。

- 硬件配置

```
能开机的电脑
```

- 项目环境

```
numpy                     1.24.3
python                    3.8.18
pillow                    10.0.1
matplotlib                3.7.2
tqdm
```

注1：matplotlib 库不是必须的，只是能更好的展示效果，完全可以直接输出测试照片的正确率和置信度来查看模型的好坏。

注2：tqdm 也不是必须的，为训练过程添加一个进度条，方便查看训练的进度。

## 2 >> 构建步骤

- 001 >> [数据准备](https://github.com/fangqing408/00-MNIST/blob/master/recognition/001.md)
- 002 >> [网络参数初始化](https://github.com/fangqing408/00-MNIST/blob/master/recognition/002.md)
- 003 >> [前向传播](https://github.com/fangqing408/00-MNIST/blob/master/recognition/003.md)
- 004 >> [反向传播](https://github.com/fangqing408/00-MNIST/blob/master/recognition/004.md)
- 005 >> [模型训练](https://github.com/fangqing408/00-MNIST/blob/master/recognition/005.md)
- 006 >> [模型保存和预测](https://github.com/fangqing408/00-MNIST/blob/master/recognition/006.md)
