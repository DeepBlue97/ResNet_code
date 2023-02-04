# ResNet_code
ResNet 由粗到细(coarse-to-fine)解读

我们将结合[ResNet论文](https://arxiv.org/abs/1512.03385)和代码一起来讲解ResNet。

代码是从torchvision官方代码[resnet.py](https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py)中拷贝而来。

## Summary
- Background
- Why ResNet
- Theory Straightforward
- How to Use it
- Code Detail

## Background
Deeper neural networks are more difficult to train.

## Why ResNet
ease the training of networks that are substantially(大幅) deeper than those used previously.

- ResNet 改善深网络的退化问题。
- ResNet 可以加快收敛。
- ResNet 几乎不增加参数和计算量。


## Theory Straightforward
每次学一点，别学歪了。

## How to Use it

1. Pytorch中直接引用

```Python
from 

```

2. MMDetection中引用


## Code Detail


模型复杂度：FLOPs = (卷积核高×卷积核宽×输入通道数) × (输出高×输出宽×输出通道数)

ResNet-18:

ResNet-34:

