---
layout: default
title: 课程主题
nav_order: 3
has_children: false
---

# 课程主题
作为阅读资源，请查看以下课程主题及相关材料列表。在每个主题下，我们包括了一系列相关阅读材料，包括讲座笔记、博客文章、论文和其他资源。

我们将课程主题广泛地组织在三个领域：

**（1）** [基础知识](#基础知识)
**（2）** [现有基础模型（FMs）及其应用的调查](#现有基础模型及其应用的调查)
**（3）** [社会考量与影响](#社会考量与影响)。
    
---

### 目录  

- [**基础知识**](#基础知识)  

  - [什么是基础模型（FMs）？为什么它们有趣？](#什么是基础模型FMs及为什么它们有趣)  
  - [数据如何影响FMs及其下游效应？](#数据如何影响FMs及其下游效应)  
  - [我们如何训练FMs及其下游效应？](#我们如何训练FMs及其下游效应)  
  - [FMs的模型架构和训练目标](#FMs的模型架构和训练目标)  
  - [涌现行为和能力](#涌现行为和能力)  
  - [将FMs适应于新任务和数据领域](#将FMs适应于新任务和数据领域)  
  - [训练方法和基础设施](#训练方法和基础设施)

- [**现有基础模型及其应用的调查**](#现有基础模型及其应用的调查)  

  - [文本及（掩码）语言建模FMs](#文本及掩码语言建模FMs)   
  - [图像-文本和多模态FMs](#图像-文本和多模态FMs)    

- [**社会考量与影响**](#社会考量与影响)  

  - [安全与隐私](#安全与隐私)
  - [环境影响](#环境影响)  
  - [法律考量](#法律考量)

---

## 基础知识

### 什么是基础模型（FMs）？为什么它们有趣？   

* *背景知识：神经网络（Andrej Karpathy的课程系列）*：
  - [神经网络：从零到英雄](https://github.com/karpathy/nn-zero-to-hero)    
* *课程笔记*:  
  - [大型语言模型（LLM）的能力](https://aithoughts.github.io/large-language-models/lectures/capabilities/)      
* *博客文章*：
  - [基础模型如何改变了我们的工作](https://hazyresearch.stanford.edu/blog/2022-11-16-whatsup)    
* *论文*:  
  - [语言模型是少量样本学习者](https://arxiv.org/abs/2005.14165)      
  - [论基础模型的机会与风险](https://arxiv.org/abs/2108.07258)      

### 数据如何影响FMs及其下游效应？

* *课程笔记*:  
  - [用于训练FMs的数据](https://aithoughts.github.io/large-language-models/lectures/data/)    
  - [数据的危害（第一部分）](https://aithoughts.github.io/large-language-models/lectures/harms-1/)    
  - [数据的危害（第二部分）](https://aithoughts.github.io/large-language-models/lectures/harms-2/)    
* *博客文章*：
  - [基础模型正在进入其以数据为中心的时代](https://hazyresearch.stanford.edu/blog/2022-10-11-datacentric-fms)    
* *论文*:  
  - [大量多样化的文本数据集：用于语言建模的800GB数据](https://arxiv.org/abs/2101.00027)    
  - [去重训练数据使语言模型更好](https://arxiv.org/abs/2107.06499)    
  - [重复数据的学习可扩展性和可解释性](https://arxiv.org/abs/2205.10487)    
  - [随机鹦鹉的危险：语言模型是否可能过大？ 🦜](https://dl-acm-org.stanford.idm.oclc.org/doi/abs/10.1145/3442188.3445922)    

### FMs的模型架构和训练目标  

* *课程笔记*：
  - [LLM架构](https://aithoughts.github.io/large-language-models/lectures/modeling/)      
  - [LLM训练目标](https://aithoughts.github.io/large-language-models/lectures/training/)    
* *博客文章*：
* *论文*: 
  - [注意力机制即你所需要的一切](https://arxiv.org/abs/1706.03762)      
  - [ELECTRA：将文本编码器预训练为判别器而非生成器](https://arxiv.org/abs/2003.10555)      
  - [统一语言学习范式](https://arxiv.org/abs/2205.05131)      
  - [使用统一文本到文本转换器探索迁移学习的极限](https://arxiv.org/abs/1910.10683)      

### 涌现行为和能力  

* *课程笔记*:  
  - [扩展定律](https://aithoughts.github.io/large-language-models/assets/pdfs/Scaling%20laws%20pdf.pdf)      
* *博客文章*:  
  - [上下文学习如何工作？](https://ai.stanford.edu/blog/understanding-incontext/)    
* *论文*: 
  - [神经语言模型的扩展定律](https://arxiv.org/abs/2001.08361)      
  - [展示你的工作：使用语言模型的中间计算草稿](https://arxiv.org/abs/2112.00114)        
  - [思维链提示引发大型语言模型的推理](https://arxiv.org/abs/2201.11903)      
  - [问我任何事：一种简单的语言模型提示策略](https://arxiv.org/abs/2210.02441)      
  - [大型语言模型的涌现能力](https://arxiv.org/abs/2206.07682)      
  - [数据分布属性驱动变压器中的少量样本学习](https://arxiv.org/abs/2205.05055)        
  - [将上下文学习解释为隐式贝叶斯推理](https://arxiv.org/abs/2111.02080)      
  - [重新思考示范的作用：是什么让上下文学习工作？](https://arxiv.org/abs/2202.12837)    

### 将FMs适应于新任务和数据领域    

* *课程笔记*：
  - [适应大型语言模型](https://aithoughts.github.io/large-language-models/lectures/adaptation/)      
* *博客文章*:  
* *论文*：
  - [多任务提示训练使零样本任务泛化成为可能](https://arxiv.org/abs/2110.08207)        
  - [微调语言模型是零样本学习者](https://arxiv.org/abs/2109.01652)        
  - [前缀调整：优化生成任务的连续提示](https://arxiv.org/abs/2101.00190)        
  - [训练语言模型以遵循人类反馈的指示](https://arxiv.org/abs/2203.02155)      
  - [规模对参数高效提示调整的功效](https://arxiv.org/abs/2104.08691)      
  - [LoRA：低秩适应大型语言模型](https://arxiv.org/abs/2106.09685)      
  - [大规模快速模型编辑](https://arxiv.org/abs/2110.11309)      

### 训练方法和基础设施  

* *课程笔记*:  
* *博客文章*:  
  - [BLOOM训练背后的技术](https://huggingface.co/blog/bloom-megatron-deepspeed)      
* *论文*:  
  - [在异构环境中分布式训练基础模型](https://arxiv.org/abs/2206.01288)       
  - [Megatron-LM：使用模型并行性训练数十亿参数的语言模型](https://arxiv.org/abs/1909.08053)      
  - [FlashAttention：快速且内存高效的精确注意力机制与IO感知](https://arxiv.org/abs/2205.14135)      
  - [训练过程（第2.5节），OPT：开放预训练转换器语言模型](https://arxiv.org/abs/2205.01068)     (也请参见[完整的训练日志](https://github.com/facebookresearch/metaseq/blob/main/projects/OPT/chronicles/README.md))      

---

## 现有基础模型及其应用的调查

### 文本及（掩码）语言建模FMs  

* *课程笔记*:  
* *博客文章*:  
  - [使语言模型遵循指示](https://openai.com/blog/instruction-following/)      
  - [PubMedGPT](https://crfm.stanford.edu/2022/12/15/pubmedgpt.html)      
* *论文*:  
  - [语言模型是无监督多任务学习者](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)    
  - [语言模型是少量样本学习者](https://arxiv.org/abs/2005.14165)      
  - [训练语言模型以遵循人类反馈的指示](https://arxiv.org/abs/2203.02155)    
  - [CodeGen：一个用于代码的开源大型语言模型，具有多轮程序合成能力](https://ui.adsabs.harvard.edu/abs/2022arXiv220313474N/abstract)    
  - [使用AlphaFold高度准确地预测蛋白质结构](https://pubmed.ncbi.nlm.nih.gov/34265844/)    
  - [在进化尺度上对蛋白质序列的语言模型进行结构预测](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1)    
  - [GatorTron：一个用于临床自然语言处理的的大型语言模型](https://www.medrxiv.org/content/10.1101/2022.02.27.22271257v2.full)     
  - [法律堆：从法律和256GB开源法律数据集中学习负责任的数据过滤](https://arxiv.org/abs/2207.00220)      
  - [LegalBench：为法律推理原型化协作基准](https://arxiv.org/abs/2209.06120)      

### 图像-文本和多模态FMs  

* *课程笔记*:  
* *博客文章*:  
* *论文*: 
  - [从自然语言监督中学习可转移的视觉模型](https://arxiv.org/abs/2103.00020)      
  - [零样本文本到图像生成](https://arxiv.org/abs/2102.12092)      
  - [去噪扩散概率模型](https://arxiv.org/abs/2006.11239)      
  - [使用潜在扩散模型的高分辨率图像合成](https://arxiv.org/abs/2112.10752)      
  - [具有深度语言理解能力的真实文本到图像扩散模型](https://arxiv.org/abs/2205.11487)      
  - [Imagen Video：使用扩散模型的高清视频生成](https://arxiv.org/abs/2210.02303)      
  - [Make-A-Video：无需文本-视频数据的文本到视频生成](https://arxiv.org/abs/2209.14792)      
  - [DreamFusion：使用2D扩散的文本到3D](https://arxiv.org/abs/2209.14988)      
  - [Point-E：一个用于从复杂提示生成3D点云的系统](https://arxiv.org/abs/2212.08751)      
  - [Flamingo：一个用于少量样本学习的视觉语言模型](https://arxiv.org/abs/2204.14198)      
  - [CM3：互联网的因果掩码多模态模型](https://arxiv.org/abs/2201.07520)      
  - [A Generalist Agent](https://arxiv.org/abs/2205.06175)    
  - [Video PreTraining (VPT)：通过观看未标记在线视频学习行动](https://arxiv.org/abs/2206.11795)      
  - [MineDojo：构建具有互联网规模知识的开放性身体化代理](https://arxiv.org/abs/2206.08853)      

---

## 社会考量与影响

### 安全与隐私  

* *课程笔记*:  
  - [安全与隐私](https://aithoughts.github.io/large-language-models/assets/pdfs/Privacy%20pdf.pdf)      
* *博客文章*:  
* *论文*:  
  - [从大型语言模型中提取训练数据](https://arxiv.org/abs/2012.07805)       
  - [公平学习](https://texaslawreview.org/fair-learning/)      
  - [大型语言模型可以是强差分隐私学习者](https://arxiv.org/abs/2110.05679)      
  - [基础模型能帮助我们实现完美保密吗？](https://arxiv.org/abs/2205.13722)    

### 环境影响 

* *课程笔记*:  
  - [环境影响](https://aithoughts.github.io/large-language-models/lectures/environment/)      
* *博客文章*:  
* *论文*:  
  - [深度学习在NLP中的能源和政策考量](https://arxiv.org/abs/1906.02243)      
  - [大型神经网络训练的碳排放](https://arxiv.org/abs/2104.10350)      
  - [揭示AI解决方案对环境的隐藏环境影响](https://arxiv.org/abs/2110.11822)      
  - [基础模型的机会与风险中的环境影响部分](https://crfm.stanford.edu/assets/report.pdf#environment)      

### 法律考量 

* *课程笔记*:  
  - [法律性](https://aithoughts.github.io/large-language-models/lectures/legality/)      
* *博客文章*:  
  - [从机器学习中的歧视到法律中的歧视，第一部分：歧视性对待](https://ai.stanford.edu/blog/discrimination_in_ML_and_law/)      
  - [从机器学习中的歧视到法律中的歧视，第二部分：歧视性影响](https://ai.stanford.edu/blog/discrimination_in_ML_and_law_p2/)      
* *论文 / 文章*:  
  - [互联网法](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3191751)      
  - [AI监管即将到来](https://hbr.org/2021/09/ai-regulation-is-coming)      
  - [基础模型的机会与风险中的法律性部分](https://crfm.stanford.edu/assets/report.pdf#legality)   

---

## 结论

本课程旨在提供关于基础模型（FMs）的基础知识和深入探讨，以及它们在社会、法律、伦理和环境影响方面的考量。我们通过一系列的主题和阅读材料，探讨这些模型的工作原理、它们的局限性以及它们对社会的影响。通过这些学习，我们希望你能够更好地理解这些模型，并能够评估它们在现实世界中的应用。