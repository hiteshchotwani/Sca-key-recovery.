# 🔐 Side-Channel Key Recovery (Unsupervised - AES Synthetic Traces)

This project demonstrates unsupervised key recovery using synthetic power traces from AES encryption. It simulates a side-channel attack leveraging the Hamming-weight leakage model, clustering, and correlation analysis to recover a secret key byte.

---

## 🚀 Features

- ✅ Generates synthetic AES power traces based on Hamming-weight leakage
- ✅ Applies **KMeans clustering** and **PCA** for unsupervised classification
- ✅ Uses **correlation analysis** to recover key byte
- ✅ Evaluates clustering accuracy using Adjusted Rand Index (ARI)

---

## 🧰 Tech Stack

- **Language:** Python
- **ML Libraries:** NumPy, scikit-learn, SciPy
- **Visualization:** Matplotlib
- **Crypto Modeling:** AES S-box, Hamming-weight leakage model

---

## 📂 File Structure

- `sca.ipynb`: Jupyter Notebook implementing the full pipeline
- `requirements.txt`: All required libraries
- `README.md`: Documentation

---

## 🧪 Run the Project Locally

```bash
pip install -r requirements.txt
jupyter notebook sca.ipynb
