# 🔐 Side-Channel Key Recovery (Unsupervised - Streamlit App)

This project demonstrates unsupervised key recovery using synthetic power traces from AES encryption. It simulates a side-channel attack leveraging the Hamming-weight leakage model, clustering, and correlation analysis — now in an interactive Streamlit interface.

## 🚀 Features

- Generates synthetic AES power traces using Hamming-weight leakage model
- Performs KMeans clustering and PCA visualization
- Recovers key byte using correlation-based inference
- Streamlit-based interactive app (adjust parameters, visualize, download results)

## 🧰 Tech Stack

- Python, NumPy, scikit-learn, Matplotlib, Streamlit
- Unsupervised learning: KMeans, PCA
- Cryptographic: AES S-box and Hamming-weight model

## 📷 Screenshot

![App Screenshot](screenshot.png)

## 🔧 Run the App

```bash
pip install -r requirements.txt
streamlit run app.py
