---
layout: page
title:  "Projects"
permalink: "/projects/"
order: 3
---

### Pulse Detection from Facial Videos
Implemented algorithms for calculating the human pulse from videos of the patient's face. The repository entails 2 implementations, namely, the [movement-based](https://people.csail.mit.edu/mrub/vidmag/papers/Balakrishnan_Detecting_Pulse_from_2013_CVPR_paper.pdf) and the [colour-based](http://people.csail.mit.edu/mrub/papers/vidmag.pdf). The movement-based algorithm finds features points on the face and tracks their movements while the colour-based method amplifies the colour changes dur to blood flow and track the corresponding changes. PCA analysis is used to decompose the tracked signals and the best pulse signal is found.

Code for the Project : [Link](https://github.com/Anirudh0707/Pulse_Detection_From_Videos)

### Segmentation of Roads and Buildings from Aerial Images
Implemented 2 fully convolutional neural network for binary and semantic segmentation of aerial images. A FCN-8 network was implemented and trained on 512x512 aerial images for binary segmentation of roads. Additionally, an U-Net architecture was implemented and trained for task the task of segmenting buildings and roads from aerial images (the semantic segmentation dataset is provided [here](https://arxiv.org/pdf/1707.06879.pdf)). All implementations were carried out using the PyTorch library. 

Code for the Project : [Link](https://github.com/Anirudh0707/Roads-and-Building-Segmentation)

### A Speaker Independent Isolated Word Recognition system
An implementation for a speaker independent word recognition system that would recognize any given input word present in the system’s vocabulary. An unknown word is taken as an input. The feature extraction and matching are carried out with the help of Linear Predictive Coding and Dynamic Time Warping which are calculated for multiple time frames. The K Nearest Neighbour Rule is used as the final step for the word recognition. In order to improve the accuracy and run-time of the recognition a clustering operation is performed on the dataset.

Project Report : [Link](https://anirudh0707.github.io/assets/pdfs/NITK/Report_Speaker_Independent_Word_Recognition.pdf)

Code for the Project : [Link](https://github.com/Anirudh0707/Audio-and-Speech-Processing-Mini-Project)

Collaborator : [Rithwik Udayagiri](https://github.com/RithwikU), Shivam Kumar

### 5th Order ButterWorth Filter in LTSpice
Implementation of a ButterWorth 5th order low pass filter. This project comprises of 4 implementations, namely, a passive implementation of the low pass filter, an ideal current-source based implementation of the low pass filter, a fully differential amplifier and a GmC version of the low pass filter using the trans conductor blocks.

Code for the Project : [Link](https://github.com/Anirudh0707/Active_Filters)

Collaborator : [S Ashwin Hebbar](https://github.com/hebbarashwin)

### VLSI Laboratory Assignments and Project
Designing and implementation of a 4 Bit Arithmetic Unit. This arithmetic unit is capable of performing 3 separate operations namely multiplication, addition and subtraction. The layout for the Arithmetic Unit was created using the MAGIC software. The layout was then tested using the switch level logic simulator IRSIM.

Project Report : [Link](https://anirudh0707.github.io/assets/pdfs/NITK/16EC105_118_VLSI_Project_Report.pdf)

Code for the Project : [Link](https://github.com/manan-sharma/vlsi_lab)

Collaborator : [Manan Sharma](https://github.com/manan-sharma)