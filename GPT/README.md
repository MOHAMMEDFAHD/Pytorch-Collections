# GPT Research & Replication Labs

Welcome to the **GPT Research & Replication Labs Repository**.  
This repository is a structured educational and research-oriented collection of **replications, summaries, and experiments** with the **Generative Pretrained Transformer (GPT)** family of models, from **GPT-1 to GPT-4**, and beyond.  

The aim is to provide:
- **Concise academic summaries** of each GPT paper.  
- **Mathematical/statistical breakdowns** of core methods.  
- **ASCII diagrams** for model architectures.  
- **Full educational PyTorch labs** (training, evaluation, prediction, visualization).  
- **Comparisons and lineage tables** to trace the evolution of GPT and related LLMs.  

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Research Goals](#research-goals)  
3. [Paper Replications](#paper-replications)  
   - [GPT-1 (2018) – Improving Language Understanding](#gpt-1-2018)  
   - [GPT-2 (2019) – Language Models are Unsupervised Multitask Learners](#gpt-2-2019)  
   - [GPT-3 (2020) – Language Models are Few-Shot Learners](#gpt-3-2020)  
   - [GPT-4 (2023) – Technical Report](#gpt-4-2023)  
   - [Beyond GPT: Other Transformer LMs](#beyond-gpt)  
4. [Comparative Evolution of GPT Models](#comparative-evolution)  
5. [Planned Extensions](#planned-extensions)  
6. [Citations](#citations)  

---

## Introduction

The **Generative Pretrained Transformer (GPT)** series, introduced by OpenAI, reshaped natural language processing through large-scale **autoregressive Transformers**.  
This repo replicates **key GPT models** and **educational experiments**, while also comparing them to **non-OpenAI models** (e.g., PaLM, LLaMA, Chinchilla).  

---

## Research Goals

- Provide **open educational resources** for understanding GPT evolution.  
- Offer **hands-on labs** for students and researchers.  
- Build a **unified timeline** of GPT and other LLMs.  
- Highlight **mathematical/statistical foundations** behind scaling laws and training.  
- Discuss **limitations, risks, and alignment methods** of large-scale LMs.  

---

## Paper Replications

### GPT-1 (2018)
**Paper**: *Improving Language Understanding by Generative Pre-Training* (Radford et al., 2018)  
- **Problem**: Need for task transfer without supervised training for every task.  
- **Solution**: Pre-train a Transformer LM on unlabeled text, then fine-tune on downstream tasks.  
- **Lab**: [gpt1_lab.py](./labs/gpt1_lab.py) – small-scale PyTorch replication with text classification task.  

---

### GPT-2 (2019)
**Paper**: *Language Models are Unsupervised Multitask Learners* (Radford et al., 2019)  
- **Problem**: Limited zero-shot task performance.  
- **Solution**: Scale model (1.5B params) and use natural language prompting.  
- **Lab**: [gpt2_lab.py](./labs/gpt2_lab.py) – text generation, perplexity analysis, news-style generation.  

---

### GPT-3 (2020)
**Paper**: *Language Models are Few-Shot Learners* (Brown et al., 2020)  
- **Problem**: Dependence on fine-tuning; unclear if scaling further helps.  
- **Solution**: Train 175B Transformer with zero-/one-/few-shot prompting.  
- **Lab**: [gpt3_lab.py](./labs/gpt3_lab.py) – few-shot experiments with QA, reasoning, and translation.  

---

### GPT-4 (2023)
**Paper**: *GPT-4 Technical Report* (OpenAI, 2023)  
- **Problem**: Reliability, scaling predictions, multimodal integration, alignment.  
- **Solution**: Large-scale multimodal Transformer, trained predictably with scaling laws and RLHF.  
- **Lab**: [gpt4_lab.py](./labs/gpt4_lab.py) – multimodal text experiment, exam benchmarks simulation, factuality checks.  

---

### Beyond GPT
This repo will expand to include **other frontier LLMs** for comparison and study:  
- **PaLM** (Chowdhery et al., 2022) – Scaling with Pathways.  
- **Chinchilla** (Hoffmann et al., 2022) – Compute-optimal training.  
- **LLaMA** (Meta, 2023) – Smaller, efficient LMs for researchers.  
- **Anthropic’s Constitutional AI** – Alignment without RLHF.  

Labs for these will follow the same format: **summary + math + diagram + PyTorch lab**.  

---

## Comparative Evolution

| Model | Year | Params | Key Idea | Evaluation Setting | Contributions |
|-------|------|--------|----------|--------------------|---------------|
| GPT-1 | 2018 | 117M | Pre-training + fine-tuning | Supervised fine-tuning | First GPT, introduced generative pretraining. |
| GPT-2 | 2019 | 1.5B | Zero-shot via prompting | Zero-shot | Showed unsupervised multitask learning. |
| GPT-3 | 2020 | 175B | Few-shot prompting | Zero-/one-/few-shot | Proved scaling → emergent abilities. |
| GPT-4 | 2023 | undisclosed | Multimodal + alignment | Few-shot, exams, vision | Human-level benchmarks, strong safety pipeline. |

---

## Planned Extensions

- Add **notebooks** for PaLM, LLaMA, Chinchilla, etc.  
- Extend to **survey papers** on scaling laws, alignment, safety.  
- Add **visual interactive demos** for prompting strategies.  
- Create **timeline of GPT + beyond GPT** (2018 → 2025).  

---

## Citations

For academic accuracy, please cite the original papers when using this repo:  

- Radford, A. et al. (2018). *Improving Language Understanding by Generative Pre-Training.*  
- Radford, A. et al. (2019). *Language Models are Unsupervised Multitask Learners.*  
- Brown, T. et al. (2020). *Language Models are Few-Shot Learners.*  
- OpenAI. (2023). *GPT-4 Technical Report.*  
- Hoffmann, J. et al. (2022). *Training Compute-Optimal Large Language Models (Chinchilla).*  
- Chowdhery, A. et al. (2022). *PaLM: Scaling Language Models with Pathways.*  
- Touvron, H. et al. (2023). *LLaMA: Open and Efficient Foundation Language Models.*  

---

## Maintainer

Developed and curated by **Mohammed Fahd Abrah (Programming Ocean Academy)**,  
with the goal of democratizing access to cutting-edge AI research and training resources.

