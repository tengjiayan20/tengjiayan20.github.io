---
title: "Discovering New Intents with Deep Aligned Clustering"
collection: publications
permalink: /publication/DeepAligned
excerpt: 'Discovering new intents is a crucial task in dialogue systems. Most existing methods are limited in transferring the prior knowledge from known intents to new intents. They also have difficulties in providing high-quality supervised signals to learn clustering-friendly features for grouping unlabeled intents. In this work, we propose an effective method, Deep Aligned Clustering, to discover new intents with the aid of the limited known intent data. Firstly, we leverage a few labeled known intent samples as prior knowledge to pre-train the model. Then, we perform k-means to produce cluster assignments as pseudo-labels. Moreover, we propose an alignment strategy to tackle the label inconsistency problem during clustering assignments. Finally, we learn the intent representations under the supervision of the aligned pseudo-labels. With an unknown number of new intents, we predict the number of intent categories by eliminating low-confidence intent-wise clusters. Extensive experiments on two benchmark datasets show that our method is more robust and achieves substantial improvements over the state-of-the-art methods. The codes are released at https://github.com/thuiar/DeepAlignedClustering.'
date: 2021-5-18
venue: 'AAAI'
paperurl: '/files/AAAI21-DeepAligned/DeepAligned.pdf'


---
Discovering new intents is a crucial task in dialogue systems. Most existing methods are limited in transferring the prior knowledge from known intents to new intents. They also have difficulties in providing high-quality supervised signals to learn clustering-friendly features for grouping unlabeled intents. In this work, we propose an effective method, Deep Aligned Clustering, to discover new intents with the aid of the limited known intent data. Firstly, we leverage a few labeled known intent samples as prior knowledge to pre-train the model. Then, we perform k-means to produce cluster assignments as pseudo-labels. Moreover, we propose an alignment strategy to tackle the label inconsistency problem during clustering assignments. Finally, we learn the intent representations under the supervision of the aligned pseudo-labels. With an unknown number of new intents, we predict the number of intent categories by eliminating low-confidence intent-wise clusters. Extensive experiments on two benchmark datasets show that our method is more robust and achieves substantial improvements over the state-of-the-art methods. The codes are released at https://github.com/thuiar/DeepAlignedClustering.

[[pdf]](/files/AAAI21-DeepAligned/DeepAligned.pdf)
[[code]](https://github.com/thuiar/DeepAligned-Clustering)
[[bib]](/files/AAAI21-DeepAligned/DeepAligned.bib)