---
title: "Less Is More: Vision Representation Compression for Efficient Video Generation with Large Language Models"
collection: publications
permalink: /publication/paper-9-vrc
date: 2026-01-01
venue: 'AAAI'
authors:
---
Authors: Yucheng Zhou<sup>*</sup>, **Jihai Zhang**<sup>*</sup>, Guanjie Chen, Jianbing Shen<sup>&dagger;</sup>, Yu Cheng<sup>&dagger;</sup>

<sup>*</sup> Equal contribution. <sup>&dagger;</sup> Corresponding authors.

**Abstract:**
Video generation using Large Language Models (LLMs) has shown promising potential, effectively leveraging the extensive LLM infrastructure to provide a unified framework for multimodal understanding and content generation. However, these methods face critical challenges, i.e., token redundancy and inefficiencies arising from long sequences, which constrain their performance and efficiency compared to diffusion-based approaches. In this study, we investigate the impact of token redundancy in LLM-based video generation by information-theoretic analysis and propose Vision Representation Compression (VRC), a novel framework designed to achieve More in both performance and efficiency with Less video token representations. VRC introduces learnable representation compressor and decompressor to compress video token representations, enabling autoregressive next-sequence prediction in a compact latent space. Our approach reduces redundancy, shortens token sequences, and improves model's ability to capture underlying video structures. Our experiments demonstrate that VRC reduces token sequence lengths by a factor of 4, achieving more than 9-14x acceleration in inference while maintaining performance comparable to state-of-the-art video generation models. VRC not only accelerates the inference but also significantly reduces memory requirements during both model training and inference.

[[PDF]](/files/paper-9-vrc.pdf)
