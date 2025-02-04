# DataDiggers Project

## Fraud Detection in E-Commerce Transactions  
**Analyzing Patterns and Anomalies in Online Retail Data**

### Team Members:
- **Vinay Kumar Kolukula Pally** - Problem Definition & Exploratory Analysis  
- **Shiva Boda** - Data Cleaning & Feature Engineering  
- **Charitha Banda** - Predictive Modeling & Model Evaluation  
- **Deepthi Tamma** - Project Coordination & Report Compilation  

---

## Project Overview
The DataDiggers project focuses on detecting fraudulent transactions in online retail by analyzing purchasing patterns, segmenting customers, and building predictive models. This research aims to improve **stock management, pricing strategies, and targeted marketing** using **machine learning** and **data mining** techniques.

---

## Objectives
- **Identify customer segments** based on purchasing behavior and geography.
- **Forecast sales volumes** using **regression models, decision trees, and neural networks**.
- **Detect fraudulent transactions** through anomaly detection techniques.
- **Provide actionable insights** for inventory management and marketing.

---

## Dataset
**Source:** [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)  
**Features:**
- `InvoiceNo`: Unique transaction ID  
- `StockCode`: Product identifier  
- `Description`: Product details  
- `Quantity`: Number of units purchased  
- `InvoiceDate`: Timestamp of transaction  
- `UnitPrice`: Price per unit  
- `CustomerID`: Unique customer identifier  
- `Country`: Country where the transaction occurred  

---

## Methodology
### **1️Exploratory Data Analysis (EDA)**
- **Customer Segmentation**: K-means and hierarchical clustering for identifying distinct buyer groups.  
- **Geographic Trends**: Sales distribution across different countries.  
- **Time-Series Analysis**: Identifying seasonal trends and peak purchasing periods.  

### **2️Predictive Modeling**
- **Regression Models**: To predict sales volume.  
- **Decision Trees & Neural Networks**: Used for forecasting and fraud detection.  
- **Model Evaluation**: Metrics include **RMSE, R-squared, and confusion matrices**.  

### **3️Anomaly Detection**
- **Cluster-Based Detection**: Identifying outliers using centroid clustering.  
- **Feature Engineering**: Using transaction frequency, amount, and customer behavior.  

---

## Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **SAS Enterprise Miner**: Advanced analytics and data mining  
- **Jupyter Notebook**: Data exploration and visualization  
- **Git & GitHub**: Version control and collaboration  

---

## Results & Insights
- **Identified 5 distinct customer segments** based on spending behavior.  
- **Decision Trees and Regression Models** provided the most accurate sales predictions.  
- **Cluster analysis** detected anomalies, highlighting possible fraudulent transactions.  

---

## Key Takeaways
- **Optimized inventory management**: Forecasting models help prevent overstocking and stockouts.  
- **Targeted marketing**: Segmentation allows personalized promotions and increased customer retention.  
- **Dynamic pricing strategies**: Adjusting prices based on customer behavior and regional trends.  

---

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/DataDiggers_Project.git
   cd DataDiggers_Project
