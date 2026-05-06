# PyTorch GAN Facial Image Generation

## Overview

This project demonstrates the implementation of a Generative Adversarial Network (GAN) using PyTorch to generate synthetic facial images from the CelebA dataset.

The objective of this project was to build and evaluate a deep learning workflow capable of preprocessing image data, training a GAN model, and generating facial image outputs using adversarial learning techniques.

The project includes data preprocessing, image normalization, GAN architecture implementation, adversarial training, generated image evaluation, and visualization of synthetic outputs.

---

## Features

- Deep learning workflow using PyTorch
- CelebA facial image dataset preprocessing
- Generator and Discriminator neural networks
- Adversarial training process
- Image normalization and tensor conversion
- Generated image visualization
- Loss monitoring during training
- GAN-based synthetic image generation
- End-to-end deep learning pipeline

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Google Colab
- Jupyter Notebook

---

## Dataset Information

This project uses the CelebA facial image dataset.

The dataset contains celebrity face images used for deep learning and computer vision research.

The preprocessing workflow included:

- Image resizing
- Center cropping
- Tensor conversion
- Image normalization
- Batch preparation for training

---

## Deep Learning Workflow

### Data Acquisition

- CelebA dataset loading
- Image extraction and inspection
- Dataset validation

### Data Preprocessing

- Image resizing
- Center cropping
- Tensor conversion
- Pixel normalization
- Batch loading

### GAN Architecture

#### Generator Network

- Latent noise vector input
- Fully connected layers
- Convolutional upsampling
- Batch normalization
- Image generation

#### Discriminator Network

- Convolutional feature extraction
- Real vs fake image classification
- Binary output prediction

### Adversarial Training

- Generator optimization
- Discriminator optimization
- Loss monitoring
- Epoch-based training

### Results and Evaluation

- Generated facial image samples
- Training visualization
- Loss analysis
- GAN output evaluation

---

## Model Architecture

### Generator

The Generator network creates synthetic facial images from random latent noise vectors.

### Discriminator

The Discriminator network distinguishes between real CelebA images and generated fake images.

---

## Deep Learning Concepts Demonstrated

- Neural networks
- Convolutional layers
- Adversarial learning
- Backpropagation
- Loss optimization
- Tensor operations
- Deep learning preprocessing
- Image generation

---

## Results

The GAN model successfully demonstrated:

- Synthetic image generation
- Adversarial training workflow
- Generator and Discriminator interaction
- Deep learning image preprocessing
- GAN architecture implementation
- Image tensor handling

Although image quality was limited due to CPU-only training and limited epochs, the project successfully demonstrated the core functionality of GAN-based image generation.

---

## Project Structure

```text
PyTorch-GAN-Facial-Image-Generation/
│
├── IT621_Unit4_GAN_CelebA_CPU.ipynb
├── README.md
