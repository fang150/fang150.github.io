---
title: "Opening up the blackbox: an interpretable deep neural network-based classifier for cell-type specific enhancer predictions"
collection: publications
permalink: /publication/2016-08-01-BMC_System_Biology
excerpt: 'This paper is about designing an interpretable deep neural network for enhancer prediction task.'
date: 2016-08-01
venue: 'BMC System Biology'
paperurl: 'https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4977478/'
citation: #'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Background
======
Gene expression is mediated by specialized cis-regulatory modules (CRMs), the most prominent of which are called enhancers. Early experiments indicated that enhancers located far from the gene promoters are often responsible for mediating gene transcription. Knowing their properties, regulatory activity, and genomic targets is crucial to the functional understanding of cellular events, ranging from cellular homeostasis to differentiation. Recent genome-wide investigation of epigenomic marks has indicated that enhancer elements could be enriched for certain epigenomic marks, such as, combinatorial patterns of histone modifications.

Methods
======
Our efforts in this paper are motivated by these recent advances in epigenomic profiling methods, which have uncovered enhancer-associated chromatin features in different cell types and organisms. Specifically, in this paper, we use recent state-of-the-art Deep Learning methods and develop a deep neural network (DNN)-based architecture, called EP-DNN, to predict the presence and types of enhancers in the human genome. It uses as features, the expression levels of the histone modifications at the peaks of the functional sites as well as in its adjacent regions. We apply EP-DNN to four different cell types: H1, IMR90, HepG2, and HeLa S3. We train EP-DNN using p300 binding sites as enhancers, and TSS and random non-DHS sites as non-enhancers. We perform EP-DNN predictions to quantify the validation rate for different levels of confidence in the predictions and also perform comparisons against two state-of-the-art computational models for enhancer predictions, DEEP-ENCODE and RFECS.

Results
======
We find that EP-DNN has superior accuracy and takes less time to make predictions. Next, we develop methods to make EP-DNN interpretable by computing the importance of each input feature in the classification task. This analysis indicates that the important histone modifications were distinct for different cell types, with some overlaps, e.g., H3K27ac was important in cell type H1 but less so in HeLa S3, while H3K4me1 was relatively important in all four cell types. We finally use the feature importance analysis to reduce the number of input features needed to train the DNN, thus reducing training time, which is often the computational bottleneck in the use of a DNN.

Conclusions
======
In this paper, we developed EP-DNN, which has high accuracy of prediction, with validation rates above 90 % for the operational region of enhancer prediction for all four cell lines that we studied, outperforming DEEP-ENCODE and RFECS. Then, we developed a method to analyze a trained DNN and determine which histone modifications are important, and within that, which features proximal or distal to the enhancer site, are important.

[Download paper here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4977478/pdf/12918_2016_Article_302.pdf)
