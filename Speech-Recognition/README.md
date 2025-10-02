#  Speech Recognition Repository  
*Programming Ocean Academy – Deep Learning Track*

---

##  Overview
This repository is a **comprehensive academic and practical resource** for **Automatic Speech Recognition (ASR)**.  
It covers the **historical foundations**, **mathematical models**, and **modern deep learning techniques** that power today’s real-world speech systems.

The repo bridges **statistical methods** (HMMs, GMMs) with **neural architectures** (RNNs, LSTMs, Attention, Transformers, Wav2Vec2.0), documenting the evolution of ASR from physics-inspired models to large-scale deep learning.

---

##  Repository Contents

###  Tutorials & Foundations
- **A_Tutorial_on_Hidden_Markov_Models_and_Selected_Applications.pdf**  
  Classic reference on HMMs, the backbone of early ASR systems.  

- **Evolution_of_Speech_Recognition_(ASR)_&_Core_Mathematical_Formulations.pdf**  
  Timeline from Ising → HMM → RNN → Transformers, with key equations.  

- **Comparative_overview_of_NLP_vs_ASR_&_Landmark_Academic_Papers.pdf**  
  Concise comparison of NLP vs ASR, plus important research papers.  

---

###  Deep Learning Architectures
- **Deep_Neural_Networks_for_Acoustic_Modeling_in_Speech_Recognition.pdf**  
  Transition from GMM-HMMs to DNN-HMM hybrids.  

- **Speech_Recognition_with_Deep_Recurrent_Neural_Networks_in_PyTorch.ipynb**  
  Implementation of RNN/LSTM models for sequence-to-sequence ASR.  

- **Listen_Attend_and_Spell_(LAS)_in_PyTorch.ipynb**  
  End-to-end attention-based encoder–decoder model for speech recognition.  

- **Wav2vec_2_0_A_Framework_for_Self_Supervised_Learning_of_Speech.pdf**  
  Modern self-supervised framework for ASR, state-of-the-art performance.  

- **Robust_Speech_Recognition_via_Large_Scale_Weak_Supervision.pdf**  
  Techniques for scaling speech recognition with weakly labeled data.  

---

##  Core Mathematical Foundations
Speech recognition builds on **statistical physics + probability + deep learning**:

1. **Ising Model (1920s)** → binary states, energy functions.  
2. **HMMs (1970s)** → probabilistic sequence modeling.  
3. **RNNs / LSTMs (1990s–2000s)** → sequence learning with long context.  
4. **Attention & Transformers (2017–)** → global context, parallel training.  
5. **Self-Supervised Models (2020–)** → Wav2Vec2.0, Whisper, scaling ASR.  

Key math tools:  
- Markov chains, EM algorithm, Viterbi decoding.  
- Logistic/sigmoid probability functions.  
- Cross-entropy, KL divergence.  
- Backpropagation through time (BPTT).  
- Self-attention and sequence-to-sequence loss functions (CTC, seq2seq).  

---

##  Real-World Deployments
- **Google Voice Search / Assistant** (LAS, RNN-T).  
- **Apple Siri** (Hybrid HMM → Deep Learning).  
- **Amazon Alexa** (RNN-T, Transformers).  
- **Microsoft Cortana / Azure Speech** (Deep CNNs + RNNs).  
- **OpenAI Whisper** (Transformer-based multilingual ASR).  

---

##  Purpose
This repository is designed for:
- **Students & researchers**: understanding ASR theory and practice.  
- **Engineers**: ready-to-run PyTorch implementations of key models.  
- **Educators**: teaching the evolution of ASR in a structured way.  

---

##  How to Use
1. Start with **Evolution_of_Speech_Recognition** to get historical + mathematical context.  
2. Explore **HMM and DNN tutorials** for foundations.  
3. Move to **RNN/LSTM and LAS notebooks** for hands-on deep learning models.  
4. Study **Wav2Vec2.0 & large-scale weak supervision papers** for modern SOTA methods.  

---

##  References
This repo consolidates landmark works such as:  
- Rabiner (1989) – HMM Tutorial.  
- Graves et al. (2013) – RNNs for Speech.  
- Bahdanau et al. (2015) – Attention for Seq2Seq.  
- Chan et al. (2016) – Listen, Attend and Spell.  
- Baevski et al. (2020) – Wav2Vec2.0.  
- Radford et al. (2022) – Whisper.  

---

##  Contribution
Feel free to fork, experiment, and contribute improvements to models, tutorials, or references.  
Our goal is to build a **living academic hub** for speech recognition under **Programming Ocean Academy**.

---

