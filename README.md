# 🛍️ Customer Segmentation Using Unsupervised Learning

## 📌 Project Overview

This project applies **unsupervised machine learning** techniques to segment mall customers based on their spending behavior and annual income.

The goal is to identify meaningful customer groups and propose targeted marketing strategies to improve engagement, retention, and overall revenue.

---

## 📝 Problem Statement

Customers exhibit diverse income levels and spending patterns, making it difficult for businesses to design effective marketing campaigns. Without proper segmentation, marketing efforts may target the wrong audience, waste resources, and fail to retain high-value customers.

This project analyzes customer data and clusters customers into distinct segments based on spending behavior to enable data-driven marketing decisions.

---

## 🎯 Objective

- Segment customers using **K-Means Clustering**
- Identify behavioral patterns in income and spending
- Visualize clusters using **Principal Component Analysis (PCA)**
- Recommend tailored marketing strategies for each segment

---

## 📂 Dataset

**Mall Customers Dataset**

Features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

For clustering:
- `CustomerID` was removed (no analytical value)
- Focused primarily on `Annual Income` and `Spending Score`

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔎 Project Workflow

### 1️⃣ Data Loading & Inspection
- Loaded dataset using pandas
- Checked dataset structure and data types
- Verified absence of missing values

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed distribution of Age, Income, and Spending Score
- Visualized relationship between Income and Spending
- Identified behavioral patterns

### 3️⃣ Feature Selection & Scaling
- Selected relevant features for clustering
- Applied **StandardScaler** for normalization

### 4️⃣ Optimal Cluster Selection
- Used **Elbow Method**
- Determined optimal number of clusters (k = 5)

### 5️⃣ K-Means Clustering
- Applied K-Means algorithm
- Assigned cluster labels to customers

### 6️⃣ Cluster Visualization
- Visualized clusters in feature space
- Applied PCA for dimensionality reduction
- Confirmed clear cluster separation

### 7️⃣ Cluster Profiling
- Calculated average Age, Income, and Spending Score per cluster
- Interpreted segment characteristics

---

## 📊 Key Insights

- Spending behavior does not always correlate directly with income.
- Five distinct customer segments were identified.
- High-income high-spending customers represent the most valuable segment.
- Data-driven segmentation enables precise and efficient marketing strategies.

---

## 📈 Marketing Strategy Recommendations

| Segment Type | Recommended Strategy |
|--------------|---------------------|
| High Income – High Spending | VIP programs, premium services, exclusive offers |
| High Income – Low Spending | Personalized promotions, premium positioning |
| Low Income – High Spending | Discounts, loyalty rewards, bundle offers |
| Low Income – Low Spending | Mass marketing, cost-efficient campaigns |
| Moderate Income – Moderate Spending | Cross-selling and upselling |

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation


### 2️⃣ Install Required Libraries

Make sure Python (3.x) is installed. Then install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


### 3️⃣ Place the Dataset

Download the Mall Customers Dataset and place the file:

Mall_Customers.csv


inside the main project folder.



### 4️⃣ Run the Notebook

Open Jupyter Notebook and run:

jupyter notebook
Then:

Open the notebook file

Run all cells sequentially


## 📌 Conclusion

K-Means clustering successfully segmented customers into meaningful groups.
PCA visualization confirmed clear separation between clusters.

This project demonstrates how unsupervised learning techniques can support strategic marketing decisions and improve business efficiency.

## 🚀 Future Improvements

- Apply **Silhouette Score** for additional cluster validation

- Compare K-Means with **DBSCAN or Hierarchical Clustering**

- Include additional features such as Age and Gender

-  Deploy as an interactive dashboard using **Streamlit or Power BI**

- Automate clustering pipeline using reusable functions


---

## 👩‍💻 Author

**Tehmina Afzal**  
AI & Data Science Intern at ITSOLERA PVT LTD
