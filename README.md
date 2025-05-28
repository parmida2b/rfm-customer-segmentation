# 🧠 RFM Customer Segmentation with KMeans & Random Forest

This project performs **customer segmentation** using the RFM (Recency, Frequency, Monetary) model combined with **KMeans clustering** and **Random Forest classification**. The entire analysis is implemented in **Google Colab** using a retail sales dataset.

---

## 📌 Overview

- 🔍 Extract RFM features from transactional data
- 📊 Score and classify customers (e.g., VIPs, dormant)
- 🤖 Cluster using KMeans (Elbow method for optimal `k`)
- 🧠 Predict segments with Random Forest classifier
- 📈 Visualize monthly trends and customer patterns

---

## 🗂️ Dataset

- Source: Simulated Superstore dataset
- Fields: `Order Date`, `Customer ID`, `Sales`, `Region`, etc.
- Format: CSV (`Sample - Superstore.csv`)

---

## 🔧 Tools & Libraries

- **Python**: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
- **Google Colab**: Used as development environment
- **Jupyter Notebook**: Output saved as `.ipynb`

---

## 🚀 Execution (via Colab)

To run this project in Google Colab:

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook: `rfm_customer_segmentation.ipynb`
3. Upload the dataset: `Sample - Superstore.csv`
4. Run all cells sequentially

---

## 📊 Key Visuals

- Monthly Sales Trend (Line Plot)
- Regional Sales Breakdown (Bar Chart)
- RFM Segment Heatmap (Recency × Frequency)
- KMeans Clustering Scatterplots
- Random Forest Classification Report

---

## 👩‍💻 Author

**Parmida Mohammadzadeh**

---

## 📁 Files

- `rfm_customer_segmentation.ipynb`: Complete Colab notebook
- `Sample - Superstore.csv`: Dataset (optional if licensed)

---

## 📜 License

Shared under the MIT License.
