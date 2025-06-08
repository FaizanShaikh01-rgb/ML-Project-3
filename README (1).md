
# 📊 ML Project 3 – Telecom Customer Segmentation

This project applies **K-Means Clustering** to segment customers of a telecom company into meaningful groups based on their behavior and service usage. These insights help drive **targeted marketing**, **churn reduction**, and **resource optimization**.

---

## 📁 Dataset

The dataset contains 7,043 records of telecom customers and 21 features including:

- **Demographics**: gender, senior citizen, dependents
- **Service usage**: internet, streaming, phone lines
- **Billing**: monthly charges, total charges, payment method
- **Contract types**: month-to-month, one-year, two-year

> Source: IBM Sample Dataset (Telco Customer Churn)

---

## 🎯 Objective

To identify **natural customer segments** using **unsupervised learning (K-Means)** without predefined labels. This helps:

- Reduce churn through focused retention strategies
- Offer tailored upsells, bundles, and upgrades
- Allocate support resources more efficiently

---

## 🧪 Key Steps

### 1. Data Preprocessing
- Converted `TotalCharges` to numeric
- Handled missing values
- Encoded binary and categorical variables
- Scaled numerical features using `StandardScaler`

### 2. Optimal Clusters Selection
- Used **Elbow Method** and **Silhouette Analysis**
- Chose `k = 4` for optimal balance between inertia and interpretability

### 3. K-Means Clustering
- Applied clustering and assigned labels
- Validated cluster stability with different random seeds

### 4. Cluster Profiling
- Described each cluster using summary statistics
- Identified behavioral traits: high spenders, new customers, loyal users, etc.

### 5. Visualization
- **PCA Projection** to 2D space
- Bar plots and boxplots for features like:
  - Tenure
  - Monthly Charges
  - Internet Service
  - Contract type

---

## 📈 Cluster Insights (Example)

| Cluster | Description | Strategy |
|---------|-------------|----------|
| 0 | Budget Newcomers | Offer loyalty discounts, promote annual plans |
| 1 | Loyal High-Value Users | Upsell new features, provide VIP support |
| 2 | High-Spend Short-Term | Prevent churn via timely incentives |
| 3 | Basic Plan Seniors | Simplify packages, add tech support |

---

## 🛠 Tech Stack

- **Python 3.8+**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/FaizanShaikh01-rgb/ML-Project-3.git

# Move into the directory
cd ML-Project-3

# (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 📄 License

This project is for educational purposes. You are free to use and adapt it with credit.

---

## 🤝 Contact

**Author**: Faizan Shaikh  
📧 Email: [shaikhfaizan1765@gmail.com]  
🌐 GitHub: [FaizanShaikh01-rgb](https://github.com/FaizanShaikh01-rgb)
