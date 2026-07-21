# 🤖 Machine Learning Algorithms

A structured and continuously growing collection of **Machine Learning, Deep Learning, Reinforcement Learning, Probabilistic Models, and Semi-Supervised Learning** algorithms.

This repository is my personal learning journey and reference library. Every algorithm includes clean notes, intuitive explanations, mathematical foundations, interview concepts, and Python implementations whenever possible.

The goal isn't just to learn how to use an algorithm—but to understand **how it works, when to use it, why it works, and its strengths and limitations.**

---

# 📚 Repository Structure

```
Machine-Learning-Algorithm/
│
├── Supervised Learning/
│   │
│   ├── Regression/
│   │   ├── Linear Regression
│   │   ├── Polynomial Regression
│   │   ├── Ridge Regression
│   │   ├── Lasso Regression
│   │   ├── Elastic Net
│   │   ├── Support Vector Regression (SVR)
│   │   ├── Bayesian Linear Regression
│   │   ├── Quantile Regression
│   │   └── Poisson Regression
│   │
│   ├── Classification/
│   │   ├── Logistic Regression
│   │   ├── K-Nearest Neighbors (KNN)
│   │   ├── Support Vector Machine (SVM)
│   │   ├── Naive Bayes
│   │   ├── Decision Tree
│   │   ├── Linear Discriminant Analysis (LDA)
│   │   ├── Quadratic Discriminant Analysis (QDA)
│   │   └── Perceptron
│   │
│   └── Ensemble Learning/
│       ├── Bagging
│       ├── Random Forest
│       ├── Extra Trees
│       ├── AdaBoost
│       ├── Gradient Boosting
│       ├── XGBoost
│       ├── LightGBM
│       ├── CatBoost
│       ├── Stacking
│       └── Voting Classifier
│
├── Unsupervised Learning/
│   │
│   ├── Clustering/
│   │   ├── K-Means
│   │   ├── Hierarchical Clustering
│   │   ├── DBSCAN
│   │   ├── OPTICS
│   │   ├── Mean Shift
│   │   ├── Gaussian Mixture Model (GMM)
│   │   ├── Spectral Clustering
│   │   ├── Affinity Propagation
│   │   └── BIRCH
│   │
│   ├── Dimensionality Reduction/
│   │   ├── Principal Component Analysis (PCA)
│   │   ├── Linear Discriminant Analysis (LDA)
│   │   ├── t-SNE
│   │   ├── UMAP
│   │   ├── Independent Component Analysis (ICA)
│   │   ├── Factor Analysis
│   │   ├── Kernel PCA
│   │   ├── Singular Value Decomposition (SVD)
│   │   └── Non-Negative Matrix Factorization (NMF)
│   │
│   └── Association Rule Learning/
│       ├── Apriori
│       ├── Eclat
│       └── FP-Growth
│
├── Semi-Supervised Learning/
│   ├── Label Propagation
│   ├── Label Spreading
│   ├── Self-Training
│   └── Co-Training
│
├── Probabilistic Graphical Models/
│   ├── Hidden Markov Model (HMM)
│   ├── Bayesian Network
│   ├── Markov Random Field (MRF)
│   └── Conditional Random Field (CRF)
│
├── Deep Learning/
│   ├── Artificial Neural Network (ANN)
│   ├── Convolutional Neural Network (CNN)
│   ├── Recurrent Neural Network (RNN)
│   ├── Long Short-Term Memory (LSTM)
│   ├── Gated Recurrent Unit (GRU)
│   ├── Transformer
│   ├── Autoencoder
│   ├── Variational Autoencoder (VAE)
│   ├── Generative Adversarial Network (GAN)
│   ├── Self-Organizing Map (SOM)
│   ├── Radial Basis Function Network (RBFN)
│   ├── Deep Belief Network (DBN)
│   ├── Restricted Boltzmann Machine (RBM)
│   └── Graph Neural Network (GNN)
│
├── Reinforcement Learning/
│   ├── Q-Learning
│   ├── Deep Q-Network (DQN)
│   ├── SARSA
│   ├── Policy Gradient
│   ├── Actor-Critic
│   ├── Deep Deterministic Policy Gradient (DDPG)
│   ├── Proximal Policy Optimization (PPO)
│   ├── Trust Region Policy Optimization (TRPO)
│   ├── Monte Carlo Tree Search (MCTS)
│   └── Asynchronous Advantage Actor-Critic (A3C)
│
└── README.md
```

---

# 🎯 Repository Goals

This repository focuses on understanding algorithms from first principles.

For every algorithm, I aim to include:

- ✅ Plain-English explanation
- ✅ Mathematical intuition
- ✅ Core equations
- ✅ Step-by-step working
- ✅ Visual illustrations
- ✅ Python implementation
- ✅ Scikit-Learn (or framework) example
- ✅ Hyperparameters
- ✅ Advantages & disadvantages
- ✅ Real-world applications
- ✅ Interview questions
- ✅ Common mistakes
- ✅ Comparison with similar algorithms

---

# 📖 Learning Categories

## 🟢 Supervised Learning

Algorithms trained using labeled data.

### Regression
Predict continuous numerical values.

Examples:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Polynomial Regression
- SVR
- Bayesian Regression
- Quantile Regression
- Poisson Regression

---

### Classification

Predict discrete classes.

Examples:

- Logistic Regression
- KNN
- SVM
- Naive Bayes
- Decision Tree
- Perceptron
- LDA
- QDA

---

### Ensemble Learning

Combine multiple models for stronger predictions.

Examples:

- Random Forest
- Bagging
- Extra Trees
- AdaBoost
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost
- Stacking
- Voting Classifier

---

# 🔵 Unsupervised Learning

Learn patterns from unlabeled data.

### Clustering

- K-Means
- Hierarchical Clustering
- DBSCAN
- OPTICS
- Mean Shift
- Gaussian Mixture Models
- Spectral Clustering
- Affinity Propagation
- BIRCH

---

### Dimensionality Reduction

Reduce feature dimensions while preserving information.

Examples:

- PCA
- Kernel PCA
- ICA
- LDA
- t-SNE
- UMAP
- SVD
- NMF
- Factor Analysis

---

### Association Rule Learning

Discover relationships between items.

Examples:

- Apriori
- Eclat
- FP-Growth

---

# 🟡 Semi-Supervised Learning

Learn using a small amount of labeled data and a large amount of unlabeled data.

Algorithms:

- Label Propagation
- Label Spreading
- Self-Training
- Co-Training

---

# 🟣 Probabilistic Graphical Models

Model uncertainty using probability graphs.

Algorithms:

- Hidden Markov Model (HMM)
- Bayesian Network
- Markov Random Field (MRF)
- Conditional Random Field (CRF)

---

# 🔴 Deep Learning

Neural network architectures for complex learning tasks.

Algorithms:

- ANN
- CNN
- RNN
- LSTM
- GRU
- Transformer
- Autoencoder
- Variational Autoencoder
- GAN
- SOM
- RBF Network
- Deep Belief Network
- Restricted Boltzmann Machine
- Graph Neural Network

---

# 🟠 Reinforcement Learning

Learning by interacting with an environment.

Algorithms:

- Q-Learning
- Deep Q-Network (DQN)
- SARSA
- Policy Gradient
- Actor-Critic
- DDPG
- PPO
- TRPO
- Monte Carlo Tree Search
- A3C

---

# 💻 Tech Stack

- Python
- NumPy
- Pandas
- Scikit-Learn
- TensorFlow
- PyTorch
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Akram23679/Machine-Learning-Algorithm.git
```

Move into the project:

```bash
cd Machine-Learning-Algorithm
```

Launch Jupyter:

```bash
jupyter notebook
```

Open any notebook or notes and start exploring.

---

# 🎓 Who Is This Repository For?

- Students
- Beginners learning Machine Learning
- Data Science learners
- AI enthusiasts
- Interview preparation
- Placement preparation
- Revision before exams
- Anyone wanting clean explanations with working examples

---

# 📈 Repository Status

🚧 This repository is actively growing.

Current focus includes:

- More mathematical derivations
- Better visual explanations
- End-to-end projects
- Interview notes
- Python implementations
- Real-world datasets
- Deep Learning architectures
- Reinforcement Learning algorithms

New algorithms and improvements are added regularly.

---

# ⭐ Support

If this repository helps you learn Machine Learning, consider giving it a **⭐ Star**.

It motivates me to continue adding high-quality notes, visual explanations, implementations, and projects for the community.

Happy Learning! 🚀
