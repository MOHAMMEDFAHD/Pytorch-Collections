#  Convolutional Neural Networks (CNN) — Replication Labs

Welcome to the **CNN Collection** of the **Programming Ocean Academy**   
This repository offers a **didactic atlas** of convolutional architectures — from the early days of LeNet to hybrid Conv-Transformer models in 2025.

Our philosophy: **learn by replicating history**. Each notebook is a hands-on reproduction of a seminal CNN paper — connecting **theory → PyTorch code → results**.

---

##  Historical Context: CNNs (1997 → 2025)

Convolutional Neural Networks have **revolutionized computer vision**, enabling AI to see and understand pixels. This collection chronicles their **milestones**:

- **1997** – LeNet-5 (*LeCun et al.*)  
  → Handwritten digit recognition; early use of convolutions + subsampling  

- **2012** – AlexNet (*Krizhevsky et al.*)  
  → ImageNet breakthrough; ReLU, dropout, GPU training  

- **2014** – VGGNet (*Simonyan & Zisserman*)  
  → Deep stacks of 3×3 convs; simplicity + depth  

- **2014** – GoogLeNet / Inception (*Szegedy et al.*)  
  → Inception modules, multi-scale features, efficiency  

- **2015** – ResNet (*He et al.*)  
  → Skip connections; enables ultra-deep architectures  

- **2016** – DenseNet (*Huang et al.*)  
  → Dense connectivity; feature reuse  

- **2016** – Xception (*Chollet*)  
  → Depthwise separable convolutions  

- **2017** – SENet (*Hu et al.*)  
  → Squeeze-and-excitation blocks for channel attention  

- **2017** – FractalNet (*Larsson et al.*)  
  → Implicit deep ensembles with fractal patterns  

- **2018** – EfficientNet (*Tan & Le*)  
  → Compound scaling: balance depth, width, resolution  

- **2019–2021** – MobileNets / SqueezeNets  
  → Tiny CNNs for mobile and edge devices  

- **2020–2023** – Vision Transformers (ViT, Swin)  
  → CNNs challenged by pure attention models  

- **2023–2025** – Hybrid CNN–Transformer Models  
  → CNNs evolve to integrate attention mechanisms  

---

##  Repository Structure

Each notebook is a **self-contained lab**: mathematical background, PyTorch implementation, and reproducible experiments.

### 🔬 Core CNN Replications

| Notebook | Description |
|----------|-------------|
| `A_Pedagogical_Exposition_of_Convolutional_Neural_Networks_for_Image_Classification.ipynb` | Intro to convolutions, pooling, ReLU, backprop. |
| `MiniAlexNetEdu_A_Pedagogical_Deep_Convolutional_Prototype.ipynb` | Compact AlexNet-style network (ImageNet influence). |
| `MicroVGGNet_A_Didactic_VGG-Derived_Framework.ipynb` | Simple VGG-style model with deep stacks of convs. |
| `Mini-InceptNet_A_Pedagogical_Inception-Based_Architecture.ipynb` | Reproduction of Inception blocks (GoogLeNet). |
| `Deep_Residual_Networks_from_First_Principles_A_Creative_Replication_of_ResNet.ipynb` | ResNet with skip connections from scratch. |
| `Residual_Learning_in_Action_A_Lightweight_ResNet_Bottleneck.ipynb` | Bottleneck implementation in ResNet-50 style. |

---

###  Advanced CNN Variants

| Notebook | Description |
|----------|-------------|
| `Pedagogical_Replication_of_DenseNet.ipynb` | Feature reuse via dense connectivity (DenseNet). |
| `Replication_of_Xception_A_Concise_Implementation.ipynb` | Depthwise separable convolutions (Xception). |
| `Reproducing_Squeeze-and-Excitation_Networks.ipynb` | Channel recalibration with SE blocks. |
| `ReproFractalNet_2017_A_PyTorch_Replication.ipynb` | Self-similar fractal CNNs with dropout alternatives. |
| `Replication_of_EfficientNet_A_Concise_Implementation.ipynb` | Compound scaling CNN (EfficientNet). |
| `Pedagogical_Replication_of_MobileNet.ipynb` | Lightweight mobile architecture using depthwise convs. |
| `Educational_SqueezeNet-Lite.ipynb` | Ultra-compact CNN with fire modules. |

---

###  Exploratory & Modern Labs

| Notebook | Description |
|----------|-------------|
| `DotVisionNet_A_Minimalist_Framework_for_Visual_Counting.ipynb` | Minimalist CNN for object counting. |
| `Pedagogical_Replication_of_Transformer_Architecture_in_CNN_Context.ipynb` | CNN → ViT hybrid explorations. |
| `Laboratory_Replication_of_Capsule_Networks_Dynamic_Routing.ipynb` | Capsules (Sabour et al., 2017) with dynamic routing. |

---

##  Suggested Learning Path

1.  **Start Simple**: `Intro CNN`, `MiniAlexNet`, `MicroVGGNet`  
2.  **Go Deeper**: `Mini-InceptNet`, `ResNet`, `DenseNet`  
3.  **Explore Efficiency**: `MobileNet`, `SqueezeNet`, `EfficientNet`  
4.  **Add Attention**: `SENet`, `ConvTransformer`, `Capsule Networks`  
5.  **Go Modern**: Vision Transformers, hybrids, and counting networks

---

##  Key References

- LeCun, Y. et al. (1998). *Gradient-Based Learning Applied to Document Recognition*  
- Krizhevsky, A. et al. (2012). *ImageNet Classification with Deep Convolutional Neural Networks*  
- Simonyan, K., & Zisserman, A. (2014). *Very Deep Convolutional Networks for Large-Scale Image Recognition*  
- Szegedy, C. et al. (2014). *Going Deeper with Convolutions*  
- He, K. et al. (2015). *Deep Residual Learning for Image Recognition*  
- Huang, G. et al. (2016). *Densely Connected Convolutional Networks*  
- Chollet, F. (2016). *Xception: Deep Learning with Depthwise Separable Convolutions*  
- Hu, J. et al. (2017). *Squeeze-and-Excitation Networks*  
- Tan, M., & Le, Q. (2018). *EfficientNet: Rethinking Model Scaling for CNNs*  
- Dosovitskiy, A. et al. (2020). *An Image is Worth 16x16 Words* (ViT)

---

##  Vision

This is not just a repo. It’s a **learning platform** and **historical archive** of CNN progress.

-  Understand design choices behind each architecture  
-  Compare performance, parameters, and efficiency  
-  Get inspired to build the next generation of **hybrid models** combining **CNNs, RNNs, and Transformers**

---

 **AI Era: Teaching AI by Recreating Its History**  
Replicate. Learn. Innovate. 

