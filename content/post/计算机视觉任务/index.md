---
title: Computer vision basic tasks
subtitle: Some understanding of computer vision basic tasks.

# Summary for listings and search engines
summary: Some understanding of computer vision basic tasks.

# Link this post with a project
projects: []

# Date published
date: '2022-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'classical tasks'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 肖睿强

tags:
  - Academic

categories:
  - Demo
---

##  计算机视觉任务

<img src="https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302021825208.png" alt="image-20230202182528109" style="zoom:67%;" />

主要分为几大类：

- 输入一张完整图像 --> single label（single object）--> ==**classification**==
- 输入一张完整图像 --> single object + anchor--> ==**classification + localization**==
- 输入一张完整图像 --> multiple object anchors--> ==**object detection**==
- 输入一张完整图像 --> 每一个对象具体的pixel--> ==**segmentation**==
  - 1. semantic segmentation --> 让每一个pixel都有一个label
    2. instance segmentation --> 区分每一个物体

## 机器学习和神经网络简介

### 机器学习的典型范式

- 监督学习
- 无监督学习
- 自监督学习 
- 强化学习

### 交叉熵损失函数 -- 极大似然估计

对于预测的类别概率$P \in [0, 1]^K$和类别真值$y \in \left[1, \cdots, K \right]$,定义交叉熵损失为：
$$
L(P, y) = - logP_y
$$
![image-20230202234122934](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302022341081.png)

![image-20230202234321173](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302022343225.png)

### 反向传播算法

![image-20230202234418393](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302022344490.png)

## 推荐热门AI研究方向

1. 人工智能的可解释性分析、显著性分析

2. 图机器学习、图神经网络（AlphaFold2）、知识图谱

3. 人工智能+VR/AR/数字人/元宇宙

4. 轻量化压缩部署：Web前端、智能手机、服务器、嵌入式硬件

5. Al4Science：天文、物理、蛋白质预测、药物设计、数学证明

6. 做各行各业垂直细分领域的人工智能应用

7. 神经辐射场（NERF）

8. 扩散生成模型（Diffusion）、AIGC、跨模态预训练大模型

9. 隐私计算、联邦学习、可信计算

10. AI基础设施平台（数据、算力、教学、开源、算法工具包）

11. 认知科学+类脑计算+计算神经科学
