---
layout: post
title: Tensorflow
date: 2022-03-30 22:20:01 +0800
subheading: 
author: huangwei
categories: Tech
banner:
  video: null
  loop: true
  volume: 0
  start_at: 0
  image: /assets/images/pexels.jpeg
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tag: 
  - Tensorflow
  - AI
sidebar: [article-menu]
---

# Tensorflow 错误处理

## 第一中错误

```
Could not load dynamic library 'libcudart.so.11.0'; dlerror: libcudart.so.11.0: cannot open shared object file: No such file or directory
```

TensorFlow-GPU 与 CUDA cudnn Python 版本关系：[链接](https://tensorflow.google.cn/install/source_windows?hl=en#gpu)

[CUDA 安装](https://developer.nvidia.com/cuda-toolkit-archive)
[解决办法](https://blog.csdn.net/qq_44703886/article/details/112393149)