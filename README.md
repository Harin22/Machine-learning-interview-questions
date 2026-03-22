# Machine Learning Interview Questions

A collection of **Machine Learning interview questions explained in simple terms**.  
This repository is built as a personal learning log while preparing for ML/AI roles.

---

## 1. What is Machine Learning?

Machine Learning is a sub field of Artificial Intelligence where computers learn patterns from data instead of being explicitly programmed. Instead of writing rules manually, we train a model using historical data. The model learns relationships in the data and uses those patterns to make predictions on new, unseen data.

Example:  
In spam email detection, we train a model using thousands of emails labeled **spam** or **not spam**.  
The model learns patterns from the data and predicts whether a new email is spam.

---

## 2. Types of Machine Learning

Machine Learning is generally divided into three main categories depending on how the model learns from data.

### 1. Supervised Learning

Supervised learning uses **labeled data**, meaning each input has a known output. The model learns the relationship between input features and the target output.

Example:

Input → House features  
Output → House price

Common Algorithms:

- Linear Regression  
- Logistic Regression  
- Random Forest  
- Support Vector Machines  
- Neural Networks  

---

### 2. Unsupervised Learning

In unsupervised learning, the data **does not have labels**. The model tries to find hidden patterns or structures in the data.

Example:

Customer segmentation in marketing.

Common Algorithms:

- K-Means Clustering  
- Hierarchical Clustering  
- DBSCAN  
- PCA (Dimensionality Reduction)

---

### 3. Reinforcement Learning

In reinforcement learning, an **agent interacts with an environment** and learns by receiving rewards or penalties.The agent improves its strategy over time to maximize the total reward.


Basic Concept:

Agent → Action → Reward → Learning

---

### 4. What's the difference between a parameter and a hyperparameter?

Parameters are learned from data during training (e.g, weights and biases in a neural network, coefficients in linear regression).
Hyperparameters are set before training and control the learning process (e.g. learning rate, number of layers, regularization strength, number of trees). They're tuned via grid search, random search, or Bayesian optimization.
