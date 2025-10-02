#  Transformers: From *Attention Is All You Need* to Foundation Models (2017–2025)

Welcome to the **Transformer Replication Labs** of the **Programming Ocean Academy**  
This repository is a **pedagogical and experimental collection** tracing the evolution of Transformer-based models — from the 2017 breakthrough paper to today’s multimodal foundation giants.

---

##  What This Repo Offers

-  **Faithful replications** of major Transformer papers  
-  **Clean PyTorch implementations** designed for education and experimentation  
-  **Training, evaluation, and visualization** pipelines  
-  **Historical perspective** on how attention reshaped AI — in NLP, CV, and multimodal learning

---

##  Background: Why Transformers Changed Everything

Before 2017, sequence modeling relied heavily on **RNNs** (LSTM, GRU) and **CNNs** (ConvS2S). These architectures struggled with:

- Long-range dependencies  
- Lack of parallelism  
- Memory and computation limits  

Then came the game-changer:

###  *Attention Is All You Need* (Vaswani et al., 2017)

- Replaced recurrence/convolutions with **multi-head self-attention**  
- Introduced **positional encoding** and **layer normalization**  
- Enabled **massive parallelism** in training  
- Sparked models like **BERT, GPT, ViT, T5, and LLaMA**

---

##  Repository Structure


transformers/
├── AttentionIsAllYouNeed/       # Original Transformer replication
├── BERT/                        # Bidirectional encoding (Devlin et al.)
├── GPT/                         # Generative Pre-Training (GPT-1 → GPT-3)
├── ViT/                         # Vision Transformers (Dosovitskiy et al.)
├── ALBERT/                      # Lite BERT variant
├── T5/                          # Text-to-text multitask transformer
├── LLaMA/                       # Efficient open foundation models
├── Transformer++/              # Architectural refinements
├── Utilities/                   # Tokenizers, training scripts, visualization
└── README.md

##  Key Replicated Papers

| Year | Paper                      | Authors                 | Highlights                                                |
|------|----------------------------|-------------------------|-----------------------------------------------------------|
| 2017 | *Attention Is All You Need* | Vaswani et al.          | Introduced self-attention, transformer encoder-decoder    |
| 2018 | *GPT-1*                    | Radford & Narasimhan    | First autoregressive transformer                          |
| 2018 | *BERT*                     | Devlin et al.           | Bidirectional masked pre-training                         |
| 2020 | *GPT-3*                    | Brown et al.            | Massive model enabling few-shot learning                  |
| 2020 | *ViT*                      | Dosovitskiy et al.      | First successful vision transformer                       |
| 2019 | *ALBERT*                   | Lan et al.              | Parameter-sharing for efficient BERT                      |
| 2020 | *T5*                       | Raffel et al.           | Unified text-to-text pretraining                          |
| 2021 | *PVT*                      | Wang et al.             | Hierarchical vision transformer                           |
| 2023 | *LLaMA*                    | Touvron et al.          | Open-access foundation models for efficient fine-tuning   |

---

##  Methodology

Each notebook follows a **pedagogical development cycle**:

###  Mathematical Foundations

- **Self-Attention**  
  \[
  \text{Attention}(Q, K, V) = \text{softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V
  \]

- **Multi-Head Attention**  
- **Position-wise Feedforward Networks**  
- **Layer Normalization**  
- **Positional Encoding**

---

###  Implementation

- PyTorch-first, clean, modular code  
- Core components: `MultiHeadAttention`, `EncoderBlock`, `TransformerEncoder`  
- Reproducible training loops with flexible configs

---

###  Evaluation

- **BLEU** — Translation performance  
- **Accuracy** — Classification models  
- **Perplexity** — Language modeling  

---

###  Visualization

- Attention heatmaps  
- Token-level saliency maps  
- PCA / t-SNE of hidden states  

---

##  Results Snapshot

-  Transformer (2017) achieves **SOTA BLEU** on WMT’14 En–De & En–Fr  
-  GPT-3 enables **few-shot and in-context learning**  
-  BERT pretraining creates **universal NLP representations**  
-  ViT competes with or exceeds **ResNet** on ImageNet  

---

##  Impact & Legacy

Transformers are now the **core infrastructure of modern AI** across domains:

| Domain     | Key Models                               |
|------------|-------------------------------------------|
| NLP        | BERT, GPT, T5, LLaMA, PaLM                |
| Vision     | ViT, DETR, Swin, PVT                      |
| Multimodal | CLIP, Flamingo, GPT-4, Gemini             |
| Code       | Codex, CodeT5, StarCoder                  |
| Agents     | ReAct, Toolformer, Voyager                |

---

##  Getting Started

Clone the repo and install dependencies:

git clone https://github.com/Programming-Ocean-Academy/deep-learning/transformers
cd transformers
pip install -r requirements.txt

##  References

- Vaswani et al. (2017) — *Attention Is All You Need*  
- Devlin et al. (2019) — *BERT*  
- Radford et al. (2018–2020), Brown et al. — *GPT-1 → GPT-3*  
- Dosovitskiy et al. (2020) — *Vision Transformer (ViT)*  
- Lan et al. (2019) — *ALBERT*  
- Raffel et al. (2020) — *T5: Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer*  
- Touvron et al. (2023) — *LLaMA: Open and Efficient Foundation Models*

 *See [`docs/related_work.md`](docs/related_work.md) for the full list of papers.*

---

##  Mission

This repository is both a **research chronicle** and an **educational playground**.

We aim to:

-  Demystify attention mechanisms and Transformer architecture  
-  Provide clear, first-principles implementations  
-  Empower learners and researchers to build on these foundations  

---

 **Mohammed Fahd Abrah** — *Teaching AI by Recreating Its History*  
**Replicate. Understand. Extend.** 
