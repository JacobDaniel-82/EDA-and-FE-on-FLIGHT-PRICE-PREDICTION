# **Exploratory Data Analysis and Feature Engineering**

Welcome to my repository for **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)** projects. This repository showcases my work on multiple datasets, including insights, visualizations, and data preparation for machine learning.

## **Project 1: Flight Price Prediction Dataset**
This project involves EDA and FE on a flight price dataset to understand patterns, relationships, and trends in the data while preparing it for predictive modeling.

### **1. Dataset Description**
- **Source**: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction
- **Content**:
  - Flight details (Airline, Source, Destination, etc.)
  - Date and time information
  - Price of tickets

### **2. Goals of Analysis**
- Analyze the relationship between ticket prices and factors like duration, airline, and travel route.
- Perform data preprocessing and feature engineering to make the dataset suitable for modeling.

### **3. Key Steps**
#### **Exploratory Data Analysis (EDA):**
- **Understanding the Data**: Analyzed the structure, missing values, and statistical summaries.
- **Data Visualization**: Used visualizations (bar plots, box plots, etc.) to identify patterns and outliers.
- **Insights**:
  - Certain airlines offer consistently higher or lower ticket prices.
  - Duration and route significantly impact ticket pricing.

#### **Feature Engineering (FE):**
- **Handling Missing Values**: Imputed missing values based on data patterns.
- **Outlier Treatment**: Identified and handled outliers using box plots and statistical techniques.
- **Feature Transformation**:
  - Extracted duration into hours and minutes.
  - Created new features based on time and route.
  - Encoded categorical variables using One-Hot Encoding (OHE) and Target Encoding.

### **4. Tools and Technologies**
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

### **5. Key Learnings**
- Gained hands-on experience in handling real-world data challenges.
- Improved feature engineering skills, including working with time-based features and categorical encodings.
- Enhanced understanding of visualization techniques for extracting actionable insights.

## **How to Explore This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/EDA_and_FE_Collection.git
   ```
2. Navigate to the project folder:
   ```bash
   cd EDA_and_FE_Collection
   ```
3. Open the notebook file using Jupyter Notebook or any Python IDE:
   - File: `2.0-EDA_And_FE_Flight_Price.ipynb`

## **Future Plans**
- Add more datasets for EDA and feature engineering.
- Experiment with advanced visualization techniques and modeling pipelines.

## **License**
This project is licensed under the [MIT License](LICENSE).

