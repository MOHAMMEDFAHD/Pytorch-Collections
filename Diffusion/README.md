#  Diffusion Models Repository
*A Didactic and Research-Oriented Collection of Diffusion Model Replications*

Welcome to the **Programming Ocean Academy’s diffusion playground**.  
This repository brings together **replications**, **didactic notebooks**, and **explorations** of some of the most influential works in the field of diffusion-based generative models — bridging **theory**, **math**, and **PyTorch implementations**.

---

##  Motivation
Diffusion models have rapidly become the **state-of-the-art** in generative modeling, surpassing GANs and autoregressive approaches in **visual fidelity** and **scalability**.  
Our mission is to:

-  **Teach** diffusion models through clear, didactic replications.  
-  **Replicate** landmark papers faithfully in PyTorch.  
-  **Experiment** with extensions, simplifications, and new ideas.  

---

##  Repository Structure
Each notebook is structured like a mini research paper replication:

- **Abstract & Motivation** – why the paper matters.  
- **Mathematical Foundations** – key equations with LaTeX.  
- **Architecture** – ASCII/block diagrams for clarity.  
- **Implementation** – end-to-end PyTorch code (train → evaluate → sample → visualize).  
- **Results** – generated samples, metrics, or retention heatmaps.  
- **Discussion** – interpretation, limitations, and connections.  

---

##  Contents

###  Core Replications
- A Concise Implementation of *Denoising Diffusion Probabilistic Models (DDPM)* – Ho et al. (2020)  
- DDPM from Scratch – full PyTorch pipeline, clean and minimal  
- ReproDDIM – Song et al. (2021), deterministic sampling for faster inference  
- ReproLDM – *Latent Diffusion Models* (Rombach et al., 2022), high-resolution synthesis  

###  Advanced Architectures
- Diffusion Transformers in Practice – replication of *Scalable Diffusion Models with Transformers (DiT)*, Peebles & Xie (2022)  
- ReproDiffusionGAN – combining GAN objectives with diffusion  
- Mini Palette – replication of *Palette: Image-to-Image Diffusion Models* (Saharia et al., 2022)  

###  Didactic / Analytic Explorations
- Mini AnalyticDPM – didactic replication of *Analytic-DPM* (Bao et al., 2022)  
- Fashion Diffusion – crafting clothing designs with denoising diffusion  
- ReproDiffusionLab – exploratory replication of *Deep Unsupervised Learning using Nonequilibrium Thermodynamics* (Sohl-Dickstein et al., 2015)  

###  Checkpoints
- Pretrained checkpoints: **MNIST**, **FashionMNIST**, **CIFAR-10**  

---

##  Key Papers Covered
- Sohl-Dickstein et al. (2015) – *Deep Unsupervised Learning using Nonequilibrium Thermodynamics*  
- Ho et al. (2020) – *Denoising Diffusion Probabilistic Models (DDPM)*  
- Song et al. (2021) – *Score-Based Generative Models*; **DDIM**  
- Nichol & Dhariwal (2021) – *Improved DDPM*  
- Dhariwal & Nichol (2021) – *Diffusion Models Beat GANs on Image Synthesis*  
- Saharia et al. (2022) – *Palette*; *Imagen*  
- Rombach et al. (2022) – *High-Resolution Image Synthesis with Latent Diffusion Models (LDM)*  
- Peebles & Xie (2022) – *Scalable Diffusion Models with Transformers (DiT)*  

---

##  Educational Goals
This repo is more than just code: it’s a **learning journey**.  
Each notebook is written with:  

- **Step-by-step explanations** for students  
- **Equations + intuition** for researchers  
- **Clean PyTorch code** for engineers  

---

##  Getting Started
Instructions for environment setup, training, and sampling are provided in the repository.

