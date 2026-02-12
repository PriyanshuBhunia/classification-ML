# classification-ML
# Deep Learning Assignment 1
Analysis: https://docs.google.com/document/d/15V9lhkBK7gbBFhssEB9SuGM4M21wIDUjYCjd1AzyVA8/edit?tab=t.0

This repository contains implementations of MLP and CNN models trained and evaluated on the following datasets:

- **UCI Adult Income** (binary classification)
- **CIFAR-10 & CIFAR-100** (image classification)
- **PatchCamelyon (PCam)** (binary classification from medical images)

---

## 📊 Results Summary

| Dataset      | Model | Test Accuracy | F1-score (Macro) |
|--------------|-------|---------------|------------------|
| UCI Adult    | MLP   | 85.11%        | 0.6615           |
| UCI Adult    | CNN   | 84.77%        | 0.6468           |
| CIFAR-10     | MLP   | 52.02%        | 0.5200           |
| CIFAR-10     | CNN   | 73.23%        | 0.7324           |
| CIFAR-100    | MLP   | 13.04%        | 0.1106           |
| CIFAR-100    | CNN   | 37.79%        | 0.3628           |
| PCam (1k)    | MLP   | 81.00%        | 0.8291           |
| PCam (1k)    | CNN   | 78.90%        | 0.7977           |

---

## 🛠️ Frameworks Used

- Python 3.x
- PyTorch
- torchvision
- scikit-learn
- numpy, matplotlib
- Google Colab / Kaggle Notebooks

---

## 📁 Structure

- `notebooks/` — Jupyter/Colab notebooks for each model and dataset
- `models/` — PyTorch model definitions
- `data/` — Dataset handling or links to external sources

---

## 📌 Notes

- PCam was trained using a 1,000 sample subset for speed.
- All experiments used `CrossEntropyLoss` or `BCELoss` as appropriate.
- Results may vary slightly based on CPU/GPU runtime.

---

## 👤 Author

Priyanshu Bhunia
Deep Learning Assignment 1 — Classification
