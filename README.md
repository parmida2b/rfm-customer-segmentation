# Customer Segmentation Using RFM and Machine Learning

This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) model combined with KMeans clustering and Random Forest classification.

## 📊 Dataset

- Sample: Superstore (Kaggle dataset)
- Format: `.csv`
- Contains transactional sales data with fields like `Order Date`, `Customer ID`, `Sales`, `Region`, etc.

## 📈 Workflow

### 1. Data Preprocessing
- Load dataset and parse dates
- Handle missing values and duplicates (if any)

### 2. RFM Feature Engineering
- Recency: Days since last purchase
- Frequency: Total number of purchases
- Monetary: Total purchase amount

### 3. RFM Scoring
- Quartile-based scoring (1 to 4) for each metric
- Generate combined `RFM_Score`

### 4. Segmentation & Visualization
- Visualize RFM distributions
- Identify VIP and low-value customers
- Heatmap of RFM segments

### 5. Clustering with KMeans
- Elbow method to determine optimal k
- Segment customers into 4 groups
- Visualize clusters (Recency vs Monetary)

### 6. Classification with Random Forest
- Train a model to predict cluster labels from RFM values
- Evaluate performance using classification metrics

## 🔍 Key Visuals
- Monthly Sales Trend
- Region-wise Sales Bar Chart
- RFM Distribution Histograms
- KMeans Clusters (Scatterplot)
- Segment Heatmap

## 💡 Tools & Libraries
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Dataset source: Kaggle

## 🚀 Author
Hosna HDY  
[Your GitHub or LinkedIn Link]

---

### 📁 Files
- `rfm_customer_segmentation.ipynb`: Jupyter notebook with full workflow
- `Sample - Superstore.csv`: Dataset used (optional to upload if allowed)

---

