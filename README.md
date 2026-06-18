# Deep Learning Foundations & Neural Architectures Library

A comprehensive, production-grade reference library mapping out the theoretical frameworks, optimization mechanics, and practical implementations of Deep Learning. This repository documents an end-to-end learning paradigm spanning fundamental Artificial Neural Networks (ANN), computer vision via Convolutional Neural Networks (CNN), and sequential/temporal processing through Recurrent Neural Networks (RNN).

---

## 📁 Core Architecture & Syllabus

The repository is divided into three major architectural domains, moving from low-level linear classifiers to deep sequential networks:

```text
├── ANN/ (Artificial Neural Networks)
│   ├── 1. Perceptron.ipynb                    # Linear baseline classifier from scratch
│   ├── 2. Perceptron trick.ipynb              # Vectorized weight update verification
│   ├── 3. Perceptron loss function.ipynb     # Loss landscape optimization geometry
│   ├── 4. MNIST classification overview.ipynb # Multi-class digit classification baseline
│   ├── 5-7. Backpropagation (Reg/Keras/Clf)   # Mathematical gradient distribution loops
│   ├── 8. BatchGD vs StochasticGD.ipynb       # Convergence speed & gradient path variance
│   ├── 9. Vanishing Gradient Problem.ipynb    # Deep network saturation analysis
│   ├── 10. Early-stopping.ipynb               # Epoch convergence optimization
│   ├── 11. Feature Scaling.ipynb              # Loss surface normalization
│   ├── 12-13. Dropout (Reg/Clf).ipynb         # Stochastic co-adaptation regularization
│   ├── 14. Regularization.ipynb               # L1/L2 weight penalty constraints
│   ├── 15. Zeroes & Constant weight init.ipynb# Symmetry breaking failures analysis
│   ├── 16. Batch Normalization.ipynb          # Internal covariate shift dampening
│   └── 17. Keras Tuner.ipynb                  # Automated hyperparameter search space
│
├── CNN/ (Convolutional Neural Networks)
│   ├── 1. Padding & Strides.ipynb             # Spatial dimension conservation math
│   ├── 2. Pooling.ipynb                       # Translational invariance & downsampling
│   ├── 3. LeNet-5 Architecture.ipynb          # Classic multi-layer spatial feature mapping
│   ├── 4. Dog v Cat Classification.ipynb      # High-dimensional binary image pipelines
│   ├── 5. Data Augmentation.ipynb             # Geometric variance transformations
│   ├── 6. Using pretrained models.ipynb       # ImageNet standard inference maps
│   ├── 7-8. Transfer learning (Extract/Tune)  # Core weight freezing vs deep fine-tuning
│   └── 9-11. Functional API Demos             # Multi-input, multi-output graph topologies
│
└── RNN/ (Recurrent Neural Networks)
    ├── 1. Simple RNN architecture.ipynb       # Recurrent hidden state feedback mapping
    ├── 2-3. Sentiment Analysis (Encoding/Emb) # Text vectorization vs dense embedding spaces
    ├── 4. LSTM word prediction project.ipynb  # Long Short-Term Memory gated cell routing
    ├── 5. Deep RNNs.ipynb                     # Stacked temporal feature learning
    └── 6. Bidirectional RNNs.ipynb            # Dual-history causal sequence analysis
```
## 🧠 1. Artificial Neural Networks (ANN)
```
This module acts as the core mathematical anchor for the library, tracing neural networks from singular linear units to deep, multi-layer optimized systems.

Mathematical Optimization: Explores backpropagation from raw gradients up to advanced stochastic optimizers. Documents the geometric pathing updates between Batch, Mini-Batch, and Stochastic Gradient Descent.

Regularization & Diagnostics: Implements code architectures analyzing structural breaking points like Vanishing Gradients caused by derivative saturation. Showcases structural fixes including L1/L2 Regularization, Stochastic Dropout, Layer/Batch Normalization, and Symmetry-Breaking Weight Initialization.
```
## 👁️ 2. Convolutional Neural Networks (CNN)
```
Focuses on spatial computing and feature extraction pipelines optimized for image matrices and computer vision tasks.

Spatial Feature Extractors: Maps out the core mathematics behind sliding window kernels, padding boundaries, stride offsets, and Max/Average pooling matrices.

Advanced Topologies: Progresses from historical benchmarks like LeNet-5 up to modern production paradigms using the Keras Functional API to map out complex multi-input and multi-output network graphs.

Transfer Learning: Implements production-grade model modification by utilizing ImageNet backbones, freezing feature-extraction layers, and fine-tuning deep convolutional blocks for specialized target tasks (e.g., Cat vs. Dog classification).
```
## 🔀 3. Recurrent Neural Networks (RNN)
```
Engineered for temporal dependencies, natural language processing, and variable-length sequence modeling.

Vector Embedding Layers: Features step-by-step pipelines transforming text datasets into model-ready sequences using basic Integer Encoding up to multi-dimensional, trained Dense Embedding Spaces.

Gated Control Sequences: Implements Long Short-Term Memory (LSTM) architectures to combat standard temporal gradient dissipation by utilizing internal input, forget, and output gate routing structures.

Sequence Modeling: Showcases practical contextual systems including text Sentiment Analytics classifiers and automated Next-Word Predictor language engines driven by Bidirectional RNN networks.
```
