---
title: "Fast GPU-Enabled Color Normalization for Digital Pathology"
collection: publications
permalink: /publication/colornorm2019
excerpt: 'This paper presents a GPU-based color-normalization method for whole-slide gigapixel images in digital pathology.'
date: 2019-06-04
venue: '(Accepted) 26th International Conference on Systems, Signals and Image Processing, IWSSIP 2019'
image: 'MICCAI_Flowchart3.png'
width: '800'
---
Normalizing unwanted color variations due to differences in staining processes and scanner responses has been shown to aid machine learning in computational pathology. Of the several popular techniques for color normalization, structure preserving color normalization (SPCN) is well-motivated, convincingly tested, and published with its code base. However, SPCN makes occasional errors in color basis estimation leading to artifacts such as swapping the color basis vectors between stains or giving a colored tinge to the background with no tissue. We made several algorithmic improvements to remove these artifacts. Additionally, the original SPCN code is not readily usable on gigapixel whole slide images (WSIs) due to long run times, use of proprietary software platform and libraries, and its inability to automatically handle WSIs. We completely rewrote the software such that it can automatically handle images of any size in popular WSI formats. Our software utilizes GPU-acceleration and open-source libraries that are becoming ubiquitous with the advent of deep learning. We also made several other small improvements and achieved a multifold overall speedup on gigapixel images, processing $10^9$ pixels in 3 minutes. Our algorithm and software is usable right out-of-the-box by the computational pathology community.

### Citation
'<b>Anand, D</b>, Ramakrishnan, G, and Sethi A. (2019). &quot;Fast GPU-Enabled Color Normalization for Digital Pathology.&quot; <i>26th International Conference on Systems, Signals and Image Processing, IWSSIP 2019</i>. <b>(Equal contribution by Ramakrishnan G. and Anand D.)</b>.'

[Paper Link](https://arxiv.org/abs/1901.03088)
