# **AI & ML Concepts – Algorithms Collection**

This repository contains a curated collection of **Machine Learning** and **Artificial Intelligence** algorithms implemented in **Jupyter Notebooks**.
Each notebook demonstrates the logic, intuition, and working of classical ML/AI algorithms commonly taught in undergraduate AI/ML courses.

The repository also includes sample **datasets (.csv)** used for training and testing each algorithm.

---

## 📌 **Table of Contents**

* [Overview](#overview)
* [Algorithms Implemented](#algorithms-implemented)
* [How to Run the Notebooks](#how-to-run-the-notebooks)
* [Datasets](#datasets)

---

## 🧠 **Overview**

This repo is a consolidated set of important **AI/ML algorithms**, including:

* Basic learning algorithms
* Classification & regression
* Clustering
* Bayesian networks
* Candidate elimination
* Decision trees
* Backpropagation
* EM algorithm
* K-Means
* Hierarchical clustering
* KNN
* Linear regression

Each algorithm is implemented in a clear, easy-to-understand, step-by-step manner suitable for **students**, **beginners**, and **exam preparation**.

---

## 📘 **Algorithms Implemented**

| Algorithm                          | Notebook                                        | Description                                             |
| ---------------------------------- | ----------------------------------------------- | ------------------------------------------------------- |
| **Simple Linear Regression**       | `simple_Linear_Regression.ipynb`                | Implements linear regression using least squares.       |
| **Backpropagation Neural Network** | `Back_propagation.ipynb`                        | Single hidden layer NN with forward/backward pass.      |
| **Candidate Elimination**          | `Candidate_Elimination.ipynb`                   | Finds version space boundaries (G,S sets).              |
| **Decision Tree (ID3 Algorithm)**  | `Decision_Tree_ID3.ipynb`                       | Entropy, Information Gain, ID3 tree construction.       |
| **Expectation Maximization (EM)**  | `EM.ipynb`                                      | EM algorithm for clustering/mixture models.             |
| **FIND-S Algorithm**               | `FIND_S.ipynb`                                  | Learns maximally specific hypothesis.                   |
| **Hierarchical Clustering**        | `Hierarchical_Clustering.ipynb`                 | Single-link/Agglomerative clustering.                   |
| **K-Nearest Neighbors (KNN)**      | `KNN.ipynb`                                     | k-NN classification with Euclidean distance.            |
| **K-Means Clustering**             | `K_Means.ipynb`                                 | K-Means clustering with centroid updates.               |

---

## 📊 **Datasets Included**

Each notebook has its own dataset:

| Dataset                                   | Used In                 |
| ----------------------------------------- | ----------------------- |
| `CE.csv`                                  | Candidate Elimination   |
| `ID3.csv`                                 | Decision Tree (ID3)     |
| `EM.csv`                                  | EM Algorithm            |
| `FIND-S.csv`                              | FIND-S                  |
| `HCC.csv`                                 | Hierarchical Clustering |
| `KNN.csv`                                 | KNN                     |
| `simple_Linear_Regression.csv` *(if any)* | Linear Regression       |

**Important:**
You do **not** need absolute paths like
`C:/Users/<username>/...`
Use **relative paths** instead:

```python
df = pd.read_csv("CE.csv")
```

This prevents leaking your username/path and ensures code runs anywhere.

---
