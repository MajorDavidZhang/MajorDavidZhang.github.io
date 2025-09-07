---
title: "Are Unified Vision-Language Models Necessary: Generalization Across Understanding and Generation"
collection: publications
permalink: /publication/paper-8-unified-vlm
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-05-29
venue: 'arxiv'
authors:
#paperurl: 'http://majordavidzhang.github.io/files/paper-1-learning-the-unlearned.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors: **Jihai Zhang**, Tianle Li, Linjie Li, Zhengyuan Yang, Yu Cheng

**Abstract:** 
Recent advancements in unified vision-language models (VLMs), which integrate both visual understanding and generation capabilities, have attracted significant attention. The underlying hypothesis is that a unified architecture with mixed training on both understanding and generation tasks can enable mutual enhancement between understanding and generation. However, this hypothesis remains underexplored in prior works on unified VLMs. To address this gap, this paper systematically investigates the generalization across understanding and generation tasks in unified VLMs. Specifically, we design a dataset closely aligned with real-world scenarios to facilitate extensive experiments and quantitative evaluations. We evaluate multiple unified VLM architectures to validate our findings. Our key findings are as follows. First, unified VLMs trained with mixed data exhibit mutual benefits in understanding and generation tasks across various architectures, and this mutual benefits can scale up with increased data. Second, better alignment between multimodal input and output spaces will lead to better generalization. Third, the knowledge acquired during generation tasks can transfer to understanding tasks, and this cross-task generalization occurs within the base language model, beyond modality adapters. Our findings underscore the critical necessity of unifying understanding and generation in VLMs, offering valuable insights for the design and optimization of unified VLMs.

[[Code]](https://github.com/MajorDavidZhang/Generalization_unified_VLM)
[[PDF]](http://majordavidzhang.github.io/files/paper-8-unified-vlm.pdf)