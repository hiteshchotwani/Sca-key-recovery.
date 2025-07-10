
# 🔐 Side-Channel Attack (SCA) Key Recovery using Machine Learning

This project demonstrates how **unsupervised learning** (clustering) can be used for **Side-Channel Attacks (SCA)** to recover a key byte from AES traces using a simulated Hamming-weight leakage model.

---

## 🎯 Features

- Simulates AES-like traces with known leakage model
- Performs PCA + KMeans clustering on traces
- Recovers AES key byte by correlating predicted leakage with key guesses
- Includes interactive **Streamlit UI**
- High recovery accuracy (ARI ≈ 0.86)

---

## 🧪 Run It Locally

```bash
git clone https://github.com/yourusername/sca-key-recovery.git
cd sca-key-recovery
pip install -r requirements.txt
streamlit run sca_app.py
```

---

## 📦 Dependencies

```txt
streamlit
numpy
matplotlib
scikit-learn
scipy
```

---

## 🖼️ Screenshots

| Clustering PCA | Key Correlation |
|----------------|-----------------|
| ![](screenshots/pca.png) | ![](screenshots/correlation.png) |

---

## 📂 Folder Descriptions

- `sca_app.py`: Main Streamlit-based app
- `sample_traces/`: (Optional) Pre-saved traces
- `screenshots/`: PCA and correlation graphs
- `requirements.txt`: Dependencies
