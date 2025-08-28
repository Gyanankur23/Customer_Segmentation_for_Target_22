# Customer_Segmentation_for_Target_22 CaseCraft Analytics Project Sprint Project 22

## 🧬 Overview  
This project segments Target’s customer base using synthetic demographic and behavioral data. It combines clustering, visualization, and classification to uncover actionable customer profiles for personalized marketing and inventory planning.

## 🎯 Objective  
To identify distinct customer segments based on age, income, purchase frequency, and product affinity, and predict segment membership using decision trees.

## 📦 Dataset & Features  
- Customers: 600 synthetic entries  
- Features:  
  - `age`: 18–65  
  - `income`: ₹20,000–₹120,000  
  - `purchase_freq`: Poisson-distributed frequency  
  - `avg_basket_value`: ₹300–₹5,000  
  - `product_affinity`: Tech, Fashion, Home, Grocery

## 📊 Visual Explorations  
- **Histogram**: Age distribution  
- **Scatterplot**: Income vs basket value by product affinity  
- **Boxplot**: Purchase frequency by product type  
- **Violin Plot**: Basket value distribution  
- **Heatmap**: Feature correlations  
- **Cluster Scatterplot**: KMeans clusters on income and basket value  
- **Bar Chart**: Segment sizes  
- **Radar Plot**: Cluster feature profiles

## 🔍 Modeling  
- **Clustering**: KMeans with 4 segments  
- **Classification**: Decision Tree (max depth = 5)  
- **Accuracy**: **98.89%** on segment prediction

## 🧠 Key Insights  
1. **Segment Diversity**: Four distinct clusters emerged  
2. **High-Value Segments**: Tech and Fashion buyers had higher basket values  
3. **Behavioral Profiles**: Cluster 0 = high-income, high-spend, low frequency  
4. **Correlation Matrix**: Weak age-purchase link; moderate income-basket value link  
5. **Radar Plot**: Clear behavioral separation across clusters  
6. **Strategic Leverage**: Segments support tailored campaigns and inventory planning

## ✅ Final Conclusion  
Customer segmentation reveals rich behavioral diversity. Target can deploy premium bundles for high-value clusters and loyalty incentives for frequent shoppers. The combination of clustering and classification enables scalable personalization and strategic inventory alignment.