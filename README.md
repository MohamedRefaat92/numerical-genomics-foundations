# Numerical Methods for Functional Genomics

A comprehensive learning repository covering mathematical foundations for computational genomics, with applications in transcriptomics, DNA methylation, and cancer research.

## 🎯 Learning Objectives

- Master calculus and optimization for machine learning
- Understand numerical linear algebra foundations
- Connect mathematical concepts to genomics tools (DESeq2, scVI, etc.)
- Build intuition through PyTorch implementations

## 📚 Resources Used

| Book | Strength | Primary Use |
|------|----------|-------------|
| **Numerical Algorithms** (Solomon) | Rigorous proofs | Core algorithms |
| **Practical Linear Algebra** (Cohen) | Geometric intuition | Visualization |
| **Why Machines Learn** (Ananthaswamy) | Historical context | Understanding "why" |
| **Introduction to Statistical Learning** | Statistical perspective | Inference |
| **Machine Learning Algorithms in Depth** (Smolyakov) | Implementations | Code patterns |
| **Deep Learning with PyTorch** | Neural networks | DL applications |

## 📁 Repository Structure

```
numerical-genomics-foundations/
├── README.md
├── requirements.txt
├── phase1-foundations/
│   ├── module1.1-calculus-optimization/
│   │   ├── 01_gradients_derivatives.ipynb
│   │   ├── 02_hessian_newton.ipynb
│   │   ├── 03_jacobian_backprop.ipynb
│   │   ├── 04_autodiff.ipynb
│   │   └── 05_genomics_applications.ipynb
│   └── module1.2-linear-systems/
│       └── (coming soon)
├── phase2-decompositions/
│   └── (SVD, PCA, eigendecomposition)
├── phase3-optimization/
│   └── (advanced optimization methods)
├── data/
│   └── (sample datasets)
└── utils/
    └── (helper functions)
```

## 🚀 Getting Started

### Prerequisites

```bash
# Create conda environment
conda create -n genomics-math python=3.10
conda activate genomics-math

# Install dependencies
pip install -r requirements.txt
```

### Running Notebooks

```bash
# Start Jupyter
jupyter notebook

# Or use JupyterLab
jupyter lab
```

## 📖 Phase 1: Foundations

### Module 1.1: Calculus & Optimization ✅

| Notebook | Topics | Key Concepts |
|----------|--------|--------------|
| `01_gradients_derivatives` | Partial derivatives, gradient vector | ∇f, directional derivative |
| `02_hessian_newton` | Second derivatives, optimization | Hessian, positive definiteness, Newton's method |
| `03_jacobian_backprop` | Vector-valued functions | Jacobian, chain rule, backpropagation |
| `04_autodiff` | Automatic differentiation | Computation graphs, forward/backward mode |
| `05_genomics_applications` | DESeq2, scVI internals | IRLS, condition numbers |

### Module 1.2: Linear Systems & Least Squares ⏳

Coming soon...

## 🧬 Genomics Connections

Throughout these notebooks, we connect math to real genomics:

- **Gradient descent** → Neural network training in scVI
- **Hessian/Newton** → DESeq2's IRLS algorithm
- **Condition numbers** → Why some analyses fail
- **Jacobian** → Backpropagation in gene expression autoencoders

## 📝 License

Educational use. See individual resources for their licenses.

## 🤝 Acknowledgments

Developed through interactive learning sessions, integrating multiple textbook perspectives with genomics applications.
