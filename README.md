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
   git clone https://github.com/JacobDaniel-82/EDA_and_FE_Collection.git
   ```
2. Navigate to the project folder:
   ```bash
   cd EDA_and_FE_Collection
   ```
3. Open the notebook file using Jupyter Notebook or any Python IDE:
   - File: `2.0-EDA_And_FE_Flight_Price.ipynb`

## **License**
This project is licensed under the [MIT License](LICENSE).




## **Project 2: Google Playstore Dataset**

# EDA and Feature Engineering of Google Play Store Dataset

## Overview
Today, there are over **1.85 million apps** available for users to download, with Android users enjoying access to a staggering **2.56 million apps** through the Google Play Store. These apps have transformed the way we live, work, and interact with the world.  
This project aims to analyze the Google Play Store dataset, focusing on:  
- Finding the most popular category.  
- Identifying the app with the largest number of installs.  
- Discovering the app with the largest size.  

The project demonstrates the use of **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)** to extract meaningful insights and prepare the data for future use in machine learning or statistical models.

---

## Dataset
- **Size**: 10,841 rows × 20 columns  
- **Source**: [Google Play Store Dataset](https://www.kaggle.com/lava18/google-play-store-apps)  
- The dataset includes various app attributes such as:  
  - Name  
  - Category  
  - Ratings  
  - Reviews  
  - Size  
  - Installs  
  - Price  
  - Content Rating  
  - Last Updated, etc.  

---

## Problem Statement
With millions of apps available, businesses and developers need to understand user preferences and market trends. This analysis will help answer key questions like:  
1. What are the most popular app categories?  
2. Which app has the largest number of installs?  
3. Which app has the largest size?  

---

## EDA Highlights
The EDA process includes:  
- **Data Cleaning**:  
  - Handled missing values and inconsistent data.  
  - Converted data types for better analysis (e.g., "Installs" and "Size").  
- **Statistical Analysis**:  
  - Summarized key metrics such as average ratings and install counts.  
- **Visualizations**:  
  - Used bar plots, pie charts, and heatmaps to explore relationships between variables.  
- **Trend Analysis**:  
  - Analyzed trends across categories, size distributions, and user reviews.

---

## Feature Engineering Techniques
Key techniques implemented include:  
- **Handling Missing Values**:  
  - Applied imputation for numerical and categorical variables.  
- **Outlier Detection and Treatment**:  
  - Identified outliers using boxplots and statistical thresholds, then addressed them appropriately.  
- **Encoding**:  
  - Converted categorical features using methods like One-Hot Encoding and Target Guided Encoding.  
- **Feature Scaling**:  
  - Used transformations to normalize and scale features for better model performance.

---

## Installation
1. Clone this repository:  
   ```bash
   git clone https://github.com/JacobDaniel-82/EDA_and_FE_Collection.git
   ```  
2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open the notebook in Jupyter:  
   ```bash
   jupyter notebook
   ```

---

## Results
- Found insights into popular app categories and trends.  
- Identified key outliers and cleaned the dataset for further analysis.  
- Prepared the dataset for predictive modeling.  

---

## Contributions
Contributions are welcome! Fork the repository, raise issues, or submit pull requests to enhance the project.  

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## **Future Plans**
- Add more datasets for EDA and feature engineering.
- Experiment with advanced visualization techniques and modeling pipelines.



