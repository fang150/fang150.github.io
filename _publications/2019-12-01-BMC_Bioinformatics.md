---
title: "Aikyatan: mapping distal regulatory elements using convolutional learning on gpu."
collection: publications
permalink: /publication/2019-12-01-BMC_Bioinformatics
excerpt: 'This paper is about designing the convolutional neural network to utilize the shift-invariant property of the histone modification signals to increase the regulatory elements prediction rate.'
date: 2019-12-01
venue: 'BMC Bioinformatics'
paperurl: 'https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3049-1'
citation: #'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Background
======
The data deluge can leverage sophisticated ML techniques for functionally annotating the regulatory non-coding genome. The challenge lies in selecting the appropriate classifier for the specific functional annotation problem, within the bounds of the hardware constraints and the model’s complexity. In our system AIKYATAN, we annotate distal epigenomic regulatory sites, e.g., enhancers. Specifically, we develop a binary classifier that classifies genome sequences as distal regulatory regions or not, given their histone modifications’ combinatorial signatures. This problem is challenging because the regulatory regions are distal to the genes, with diverse signatures across classes (e.g., enhancers and insulators) and even within each class (e.g., different enhancer sub-classes).

Results
======
We develop a suite of ML models, under the banner AIKYATAN, including SVM models, random forest variants, and deep learning architectures, for distal regulatory element (DRE) detection. We demonstrate, with strong empirical evidence, deep learning approaches have a computational advantage. Plus, convolutional neural networks (CNN) provide the best-in-class accuracy, superior to the vanilla variant. With the human embryonic cell line H1, CNN achieves an accuracy of 97.9% and an order of magnitude lower runtime than the kernel SVM. Running on a GPU, the training time is sped up 21x and 30x (over CPU) for DNN and CNN, respectively. Finally, our CNN model enjoys superior prediction performance vis-‘a-vis the competition. Specifically, AIKYATAN-CNN achieved 40% higher validation rate versus CSIANN and the same accuracy as RFECS.

Conclusions
======
Our exhaustive experiments using an array of ML tools validate the need for a model that is not only expressive but can scale with increasing data volumes and diversity. In addition, a subset of these datasets have image-like properties and benefit from spatial pooling of features. Our AIKYATAN suite leverages diverse epigenomic datasets that can then be modeled using CNNs with optimized activation and pooling functions. The goal is to capture the salient features of the integrated epigenomic datasets for deciphering the distal (non-coding) regulatory elements, which have been found to be associated with functional variants. Our source code will be made publicly available at: https://bitbucket.org/cellsandmachines/aikyatan.
[Download paper here](https://bmcbioinformatics.biomedcentral.com/track/pdf/10.1186/s12859-019-3049-1)

