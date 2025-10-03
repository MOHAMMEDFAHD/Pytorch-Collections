#  Old Neural Networks: Foundations to Markov-Inspired Models (1943–2014)

This repository is a curated collection of **educational PyTorch implementations** of foundational neural network and probabilistic models, tracing their historical evolution from the **McCulloch–Pitts Neuron (1943)** to **GRUs (2014)**.  

Each notebook combines:
- Clear theoretical explanation
- Concise mathematical formulations
- Historical context and relevance
- PyTorch implementations
- Training and generalization experiments
- Comparative visualizations

---

##  Repository Structure

### Early Foundations
- **McCulloch–Pitts Neuron (1943) in PyTorch**
- **Hebbian Learning Rule (1949) in PyTorch**
- **Perceptron (Rosenblatt, 1958) in PyTorch**
- **Adaline & Delta Rule (Widrow & Hoff, 1960) in PyTorch**
- **Backpropagation (Rumelhart, Hinton, Williams, 1986) in PyTorch**

### Statistical Physics & Probabilistic Inspirations
- **Ising Model (1925) in PyTorch**
- **Hopfield Network (1982) in PyTorch**
- **Boltzmann Machine (1985) & RBM + Deep Belief Network (2006) in PyTorch**
- **Markov Models & Hidden Markov Models (Sampling, Likelihood, Visualization) in PyTorch**
- **Hidden Markov Model (HMM).ipynb**

### Time-Dependent Models (Sequential Learning)
- **Jordan Net (1986) and Elman Net (1989) in PyTorch**
- **Vanilla RNNs (1990s)**
- **Long Short-Term Memory (LSTM, 1997) in PyTorch**
- **Gated Recurrent Units (GRU, 2014) in PyTorch**

### Integrative Notebook
- **Early Models Related to Markov Neural Foundations (1900–1990).ipynb**

---

##  Experiments

We provide **training loss curves**, **generalization tests**, and **MSE-based comparisons** across datasets such as:
- **Sine wave (train)**
- **Cosine wave (out-of-distribution)**
- **Shifted sine wave**

### Example: Generalization Comparison (Lower MSE = Better)

| Model                  | Sine (Train) | Cosine (OOD) | Shifted Sine |
|-------------------------|--------------|--------------|--------------|
| Jordan Net (1986)      | 0.006090     | 0.006092     | 0.006092     |
| Elman Net (1989)       | 0.001806     | 0.001803     | 0.001803     |
| Vanilla RNN (1990s)    | 0.001944     | 0.001944     | 0.001944     |
| LSTM (1997)            | 0.000597     | 0.000596     | 0.000596     |
| GRU (2014)             | 0.000537     | 0.000536     | 0.000536     |

 Results show steady improvement in **generalization and training efficiency** across decades of sequence modeling research.

---

##  Learning Outcomes

By exploring this repo, you will:
1. Understand the historical milestones in neural network research.
2. Learn how statistical physics influenced modern AI.
3. See how recurrent architectures evolved from simple feedback loops to gated memory cells.
4. Compare models quantitatively and visually using PyTorch.
5. Build intuition on why architectures like **LSTM** and **GRU** revolutionized sequence learning.

---

##  How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/MOHAMMEDFAHD/Pytorch-Collections.git
   cd Old-Neural-Networks-Model

   #  Citation & Acknowledgement

This repo is intended as an **educational atlas** of neural network history in PyTorch.  
Inspired by seminal works of **McCulloch & Pitts, Rosenblatt, Hopfield, Hinton, Jordan, Elman, Hochreiter & Schmidhuber, Cho et al.**, and many others.

---

#  License

**MIT License** – Free for educational and research purposes.


