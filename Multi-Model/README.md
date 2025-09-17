# 🌐 Multi-Modal Deep Learning Models: From Attention to Conformers

> A curated PyTorch implementation and experimental playground for **multi-modal sequence modeling** — spanning *Transformers, Conformers, Visual Speech Recognition (VSR), Audio-Visual Fusion, and Fast Conformer variants*.  
> Inspired by seminal works such as **Attention is All You Need (Vaswani et al., 2017)**, **Conformer (Gulati et al., 2020)**, and **Conformers are All You Need for Visual Speech Recognition (Chang et al., 2023)**.

---

## 🚀 Overview
This repository serves as a **research & education hub** for experimenting with *multi-modal deep learning*.  
It reimplements and benchmarks key architectures in:
- **Natural Language Processing (NLP)**  
- **Automatic Speech Recognition (ASR)**  
- **Visual Speech Recognition (VSR)**  
- **Audio-Visual Speech Recognition (AVSR)**  

We go beyond replication — each notebook is a *didactic lab* that trains, evaluates, predicts, and visualizes results.

---

## 🏛️ Academic Lineage

### 📌 Transformers
- **Attention is All You Need** (Vaswani et al., 2017): Introduced the Transformer, replacing recurrence with pure attention.  
- **Subsequent VSR works** (Zhou et al., 2019; Afouras et al., 2020): Applied Transformers for lip-reading and AVSR.

### 📌 Conformers
- **Conformer** (Gulati et al., 2020): Combined convolution for local features with attention for global context.  
- **Fast Conformer** (Rekesh et al., 2023): Efficient variant with downsampling + scalable attention.  
- **Conformer-1 (Ramponi et al., 2023)**: Trained on 650K hours, achieving robustness on noisy real-world audio.  
- **Nextformer (Jiang et al., 2022)**: Hybrid ConvNeXt + Conformer for efficient ASR.  
- **Apple / Nvidia Riva**: Edge-optimized and CTC/Transducer variants.  

### 📌 Visual Speech Recognition
- **LipNet** (Assael et al., 2016): First end-to-end lip-reading using spatiotemporal CNN + GRU.  
- **LRW / LRS2 / LRS3 datasets** (Chung et al., 2017–18): Standardized large-scale lip-reading benchmarks.  
- **Conformers are All You Need for VSR** (Chang et al., 2023): Demonstrated strong performance with simplified visual front-ends.

### 📌 Multi-Modal Extensions
- **Audio-Visual Conformer** (Ma et al., 2021): Robust fusion under noisy audio.  
- **Cross-Attention Conformer** (Narayanan et al., 2021): Context modeling for speech enhancement.  
- **End-to-End AVSR** (Makino et al., 2019; Sterpu et al., 2018): Large-scale multimodal systems.  

---

## 📂 Repository Structure

📦 multi-modal
┣ 📜 README.md
┣ 📂 notebooks
┃ ┣ attention_is_all_you_need.ipynb
┃ ┣ beyond_attention.ipynb
┃ ┣ conformer.ipynb
┃ ┣ fast_conformer.ipynb
┃ ┣ conformer_visual_speech.ipynb
┃ ┣ audio_visual_conformer.ipynb
┃ ┗ conformal_sympow_transformer.ipynb
┣ 📂 data
┃ ┣ toy_text.txt
┃ ┣ toy_audio.wav
┃ ┗ toy_video.mp4
┣ 📂 models
┃ ┣ transformer.py
┃ ┣ conformer.py
┃ ┣ fast_conformer.py
┃ ┣ conformal_sympow.py
┃ ┗ multimodal_fusion.py
┗ 📂 results
┣ loss_curves/
┗ generated_samples/


---

## 🔬 Implemented Models

| Model | Paper | Key Contribution |
|-------|-------|------------------|
| Transformer | Vaswani et al., 2017 | Pure self-attention, sequence modeling |
| Beyond Attention | Chen, 2023 | Re-assessment of attention bottlenecks |
| Conformer | Gulati et al., 2020 | Convolution + Attention synergy |
| Fast Conformer | Rekesh et al., 2023 | Scalable attention, downsampling |
| Conformer VSR | Chang et al., 2023 | Conformers for lip-reading |
| AV-Conformer | Ma et al., 2021 | Audio-visual fusion |
| Conformal-Sympow Transformer | Wang et al., 2023 | Symmetric power transformations |

---

## 📊 Results (Sample)

- **Training Curves**: Loss decreases steadily with epochs across models (see `results/loss_curves`).  
- **Perplexity Trends**:  
  - Transformer baseline: ~4–5  
  - Conformer: ~3–3.5  
  - Fast Conformer: ~2.3–2.6 (faster convergence)  
  - Conformer VSR: ~20 (toy lip-reading)  

---

## 🛠️ Getting Started

### Installation

git clone https://github.com/your-username/multi-modal.git
cd multi-modal
pip install -r requirements.txt
Quick Run (Toy Example)
bash

cd notebooks
jupyter notebook conformer.ipynb
📚 References
Vaswani et al., Attention is All You Need, NeurIPS 2017.

Gulati et al., Conformer: Convolution-augmented Transformer for Speech Recognition, Interspeech 2020.

Chang et al., Conformers are All You Need for Visual Speech Recognition, arXiv 2023.

Ma et al., End-to-End Audio-Visual Speech Recognition with Conformers, arXiv 2021.

Rekesh et al., Fast Conformer, arXiv 2023.

Ramponi et al., Conformer-1: Robust ASR Model, 2023.

and many more — see papers.md.

🌟 Acknowledgements
This repo builds upon the academic contributions of the ASR, VSR, and AVSR communities. It is designed as a learning and research tool for those interested in multi-modal deep learning architectures.
