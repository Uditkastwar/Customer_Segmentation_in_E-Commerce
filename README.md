# Customer_Segmentation_in_E-Commerce
Sure! Here's a clean and professional **README description** that you can use in your GitHub repository for this **Customer Segmentation in E-commerce** project:

---

## 🛍️ Customer Segmentation in E-commerce

This project performs **Customer Segmentation** using the **Online Retail Dataset** from the UCI Machine Learning Repository. The goal is to identify distinct groups of customers based on their purchasing behavior using unsupervised learning techniques (KMeans Clustering).

### 🔍 Objective
To group customers into segments based on **Recency, Frequency, and Monetary (RFM)** analysis for better targeting and marketing strategies.

---

### 📁 Dataset

- **Name:** Online Retail Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)  
- **Description:** This dataset contains transactional data from a UK-based online retailer from 2010 to 2011.

---

### 📊 Features Used

| Feature     | Description |
|-------------|-------------|
| Recency     | Days since the customer's last purchase |
| Frequency   | Total number of purchases (invoices) made |
| Monetary    | Total money spent by the customer |

---

### 🧠 Techniques Used

- **Data Cleaning** and preprocessing
- **RFM Feature Engineering**
- **Feature Scaling** using `StandardScaler`
- **KMeans Clustering** for segmentation
- **Silhouette Score** for cluster evaluation
- **3D Visualization** using Plotly for interactive analysis

---

### ✅ Results

- The model dynamically identifies the best number of clusters (K) based on **Silhouette Score**.
- Interactive 3D plots are used to visualize the clusters.
- A summary table shows average RFM values and customer count in each cluster.

---

### 📦 Requirements

This project is built in **Google Colab** and uses the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `plotly`

---

### 📁 How to Use

1. Clone the repository
2. Upload the dataset `Online Retail.xlsx` (manually downloadable [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx))
3. Run the Colab notebook
4. View segmentation results and use the clusters for further customer analysis or marketing strategies

---

### 📌 Use Case

Customer segmentation allows e-commerce businesses to:
- Identify **loyal customers**
- Target **high spenders**
- Reactivate **dormant users**
- Personalize **marketing campaigns**

