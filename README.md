# 🌊 Deep Learning With Pytorch Framework

Welcome to **Mohammed Abrah's PyTorch Deep Learning Repository**! This project is a comprehensive educational suite showcasing a variety of **generative models** implemented with PyTorch, ranging from foundational architectures to modern, cutting-edge designs.

---

## 🎯 Objective

This repository serves as an academic and teaching-oriented resource for understanding, building, and visualizing deep generative models. It is designed to help students, researchers, and practitioners explore the diversity of generative learning approaches in a modular and clear format.

---

## 📚 Repository Structure

Each folder represents a specific category of generative or neural architecture:

| Folder Name                          | Description                                               |
| ------------------------------------ | --------------------------------------------------------- |
| `auto-regressive-models`             | PixelCNN and related sequential density estimators        |
| `cnn`                                | Basic CNN models for image recognition                    |
| `diffusion`                          | Denoising Diffusion Probabilistic Models (DDPM, DDIM)     |
| `dit-models`                         | Diffusion Transformers (DiT)                              |
| `energy-based-models`                | EBMs trained with Langevin dynamics                       |
| `flow-based-models`                  | RealNVP, Glow, and other invertible models                |
| `gans`                               | GAN, DCGAN, WGAN, and conditional variants                |
| `latent-manifold-auto-encoder`       | Latent space exploration with VAEs and AEs                |
| `multi-model`                        | Cross-modal tasks (e.g., text-to-image, image captioning) |
| `restricted-boltzmann-machine`       | Contrastive Divergence and RBMs                           |
| `rnn`                                | Recurrent networks (LSTM, GRU)                            |
| `score-based-generative-convolution` | Score-matching models with CNN backbones                  |
| `score-based-generative-models`      | Langevin and NCSN-style samplers                          |
| `time-series`                        | Forecasting models for temporal data                      |
| `transformer`                        | Sequence models and transformers (Vanilla, GPT)           |
| `variational-auto-encoder`           | VAEs and conditional variants                             |
| `vision-transformer`                 | ViT for image understanding                               |

---

## 🔍 Highlighted Projects

### 1. **Diffusion Models**

> *"A Concise Implementation of Denoising Diffusion Probabilistic Models for Generative Image Synthesis in PyTorch"*

* U-Net architecture with Gaussian noise scheduling
* Reverse sampling with denoising

### 2. **GANs**

> *"Adversarial Image Synthesis with Generative Networks: A PyTorch Implementation of GANs on MNIST"*

* Generator + Discriminator loop
* Real vs. generated image comparison

### 3. **VAEs**

> *"Latent Variable Modeling and Image Generation with Variational Autoencoders: A PyTorch-Based Study on MNIST"*

* Reparameterization trick
* Sampling and interpolation

### 4. **Score-Based Models**

> *"Unsupervised Image Synthesis via Score Matching and Langevin Dynamics: A Score-Based Generative Framework on MNIST"*

* Trainable score networks
* MCMC sampling

### 5. **Text-to-Image (Mini DALL·E)**

> *"Learning Discrete Visual Representations from Textual Descriptions: A Simplified VQ-VAE Framework for Text-to-Image Generation"*

* VQ-VAE + Transformer
* Color/shape captioned image generation

### 6. **Image Captioning**

> *"Visual Grounding through Language: A Minimalist Encoder-Decoder Framework for Image Captioning with Attention in PyTorch"*

* ResNet + LSTM with soft attention
* Caption generation for synthetic scenes

---

## 🛠️ Usage

All notebooks are written for clarity and modularity.

```bash
# Clone the repository
git clone https://github.com/mohammedabrah/pytorch-deep-learning.git
```

Open any `.ipynb` file in JupyterLab, Google Colab, or VSCode and run directly.

---

## ✨ Contributing

We welcome contributions to extend this educational repository:

* Add new generative model examples
* Improve visualizations or metrics
* Refactor notebooks into scripts or modules

---

## 📜 License

MIT License. Free for personal, educational, and research use.

---

## 🙏 Acknowledgements

Inspired by work from:

* OpenAI, DeepMind, LucidRain
* PyTorch community and tutorials
* DALL·E, VQ-VAE, and DDPM original papers

---

Enjoy exploring generative deep learning with PyTorch! 🌊
