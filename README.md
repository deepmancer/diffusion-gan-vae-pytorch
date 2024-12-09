# 🎨 Deep Generative Models in PyTorch

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=Python&logoColor=ffdd54" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter Notebook">
  <img src="https://img.shields.io/github/stars/deepmancer/diffusion-gan-vae-pytorch?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/deepmancer/diffusion-gan-vae-pytorch?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/license/deepmancer/diffusion-gan-vae-pytorch" alt="License">
</p>

> Master deep generative models in PyTorch with ease!

Welcome to **Diffusion-GAN-VAE-PyTorch**! This repository is your ultimate resource for mastering deep generative models, implemented from scratch in PyTorch. It features **Variational Autoencoders (VAE)**, **Generative Adversarial Networks (GAN)**, **Conditional GANs**, **Diffusion Models**, and **Conditional Diffusion Models**, all crafted with clarity and precision. 

## 🌟 Highlights

- 🧩 Modular & Educational
- 🔍 Explore Cutting-Edge Models
- 💡 Beginner-Friendly Yet Research-Ready
- 📕 Fully documented

👉 **[Star this repo](https://github.com/deepmancer/diffusion-gan-vae-pytorch/stargazers)** if you find it helpful, and join our community of AI enthusiasts!

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

## 🛠️ Installation

### Requirements
Ensure the following dependencies are installed:

- **Python 3**: The programming language used.
- **PyTorch**: The deep learning framework for model building and training.
- **NumPy**: For numerical computations.
- **Matplotlib**: For result visualizations.
- **tqdm**: For progress tracking.

Install dependencies with pip:

```bash
pip install torch numpy matplotlib tqdm
```

---

## 🌀 Models Overview

### 🔹 Variational Autoencoder (VAE)
A **VAE** learns a probabilistic latent space, enabling smooth interpolation and robust generation of new data points.

### 🔹 Generative Adversarial Network (GAN)
**GANs** pit a generator against a discriminator in a game-like setup, creating highly realistic samples over time.

### 🔹 Conditional Generative Adversarial Network (cGAN)
**cGANs** incorporate conditional inputs (like class labels) to control data generation, enabling targeted synthesis.

### 🔹 Diffusion Models
**Diffusion Models** simulate a stochastic process to progressively model complex distributions, resulting in high-quality generation.

### 🔹 Conditional Diffusion Models
Building on diffusion models, **Conditional Diffusion Models** allow for guided, condition-driven generation.

---

## 🌟 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/deepmancer/diffusion-gan-vae-pytorch.git
   cd diffusion-gan-vae-pytorch
   ```

2. Install dependencies.

3. Run the notebook!

---

## 📝 License

This project is licensed under the **MIT License**. Feel free to use it in your projects while crediting the repository. See the [LICENSE](LICENSE) file for details.
