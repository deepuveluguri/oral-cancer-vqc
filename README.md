# 🧬 Oral Cancer Detection using Hybrid Quantum Machine Learning

## 🔍 Overview

This project presents a **Hybrid Quantum-Classical Machine Learning model** for detecting oral cancer from medical images.

It combines:

* 🧠 Deep Learning (CNN - EfficientNet-B3)
* 📉 PCA (Dimensionality Reduction)
* ⚛️ Quantum Machine Learning (Variational Quantum Classifier - VQC)

---

## 🎯 Objective

To explore the potential of **quantum computing in healthcare AI** by building a hybrid model that improves classification performance in medical imaging tasks.

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* PennyLane (Quantum Machine Learning)
* NumPy, Matplotlib, Seaborn

---

## 🧠 Model Architecture

```
Input Image
     ↓
CNN (EfficientNet-B3)
     ↓
Feature Vector (1536-D)
     ↓
PCA (Dimensionality Reduction)
     ↓
Variational Quantum Circuit (VQC)
     ↓
Classification (Cancer / Normal)
```

---

## ⚛️ Quantum Component

* Framework: **PennyLane**
* Model: **Variational Quantum Classifier (VQC)**
* Encoding: Angle Encoding using RY rotations
* Entanglement: CNOT chain
* Backend: `default.qubit` simulator

---

## 📊 Results

* ✅ Accuracy: **>90%**
* 📈 Strong classification performance on test data
* 📉 PCA retained significant variance
* 🔬 Demonstrates potential of quantum ML in healthcare applications

---

## 📂 Project Structure

```
oral-cancer-vqc/
│
├── oral_cancer_vqc.ipynb   # Main notebook
├── README.md               # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/deepuveluguri/oral-cancer-vqc.git
```

2. Navigate to the folder:

```
cd oral-cancer-vqc
```

3. Install dependencies:

```
pip install pennylane tensorflow scikit-learn matplotlib seaborn
```

4. Open the notebook:

* Use **Jupyter Notebook** or **Google Colab**

5. Run all cells

---

## 💡 Future Improvements

* Add a **web interface (Streamlit / Gradio)**
* Compare with classical ML models (SVM, CNN)
* Deploy model for real-time prediction
* Test on real quantum hardware (IBM Quantum)

---

## 🌟 Key Highlights

* Hybrid Quantum + Deep Learning model
* Real-world healthcare application
* End-to-end pipeline (Image → Prediction)
* Research-oriented implementation

---

## 🤝 Connect with Me

If you found this interesting, feel free to connect and collaborate!

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
