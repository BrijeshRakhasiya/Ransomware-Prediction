
# 🛡️ Ransomware Detection using RandomForest Classifier

This project aims to develop an intelligent antivirus component that flags potentially malicious Windows `.exe` files by analyzing structural properties like entropy, version size, and base address. Using machine learning, specifically a **RandomForest Classifier**, the model can detect ransomware with exceptional performance.

---

## 🧠 Problem Statement

To enhance Windows security, we built a model that analyzes certain metadata and structural properties of executable files to detect ransomware before execution.

Key features used for detection:

- **ImageBase**: Preferred memory load address
- **VersionInformationSize**: Metadata size, often indicative of tampering
- **SectionsMaxEntropy**: Measures obfuscation and randomness

---

## ✅ Model Used

- **RandomForest Classifier**  
An ensemble-based model known for robustness, especially effective for tabular malware data.

---

## 📊 Model Performance

| Metric                 | Score     |
|------------------------|-----------|
| **Accuracy**           | 0.9940    |
| **Precision**          | 0.9884    |
| **Recall**             | 0.9916    |
| **F1 Score**           | 0.9900    |
| **Matthews Corr. Coef**| 0.9857    |
| **False Positive Rate**| 0.0050    |
| **AUC Score**          | 0.9996    |

These metrics show the model is highly effective in detecting ransomware with near-perfect separation capabilities.

---

## 🧪 Requirements

```bash
pip install lazypredict
pip install lime
pip install scikit-learn pandas matplotlib seaborn
```

1. Clone the repository:

```bash
git clone https://github.com/BrijeshRakhasiya/Ransomware-Prediction.git
```

# 🔒 Use Cases
Malware detection before software installation

Endpoint protection systems

Antivirus engines for enterprises


# 🙋‍♂️ Author
Brijesh Rakhasiya
AI/ML Enthusiast | Data Scientist | Problem Solver


## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**e.
