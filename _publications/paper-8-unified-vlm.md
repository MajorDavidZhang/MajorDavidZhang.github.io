---
title: "Cross-Task Generalization Between Understanding and Generation in Unified Vision-Language Models: A Controlled Study"
collection: publications
permalink: /publication/paper-8-unified-vlm
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-05-29
venue: 'BMVC 2026'
authors:
#paperurl: 'http://majordavidzhang.github.io/files/paper-1-learning-the-unlearned.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors: **Jihai Zhang**, Tianle Li, Linjie Li, Zhengyuan Yang, Yu Cheng

**Abstract:** 
Unified vision-language models (VLMs) aim to support both visual understanding and generation within a single framework, but it remains unclear when mixed training benefits both capabilities and when it introduces conflicts. This paper presents a controlled empirical study of cross-task generalization between understanding and generation in unified VLMs. We construct two controllable image-text benchmarks, SmartWatch and modified CelebA, with paired VQA, captioning, and text-to-image generation tasks, and evaluate multiple LLM-based unified architectures built from SigLIP and VQ-VAE visual spaces. Our experiments show that mixed understanding-generation training can improve both tasks over task-specific training, but the benefit depends strongly on the relation between vision input and output spaces. Unified models with better aligned visual spaces exhibit stronger cross-task transfer, while reversible affine distortions of the input visual space substantially weaken this effect and can turn mutual benefits into conflicts. We further find that increasing data from one task can initially improve the other, but excessive imbalance between understanding and generation data may degrade the complementary task. By controlling attribute frequencies, we show that generation supervision can help recover underrepresented visual concepts for understanding. Adapter analyses suggest that this transfer is not primarily caused by richer visual adapter features, but by the base language model learning relationships that generalize across aligned visual spaces. A real-case experiment on LLaVA provides additional evidence that mixed understanding-generation training can benefit visual understanding beyond controlled benchmarks. Our source code is available at github.com/MajorDavidZhang/Generalization_unified_VLM.

[[Code]](https://github.com/MajorDavidZhang/Generalization_unified_VLM)
[[PDF]](http://majordavidzhang.github.io/files/paper-8-unified-vlm.pdf)
