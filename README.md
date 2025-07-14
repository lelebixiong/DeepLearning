# 🔗 Deep Learning on Graphs: GNN Playground

A modular and extensible PyTorch-based project for experimenting with **Graph Neural Networks (GNNs)** on various datasets including citation networks, molecular graphs, and social networks.

## 📚 Overview

Graph-structured data appears in many real-world applications, such as:

- Social networks (e.g., Twitter, Facebook)
- Biological systems (e.g., protein-protein interaction networks)
- Knowledge graphs (e.g., Freebase, ConceptNet)
- Molecules (e.g., atoms as nodes, bonds as edges)

This project implements and compares popular GNN models:

- **GCN** (Graph Convolutional Network)
- **GAT** (Graph Attention Network)
- **GraphSAGE**
- **GIN** (Graph Isomorphism Network)
- **MPNN** (Message Passing Neural Network)

All models are evaluated on common benchmarks like **Cora**, **Citeseer**, **PubMed**, **ZINC**, and **ogbn-arxiv**.

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/yourname/gnn-playground.git
cd gnn-playground
```

### 2. Install Dependencies

```bash
复制
编辑
pip install -r requirements.txt
```

This will install:
- **torch**
- **torch_geometric**
- **networkx**
- **tqdm**
- **matplotlib** 
- **scikit-learn**

## 🧠 Available Models

| Model     | Paper Reference                                             | Notes                      |
| --------- | ----------------------------------------------------------- | -------------------------- |
| GCN       | [Kipf & Welling, 2017](https://arxiv.org/abs/1609.02907)    | Spectral-based convolution |
| GAT       | [Velickovic et al., 2018](https://arxiv.org/abs/1710.10903) | Attention on neighbors     |
| GraphSAGE | [Hamilton et al., 2017](https://arxiv.org/abs/1706.02216)   | Sampling-based aggregator  |
| GIN       | [Xu et al., 2018](https://arxiv.org/abs/1810.00826)         | Strong expressiveness      |

## 🧪 Evaluation Metrics

We support the following metrics:

- **Accuracy, F1-score (Node classification)**

- **MAE, RMSE (Regression tasks)**

- **AUC-ROC (Graph classification)**

## 🧩 Project Structure

gnn-playground/

├── models/           # GCN, GAT, etc.

├── datasets/         # Dataset loaders

├── utils/            # Metrics, training utils

├── configs/          # YAML config files

├── train.py          # Training entry point

└── evaluate.py       # Evaluation script




