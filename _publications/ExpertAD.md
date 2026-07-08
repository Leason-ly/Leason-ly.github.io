---
title: "ExpertAD: Enhancing Autonomous Driving Systems with Mixture of Experts"
collection: publications
permalink: /publication/ExpertAD
excerpt: 'Automated Driving System'
date: 2026-03-14
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence'
# slidesurl: 'http://academicpages.github.io/files/DiaVio_slide-chen.pptx'
paperurl: 'http://leason-ly.github.io/files/aaai26-jiang-expertad.pdf'
citation: 'Jiang, H., Huang, X., Lu, Y., Wang, D., Cao, Y., Sha, C., … Peng, X. (2026). ExpertAD: Enhancing Autonomous Driving Systems with Mixture of Experts. Proceedings of the AAAI Conference on Artificial Intelligence, 40(7), 5378–5387. https://doi.org/10.1609/aaai.v40i7.37454'
---

Recent advancements in end-to-end autonomous driving systems (ADSs) underscore their potential for perception and planning capabilities. However, challenges remain. Complex driving scenarios contain rich semantic information, yet ambiguous or noisy semantics can compromise decision reliability, while interference between multiple driving tasks may hinder optimal planning. Furthermore, prolonged inference latency slows decision-making, increasing the risk of unsafe driving behaviors. To address these challenges, we propose ExpertAD, a novel framework that enhances the performance of ADS with Mixture of Experts (MoE) architecture. We introduce a Perception Adapter (PA) to amplify task-critical features, ensuring contextually relevant scene understanding, and a Mixture of Sparse Experts (MoSE) to minimize task interference during prediction, allowing for effective and efficient planning. Our experiments show that ExpertAD reduces average collision rates by up to 20% and inference latency by 25% compared to prior methods. We further evaluate its multi-skill planning capabilities in rare scenarios (e.g., accidents, yielding to emergency vehicles) and demonstrate strong generalization to unseen urban environments. Additionally, we present a case study that illustrates its decision-making process in complex driving scenarios. Codes are included in the supplementary material.