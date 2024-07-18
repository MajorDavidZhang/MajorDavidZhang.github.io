---
title: "Learning the Unlearned: Mitigating Feature Suppression in Contrastive Learning"
collection: publications
permalink: /publication/paper-1-learning-the-unlearned
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-07-10
venue: 'ECCV 2024'
authors:
paperurl: 'http://majordavidzhang.github.io/files/paper-1-learning-the-unlearned.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors: **Jihai Zhang**, Xiang Lan, Xiaoye Qu, Yu Cheng, Mengling Feng, Bryan Hooi

**Abstract:** 
Self-Supervised Contrastive Learning has proven effective in deriving high-quality representations from unlabeled data. 
However, a major challenge that hinders both unimodal and multimodal contrastive learning is feature suppression, a phenomenon where the trained model captures only a limited portion of the information from the input data while overlooking other potentially valuable content. This issue often leads to indistinguishable representations for visually similar but semantically different inputs, adversely affecting downstream task performance, particularly those requiring rigorous semantic comprehension.
To address this challenge, we propose a novel model-agnostic **M**ultistage **C**ontrastive **L**earning (MCL) framework. 
Unlike standard contrastive learning which inherently captures one single biased feature distribution, MCL progressively learns previously unlearned features through feature-aware negative sampling at each stage, where the negative samples of an anchor are exclusively selected from the cluster it was assigned to in preceding stages. Meanwhile, MCL preserves the previously well-learned features by cross-stage representation integration, integrating features across all stages to form final representations.
Our comprehensive evaluation demonstrates MCL's effectiveness and superiority across both unimodal and multimodal contrastive learning, spanning a range of model architectures from ResNet to Vision Transformers (ViT).
Remarkably, in tasks where the original CLIP model has shown limitations, MCL dramatically enhances performance, with improvements up to threefold on specific attributes in the recently proposed MMVP benchmark.

[[Code]](https://github.com/MajorDavidZhang/MCL)