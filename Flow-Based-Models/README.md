# Flow-Based Generative Models  
## From NICE to FFJORD — Theory, Mathematics, and Evolution

---

## Overview

This repository provides a comprehensive, research-oriented study of **flow-based generative models**, covering their **mathematical foundations**, **architectural evolution**, and **statistical interpretations**.

Flow-based models are a class of **exact-likelihood generative models** built on **invertible transformations** and the **change-of-variables theorem**. Unlike GANs or VAEs, they allow:

- Exact density evaluation  
- Exact latent inference  
- Deterministic and invertible generation  

This repository traces the **chronological evolution** of flow-based models, starting from **NICE** and culminating in **continuous normalizing flows (FFJORD)**, explaining **why each paper exists**, **what limitation it addresses**, and **how mathematical constraints shaped its design choices**.

---

## Scope of the Repository

This repository focuses on **conceptual clarity, mathematics, and research understanding**, not just implementation.

It includes:

- Paper-by-paper **problem → limitation → solution** analysis  
- Full **mathematical and statistical extraction** from original papers  
- Clear explanations of **Jacobians, determinants, traces, and ODE dynamics**  
- Explicit discussion of **trade-offs** (expressivity vs. tractability vs. speed)  
- A **unifying view** connecting density estimation, variational inference, and continuous dynamics  

---

## Papers Covered (Chronological)

The repository covers the following core flow-based papers:

1. **NICE — Non-linear Independent Components Estimation**  
2. **IAF — Improved Variational Inference with Inverse Autoregressive Flow**  
3. **Real NVP — Density Estimation Using Real NVP**  
4. **MAF — Masked Autoregressive Flow for Density Estimation**  
5. **Glow — Generative Flow with Invertible 1×1 Convolutions**  
6. **FFJORD — Free-form Continuous Dynamics for Scalable Reversible Generative Models**

Each paper is analyzed **in isolation** and **in context**—how it builds on and fixes the previous generation.

---

## Core Mathematical Foundation

All models in this repository rely on the **change-of-variables formula**:

\[
\log p_X(x)
=
\log p_Z(f(x))
+
\log \left| \det \frac{\partial f(x)}{\partial x} \right|
\]

Where:

- \( x \) is the data  
- \( z = f(x) \) is a latent variable  
- \( f \) is an invertible transformation  
- \( p_Z \) is a simple base distribution (usually Gaussian)  

---

## Central Design Question

**How do we design expressive invertible transformations while keeping the Jacobian determinant tractable?**

Every flow model answers this question differently.

---

## Conceptual Axes of Comparison

This repository organizes flow models along four fundamental axes.

### 1. Jacobian Structure

- Unit determinant (NICE)  
- Triangular Jacobian (Real NVP, MAF, IAF)  
- Full but structured determinant (Glow)  
- Trace-based continuous Jacobian (FFJORD)  

### 2. Expressivity

- Additive vs. affine transformations  
- Coupling vs. autoregressive flows  
- Discrete vs. continuous flows  

### 3. Computational Trade-offs

- Sampling speed  
- Likelihood evaluation speed  
- Parallelizability  
- Memory usage and ODE solver cost  

### 4. Statistical Objective

- Density estimation (NICE, Real NVP, MAF, Glow)  
- Variational inference (IAF)  
- Continuous probability flow modeling (FFJORD)  

---

## Paper-by-Paper Summary (High-Level)

### NICE
- Introduces coupling layers  
- Guarantees tractable Jacobian determinant  
- Limited by volume preservation  
- Establishes the core flow paradigm  

### IAF
- Brings flows into variational inference  
- Uses autoregressive structure for scalable posteriors  
- Optimized for sampling, not density evaluation  

### Real NVP
- Introduces affine coupling  
- Enables input-dependent volume change  
- Adds multi-scale image architecture  

### MAF
- Uses masked autoregressive networks  
- Strong density estimation performance  
- Sampling is sequential and slow  

### Glow
- Learns permutations via invertible 1×1 convolutions  
- Uses LU decomposition for efficient log-determinant computation  
- Improves mixing and large-scale image modeling  

### FFJORD
- Moves to continuous normalizing flows  
- Replaces log-determinant with Jacobian trace  
- Enables free-form neural architectures  
- Introduces ODE solvers into generative modeling  

---

## Mathematical Highlights Extracted

The repository explains in detail:

- Why Jacobian determinants are expensive \( O(D^3) \)  
- How triangular Jacobians reduce complexity to \( O(D) \)  
- Why affine coupling layers isolate neural network complexity  
- How autoregressive ordering creates triangular Jacobians  
- Why continuous flows replace determinants with traces  
- How probability mass evolves under ODE dynamics  

---


This repository is designed as:

**A conceptual and mathematical atlas of flow-based generative modeling**

---

## Intended Audience

This repository is for:

- AI researchers and graduate students  
- ML engineers studying generative models  
- Readers transitioning from VAEs/GANs to flows  
- Anyone seeking a mathematically grounded understanding of normalizing flows  

Recommended background:

- Linear algebra  
- Probability theory  
- Multivariate calculus  

---

## Suggested Reading Order

1. Start with **NICE** to understand invertibility and coupling  
2. Read **Real NVP** for expressive discrete flows  
3. Compare **IAF vs. MAF** to understand autoregressive trade-offs  
4. Study **Glow** for learned mixing and scalable image flows  
5. Finish with **FFJORD** to see how continuous dynamics remove architectural constraints  

---

## Conceptual Takeaway

Flow-based models are **not about sampling tricks**.  
They are about **engineering probability distributions through invertible geometry**.

Each generation trades **structure for freedom**, until **FFJORD removes discrete constraints entirely** by turning probability modeling into a **dynamical system**.

---

## Citation

If you use this repository for academic or educational purposes, please cite the **original papers** accordingly.  
This repository does not replace the original publications; it **systematizes and explains** them.

---

## License

This repository is intended for **educational and research use**.  
Please check individual paper licenses for redistribution restrictions.

---

## Maintainer’s Note

This repository is designed to grow:

- Additional flow variants (Neural Spline Flows, Residual Flows, CNF variants)  
- Mathematical appendices  
- Visual Jacobian intuition diagrams  
- Connections to diffusion and score-based models  

