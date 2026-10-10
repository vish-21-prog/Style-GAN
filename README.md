# StyleGAN-Inspired CIFAR-10 Image Generation Using TensorFlow

## Project Overview

This project implements a compact StyleGAN-inspired generative adversarial network using TensorFlow and Keras. The model learns to generate 32 × 32 RGB images using the CIFAR-10 dataset.

## Key Features

- Mapping network that transforms latent vectors into style vectors.
- Style-based image synthesis network.
- Generator and discriminator networks.
- Adversarial training using logistic GAN loss.
- Style mixing and latent interpolation.
- Visualization of generated images.

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- CIFAR-10 dataset

## Project Structure

- `StyleGAN_CIFAR10_TensorFlow.ipynb` — model implementation, training, and visualization.
- `outputs/` — generated image samples, when saved.

## How to Run

1. Install Python and the required libraries.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Run the cells in order.
4. Train the model and view the generated images.

## Dataset

The project uses CIFAR-10, a dataset containing 32 × 32 color images across 10 classes.

## Note

This is a StyleGAN-inspired implementation for educational and experimental purposes. It is not a full reproduction of the original StyleGAN architecture.
