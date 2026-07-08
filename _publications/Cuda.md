---
title: "Understanding Performance Problems in CUDA Programs"
collection: publications
permalink: /publication/Cuda
excerpt: 'Regression Error, Ensemble Model, Spoken QA System'
date: 2025-06-25
venue: 'Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE ’26)'
paperurl: 'http://leason-ly.github.io/files/fse25-cao-regtrieve.pdf'
citation: 'Yuyang Bi, Junming Cao, You Lu, Bihuan Chen, Tianwei Gan, Dingji Wang, and Xin Peng. 2026. Understanding Performance Problems in CUDA Programs. Proc. ACM Softw. Eng. 3, FSE, Article FSE016 (July 2026), 22 pages. https://doi.org/10.1145/3797143'
---

With the wide adoption of GPUs, CUDA programming has become essential for leveraging GPU parallelism. However, its complex programming model poses challenges in performance optimization. Consequently, CUDA programs often suffer from performance problems. In that sense, it is crucial to understand the performance problems specific to CUDA programming. Unfortunately, no systematic study has been conducted in literature. 
To bridge this gap, we conduct the first systematic study to 1) characterize the symptoms and root causes of 216 performance problems collected from 55 StackOverflow posts and 122 NVIDIA forum posts, and 2) measure the speedup of fixing performance problems, and assess the capability of existing performance analysis methods in identifying performance problems, using a dataset of 69 reproduced performance problems. Our findings provide practical guidance for developers, and opportunities for researchers to advance performance analysis.