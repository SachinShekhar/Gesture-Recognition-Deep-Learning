# Gesture Recognition

To build a neural network to recognise five different gestures to control a smart TV (with webcam) without using a remote. The gestures are as follows:

1. Thumbs up: Increase the volume
2. Thumbs down: Decrease the volume
3. Left swipe: 'Jump' backwards 10 seconds
4. Right swipe: 'Jump' forward 10 seconds
5. Stop: Pause the movie

## Table of Contents
* [Dataset Info](#dataset-information)
* [Libraries Used](#libraries-used)
* [Hardware Accelerator Used](#hardware-accelerator-used)
* [Acknowledgements](#acknowledgements)
* [Project Collaborators](#project-collaborators)

## Dataset Information

The training data consists of several hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames. These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.

![Training Dataset Sample](./Dataset%20Sample.png)

## Libraries Used

  - Tensorflow 2.11.0
  - OpenCV 4.7.0
  - Matplotlib 2.5.3

## Hardware Accelerator Used

Nvidia A100 Tensor Core GPU

  - CUDA Version: 12.0
  - Driver: NVIDIA-SMI 525.85.12
  - GPU RAM: 40 GB

## Acknowledgements
We would like to express our deepest appreciation to Rui Hou, Chen Chen & Mubarak Shah for their research paper: [An End-to-end 3D Convolutional Neural Network for Action Detection and Segmentation in Videos](https://arxiv.org/pdf/1712.01111.pdf).

## Project Collaborators

  - Sachin Shekhar
  - Ashish Kulkarni
  - Tejashwini Junjoor
