# How-to-configure-TensorFlow-GPU-on-Ubuntu_16_04

## 概述

本教程配置环境为：

• Ubuntu 16.04×86_64 LTS、NVIDIA GeForce GTX 1080Ti

• Python 3.5.2、CUDA 9.0 、cuDNN 7.0、TensorFlow-GPU 1.9.0

文中首先介绍了配置之前的相关准备工作，包括查看 NVIDIA 显卡型号和对应驱动是否安装、验证 NVIDIA 显卡是否支持 CUDA、修改 ubuntu 默认python 版本、安装 pip 并升级、完全卸载旧版本 CUDA；其次介绍了 CUDA9.0 、cuDNN 7.0 以及 libcupti-dev 库的安装；再次介绍了环境变量的配置、测试 CUDA 9.0 和 cuDNN 7.0 的安装情况；随后介绍了配置 TensorFlow-GPU 环境并测试其安装情况；最后介绍了导入 tensorflow 出现的常见问题及其解决办法。

本文所述方法适用于以上环境但所体现的思想不限于此种组合，读者可根据本教程配置类似组合。

## 具体步骤

详见文档


## Updates

14 Jul. 2018

- 配置 [tensorflow_gpu-1.9.0 (229.6 MB)  Jul 10, 2018](https://pypi.org/project/tensorflow-gpu/#files)


16 Mar. 2018

- 配置 [tensorflow_gpu-1.6.0 (209.2 MB)  Jul 10, 2018](https://pypi.org/project/tensorflow-gpu/1.6.0/#files)
