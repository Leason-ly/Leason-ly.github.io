---
title: "RegTrieve: Reducing System-Level Regression Errors for Machine Learning Systems via Retrieval-Enhanced Ensemble"
collection: publications
permalink: /publication/RegTrieve
excerpt: 'Regression Error, Ensemble Model, Spoken QA System'
date: 2025-06-25
venue: 'Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE ’25)'
paperurl: 'http://leason-ly.github.io/files/fse25-cao-regtrieve.pdf'
citation: 'Junming Cao, Xuwen Xiang, Mingfei Cheng, Bihuan Chen, Xinyan Wang, You Lu, Chaofeng Sha, Xiaofei Xie, and Xin Peng. 2025. RegTrieve: Reducing System-Level Regression Errors for Machine Learning Systems via Retrieval-Enhanced Ensemble. Proc. ACM Softw. Eng. 2, FSE, Article FSE088 (July 2025), 23 pages. https://doi.org/10.1145/3729358'
---

Multiple machine learning (ML) models are often incorporated into real-world ML systems. However, updating an individual model in these ML systems frequently results in regression errors, where the new model performs worse than the old model for some inputs. While model-level regression errors have been widely studied, little is known about how regression errors propagate at system level. To address this gap, we propose RegTrieve, a novel retrieval-enhanced ensemble approach to reduce regression errors at both model and system level. Our evaluation across various model update scenarios shows that RegTrieve reduces system-level regression errors with almost no impact on system accuracy, outperforming all baselines by 20.43% on average.