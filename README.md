# 🧠 Artificial Neural Networks (ANN) — Classification & Regression

This repository contains two complete Artificial Neural Network (ANN) projects built using **TensorFlow/Keras**, demonstrating:

* **Binary Classification** (Customer Churn Prediction)
* **Regression** (Salary Prediction)

Both examples include preprocessing, training, saved models, encoders, notebooks, and a **Streamlit app** for running predictions.

---

## 📌 Features

### ✅ ANN Classification (Churn Prediction)

* Predict whether a customer will leave the bank
* Uses Label Encoding, One-Hot Encoding, and Standard Scaling
* Model saved as `.h5`
* Includes encoders (`.pkl` files)
* Streamlit app (`app.py`) to run predictions interactively

### ✅ ANN Regression (Salary Prediction)

* Predict a continuous numeric salary value
* ANN with dense layers
* Model saved as `.h5`

---

## 🛠️ Setup (Recommended: Anaconda)

### 1️⃣ Install Anaconda

Download & install Anaconda from:
[https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)

---

### 2️⃣ Create Conda Environment

Use **Python 3.9 / 3.10 / 3.11** (compatible with TensorFlow 2.15):

```bash
conda create -n ann python=3.10
conda activate ann
```

---

### 3️⃣ Install Dependencies

#### Option A (recommended) — Install everything from `requirements.txt`

From the project folder:

```bash
pip install -r requirements.txt
```

#### Option B — Install Streamlit explicitly (if needed)

If Streamlit is not installed or you want to be explicit:

```bash
pip install streamlit
```

(or with conda)

```bash
conda install -c conda-forge streamlit
```

The main libraries used are:

* `tensorflow==2.15.0`
* `pandas`
* `numpy`
* `scikit-learn`
* `tensorboard`
* `matplotlib`
* `streamlit`
* `scikeras`

---

## ▶️ Run the Streamlit App

After activating the `ann` environment and installing dependencies, run:

```bash
streamlit run app.py
```

This will open a browser UI where you can input features (customer details, etc.) and get predictions from the trained ANN model.

---

## 📊 Training & Experiments (Optional)

You can explore and modify the training process using the Jupyter notebooks, for example:

* `experiments.ipynb`
* `hyperparametertuningann.ipynb`
* `prediction.ipynb`
* `salaryregression.ipynb`

If you have logs saved, you can also launch TensorBoard:

```bash
tensorboard --logdir=logs/
```

Then open:

```text
http://localhost:6006/
```

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* Streamlit
* Pandas, NumPy
* Matplotlib
* TensorBoard
* Anaconda / Conda (for environment management)

---

## 🤖 Models Included

### Classification

* Trained ANN model (`model.h5`)
* Preprocessing artifacts:

  * `scaler.pkl`
  * `label_encoder_gender.pkl`
  * `onehot_encoder_geo.pkl`

### Regression

* Trained regression ANN model (`regression_model.h5`)

These can be used directly for inference without retraining.

---

## 👤 Maintainer

**Hassaan**
ML / AI Engineer

---
