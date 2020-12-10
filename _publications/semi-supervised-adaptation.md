---
title: "Active learning for few shot semi-supervised domain adaptation."
collection: publications
permalink: /publication/semi-supervised-adaptation
date: '2020-10-29'
venue: '--'
paperurl: ''
citation: '<b>Naren Doraiswamy*</b>, Titir Dutta, Soma Biswas, Sawa Takamuku, Aditya Chepuri, Balasubramanian Vengatesan, Naotake Natori.<i>Under review</i>'
---

[[PDF]](https://drive.google.com/file/d/1ikgx8ZdBsUiyktPL7KtdrYuBliPIgP51/view?usp=sharing)

Abstract:Recently, semi-supervised domain adaptation approaches have shown impressive performance for domain adaptation task. They effectively utilise few labeled target samples along with the unlabeled data to account for the distribution shift across the source and target domains. Choosing few, but equal number of samples from each class in the target domain also requires significant amount of manual effort. In this work, we propose an active learning based semi-supervised domain adaptation framework by modeling both diversity and uncertainty in class-wise domain adaptation. By utilizing the k-means initialized cluster centers for picking a small pool of diverse unlabeled target samples, we then compute a novel classifier adaptation uncertainty term to select the most effective samples from this pool, which are queried to obtain their true labels from an oracle. Incorporating this in a recent semi-supervised domain adaptation backbone, we observe that the proposed technique of automatically selecting few effective unlabeled target samples can serve as a favorable alternative to the current approach of picking equal number of samples per class. We showcase the effectiveness of the proposed framework at very low labeled target data regime for three domain adaptation benchmark datasets.

