---
layout: page
title: Assignment
description: Description of early assignment.
nav_exclude: false
nav_order: 4
---

## CS324 介绍性作业
### 概述
在这个作业中，你将熟悉使用 Google Colab 笔记本提示各种基础模型的过程。具体来说，你将使用大型语言模型（LLMs）如 [BLOOM](https://huggingface.co/bigscience/bloom) 和 [BLOOMZ](https://huggingface.co/bigscience/bloomz)（BigScience）。语言模型提示是将输入文本提供给模型，然后让模型生成响应作为输出。例如，你可以给语言模型提供提示“The sky is”和模型可能会生成“blue”作为响应。
提示可以用于完成各种任务，如总结（例如，“总结以下段落：\<在这里写出段落\> 摘要：”）或提取（例如，“从用户简介中提取电话号码：\<在这里写出简介\>。”）
作业分为三个部分：
1. **任务选择**：在作业的第一部分，你将选择一个任务和评估数据集，这些你将在剩余的作业中使用。
2. **提示开发**：在作业的第二部分，你将探索如何为 LLMs 开发有效的提示。在这个过程中，你可能会遇到提示的喜悦和痛苦。  
  * 一方面，正确的提示和模型可以神奇地解决看似复杂且与模型 *训练目标* 无关的任务。
  * 另一方面，提示可能是一种脆弱的技术，可能需要时间、努力和创造力来开发一个充分的提示。
3. **模型比较**：在作业的最后一部分，你将比较几种 LLMs 的性能（定性和定量）。模型比较将在两个维度上进行：
  * 模型大小
  * 训练技术（例如，普通自回归 vs. 指令调整）
### 提交说明
完成以下部分。下载并提交这个笔记本（作为 .ipynb 文件）到 Canvas，截止日期为 2023 年 1 月 24 日晚上 11:59。
Colab 笔记本链接：[https://colab.research.google.com/drive/13gyUcsX7KtkwSJ1PfW8MrlXQePVD_jFP](https://colab.research.google.com/drive/13gyUcsX7KtkwSJ1PfW8MrlXQePVD_jFP)