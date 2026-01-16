# AI Representations – A Deep Dive into Neural Network Representations

This repository is a research-oriented collection of executable notebooks dedicated to understanding how neural networks represent information internally.

Rather than treating neural networks as black boxes, this project follows a **zoom-in philosophy**: we study neurons, features, representations, and circuits as concrete, analyzable objects—much like cells in biology or components in physical systems.

The work is inspired by the Circuits research program and modern advances in representation learning, interpretability, and mechanistic understanding of deep networks.

---

## Core Philosophy

Most machine learning projects focus on performance.  
This repository focuses on **understanding**.

The guiding questions include:

- What features do neural networks actually learn?
- How do low-level representations (edges, curves) compose into high-level concepts?
- Can meaningful algorithms be traced inside learned weights?
- How do representations evolve across layers, architectures, and training paradigms?
- What does it mean for a neuron, direction, or feature to be meaningful?

This aligns with the view of interpretability as a **natural science**, where neural networks are treated as empirical objects of study rather than opaque function approximators.

---

## Conceptual Foundations

The notebooks explore themes such as:

- Distributed representations  
- Hierarchical feature learning  
- Emergent structure in neural activations  
- Neuroscience-inspired analysis of vision models  
- From single neurons to circuits  
- Historical foundations of representation learning  

Rather than isolated demonstrations, the notebooks form a coherent conceptual trajectory from early theoretical ideas to modern deep learning systems.

---

## Repository Structure

Each notebook corresponds to a seminal idea, paper, or conceptual milestone in representation learning and neural network understanding.

### Core Notebooks

| Notebook | Focus |
|--------|------|
| `AI_Representations_Playground_A_Visual_Tour_of_Neural_Networks.ipynb` | Interactive visual exploration of neural representations and activations |
| `LEARNING_DISTRIBUTED_REPRESENTATIONS_OF_CONCEPTS.ipynb` | Foundational ideas behind distributed representations |
| `Representation_Learning_A_Review_and_New_Perspectives.ipynb` | Systematic overview of representation learning paradigms |
| `Deep_Representation_Learning_Fundamentals_Perspectives_Applications_and_Open_Challenges.ipynb` | Theory, applications, and open problems in deep representations |
| `Learning_Deep_Architectures_for_AI.ipynb` | Why depth matters and how deep representations emerge |

### Vision and Neuroscience Lineage

| Notebook | Focus |
|--------|------|
| `Receptive_Fields_Binocular_Interaction_and_Functional_Architecture_in_the_Cat’s_Visual_Cortex.ipynb` | Biological foundations of hierarchical vision |
| `Neocognitron_A_Self_Organizing_Neural_Network_Model_for_a_Mechanism_of_Pattern_Recognition.ipynb` | Pre-backpropagation convolutional ideas |
| `Visualizing_and_Understanding_Convolutional_Networks_(Zeiler_&_Fergus_2014).ipynb` | Feature visualization and interpretability |
| `Gradient_Based_Learning_Applied_to_Document_Recognition.ipynb` | Early practical CNN representations |
| `Backpropagation_Applied_to_Handwritten_Zip_Code_Recognition.ipynb` | End-to-end learning of representations |

---

## Methodological Approach

Across notebooks, a rigorous interpretability toolkit is applied, including:

- Feature visualization  
- Dataset-driven activation analysis  
- Synthetic stimuli  
- Layer-by-layer representation tracing  
- Conceptual circuit decomposition  
- Historical comparison across architectures  

This mirrors methodologies from visual neuroscience, adapted for artificial neural systems.

---

## Key Ideas Emphasized

- Features as directions in representation space  
- Neurons are not always the correct unit of analysis  
- Polysemantic versus pure features  
- Compositionality of representations  
- Progression from edge detectors to curves, shapes, and objects  
- Emergent invariances to pose, orientation, and scale  
- Why understanding learned weights is possible and meaningful  

---

## Intended Audience

This repository is designed for:

- AI and machine learning researchers  
- Deep learning practitioners seeking theoretical depth  
- Interpretability researchers  
- Advanced students (graduate level or equivalent)  
- Anyone interested in how neural networks process information internally  

This is **not** an introductory machine learning tutorial repository.  
Familiarity with neural networks, backpropagation, and convolutional models is assumed.

---

## Requirements

- Python 3.8 or higher  
- PyTorch  
- NumPy  
- Matplotlib or Seaborn  
- Jupyter Notebook or JupyterLab  

Each notebook is self-contained and can be executed independently.

---

## Long-Term Vision

This repository is part of a broader effort to:

- Build a systematic atlas of neural representations  
- Bridge deep learning, neuroscience, and interpretability  
- Treat neural networks as objects of scientific inquiry rather than purely engineering tools  

Future expansions may include:

- Explicit circuit reconstructions  
- Cross-model representation comparisons  
- Mechanistic experiments via weight editing  
- Universality studies across architectures  

---

## Acknowledgment of Intellectual Lineage

This work builds on decades of research spanning:

- Biological vision  
- Early neural network theory  
- Representation learning  
- Modern interpretability and circuits research  

The goal is not merely to reproduce results, but to internalize and extend the ideas behind them.

---

## Final Note

Understanding neural networks is not about explaining everything at once.  
It is about zooming in until understanding becomes possible.

Readers are encouraged to experiment, modify, extend, and critically question everything in this repository.

