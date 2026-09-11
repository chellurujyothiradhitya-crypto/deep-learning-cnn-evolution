# Evolution of Deep Convolutional Neural Networks

A research report and PyTorch implementation analyzing the structural evolution of CNNs—from LeNet-5 to ResNet—featuring a custom modular hybrid classifier trained on CIFAR-10.

---

## 📌 Features & Highlights
* **Theoretical Report:** Comprehensive analysis covering LeNet-5, AlexNet, VGGNet, GoogLeNet, and ResNet.
* **Modular Modules:** Custom, parameterized PyTorch implementations for `VGGBlock` and `ResidualBlock`.
* **PyTorch Lightning Pipeline:** Fully automated training pipeline with real-time loss, accuracy monitoring, and dynamic learning rate scheduling.

---

## 📊 Performance Results (CIFAR-10)

| Metric | Output Value |
| :--- | :--- |
| **Total Parameters** | ~1.2 Million |
| **Training Epochs** | 20 |
| **Validation Accuracy** | ~85% - 88% |
| **Validation Loss** | ~0.35 - 0.45 |

---

## 📁 Repository Structure

```text
├── report/
│   └── Evolution_of_Deep_CNNs_Report.pdf  # Submitted Written Report
├── notebooks/
│   └── cnn_evolution_cifar10.ipynb        # Complete Kaggle/Jupyter Notebook
├── src/
│   ├── models.py                          # Parameterized VGG & Residual Blocks
│   └── train.py                           # PyTorch Lightning Training Script
├── requirements.txt                       # Project Dependencies
└── README.md                              # Documentation
