# Generative Models

This repository contains implementations of several generative models, including VAE, GAN, Conditional GAN, Diffusion Models, and Conditional Diffusion Models.

## Results

<h3 align="center">Fashion MNIST</h3>
<p align="center">
  <img src="images/fashion_mnist.png" width="800">
</p>

<h3 align="center">VAE</h3>
<p align="center">
  <img src="images/vae_1.png" width="800">
  <img src="images/vae_2.png" width="800">
</p>

<h3 align="center">GAN</h3>
<p align="center">
  <img src="images/gan_1.png" width="800">
  <img src="images/gan_2.png" width="800">
</p>

<h3 align="center">Conditional GAN</h3>
<p align="center">
  <img src="images/cgan_1.png" width="800">
  <img src="images/cgan_2.png" width="800">
</p>

<h3 align="center">Diffusion Model</h3>
<p align="center">
  <img src="images/ddpm_1.png" width="800">
  <img src="images/ddpm_2.png" width="800">
</p>

<h3 align="center">Conditional Diffusion Model</h3>
<p align="center">
  <img src="images/cddpm_1.png" width="800">
  <img src="images/cddpm_2.png" width="800">
</p>


## Requirements

To run the scripts in this repository, you will need to have the following dependencies installed:

- Python 3
- PyTorch
- NumPy
- Matplotlib
- tqdm


## Models

### VAE

The Variational Autoencoder (VAE) is a generative model that learns a latent representation of the input data and uses it to generate new data samples. In this implementation, the VAE is trainedon the MNIST dataset to generate handwritten digits.

### GAN

The Generative Adversarial Network (GAN) is another popular generative model that consists of a generator and a discriminator network. The generator learns to generate realistic data samples, while the discriminator learns to distinguish between real and fake samples. In this implementation, the GAN is trained on the CIFAR-10 dataset to generate color images of various objects.

### Conditional GAN

The Conditional Generative Adversarial Network (cGAN) extends the GAN by conditioning the generation process on additional information, such as class labels. This allows the user to generate images from a specific class or with specific attributes. In this implementation, the cGAN is trained on the MNIST dataset to generate handwritten digits from specific classes.

### Diffusion Models

Diffusion models are a class of generative models that learn to simulate the diffusion process of a stochastic system. In this implementation, the Diffusion Models are trained on the CelebA dataset to generate realistic images of faces.

### Conditional Diffusion Models

The Conditional Diffusion Models (cDM) extend the Diffusion Models by conditioning the generation process on additional information, such as class labels or attributes. In this implementation, the cDM is trained on the CelebA dataset to generate realistic images of faces with specific attributes, such as eye color or hair style.

## Results
