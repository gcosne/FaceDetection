# Face Detection using Haar feature-based cascade classifiers

The objective of this project is to develop a prototype of face detection algorithm.

Object Detection using **Haar feature-based cascade classifiers** is an effective object detection method proposed by **Paul Viola and Michael Jones** in their
**[paper](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf)**: "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

Here we will work with **face detection**. Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier. Then we need to extract features from it. For this, **Haar features** shown in the below image under Masks are used. They are just like our convolutional kernel. Each feature is a single value obtained by subtracting sum of pixels under the white rectangle from sum of pixels under the black rectangle.

<img src="https://drive.google.com/uc?export=view&id=1NElqPpQTJe_QFFIyHr472i5EWNW6hvz1" width=95%>
---

Code and results can be found on google colab [here](https://colab.research.google.com/drive/1dUWPBc9LCO2S3MGV4JdnWsViomHciYr2)  
