# E-Commerce Sales & Customer Behavior Analysis

**IBM SkillsBuild Data Analytics with AI Academic Internship Program**  
*Conducted by BharatCares in association with AICTE*

**Author:** Yuvaraj Sidaram Galagali  
**Date:** September 2026

---

## Project Description

This project performs a comprehensive analysis of e-commerce transactional data to uncover sales trends, customer behavior patterns, and product performance insights. It applies Python-based data analytics and machine learning techniques including:

- Exploratory Data Analysis (EDA)
- Sales trend visualization over time
- Category-wise and region-wise revenue analysis
- Order status and cancellation pattern analysis
- RFM (Recency, Frequency, Monetary) Customer Segmentation using K-Means Clustering
- AI-powered Sales Prediction using Linear Regression, Random Forest, and Gradient Boosting

---

## Dataset

- **Source:** Simulated real-world e-commerce dataset (generated using `numpy` and `pandas`)
- **Records:** 5,000 orders (2023–2024)
- **Features:** OrderID, CustomerID, OrderDate, Category, UnitPrice, Quantity, Discount, Sales, Region, PaymentMethod, OrderStatus, CustomerAge, Rating
- **Alternative Public Dataset:** [E-Commerce Dataset on Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

---

## Technologies Used

| Tool/Library | Purpose |
|---|---|
| Python 3.10 | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Scikit-learn | Machine learning (KMeans, RandomForest, etc.) |
| Jupyter Notebook | Interactive development environment |

---

## Project Structure

```
YuvarajSidaramGalagali_ECommerceAnalysis/
├── YuvarajSidaramGalagali_ECommerceAnalysis.ipynb   # Main code notebook
├── YuvarajSidaramGalagali_ProjectReport.docx        # Full project report
├── requirements.txt                                  # Python dependencies
└── README.md                                         # This file
```

---

## Setup & Run Instructions

### Step 1: Install Python
Ensure Python 3.10+ is installed: [https://www.python.org/downloads/](https://www.python.org/downloads/)

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Launch Jupyter Notebook
```bash
jupyter notebook
```

### Step 4: Open and Run
Open `YuvarajSidaramGalagali_ECommerceAnalysis.ipynb` and click **Run All Cells**.

---

## Key Insights

- **Electronics** is the top-grossing category, contributing ~30% of total revenue
- **Festive months (Oct–Dec)** show the highest sales spikes
- **RFM segmentation** reveals 4 customer clusters: Champions, Loyal, At Risk, and New
- **Random Forest** model achieved R² ≈ 0.97+ for sales prediction
- **UPI and Credit Card** are the dominant payment methods
- **Cancellation rate** is ~15%, highest in Electronics category

---

## Submitted Files

| File | Description |
|---|---|
| `YuvarajSidaramGalagali_ECommerceAnalysis.ipynb` | Complete code in Jupyter Notebook |
| `requirements.txt` | Python library dependencies |
| `YuvarajSidaramGalagali_ProjectReport.docx` | Full project documentation |
| `README.md` | Project overview (this file) |
