---
permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
---

Automatic Speech Reognition and Keyword Spotting in Continous Speech
---
### Advisor : Dr. Prasanta Kumar Ghosh<br/>
Some of the research statements we seek to address in this project, include:-
* Can we do reliable speech recognition on noisy multilingual data?
* Can we introduce an efficent keyword-spotting system which not only gives accurate 
results but also takes small execution time, suitable for real-time applications?
* Can we overcome the large training data restrictions usually required for producing reliable keyword spotting results?

Classification between spontaneous speech and rhythmic speech using talker's head gestures
---
### Advisor : Dr. Prasanta Kumar Ghosh<br/>
* In this work, we show that head gestures while reciting poems(rhythmic speech) have more periodic structure than while reciting spontaneous speech.
* We use a dataset of 10 subjects reciting 20 poems and a seperate set of 20 subjects narrating 5 stories. We measure the head gestures of the subjects using an Optitrack setup. We calculate three degrees of rotation and three degrees of translation of the head gestures and use it as a six dimension feature vector.
* To show the periodicity of head gestures, we use a measure based on the autocorrelation of the input signal. Using the information of peaks in the autocorrelation of an input signal, we achieve a highest periodicity of 0.489 in case of poems and a highest periodicity of 0.347 in case of stories.
* We further perform a classification task to classify between spontaneous speech and rhythmic speech. We show that head gesture features perform comparably well to the acoustic features(MFCCs), with accuracies 89% and 96% approximately. We further show that combination of head gestures and acoustic features outperform the acoustic features.

Online [automatic speech recognition](http://spire.ee.iisc.ac.in/asr-recorder/asr_template/index.php) and [Keyword Spotting](http://spire.ee.iisc.ac.in/asr-recorder/kws_template/) Interface
---
### Advisor : Dr. Prasanta Kumar Ghosh<br/>
* The automatic speech recognition interface outputs the set of words spoken in a live recorded file or in an uploaded audio file.
* The keyword spottting interface outputs at what times, a list of keywords are detected in an audio file.
* Deep neural networks trained on several datasets are used for this purpose.
* The deep neural network outputting the least word error rate for each dataset is used.

Copy-Move Forgery Detection Using ASIFT
---
### Advisor : Prof. Ram Kumar Karsh<br/>
* Copy Move forgeries in images represent forged regions which are duplicates of other regions from the same
image. This is done so as to alter the original information in the image.
* Compared affine transfored copy-move forgeries in images using Scale Invariant Feature Transform(SIFT)
and affine SIFT(ASIFT).
* Artficially affine transformed regions were introduced on existing images from the CoMoFoD database.
These images were used for training and testing. AISFT was later shown to outperform SIFT in the Copy-Move Forgery Task.
[Please find the Project Description here](https://dasanurag.github.io/publications/)

Image Splicing Detection Using Gaussian Blur
---
### Advisor : Dr. Pravin Kumar Bora, Prof. Ram Kumar Karsh<br/>
* Image Splicing involves introduction of artificial regions in an image so as to alter its original content.
Potential image splicing was evaluated on a set of natural images.
* Standard deviation of Gaussian blur for different blocks across the image were compared initially for
detecting forgeries.
* Ringing effects obtained after deblurring were used to check the authenticity of images.
[Please find the Project Description here](https://dasanurag.github.io/publications/)

Classification of masses in mammograms into benign(normal) and malignant(cancerous)
---
### Advisor : Dr. Jayasree Chakraborty
* Given a set of mammogram images, we tried to classify normal masses(benign) from potentially cancerous
masses(malignant).
* An artificial neural network was used for the classification. 
* Features were extracted on images from mini-MIAS dataset.
