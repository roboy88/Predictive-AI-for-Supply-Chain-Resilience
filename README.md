# Predictive-AI-for-Supply-Chain-Resilience
This project uses machine learning to **predict late deliveries in complex supply chains**, helping businesses proactively manage delays and improve logistics performance. Trained on over 180,000 supply chain transactions and 450,000 access logs, the model demonstrates how AI can support data-driven supply chain decision-making.  
# Predictive AI for Supply Chain Resilience

Author: [Roman Dobczansky](https://github.com/roboy88)  
Status: In Progress | Last Updated: May 2025

## 📦 Overview

This project uses machine learning to **predict late deliveries in complex supply chains**, helping businesses proactively manage delays and improve logistics performance. Trained on over 180,000 supply chain transactions and 450,000 access logs, the model demonstrates how AI can support data-driven supply chain decision-making.

Built to showcase my skillset for the U2xAI Apprenticeship Program.

---

## 🎯 Objectives

- Predict whether a shipment will be delayed using historical order data
- Improve model accuracy through advanced feature selection and tuning
- Integrate logistics KPIs like `Sales`, `Profit`, `Shipping Mode`, and `Region`
- Enable future expansion into access log behavioral modeling and dashboard visualization

---

## 🧠 Technologies Used

- **Python** (pandas, sklearn, seaborn, matplotlib)
- **Google Colab** – for interactive development
- **Random Forest Classifier** (tuned)
- One-Hot Encoding
- Feature Engineering
- Confusion Matrix, F1, Accuracy

---

## 📁 Data Sources

1. `DataCoSupplyChainDataset.csv` – main dataset (180,000+ rows)
2. `DescriptionDataCoSupplyChain.csv` – column and metadata definitions
3. `tokenized_access_logs.csv` – user interaction logs (for advanced work)

---

## 🛠️ How to Use

1. Open the [Google Colab Notebook](https://colab.research.google.com/)
2. Upload the three CSV files manually
3. Run each cell from top to bottom
4. Review accuracy, confusion matrix, and classification report
5. Explore feature importance and plan further extensions

---

## 📊 Results

- Accuracy: **~73%** (improved from baseline of 68%)
- Tuned Random Forest with robust generalization
- Ready for business recommendation integration and Tableau dashboards

---

## 🚀 Next Steps

- Integrate `XGBoost` for accuracy boost
- Add `SHAP` explainability
- Create executive dashboard with `Plotly` or Tableau
- Use access logs for behavior clustering or demand forecasting

---

## 📞 Contact

- [LinkedIn](https://linkedin.com/in/roman-w-dobczansky)
- [GitHub Profile](https://github.com/roboy88)
