# 🧬 Personalized Medicine: Predicting Drug Response from Gene Expression

This project applies lightweight machine learning techniques to predict a patient's response to a drug based on their gene expression profile. It simulates a real-world genomics scenario where precision medicine plays a central role in tailoring treatments.


---

## 📌 Objective

- Simulate a gene expression dataset with binary drug response labels.
- Apply dimensionality reduction (PCA) to handle high-dimensional genomic features.
- Train a light-weight Logistic Regression classifier.
- Evaluate the model using ROC curve, AUC score, and confusion matrix.

---

## 📊 Techniques Used

| Step | Technique | Tools |
|------|-----------|-------|
| Data Simulation | 50 gene expression features + binary response | `numpy`, `pandas` |
| Dimensionality Reduction | Principal Component Analysis (PCA) | `sklearn.decomposition.PCA` |
| Classification | Logistic Regression | `sklearn.linear_model.LogisticRegression` |
| Evaluation | Accuracy, AUC, ROC Curve, Confusion Matrix | `sklearn.metrics`, `matplotlib`, `seaborn` |

---

## 📈 Visual Outputs

- ✅ **Correlation Heatmap** (Top 10 genes)
- ✅ **PCA Scatter Plot** (2D projection)
- ✅ **Confusion Matrix**
- ✅ **ROC Curve with AUC Score**

All visualizations are saved in the `/data/` folder.

---

## 📦 Lightweight Design Philosophy

This project is optimized for:
- Beginners in ML + Genomics
- Quick demo deployments
- Fast GitHub previews
- Low memory usage (no SHAP or deep learning yet)

---

## 🔮 Future Scope

- Integrate SHAP for model explainability
- Use real-world datasets (e.g., GDSC, TCGA)
- Try ensemble models like XGBoost
- Deploy with Streamlit as an interactive demo

---

## 📜 License

This project is open-source and available for educational and academic use.

---

> Built with ❤️ by [Sai Sarat Chandra] |

