---
title: Multi-Domain Text Summarization Evaluation
date: 2023-12-06
external_link: https://aclanthology.org/2023.gem-1.20.pdf
tags:
  - Automatic Text Summarization
  - LLM Evaluation
  - Language Generation
---

Existing literature does not give much guidance on how to build the best possible multi-domain summarization model from existing components. We present an extensive evaluation of popular pre-trained models on a wide range of datasets to inform the selection of both the model and the training data for robust summarization across several domains. We find that fine-tuned BART performs better than T5 and PEGASUS, both on in-domain and outof-domain data, regardless of the dataset used for fine-tuning. While BART has the best performance, it does vary considerably across domains. A multi-domain summarizer that works well for all domains can be built by simply fine-tuning on diverse domains. It even performs better than an in-domain summarizer, even when using fewer total training examples. While the success of such a multi-domain summarization model is clear through automatic evaluation, by conducting a human evaluation, we find that there are variations that can not be captured by any of the automatic evaluation metrics and thus not reflected in standard leaderboards. Furthermore, we find that conducting reliable human evaluation can be complex as well. Even experienced summarization researchers can be inconsistent with one another in their assessment of the quality of a summary, and also with themselves when reannotating the same summary. The findings of our study are two-fold. First, BART fine-tuned on heterogeneous domains is a great multidomain summarizer for practical purposes. At the same time, we need to re-examine not just automatic evaluation metrics but also human evaluation methods to responsibly measure progress in summarization.

<!--more-->
