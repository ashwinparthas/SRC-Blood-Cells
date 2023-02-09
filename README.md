# Sparse Representation Classifier for Artificial Intelligent Microscopy of Blood-Based Diseases Using a Tensor Processing Unit

## Purpose
Develop a sparse representation model running on a tensor processing unit that can characterize blood samples for blood-based diseases with real-time microscopic images using fewer training examples compared to a convolutional neural network.

## Abstract

Microscopic blood cell analysis is a critical activity in the pathological analysis of blood-based diseases,meaning 
automated methods to classify cell subtypes have important medical applications. A sparse representation classifier (SRC) is a 
type of algorithm that utilizes patterns to recognize characteristics of data in a low-dimensional space, which is 
particularly useful for analyzing microscopy, and typically requires fewer data to train the model. By running this algorithm on a tensor 
processing unit, these machine learning tasks can be further optimized using this specialized hardware. The purpose of this experiment was to 
develop a sparse representation model running on a tensor processing unit that could identify and characterize 
patient blood samples for blood-based diseases during real-time microscopy using fewer data examples for training compared to a convolutional
neural network (CNN). Augmented images of blood cells from four different cell subtypes were downloaded and
two separate models, a SRC and a standard CNN, were built to compare the number of data examples needed for
accurate diagnosis. The results demonstrate that when the SRC was run for 500 training images per cell subtype,
the accuracy of the model was 85.1%, which is greater than the accuracy of 84.9% for the CNN with 1500 training
images per cell subtype, approximately three times the number of training images. This demonstrates that by using
a SRC and a tensor processing unit, the amount of blood data and thus the cost and time associated with blood-
based disease diagnosis using cell subtypes can be minimized.


## Poster

![SRC-Poster](https://user-images.githubusercontent.com/106894577/217686021-19f48b04-7c4e-4aa1-846d-ff52cdd1095d.jpg)

### PDF Version of Poster:

[SRC-Poster.pdf](https://github.com/ashwinparthas/SRC-Blood-Cells/files/10691384/SRC-Poster.pdf)


## Research Paper

[SRC-Research-Paper.pdf](https://github.com/ashwinparthas/SRC-Blood-Cells/files/10691386/SRC-Research-Paper.pdf)
