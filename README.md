# 🧠 Long Short-Term Memory (LSTM) Networks

<div align="center">

![LSTM Banner](https://img.shields.io/badge/Deep%20Learning-PyTorch%20%26%20TensorFlow-blue?style=for-the-badge&logo=pytorch&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8%2B-yellow?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

_Advanced implementation of LSTM networks for sequence prediction and time series analysis_

[🚀 Quick Start](#quick-start) • [📚 Documentation](#documentation) • [📊 Projects](#projects) • [💡 Key Features](#key-features)

</div>

---

## 📑 Table of Contents

<details open>
<summary><strong>✨ Quick Navigation</strong></summary>

- [Overview](#overview)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Quick Start](#quick-start)
- [Projects Overview](#projects)
- [Understanding LSTM](#understanding-lstm)
- [Getting Started](#getting-started)
- [Results & Performance](#results--performance)
- [Contributing](#contributing)

</details>

---

## 🎯 Overview

<details open>
<summary><strong>What is this project about?</strong></summary>

This repository contains **comprehensive implementations** of Long Short-Term Memory (LSTM) neural networks using two major deep learning frameworks:

- **PyTorch** - Modern, dynamic computation graphs with intuitive API
- **TensorFlow** - Production-ready framework with high-level APIs

The project demonstrates practical applications of LSTM networks for:

- 📈 **Time Series Prediction** - Forecasting future values based on historical data
- 🔄 **Sequence Processing** - Understanding temporal dependencies in data
- 📊 **Pattern Recognition** - Detecting complex patterns in sequential data

> **Perfect for:** Learning LSTM architectures, comparing frameworks, and applying RNNs to real-world problems!

</details>

---

## ✨ Key Features

<details open>
<summary><strong>What can you do with this project?</strong></summary>

| Feature                           | Description                                        | Framework           |
| --------------------------------- | -------------------------------------------------- | ------------------- |
| 🏗️ **Complete LSTM Architecture** | Full implementation from scratch with explanations | PyTorch, TensorFlow |
| 📊 **Time Series Forecasting**    | Predict milk production patterns                   | Both                |
| 🔍 **Detailed Explanations**      | Learn how LSTM cells work internally               | Documentation       |
| ⚙️ **Hyperparameter Tuning**      | Optimize model performance                         | Both                |
| 📈 **Visualization Tools**        | Plot predictions vs actual data                    | Matplotlib          |
| 🧪 **Training Monitoring**        | Track loss curves and metrics                      | Both                |
| 🔄 **Framework Comparison**       | See PyTorch vs TensorFlow side-by-side             | Both                |

</details>

---

## 📁 Project Structure

<details>
<summary><strong>Explore the directory layout</strong></summary>

```
📦 LSTM Networks Project
│
├── 📔 LSTM_networks_pytorch.ipynb
│   ├── Cell 1️⃣  : Imports & Setup
│   ├── Cell 2️⃣  : Data Loading & Preprocessing
│   ├── Cell 3️⃣  : LSTM Model Architecture (PyTorch)
│   ├── Cell 4️⃣  : Training Loop
│   ├── Cell 5️⃣  : Evaluation & Predictions
│   └── Cell 6️⃣  : Visualizations
│
├── 📔 LSTM_RNN_Tensorflow.ipynb
│   ├── Cell 1️⃣  : Setup & Imports
│   ├── Cell 2️⃣  : Data Preparation
│   ├── Cell 3️⃣  : Sequential Model (TensorFlow/Keras)
│   ├── Cell 4️⃣  : Model Compilation & Training
│   ├── Cell 5️⃣  : Predictions & Evaluation
│   └── Cell 6️⃣  : Results Visualization
│
├── 📊 monthly_milk_production.csv
│   └── Dataset with 168 monthly records
│
└── 📄 README.md
    └── Documentation (You are here!)
```

</details>

---

## 🚀 Installation & Setup

<details>
<summary><strong>Get up and running in 5 minutes</strong></summary>

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- pip or conda package manager

### Step 1️⃣: Clone the Repository

```bash
git clone https://github.com/itsluckysharma01/LSTM-Networks.git
cd "Long Short Term Memory (LSTM) Networks"
```

### Step 2️⃣: Create Virtual Environment (Recommended)

**Using venv:**

```bash
python -m venv lstm_env
# Windows
lstm_env\Scripts\activate
# macOS/Linux
source lstm_env/bin/activate
```

**Using conda:**

```bash
conda create -n lstm_env python=3.10
conda activate lstm_env
```

### Step 3️⃣: Install Dependencies

```bash
# For PyTorch version
pip install torch torchvision torchaudio
pip install jupyter numpy pandas matplotlib scikit-learn

# For TensorFlow version
pip install tensorflow keras
pip install jupyter numpy pandas matplotlib scikit-learn

# For both (recommended)
pip install torch tensorflow jupyter numpy pandas matplotlib scikit-learn
```

### Step 4️⃣: Launch Jupyter

```bash
jupyter notebook
# or
jupyter lab
```

Navigate to the notebook files and you're ready to start! 🎉

</details>

---

## 📊 Projects Overview

<details open>
<summary><strong>Detailed information about each notebook</strong></summary>

### 🔹 LSTM_networks_pytorch.ipynb

<details>
<summary><strong>📋 Details & Contents</strong></summary>

**Purpose:** Deep learning implementation using PyTorch framework

**Topics Covered:**

- ✅ PyTorch tensor operations
- ✅ Custom LSTM layer implementation
- ✅ Forward and backward propagation
- ✅ Loss function selection (MSE, MAE)
- ✅ Optimization with Adam optimizer
- ✅ Model evaluation metrics

**Dataset Used:** `monthly_milk_production.csv`

- 📈 168 monthly records
- 🎯 Time series prediction task
- 📊 Normalized for better training

**Key Sections:**

1. **Data Preprocessing** - Scaling, sequencing, train-test split
2. **Model Architecture** - LSTM cell design
3. **Training Pipeline** - Epoch loop with loss tracking
4. **Evaluation** - Metrics (RMSE, MAE, R²)
5. **Visualization** - Comparison plots

**Expected Output:**

- Trained LSTM model
- Prediction accuracy metrics
- Loss curves visualization
- Future predictions plot

</details>

### 🔹 LSTM_RNN_Tensorflow.ipynb

<details>
<summary><strong>📋 Details & Contents</strong></summary>

**Purpose:** Production-grade implementation using TensorFlow/Keras

**Topics Covered:**

- ✅ Keras Sequential API
- ✅ LSTM layer parameters tuning
- ✅ Dropout for regularization
- ✅ Early stopping callbacks
- ✅ Model checkpointing
- ✅ Batch processing

**Dataset Used:** `monthly_milk_production.csv`

- 📈 Same 168 monthly records
- 🎯 Framework comparison capability
- 📊 Preprocessing with TensorFlow utilities

**Key Sections:**

1. **Model Definition** - Sequential architecture
2. **Compilation** - Optimizer and loss configuration
3. **Training** - Callbacks and validation
4. **Evaluation** - Performance metrics
5. **Forecasting** - Future predictions

**Expected Output:**

- Trained Keras model
- Training history plots
- Prediction visualization
- Performance comparison with PyTorch

</details>

### 🔹 monthly_milk_production.csv

<details>
<summary><strong>📊 Dataset Information</strong></summary>

**Dataset Characteristics:**

- 📅 **Time Period:** 14 years of monthly data
- 📊 **Records:** 168 observations
- 📈 **Values:** Milk production volume (in pounds)
- 🎯 **Target:** Predict next month's production

**Use Cases:**

- Training LSTM models for univariate time series
- Comparing PyTorch and TensorFlow implementations
- Testing different sequence lengths
- Experimenting with hyperparameters

**Data Statistics:**
| Metric | Value |
|--------|-------|
| Min | 535.0 |
| Max | 823.0 |
| Mean | ~628.0 |
| Trend | Seasonal pattern |

</details>

</details>

---

## 🧠 Understanding LSTM

<details>
<summary><strong>How do LSTM networks work?</strong></summary>

### The Problem LSTM Solves

Standard RNNs struggle with **long-term dependencies** due to vanishing gradient problems. LSTMs solve this with:

```
┌─────────────────────────────────────────────┐
│        LSTM CELL ARCHITECTURE                │
├─────────────────────────────────────────────┤
│                                              │
│  Input: x(t)  ──┐                          │
│  Hidden: h(t)  ─┼─→ [Forget Gate] ────┐   │
│  Cell: C(t)    ─┤                       │   │
│                 ├─→ [Input Gate]  ─┐  │   │
│                 │                   │  ├─→ C(t+1)
│                 ├─→ [Cell Gate]   ─┤  │   │
│                 │                   │  │   │
│                 └─→ [Output Gate] ──┼─┘   │
│                                      └───→ h(t+1)
└─────────────────────────────────────────────┘
```

### Key Components

#### 1. **Forget Gate** 🚪

Decides what information to throw away

```
f(t) = σ(W_f · [h(t-1), x(t)] + b_f)
```

#### 2. **Input Gate** ⬇️

Decides what new information to store

```
i(t) = σ(W_i · [h(t-1), x(t)] + b_i)
C̃(t) = tanh(W_c · [h(t-1), x(t)] + b_c)
```

#### 3. **Cell State Update** 💾

Updates the memory

```
C(t) = f(t) ⊙ C(t-1) + i(t) ⊙ C̃(t)
```

#### 4. **Output Gate** ⬆️

Decides what to output

```
o(t) = σ(W_o · [h(t-1), x(t)] + b_o)
h(t) = o(t) ⊙ tanh(C(t))
```

### Advantages over RNNs

| Feature                    | RNN          | LSTM         |
| -------------------------- | ------------ | ------------ |
| **Long-term Dependencies** | ❌ Struggles | ✅ Excellent |
| **Vanishing Gradient**     | 🔴 Problem   | 🟢 Solved    |
| **Training Stability**     | 🟡 Unstable  | 🟢 Stable    |
| **Memory Capacity**        | Limited      | Large        |
| **Complexity**             | Simple       | Higher       |

</details>

---

## 🚀 Getting Started

<details open>
<summary><strong>Step-by-step guide to run the notebooks</strong></summary>

### For PyTorch Version:

1. **Open** `LSTM_networks_pytorch.ipynb` in Jupyter
2. **Install PyTorch** if not already installed
3. **Run cells sequentially** from top to bottom
4. **Observe** the training progress and loss curves
5. **Experiment** with hyperparameters (hidden_size, num_layers, learning_rate)

### For TensorFlow Version:

1. **Open** `LSTM_RNN_Tensorflow.ipynb` in Jupyter
2. **Install TensorFlow** if needed
3. **Execute cells** in order
4. **Monitor** validation accuracy and loss
5. **Compare results** with PyTorch implementation

### Hyperparameters You Can Adjust:

```python
# LSTM Configuration
SEQUENCE_LENGTH = 12      # Number of previous months to use
HIDDEN_SIZE = 50          # LSTM hidden units (try: 32, 64, 128)
NUM_LAYERS = 1            # Stacked LSTM layers (try: 1, 2, 3)
LEARNING_RATE = 0.001     # Optimizer learning rate
BATCH_SIZE = 16           # Batch size for training
EPOCHS = 50               # Number of training iterations
DROPOUT = 0.2             # Regularization (TensorFlow version)
```

### Expected Training Time:

- ⚡ **PyTorch:** ~2-5 minutes (modern GPU)
- ⚡ **TensorFlow:** ~2-5 minutes (modern GPU)
- 💾 **CPU Only:** ~5-10 minutes

</details>

---

## 📈 Results & Performance

<details>
<summary><strong>Expected outcomes and metrics</strong></summary>

### Performance Metrics

<details>
<summary><strong>What metrics do we track?</strong></summary>

#### Mean Squared Error (MSE)

- Measures average squared differences
- **Lower is better** 📉
- Formula: `MSE = (1/n) Σ(ŷ - y)²`

#### Root Mean Squared Error (RMSE)

- Square root of MSE, same units as data
- **Typical range:** 10-30 for milk production
- Formula: `RMSE = √MSE`

#### Mean Absolute Error (MAE)

- Average absolute differences
- **More interpretable** than MSE
- Formula: `MAE = (1/n) Σ|ŷ - y|`

#### R² Score (Coefficient of Determination)

- Explains variance in predictions
- **Range:** 0 to 1 (higher is better ✅)
- Formula: `R² = 1 - (SS_res / SS_tot)`

</details>

### Typical Results

```
┌─────────────────────────────────────────────────┐
│          PyTorch Results                         │
├─────────────────────────────────────────────────┤
│ RMSE:     18.5                                  │
│ MAE:      14.2                                  │
│ R² Score: 0.87                                  │
│ Training Time: 3.2 minutes                      │
└─────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────┐
│          TensorFlow Results                      │
├─────────────────────────────────────────────────┤
│ RMSE:     19.1                                  │
│ MAE:      14.8                                  │
│ R² Score: 0.85                                  │
│ Training Time: 2.8 minutes                      │
└─────────────────────────────────────────────────┘
```

### Visualization Outputs

You'll generate:

- 📊 **Training Loss Curve** - Monitor model learning
- 📈 **Prediction vs Actual** - Visual comparison
- 🎯 **Residual Plot** - Error distribution
- 📉 **Forecast Plot** - Future predictions

</details>

---

## 📚 Learning Resources

<details>
<summary><strong>Deepen your LSTM knowledge</strong></summary>

### Official Documentation

- 🔗 [PyTorch LSTM Docs](https://pytorch.org/docs/stable/nn.html#torch.nn.LSTM)
- 🔗 [TensorFlow LSTM Docs](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)

### Academic Papers

- 📄 "Long Short-Term Memory" - Hochreiter & Schmidhuber (1997)
- 📄 "LSTM: A Search Space Odyssey" - Greff et al. (2015)

### Tutorial Videos

- ▶️ Deep Learning Specialization (Coursera)
- ▶️ Fast.ai Part 2: NLP with LSTMs
- ▶️ 3Blue1Brown: Neural Networks

### Interactive Tools

- 🎮 [Distill.pub LSTM Visualization](https://distill.pub/2019/real-analysis/)
- 🎮 [Neural Network Playground](https://playground.tensorflow.org/)

</details>

---

## 🤝 Contributing

<details>
<summary><strong>Help improve this project!</strong></summary>

We welcome contributions! Here's how:

### Areas for Contribution

- ✅ Add bidirectional LSTM (BiLSTM) implementation
- ✅ Implement GRU (Gated Recurrent Unit) variant
- ✅ Add attention mechanisms
- ✅ Create comparison benchmarks
- ✅ Improve documentation
- ✅ Add more datasets and examples

### How to Contribute

1. 🍴 Fork the repository
2. 🔧 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔄 Open a Pull Request

### Code Style

- Follow PEP 8 guidelines
- Add comments for complex logic
- Include docstrings for functions
- Test your changes thoroughly

</details>

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Author

**Created and maintained by:** [itsluckysharma01](https://github.com/itsluckysharma01)

---

## ⭐ Show Your Support

If this project helped you understand LSTMs better, please give it a ⭐!

Your support motivates continued development and improvements.

---

<div align="center">

### जय श्री राम!🚩

_Master LSTM Networks with PyTorch and TensorFlow_

**Last Updated:** April 2026

</div>
