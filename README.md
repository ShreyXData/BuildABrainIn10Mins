# 🧠 Build A Brain in 10 Minutes

![Cover](./cover.png)

[![Run on Kaggle](https://img.shields.io/badge/Run%20on-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/code/shreyxdata/build-a-brain-by-shrey)

> ✨ A quick and beginner-friendly project that teaches you how to build a simple neural network (a tiny artificial brain!) using Python + PyTorch. Train it to learn patterns like a human would — and all of this in just 10 minutes!

---

## 📚 About the Dataset

This project uses the **MNIST dataset** in IDX format — a classic dataset of handwritten digits (0 to 9).

| File Name                 | Description                    |
|--------------------------|--------------------------------|
| `train-images-idx3-ubyte` | 60,000 training digit images   |
| `train-labels-idx1-ubyte` | Labels (0–9) for training data |
| `t10k-images-idx3-ubyte`  | 10,000 test digit images       |
| `t10k-labels-idx1-ubyte`  | Labels for test data           |

The images are 28x28 grayscale and are loaded using Python's `struct` module.

---

## 🧠 What You'll Learn

- ✅ How to build a neural network from scratch using PyTorch
- ✅ How to load and train on real image data
- ✅ How machines learn using pattern recognition
- ✅ How to visualize predictions and results

---

## 🚀 How to Run It

> Want to try it yourself? Just click below:

[![Run on Kaggle](https://img.shields.io/badge/Run%20on-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/code/shreyxdata/build-a-brain-by-shrey)

Kaggle gives you:
- Free GPU 💻⚡
- No setup required
- Fast execution and sharing

---

## 🎥 Preview (Optional)

> *(You can upload a screenshot or GIF of the output later here)*

```python
# Example: Code to visualize first few training images
import matplotlib.pyplot as plt

fig, axes = plt.subplots(1, 10, figsize=(15, 2))
for i in range(10):
    axes[i].imshow(train_images[i][0], cmap="gray")
    axes[i].set_title(f"Label: {train_labels[i].item()}")
    axes[i].axis("off")
plt.show()





