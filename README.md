# Crop Leaf Image Super-Resolution using Conditional GANs

Deep learning project focused on reconstructing high-resolution crop leaf images from severely degraded low-resolution inputs using Conditional Generative Adversarial Networks (cGANs).

## Overview

This project tackles a 4× image super-resolution task in an agricultural computer vision setting. The objective is to reconstruct high-fidelity 128×128 crop leaf images from degraded 32×32 inputs while preserving biologically important textures such as leaf veins, chlorosis patterns, and necrotic lesions.

The model was developed under strict constraints requiring training from randomly initialized weights without relying on pre-trained super-resolution networks.

## Dataset

The dataset consists of paired low-resolution and high-resolution crop leaf images.

* Low-Resolution (LR): 32×32 RGB images
* High-Resolution (HR): 128×128 RGB images
* Training Samples: 1,642 image pairs
* Test Samples: 495 images

**Task:** Image Super-Resolution (4× Upscaling)

## Methodology

* Image preprocessing and augmentation
* Conditional GAN (cGAN) architecture
* Adversarial training
* Pixel-wise reconstruction loss
* Perceptual loss using VGG-19 feature representations
* Model evaluation using Mean Absolute Error (MAE)

## Architecture

* Generator Network
* Discriminator Network
* Adversarial Loss
* Perceptual Loss
* Reconstruction Loss

The model learns to simultaneously denoise and upscale low-resolution images while maintaining fidelity to the original biological structures.

## Results

Predictions were generated as 128×128 RGB images and evaluated using Mean Absolute Error (MAE) between reconstructed and ground-truth pixel values.

## Technologies

* Python
* PyTorch
* NumPy
* OpenCV
* Matplotlib
* torchvision

## Skills Demonstrated

* Generative Adversarial Networks (GANs)
* Computer Vision
* Image Super-Resolution
* Deep Learning
* PyTorch
* Custom Neural Network Design
* Model Training and Evaluation

```
```
