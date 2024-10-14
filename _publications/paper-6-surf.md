---
title: "SURf: Teaching Large Vision-Language Models to Selectively Utilize Retrieved Information"
collection: publications
permalink: /publication/paper-6-surf
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-09-21
venue: 'EMNLP'
authors:
#paperurl: 'http://majordavidzhang.github.io/files/paper-1-learning-the-unlearned.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors: Jiashuo Sun, **Jihai Zhang**, Yucheng Zhou, Zhaochen Su, Xiaoye Qu, Yu Cheng

**Abstract:** 
Large Vision-Language Models (LVLMs) have become pivotal at the intersection of computer vision and natural language processing. However, the full potential of LVLMs Retrieval-Augmented Generation (RAG) capabilities remains underutilized. Existing works either focus solely on the text modality or are limited to specific tasks. Moreover, most LVLMs struggle to selectively utilize retrieved information and are sensitive to irrelevant or misleading references. To address these challenges, we propose a self-refinement framework designed to teach LVLMs to Selectively Utilize Retrieved Information (SURf). Specifically, when given questions that are incorrectly answered by the LVLM backbone, we obtain references that help correct the answers (positive references) and those that do not (negative references). We then fine-tune the LVLM backbone using a combination of these positive and negative references. Our experiments across three tasks and seven datasets demonstrate that our framework significantly enhances LVLMs ability to effectively utilize retrieved multimodal references and improves their robustness against irrelevant or misleading information.

[[Code]](https://github.com/GasolSun36/SURf)
[[PDF]](http://majordavidzhang.github.io/files/paper-6-surf.pdf)