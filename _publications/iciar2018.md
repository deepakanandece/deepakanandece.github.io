---
title: "Classification of breast cancer histology using deep learning"
collection: publications
permalink: /publication/iciar2018
excerpt: ' In this paper, we propose a deep learning-based method for classification of H&E stained breast tissue images released for BACH challenge by deep learning and provide an efficient patch-sampling strategy.'
date: 2018-06-01
venue: 'International Conference Image Analysis and Recognition, Springer'
---
In this paper, we propose a deep learning-based method for classification of H&E stained breast tissue images released for BACH challenge by fine-tuning Inception-v3 convolutional neural network (CNN). These images are to be classified into four classes – (i) normal tissue, (ii) benign lesion, (iii) in situ carcinoma and (iv) invasive carcinoma. Our strategy is to extract patches based on nuclear density and rejecting patches that are not rich in nuclei, e.g. from non-epithelial regions. This allowed us to discard uninformative regions of the images as compared to random or grid sampling, because visual signs of tumors are most evident in the epithelium. Every patch with high nuclear density in an image is classified in one of the four above mentioned categories. The class of the entire image is determined using majority voting over the nuclear classes. We obtained an average accuracy of 85% over the four classes and 93% for non-cancer (i.e. normal or benign) vs. malignant (in situ or invasive carcinoma), which significantly improves upon a previous benchmark.

### Citation
'Golatkar, A., <b>Anand, D.</b>, and Sethi, A. (2018). &quot;Classification of breast cancer histology using deep learning.&quot; <i>International Conference Image Analysis and Recognition</i>. (pp. 837-844). Springer, Cham.'

[Paper Link](https://link.springer.com/chapter/10.1007/978-3-319-93000-8_95)
