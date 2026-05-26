---
title: "Utilizing 2D-region-based CNNs for automatic dendritic spine detection in 3D live cell imaging"
collection: publications
category: manuscripts
permalink: /publication/2023-11-scientific-reports-spine-detection
excerpt: 'We developed an efficient deep learning pipeline for automated dendritic spine detection in volumetric 2-photon imaging data.'
date: 2023-11-22
venue: 'Scientific Reports'
citation: 'FW Vogel, S Alipek, J-B Eppler, P Osuna-Vargas, J Triesch, D Bissen, A Acker-Palmer, S Rumpel, & M Kaschube. (2023). &quot;Utilizing 2D-region-based CNNs for automatic dendritic spine detection in 3D live cell imaging.&quot; <i>Scientific Reports</i>, 13, 20497. https://doi.org/10.1038/s41598-023-47070-3'
---

## Abstract

Dendritic spines are considered a morphological proxy for excitatory synapses, rendering them a target of many different lines of research. Over recent years, it has become possible to simultaneously image large numbers of dendritic spines in 3D volumes of neural tissue. In contrast, currently no automated method for 3D spine detection exists that comes close to the detection performance reached by human experts. However, exploiting such datasets requires new tools for the fully automated detection and analysis of large numbers of spines. Here, we developed an efficient analysis pipeline to detect large numbers of dendritic spines in volumetric fluorescence imaging data acquired by two-photon imaging in vivo. The core of our pipeline is a deep convolutional neural network that was pretrained on a general-purpose image library and then optimized on the spine detection task. This transfer learning approach is data efficient while achieving a high detection precision. To train and validate the model we generated a labeled dataset using five human expert annotators to account for the variability in human spine detection. The pipeline enables fully automated dendritic spine detection reaching a performance slightly below that of the human experts. Our method for spine detection is fast, accurate and robust, and thus well suited for large-scale datasets with thousands of spines. The code is easily applicable to new datasets, achieving high detection performance, even without any retraining or adjustment of model parameters.

*Keywords: dendritic spines; deep learning; convolutional neural networks; 2-photon imaging; automated detection; transfer learning*

[Read on Scientific Reports](https://doi.org/10.1038/s41598-023-47070-3) 
