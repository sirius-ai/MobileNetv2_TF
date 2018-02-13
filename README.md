# MobileNetv2_TF

## Introduction

This is a Tensorflow implementation of Google's MobileNetv2. 
MobileNet is a general architecture and can be used for multiple use cases.
Depending on the use case, it can use different input layer size and different
head (for example: embeddings, localization and classification). for details,
please reference the following paper:

[Inverted Residuals and Linear Bottlenecks Mobile Networks for Classification, Detection and Segmentation](https://arxiv.org/abs/1801.04381)

## MobileNetv2 and inverted residual block architectures

**The difference between residual block and inverted residual:**

![residual block and inverted residual](/images/residualdff.JPG)

**MobileNetv2 Neural Network:**

![MobileNetv2](/images/net.JPG)

**Bottleneck Architectures:**

![residual block architectures](/images/blockstru.JPG)
 

## Requirement

- python >= 2.7
- tensorflow >= r1.2 

## References

- [Mobilenet_v2 on arxiv](https://arxiv.org/pdf/1801.04381.pdf)
- [Mobilenet_v1 on slim](https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.py)

## Copyright

See [LICENSE](LICENSE) for details.