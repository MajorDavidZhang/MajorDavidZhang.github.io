---
title: "Learning generative RNN-ODE for collaborative time-series and event sequence forecasting"
collection: publications
permalink: /publication/paper-4-rnnode
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-06-10
venue: 'TKDE'
authors:
#paperurl: 'http://majordavidzhang.github.io/files/paper-1-learning-the-unlearned.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors: Longyuan Li, Junchi Yan, Yunhao Zhang, **Jihai Zhang**, Jie Bao, Yaohui Jin, Xiaokang Yang

**Abstract:** 
Time-series and event sequences are widely collected data types in many applications. Analysis and prediction of them play an important role in the decision-making process. A major limitation of previous methods is that they either focus on continuous time series or discrete events, rather than the combination of the two types of data, ignoring the correlation between them. In this paper, we consider the problem of joint modeling and forecasting of time-series and event sequence. However, the two types of data provide complementary information for the temporal dynamics, emphasizing the necessity of jointly modeling the both. We propose the RNN-ODE collaborative model for joint modeling and forecasting of heterogeneous time-series and event sequence data, which combines several. To learn complex correlations across heterogeneous sequences, we devise a tailored encoder to combine the advances in deep point processes models and variational recurrent neural networks. To predict the probability of event occurrence at arbitrary continuous-time horizon, we leverage the mathematical foundation of novel Neural Ordinary Differential Equations (NODE). It is proved on multiple simulation and real data sets that compared with existing methods, integrated modeling and prediction can effectively extract features and improve the prediction performance of time series and event sequences.

[[PDF]](http://majordavidzhang.github.io/files/paper-4-rnnode.pdf)