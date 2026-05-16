# 🧠 ML-Practical-Lab

> **Har concept sikhna nahi — implement karna hai.**
> A hands-on, well-structured repository for practical Machine Learning — algorithms from scratch, real datasets, clean code, and working notebooks.

---

## 📌 Repo Name Suggestion

```
ML-Practical-Lab
```
**Alternatives:**
- `learn-ml-by-doing`
- `ml-algorithms-from-scratch`
- `practical-ml-notebook`

---

## 🗂️ Repository Structure

```
ML-Practical-Lab/
│
├── 📁 01_foundations/
│   ├── linear_algebra_basics.ipynb
│   ├── probability_statistics.ipynb
│   └── numpy_pandas_essentials.ipynb
│
├── 📁 02_supervised_learning/
│   ├── linear_regression/
│   │   ├── from_scratch.py
│   │   ├── sklearn_version.py
│   │   └── notebook.ipynb
│   ├── logistic_regression/
│   ├── decision_trees/
│   ├── random_forest/
│   ├── svm/
│   ├── knn/
│   └── naive_bayes/
│
├── 📁 03_unsupervised_learning/
│   ├── kmeans_clustering/
│   ├── dbscan/
│   ├── pca_dimensionality_reduction/
│   └── anomaly_detection/
│
├── 📁 04_neural_networks/
│   ├── perceptron_from_scratch.py
│   ├── feedforward_nn/
│   ├── backpropagation_explained.ipynb
│   └── activation_functions.ipynb
│
├── 📁 05_deep_learning/
│   ├── cnn_image_classification/
│   ├── rnn_text_sequences/
│   ├── lstm_time_series/
│   └── transfer_learning/
│
├── 📁 06_nlp/
│   ├── text_preprocessing.ipynb
│   ├── tfidf_bag_of_words.ipynb
│   ├── word_embeddings/
│   └── sentiment_analysis/
│
├── 📁 07_model_evaluation/
│   ├── metrics_explained.ipynb
│   ├── cross_validation.ipynb
│   ├── confusion_matrix.ipynb
│   └── bias_variance_tradeoff.ipynb
│
├── 📁 08_feature_engineering/
│   ├── handling_missing_values.ipynb
│   ├── encoding_categorical.ipynb
│   ├── feature_scaling.ipynb
│   └── feature_selection.ipynb
│
├── 📁 09_projects/
│   ├── house_price_prediction/
│   ├── spam_classifier/
│   ├── mnist_digit_recognition/
│   └── customer_churn/
│
├── 📁 10_resources/
│   ├── cheatsheets/
│   ├── math_for_ml.md
│   └── useful_links.md
│
├── 📁 datasets/
│   └── README.md  ← (dataset sources & download links)
│
├── requirements.txt
├── .gitignore
└── README.md  ← (you are here)
```

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/ML-Practical-Lab.git
cd ML-Practical-Lab
```

### 2. Setup Virtual Environment
```bash
python -m venv venv
source venv/bin/activate        # Linux/Mac
venv\Scripts\activate           # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter
```bash
jupyter notebook
```

---

## 📦 Requirements (`requirements.txt`)

```
numpy>=1.24.0
pandas>=2.0.0
matplotlib>=3.7.0
seaborn>=0.12.0
scikit-learn>=1.3.0
scipy>=1.11.0
jupyter>=1.0.0
notebook>=7.0.0
tensorflow>=2.13.0
torch>=2.0.0
transformers>=4.30.0
xgboost>=1.7.0
lightgbm>=4.0.0
plotly>=5.15.0
tqdm>=4.65.0
```

---

## 🧩 What Each Section Contains

| Section | Kya Seekhain Gey | Implementation Style |
|---|---|---|
| **Foundations** | NumPy, Pandas, Math | Interactive Notebooks |
| **Supervised Learning** | Regression, Classification | From Scratch + Sklearn |
| **Unsupervised Learning** | Clustering, PCA | Step-by-step Notebooks |
| **Neural Networks** | Backprop, Activations | Pure Python First |
| **Deep Learning** | CNN, RNN, LSTM | PyTorch + TensorFlow |
| **NLP** | Text Processing, Embeddings | Real Dataset Projects |
| **Model Evaluation** | Metrics, CV, Overfitting | Visual Explanations |
| **Feature Engineering** | Preprocessing, Selection | Dataset Walkthroughs |
| **Projects** | End-to-End ML Pipelines | Production Style Code |

---

## 📐 Code Style Convention

Har file mein yeh structure follow karo:

```python
# ============================================================
# Algorithm  : Linear Regression (From Scratch)
# Concept    : Minimize MSE using Gradient Descent
# Dataset    : Boston Housing / Custom
# Author     : Your Name
# ============================================================

# --- 1. Imports ---
import numpy as np
import matplotlib.pyplot as plt

# --- 2. Data Preparation ---
# ...

# --- 3. Algorithm Implementation ---
class LinearRegression:
    """
    Manual implementation of Linear Regression.
    
    Parameters:
        lr (float): Learning rate
        n_iters (int): Number of gradient descent iterations
    """
    def __init__(self, lr=0.01, n_iters=1000):
        self.lr = lr
        self.n_iters = n_iters
        self.weights = None
        self.bias = None
    
    def fit(self, X, y):
        # Gradient Descent
        ...
    
    def predict(self, X):
        ...

# --- 4. Train & Evaluate ---
# ...

# --- 5. Visualize Results ---
# ...
```

---

## 📓 Notebook Convention

Har Jupyter Notebook mein yeh sections honi chahiyein:

```
1. 🎯 Objective       — Kya seekhna hai
2. 📚 Theory          — Concept 3–5 lines mein
3. 🔢 Math Behind It  — Key formulas (LaTeX)
4. 💻 Implementation  — Code with comments
5. 📊 Visualization   — Plots & results
6. ✅ Key Takeaways   — Summary bullets
7. 🔗 Next Steps      — Kahan jaayein age
```

---

## 🧠 Learning Path (Recommended Order)

```
Week 1-2  →  01_foundations
Week 3-5  →  02_supervised_learning
Week 6-7  →  03_unsupervised_learning
Week 8-9  →  07_model_evaluation + 08_feature_engineering
Week 10-12 → 04_neural_networks
Week 13-16 → 05_deep_learning
Week 17-18 → 06_nlp
Week 19+  →  09_projects (full end-to-end)
```

---

## 🏷️ Git Commit Convention

```
feat: add KNN from scratch with visualization
fix: correct gradient descent learning rate bug
docs: add theory section to logistic regression notebook
data: add titanic dataset for classification practice
refactor: clean up SVM implementation code
```

---

## 📊 Progress Tracker

Update karte raho as you complete each section:

- [x] Foundations — NumPy & Pandas
- [ ] Linear Regression
- [ ] Logistic Regression
- [ ] Decision Tree
- [ ] Random Forest
- [ ] SVM
- [ ] KNN
- [ ] K-Means Clustering
- [ ] PCA
- [ ] Neural Network from Scratch
- [ ] CNN (Image)
- [ ] RNN/LSTM (Text/Time Series)
- [ ] End-to-End Project #1
- [ ] End-to-End Project #2

---

## 📚 Key Resources

| Resource | Link |
|---|---|
| CS229 (Stanford ML) | https://cs229.stanford.edu |
| Fast.ai Practical DL | https://course.fast.ai |
| Scikit-learn Docs | https://scikit-learn.org/stable |
| PyTorch Tutorials | https://pytorch.org/tutorials |
| Kaggle Datasets | https://www.kaggle.com/datasets |
| Papers With Code | https://paperswithcode.com |
| 3Blue1Brown (Neural Nets) | https://youtube.com/3blue1brown |

---

## 🤝 How to Use This Repo

**Sirf padhne ke liye:** Directly notebooks kholo aur run karo  
**Seekhne ke liye:** Pehle theory padhein, phir `from_scratch.py` dekho, phir khud likho  
**Practice ke liye:** `09_projects/` folder mein jaao aur har project ko pehle khud try karo  

---

## 📝 .gitignore

```
# Python
__pycache__/
*.py[cod]
*.so
.env
venv/
env/

# Jupyter
.ipynb_checkpoints/
*.ipynb_checkpoints

# Data (large files)
datasets/*.csv
datasets/*.zip
datasets/*.h5

# Models (large files)
*.pkl
*.h5
*.pt
*.pth

# OS
.DS_Store
Thumbs.db
```

---

## 📈 GitHub Topics (Repo mein add karo)

```
machine-learning, deep-learning, algorithms-from-scratch,
python, jupyter-notebook, neural-networks, nlp,
scikit-learn, pytorch, tensorflow, data-science
```

---

*Yeh repo ek living document hai — jaise jaise seekhte jao, isko update karte jao.* 🚀
