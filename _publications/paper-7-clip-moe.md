---
title: "CLIP-MoE: Towards Building Mixture of Experts for CLIP with Diversified Multiplet Upcycling"
collection: publications
permalink: /publication/paper-7-clip-moe
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-09-28
venue: 'arxiv'
authors:
#paperurl: 'http://majordavidzhang.github.io/files/paper-1-learning-the-unlearned.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors: **Jihai Zhang**, Xiaoye Qu, Tong Zhu, Yu Cheng

**Abstract:** 
In recent years, Contrastive Language-Image Pre-training (CLIP) has become a
cornerstone in multimodal intelligence. However, recent studies have identified
that the information loss in the encoding process of CLIP is substantial. Such defi-
ciency significantly limits the ability of a single CLIP model to handle images rich
in visual detail. In this work, we propose a simple yet effective model-agnostic
strategy, **Diversified Multiplet Upcycling** (DMU) for CLIP. It integrates multi-
ple CLIP models that capture diversified, complementary information into a Mix-
ture of Experts (MoE) architecture. Inspired by the recently proposed Multistage
Contrastive Learning (MCL), which constructs multiple CLIP models that share
the same structure while capturing different complementary information, Diver-
sified Multiplet Upcycling efficiently fine-tunes a series of CLIP models from a
dense pre-trained CLIP checkpoint to capture different feature distributions, shar-
ing parameters except for the Feed-Forward Network (FFN). These models are
then transformed into a **CLIP-MoE** with a larger model capacity but minimal
computational overhead. Extensive experiments demonstrate the significant per-
formance of CLIP-MoE across various zero-shot retrieval, zero-shot image clas-
sification tasks, and downstream Multimodal Large Language Model (MLLM)
benchmarks by serving as a vision encoder. Furthermore, Diversified Multiplet
Upcycling enables the conversion of any dense CLIP model into CLIP-MoEs,
which can seamlessly replace CLIP in a plug-and-play manner without requiring
further adaptation in downstream frameworks. Through Diversified Multiplet Up-
cycling, we aim to provide valuable insights for future research on developing
more efficient and effective multimodal learning systems.

[[Code]](https://github.com/OpenSparseLLMs/CLIP-MoE)
[[PDF]](http://majordavidzhang.github.io/files/paper-7-clip-moe.pdf)