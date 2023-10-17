# Anaconda安装Mxnet、Pytorch和Tensorflow

## 安装Mxnet

1. 进入Anaconda Prompt；

2. 使用pip命令进行安装：pip install mxnet；

3. 安装完成之后，检查是否安装正确：输入python，后输入import mxnet。

   ### 安装gluonbook（同理）

   1. 使用pip命令：pip install gluonbook;

   2. 安装完成之后，检查是否正确安装：输入python，后输入import gluonbook。

## 安装Pytorch

1. 打开Anaconda navigator;
2. 在Environments栏选择creat;
3. 在弹出的对话框creat new environment中创建新的工作环境：Pytorch_envs；
4. 点击create待其自动创建完成；
5. 打开Anaconda prompt，激活环境：在Dos窗口中输入activate Pytorch_envs;
6. 进入 [Pytorch官网](https://pytorch.org/get-started/locally//)，将run this command中的代码复制进Dos窗口；
7. 提示是否继续的窗口输入y；
8. 后进入python环境，导入numpy、torch检验是否安装成功：import numpy，import torch。

## 安装Tensorflow

1. 打开Anaconda navigator;
2. 在Environments栏选择creat;
3. 在弹出的对话框creat new environment中创建新的工作环境：Tensorflow_envs；
4. 点击create待其自动创建完成；
5. 打开Anaconda prompt，激活环境：在Dos窗口中输入pip install --upgrade --ignore-installed tensorflow;
6. 提示是否继续的窗口输入y；
7. 后进入python环境，导入tensorflow检验是否安装成功：import tensorflow；
8. 如果出现异常：![image-20210314200721605](C:\Users\dell\AppData\Roaming\Typora\typora-user-images\image-20210314200721605.png)则需要安装cuda和cudnn；
9. 