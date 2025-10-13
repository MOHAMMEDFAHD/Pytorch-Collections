#  Recurrent Neural Networks (RNN) — Replication Labs

Welcome to the **Recurrent Neural Networks (RNN) Collection**
A curated repository of **hands-on reproductions** of classic and modern RNN architectures — from the vanilla RNNs to attention-powered neural translation models.

---

##  What’s Inside?

Each notebook in this collection is crafted to:

- Deliver **pedagogical clarity**: *math → code → visualization*
- Benchmark **Vanilla RNN**, **LSTM**, **GRU**, and attention-based models
- Trace the **evolution** of recurrent models in NLP and beyond
- Serve as a **didactic resource** for students, researchers, and engineers alike

---

##  The RNN Landscape

Recurrent Neural Networks (RNNs) have historically been the backbone of sequence modeling, enabling progress in:

- Natural Language Processing  
- Time Series Prediction  
- Speech Recognition  
- Machine Translation  

However, challenges like **vanishing gradients** sparked innovations:

-  **LSTM** — Hochreiter & Schmidhuber (1997)  
-  **GRU** — Cho et al. (2014)  
-  **Attention & Seq2Seq** — Bahdanau et al., Sutskever et al. (2014)  
-  **Neural Turing Machines**, **Pointer Networks**, and **ConvS2S**

This collection rebuilds these breakthroughs step-by-step with a strong link to the **original papers**.

---

##  Repository Structure

###  Replication Labs — Notebook Summaries

- `Empirical_Replication_of_Gated_Recurrent_Neural_Networks_Comparative_Evaluation.ipynb`  
   Replicates Chung et al. (2014) — RNN vs LSTM vs GRU on sequential tasks  

- `LSTM-SeqRepNet_A_Didactic_Reproduction_of_Hochreiter_&_Schmidhuber's_LSTM.ipynb`  
   Reproduces the foundational LSTM model using PyTorch  

- `RNN-TanhEvalNet_A_Reimplementation_of_Vanilla_Recurrent_Networks_for_Empirical_Baselines.ipynb`  
   Minimal RNN baseline for controlled experiments  

- `Modeling_Long_Term_Dependencies_with_LSTM_A_PyTorch_Replication.ipynb`  
   Explores LSTM's capacity for long-term memory  

- `Neural_Horizons_A_PyTorch_Replication_of_Recurrent_Continuous_Translation.ipynb`  
   Pre-attention encoder–decoder translation models  

- `Neural_Phrase_to_Phrase_Translation_A_PyTorch_Replication_of_RNN_Encoder-Decoder.ipynb`  
   Phrase-level encoder–decoder sequence modeling  

- `ReproLuongNMT_A_PyTorch_Replication_of_Attention-Based_NMT.ipynb`  
   Luong et al. (2015) — Local vs Global Attention  

- `ReproSeq2SeqAttn_A_PyTorch_Replication_of_Bahdanau_Attention.ipynb`  
   Additive attention (Bahdanau et al.) — align and translate  

- `Convolutional_Sequence_to_Sequence_Translation_A_PyTorch_Replication_of_Fairseq_ConvS2S.ipynb`  
   ConvS2S — sequence modeling without recurrence  

- `Coverage_Augmented_Neural_Machine_Translation_A_PyTorch_Replication.ipynb`  
   Coverage attention for reducing over-translation (Tu et al.)  

- `Hands_On_Replication_of_Neural_Turing_Machines_Copy_Task_in_PyTorch.ipynb`  
   Differentiable memory with Neural Turing Machines  

- `Hands_On_Replication_of_Pointer_Networks_Learning_to_Point_with_Attention.ipynb`  
   Pointer Networks — solving combinatorial problems via RNNs  

---

##  Key Papers Reproduced

- Hochreiter & Schmidhuber (1997) — *Long Short-Term Memory*  
- Pascanu et al. (2012) — *On the Difficulty of Training RNNs*  
- Sutskever et al. (2014) — *Seq2Seq Learning with Neural Networks*  
- Bahdanau et al. (2014) — *Attention-Based NMT*  
- Xu et al. (2015) — *Show, Attend and Tell*  
- Chung et al. (2014–2015) — *GRU and Gated Feedback RNNs*  
- Gehring et al. (2017) — *ConvS2S*  
- Tu et al. (2016) — *Coverage Attention in NMT*  
- Graves et al. (2014) — *Neural Turing Machines*  
- Vinyals et al. (2015) — *Pointer Networks*

---

##  Goals of This Collection

-  Build a **living roadmap** of RNN research via PyTorch implementations  
-  Bridge **theory ↔ equations ↔ code ↔ results**  
-  Provide **teaching labs** for instructors and self-learners  
-  Enable **reproducible benchmarks** for research

---

##  References

- Chung, J. et al. (2014). *Empirical Evaluation of Gated RNNs on Sequence Modeling*. arXiv:1412.3555  
- Hochreiter, S., & Schmidhuber, J. (1997). *Long Short-Term Memory*. Neural Computation  
- Bahdanau, D. et al. (2014). *Neural Machine Translation by Jointly Learning to Align and Translate*  
- Sutskever, I. et al. (2014). *Sequence to Sequence Learning with Neural Networks*  
- Xu, K. et al. (2015). *Show, Attend and Tell*  

---

 **From early RNNs to attention-powered translation, this lab brings the full arc of sequential modeling to your fingertips.**  
Let’s replicate, learn, and innovate together! 


