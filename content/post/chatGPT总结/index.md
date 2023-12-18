---
title: Some ChatGPT findings

subtitle: This blog talks about the historical developement of self-attention mechanism and the implementation of transformer decoder.
summary: This blog talks about the historical developement of self-attention mechanism and the implementation of transformer decoder.
# Link this post with a project
projects: []

# Date published
date: '2022-08-15T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'screenshot of ChatGPT'
  placement: 2
math: true
authors:
  - admin
  - 肖睿强
tags:
  - Academic

---

## 明确ChatGPT能解决问题的边界

```mermaid
graph TD;
世界上有很多问题其中只有一小部分是数学问题 --> 在数学问题中只有一小部分是有解的 --> 在有解的问题中只有一部分是理想状态的图灵机通过有限步骤可以解决的 --> 在后一类的问题中又只有一部分是今天实际的计算机可以解决的 --> 而人工智能可以解决的问题又只是计算机可以解决问题的一部分
```

> 故我们可知 我们无法让chatGPT直接预测明天地球会不会毁灭 即使人类也无法给出答案

## 基本原理

本质上就是大规模语言模型 按照概率输出结果

他的输出是基于之前训练输入的数据和过往的标记数据得到的结果

## 能做什么呢

### 选择一个主题  

我可以帮助你选择一个既有趣又与你的研究领域相关的题目。

![image-20230221161003710](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211610876.png)

![image-20230221161028376](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211610456.png)

### 制定提纲

我可以帮助你创建一个大纲，明确界定你的论文结构，包括导言、正文和结论。

![image-20230221161217119](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211612172.png)

### 进行研究

我可以提供进行研究的提示和资源，并寻找可靠的来源来支持你的论点。

![image-20230221161046474](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211610537.png)

![image-20230221161103655](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211611738.png)

![image-20230221161131752](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211611833.png)

![image-20230221161154883](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211611949.png)

### 撰写论文

我可以就如何写出清晰、简明、有条理的句子和段落，有效地传达你的观点提供建议。

### 修改和编辑

我可以就如何修改和编辑你的论文提供反馈，以确保它没有错误并符合学术标准。

![image-20230221161329025](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211613104.png)

### 引用资料

我可以指导你如何在论文中正确引用资料，包括使用MLA帮你写作这用方式。

***参考文献全是假的。***

### 代码实现

![image-20230221161354493](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211614495.png)

![image-20230221161431442](https://raw.githubusercontent.com/keeplearning-again/Typora_blog_images/main/blog/202302211614480.png)

## 注意事项那个

1. 尽量用英文提问
2. 提高归纳概括的能力
3. AI知识助手
4. 谨慎乐观的使用
5. 数据有泄漏风险
