---
title: "Improving Semi-Supervised domain adaptation using effective target selection and semantics."
collection: publications
permalink: /publication/semi-supervised-adaptation
date: '2020-10-29'
venue: 'CVPR L2ID workshop 2021'
paperurl: ''
citation: 'Anurag Singh*, <b>Naren Doraiswamy</b>*, Sawa Takamuku, Megh Bhalerao, Titir Dutta, Soma Biswas, Aditya Chepuri, Balasubramanian Vengatesan, Naotake Natori.<i>CVPR L2ID Workshop 2021.</i>'
---

[[PDF]](https://drive.google.com/file/d/1nbiVfV-X4OyIoNulIo_6l-Wy0OAM1X_K/view)

Abstract:Recently, semi-supervised domain adaptation (SSDA) approaches have shown impressive performance for the domain adaptation task. They effectively utilize few labeled target samples along with the unlabeled data to account for the distribution shift across the source and target domains. In this work, we make three-fold contributions, concentrating on the role of target samples and semantics for the SSDA task. First, we observe that choosing a few, but an equal number of labeled samples from each class in the target domain requires a significant amount of manual effort. To address this, we propose an active learning based framework by modeling both the sample diversity and the classifier uncertainty. By utilizing k-means initialized cluster centers for picking a small pool of diverse unlabeled target samples, we compute a novel classifier adaptation
uncertainty term to select the most effective samples from this pool, which are queried to obtain their true labels from an oracle. Second, we propose to weigh the hard target samples more, without explicitly using their predicted, possibly incorrect labels, which guides the adaptation process.Third, we note that irrespective of the domain shift, the semantics of the classes remain unchanged, so they can be effectively utilized for this task. We show that initializing the class-representations or prototypes with the class
semantics helps in bridging the domain gap significantly. These along with adversarially learnt entropy objective results in a novel framework, termed STar (Select TARgets), which sets a new state-of-the-art for the SSDA task.
