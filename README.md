# 🏠 Boston Housing Price Prediction 🤖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

> **Deep Learning Assignment 1**: Implementation of Linear Regression algorithms from scratch on the Boston Housing dataset

---

## 📋 Overview

This project implements **two linear regression models from scratch** to predict housing prices using the classic Boston Housing dataset. The implementations showcase fundamental machine learning concepts including least squares optimization and gradient descent methods.

### 🎯 Key Features

- ✨ **Least Squares Solution**: Direct analytical solution for linear regression
- 🎢 **Least Mean Squares (LMS) Algorithm**: Iterative gradient descent approach
- 🔄 **Regularization Analysis**: L2 regularization with multiple lambda values
- 📊 **Statistical Analysis**: Variance computation across different random seeds
- 🎨 **Visualization**: Performance plots and convergence analysis
- 🧪 **Robust Testing**: Multiple random initializations and train-test splits

---

## 🚀 Quick Start

### Prerequisites

```bash
numpy
pandas
matplotlib
jupyter
```

### Installation

1. Clone this repository:
```bash
git clone https://github.com/patrickjcraig/DL-HW1.git
cd DL-HW1
```

2. Install required packages:
```bash
pip install numpy pandas matplotlib jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook Main.ipynb
```

---

## 📂 Project Structure

```
DL-HW1/
│
├── 📓 Main.ipynb                    # Main implementation notebook
├── 📊 boston_housing_data.csv       # Dataset
├── 📄 boston.txt                    # Dataset description
├── 📁 figures/                      # Generated visualizations
│   └── LMS.png                      # LMS convergence plot
├── 📁 report/                       # Assignment reports
├── 📜 LICENSE                       # MIT License
└── 📖 README.md                     # This file
```

---

## 🧮 Methodology

### 1️⃣ Least Squares Solution

The closed-form solution for linear regression:

```
w* = (X^T X)^(-1) X^T y
```

**Features:**
- Direct computation of optimal weights
- Performance analysis without regularization
- Regularization with different λ values
- Comparison of condition numbers

### 2️⃣ Least Mean Squares (LMS) Algorithm

Iterative gradient descent approach:

```
w(t+1) = w(t) - η∇J(w(t))
```

**Features:**
- Multiple learning rate experiments
- Convergence analysis
- Variance computation across random seeds
- Training vs. validation performance tracking

---

## 📈 Results

The project includes comprehensive analysis of:

- 📉 **Mean Squared Error (MSE)** across different configurations
- 📊 **Variance analysis** with multiple random seeds
- 🎯 **Regularization effects** on model performance
- 🔄 **Learning rate sensitivity** in gradient descent
- 📐 **Convergence behavior** visualization

![LMS Convergence](figures/LMS.png)

---

## 🔬 Technical Details

### Data Split
- **Training**: 2/3 of the dataset
- **Testing**: 1/3 of the dataset
- **Random Seeds**: Multiple initializations for robust analysis

### Hyperparameters Explored
- Learning rates: Multiple values tested
- Regularization parameters (λ): Various levels
- Random seeds: Multiple runs for variance computation

---

## 📝 Documentation

Additional documentation includes:
- 📄 **DL_Cheat_Sheet.docx**: Deep learning reference guide
- 📄 **LEAST_MEAN_SQUARE_PROOF.docx**: Mathematical derivations

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Boston Housing dataset from the UCI Machine Learning Repository
- Deep Learning course materials and assignments

---

## 👨‍💻 Author

**Patrick J Craig**

---

<div align="center">

**⭐ Star this repository if you found it helpful! ⭐**

Made with ❤️ for Deep Learning

</div>
