---
title: "Deep Open Intent Classification with Adaptive Decision Boundary"
collection: publications
permalink: /publication/ADB
excerpt: 'Open intent classification is a challenging task in dialogue systems. On the one hand, it should ensure the quality of known intent identification. On the other hand, it needs to detect the open (unknown) intent without prior knowledge. Current models are limited in finding the appropriate decision boundary to balance the performances of both known intents and the open intent. In this paper, we propose a postprocessing method to learn the adaptive decision boundary (ADB) for  open intent classification. We first utilize the labeled known intent samples to pre-train the model. Then, we automatically learn the adaptive spherical decision boundary for each known class with the aid of well-trained features. Specifically, we propose a new loss function to balance both the empirical risk and the open space risk. Our method does not need open intent samples and is free from modifying the model architecture. Moreover, our approach is surprisingly insensitive with less labeled data and fewer known intents. Extensive experiments on three benchmark datasets show that our method yields significant improvements compared with the state-of-the-art methods. The codes are released at https://github.com/thuiar/Adaptive-Decision-Boundary.'

date: 2021-5-18
venue: 'AAAI'
paperurl: '/files/AAAI21-ADB/ADB.pdf'


---
Open intent classification is a challenging task in dialogue systems. On the one hand, it should ensure the quality of known intent identification. On the other hand, it needs to detect the open (unknown) intent without prior knowledge. Current models are limited in finding the appropriate decision boundary to balance the performances of both known intents and the open intent. In this paper, we propose a postprocessing method to learn the adaptive decision boundary (ADB) for  open intent classification. We first utilize the labeled known intent samples to pre-train the model. Then, we automatically learn the adaptive spherical decision boundary for each known class with the aid of well-trained features. Specifically, we propose a new loss function to balance both the empirical risk and the open space risk. Our method does not need open intent samples and is free from modifying the model architecture. Moreover, our approach is surprisingly insensitive with less labeled data and fewer known intents. Extensive experiments on three benchmark datasets show that our method yields significant improvements compared with the state-of-the-art methods. The codes are released at https://github.com/thuiar/Adaptive-Decision-Boundary.


[[pdf]](/files/AAAI21-ADB/ADB.pdf)
[[code]](https://github.com/thuiar/Adaptive-Decision-Boundary)
[[bib]](/files/AAAI21-ADB/ADB.bib)