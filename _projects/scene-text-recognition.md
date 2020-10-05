---
title: "Scene Text Recognition"
excerpt: "Detect, extract, and recognise texts in advertisement pictures. The recognized text will be feed to
advertisement conversion prediction machine learning models. <br/><img src='/images/scene_word.png' width='500'>"
collection: projects
---

To recognise texts from images, i.e., advertisements, traffic signals, we decompose the Scene Text Recognition to two
stages:
* Scene Text Detection (STD). Detect and extract the texts with Progressive Scale Expansion Network (PSENet).
[See paper here](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Shape_Robust_Text_Detection_With_Progressive_Scale_Expansion_Network_CVPR_2019_paper.pdf).
PSENet generates the different scale of kernels for each text instance, and gradually expands the minimal scale kernel
to the text instance with arbitrary shape.
<br/><img src='/images/psenet.png' width='500'>
* Optical Character Recognition (OCR). Recognize the extracted texts with Convolutional Recurrent Neural Network (CRNN).
[see paper here](https://arxiv.org/abs/1507.05717). CRNN extracts Convolutional features with CNN and feed the feature 
sequence to a bidirectional LSTM. It can handle different lengths of texts and does not require character- or word-level
annotation in training with the help of CTC loss. [More info for CTC loss](https://www.cs.toronto.edu/~graves/icml_2006.pdf).
<br/><img src='/images/crnn.png' width='500'>

Demo results:


