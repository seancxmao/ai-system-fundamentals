# Deep Learning System Fundamentals

## Overview

这个项目的重点，不是学习高层深度学习框架（如PyTorch或JAX）的API，也不是各种DL模型（MLP、CNN、Transformer等等），而是通过熟悉现代深度学习系统的主要组件，为深入探究深度学习系统的内部工作原理打基础。打开黑盒，穿越不同抽象层级，从高层框架（PyTorch），直到AI软件栈的最底层（CUDA），乃至GPU Architecture。

基于以上动机，选择尽量简单的任务和模型，把重点放在深度学习系统内部工作原理上。任务选MNIST，这是深度学习的果蝇。模型选择MLP。MLP是现代深度学习中最基本的计算单元之一，也是Transformer的一个核心组件。

## Sub Projects

### Big Picture

* AI Landscape
* DL Landscape

### Deep Learning

* DL in Action: 用PyTorch API实现MLP。
* AI for Science in Action
* Neural Network from Scratch: 用NumPy从零开始实现MLP。

### GPU Computing

* GPU Architecture Essentials
* CUDA in Action
* Triton in Action

### AI Compiler

* PyTorch Compiler in Action

### Serving

* Serving in Action

## Summary

至此，深入理解了深度学习系统内部的工作原理。虽然生产级的深度学习模型和深度学习系统，要复杂得多，但是很多核心的基本原理已经能够体现出来：

* 模型的本质是分层表示学习
* 训练是通过梯度下降在假设空间中搜索最优解
* 用高层框架API写一行代码，底层到底发生什么，如何穿越整个软件栈的层次结构已经清晰

LLM是最重要的AI workload，所以下一步的目标是深入理解LLM workload。
