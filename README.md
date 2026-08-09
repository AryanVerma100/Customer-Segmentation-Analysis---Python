# Customer Segmentation Analysis

A Python-based customer segmentation project using retail transaction data to analyze customer purchasing behavior and identify distinct customer groups using unsupervised learning techniques.

## 📌 Project Overview

Customer segmentation helps businesses understand differences in customer behavior and identify groups with similar purchasing characteristics.

This project analyzes a global retail dataset containing customer and transaction information. The analysis focuses on customer purchasing behavior, transaction patterns, profitability, and other sales-related characteristics.

The project uses **K-Means clustering** to group customers into distinct segments and **Principal Component Analysis (PCA)** to reduce dimensionality and visualize the resulting customer groups.

## 🎯 Objectives

* Analyze customer purchasing and transaction behavior
* Clean and preprocess retail transaction data
* Identify relevant features for customer segmentation
* Apply K-Means clustering to group similar customers
* Use PCA to visualize customer segments
* Analyze the characteristics of different customer groups
* Generate insights that can support customer-focused business strategies

## 🗂️ Dataset

The project uses a global retail dataset containing information from multiple business tables, including:

* Orders
* Customers
* Products
* Sales

Key variables used for customer analysis include:

* Customer ID
* Sales
* Quantity
* Discount
* Profit
* Shipping Cost
* Order Priority

These features provide information about customer purchasing behavior, spending, profitability, and transaction characteristics.

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning and clustering
* **Jupyter Notebook** – Analysis environment

## 🔍 Methodology

### 1. Data Preparation

* Loaded the retail dataset using Pandas
* Inspected the structure and data types
* Performed data cleaning and validation
* Selected relevant customer and transaction features

### 2. Exploratory Data Analysis

Analyzed relationships and patterns across key sales and customer behavior variables, including:

* Sales
* Quantity
* Discount
* Profit
* Shipping Cost
* Order Priority

### 3. Feature Preparation

Selected and transformed relevant numerical and categorical features to prepare the data for clustering analysis.

### 4. Customer Segmentation

Applied the **K-Means clustering algorithm** to divide customers into groups with similar behavioral characteristics.

### 5. Dimensionality Reduction

Applied **Principal Component Analysis (PCA)** to reduce the dimensionality of the feature space and visualize the customer segments.

### 6. Segment Analysis

Analyzed the characteristics of the resulting clusters to understand differences in customer purchasing behavior and profitability.

## 📊 Key Analysis Areas

The project examines customer segments based on factors such as:

* Purchasing volume
* Sales contribution
* Discount behavior
* Profitability
* Shipping costs
* Transaction characteristics

These segments can help businesses understand different customer groups and develop more targeted strategies.

## 💡 Business Applications

Customer segmentation can support:

* Targeted marketing campaigns
* Customer retention strategies
* Personalized promotions
* Identification of high-value customers
* Customer profitability analysis
* More efficient allocation of marketing resources

## 📁 Project Structure

```text
Customer-Segmentation/
│
├── Retail_Store_Customer_Segmentation.ipynb
├── store.csv
└── README.md
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the notebook in Jupyter Notebook or JupyterLab.

3. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Run the notebook cells sequentially.

## 📌 Conclusion

This project demonstrates an end-to-end approach to customer segmentation using retail transaction data. By combining data preprocessing, exploratory analysis, K-Means clustering, and PCA, customer groups can be identified based on similarities in purchasing and transactional behavior.

The resulting segmentation provides a foundation for developing more targeted and data-driven customer strategies.
