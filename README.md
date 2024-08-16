# 🎨 Deep Generative Models in PyTorch

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter Notebook">
</p>

Welcome to the **Diffusion-GAN-VAE-PyTorch** repository! This project contains PyTorch implementations (from scratch) of various deep generative models, including Variational Autoencoders (VAE), Generative Adversarial Networks (GAN), Conditional GANs, Diffusion Models, and Conditional Diffusion Models. Explore the power of these models through code and stunning visualizations!

---

## 🌠 Results

### Fashion MNIST
<p align="center">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/fashion_mnist.png" width="600" alt="Fashion MNIST Results">
</p>

### Conditional Diffusion Model
<p align="center">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/cddpm_1.png" width="600" alt="Conditional Diffusion Model Results 1">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/cddpm_2.png" width="600" alt="Conditional Diffusion Model Results 2">
</p>

### Diffusion Model
<p align="center">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/ddpm_1.png" width="600" alt="Diffusion Model Results 1">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/ddpm_2.png" width="600" alt="Diffusion Model Results 2">
</p>

### Conditional GAN
<p align="center">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/cgan.png" width="600" alt="Conditional GAN Results">
</p>

### GAN
<p align="center">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/gan_1.png" width="600" alt="GAN Results 1">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/gan_2.png" width="600" alt="GAN Results 2">
</p>

### VAE
<p align="center">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/vae_1.png" width="600" alt="VAE Results 1">
  <img src="https://raw.githubusercontent.com/deepmancer/diffusion-gan-vae-pytorch/main/images/vae_2.png" width="600" alt="VAE Results 2">
</p>

---

## 🛠️ Requirements

To get started, ensure you have the following dependencies installed:

- **Python 3**: The language of choice for deep learning.
- **PyTorch**: The core framework for building and training the models.
- **NumPy**: For numerical operations.
- **Matplotlib**: To visualize the results.
- **tqdm**: For progress bars.

You can install these dependencies via pip:

```bash
pip install torch numpy matplotlib tqdm
```

---

## 🔍 Models Overview

### 🔹 Variational Autoencoder (VAE)
The **VAE** is a powerful generative model that learns a latent representation of the input data, which can be used to generate new, unseen data samples. VAEs are particularly useful for unsupervised learning and data generation tasks.

### 🔹 Generative Adversarial Network (GAN)
The **GAN** framework consists of two neural networks—the generator and the discriminator—that compete against each other. The generator creates fake data samples, while the discriminator tries to distinguish between real and fake samples. Through this adversarial process, the generator improves its ability to create realistic data.

### 🔹 Conditional Generative Adversarial Network (cGAN)
The **cGAN** extends the GAN by conditioning the data generation process on additional information, such as class labels. This allows for more controlled generation of images, enabling the creation of samples with specific attributes or belonging to a particular class.

### 🔹 Diffusion Models
**Diffusion Models** are a class of generative models that learn to simulate the diffusion process, a gradual transformation of data through a stochastic system. These models are particularly powerful for generating high-quality samples that follow a complex distribution.

### 🔹 Conditional Diffusion Models
**Conditional Diffusion Models** take the idea of diffusion models further by conditioning the generation process on auxiliary information, similar to cGANs. This enables the model to generate data that adheres to specific conditions or classes, making it a versatile tool for controlled data generation.

---

Explore the repository to dive deep into these models, experiment with the provided implementations, and witness the power of deep generative models in action!

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
