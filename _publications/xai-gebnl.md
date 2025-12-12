---
title: "Strengths and Limitations of Word-Based Task Explainability in Vision Language Models: a Case Study on Biological Sex Biases in the Medical Domain"
collection: publications
category: conferences
permalink: xai-gebnl
excerpt: ''
date: 2025-07-31
venue: 'Proceedings of the 6th Workshop on Gender Bias in Natural Language Processing (GeBNLP)'
paperurl: 'https://aclanthology.org/2025.gebnlp-1.12/'
citation: 'Lorenzo Bertolini, Valentin Comte, Victoria Ruiz-Serra, Lia Orfei, and Mario Ceresa. 2025. Strengths and Limitations of Word-Based Task Explainability in Vision Language Models: a Case Study on Biological Sex Biases in the Medical Domain. In Proceedings of the 6th Workshop on Gender Bias in Natural Language Processing (GeBNLP), pages 111–123, Vienna, Austria. Association for Computational Linguistics.'
---

Vision-language models (VLMs) can achieve high accuracy in medical applications but can retain demographic biases from training data. While multiple works have identified the presence of these biases in many VLMs, it remains unclear how strong their impact at the inference level is. In this work, we study how well a task-level explainability method based on linear combinations of words can detect multiple types of biases, with a focus on medical image classification. By manipulating the training datasets with demographic and non-demographic biases, we show how the adopted approach can detect explicitly encoded biases but fails with implicitly encoded ones, particularly biological sex. Our results suggest that such a failure likely stems from misalignment between sex-describing features in image versus text modalities. Our findings highlight limitations in the evaluated explainability method for detecting implicit biases in medical VLMs.
