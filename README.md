<<<<<<< HEAD
# Customer Segmentation for Telecom Users (Week 3)

## Overview

Unsupervised customer segmentation using the IBM Telco Customer dataset. The goal is to identify distinct customer groups for targeted business strategies.

## Objectives

- Load and understand the dataset
- Clean & preprocess (handle data types, missing values, encode categoricals, scale)
- Exploratory visuals for numeric features
- K-Means clustering with Elbow & Silhouette to select K
- PCA for 2D visualization
- Segment profiling and insights

## Dataset

- Source: [IBM Telco Customer Churn](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)
- Size: ~7000 rows, 21 columns

## Methodology

1. **Data Loading**: Loaded from public URL, fallback to local file if needed.
2. **Cleaning & Preprocessing**:
   - Converted `TotalCharges` to numeric, dropped rows with missing values
   - Removed `customerID` and set aside `Churn` for profiling
   - One-hot encoded categorical features, scaled all features
3. **Exploratory Data Analysis**:
   - Visualized distributions for tenure, monthly charges, total charges
   - Correlation heatmap for numeric features
   - Calculated churn rate
4. **Clustering**:
   - Used Elbow and Silhouette methods to select optimal K (K=4)
   - Applied K-Means clustering
   - Visualized clusters using PCA (2D)
5. **Segment Profiling**:
   - Summarized clusters by average tenure, charges, and churn rate
   - Provided business insights for each segment

## Key Insights

- Four segments identified: new at-risk, loyal high-value, standard, new premium
- High churn observed in new/low tenure segments
- Loyal customers have high tenure and total charges, low churn
- Business value: Target retention campaigns at high-churn segments

## Next Steps

- Try other clustering algorithms (DBSCAN, Hierarchical)
- Include churn prediction after segmentation
- A/B testing on segments for retention strategies
- Feature importance per segment using SHAP or tree-based models

## How to Run

See `week3project.ipynb` for full code, analysis, and visualizations.

---

## How to Push this README to GitHub

1. Open your terminal and navigate to the project folder:
   ```
   cd "C:\Users\Aayush\Desktop\AIML\Customer Segmentation"
   ```
2. Stage the new README file:
   ```
   git add README.md
   ```
3. Commit the change:
   ```
   git commit -m "Add README.md for week 3 customer segmentation project"
   ```
4. Push to your GitHub repository:
   ```
   git push origin main
   ```
   This will upload your new README to GitHub.
=======
# Customer-Segmentation-for-Telecom-Users
Customer Segmentation for Telecom Users (Week3 Project @GNCIPL)  Objectives: - Load and understand the dataset - Clean &amp; preprocess (handle data types, missing values, encode categoricals) - Exploratory visuals for numeric features - K-Means clustering with Elbow &amp; Silhouette to select K - PCA for 2D visualization - Segment profiling and insights
>>>>>>> 714735cc088e14149bd9d9386dd0b9d89296a7ea
