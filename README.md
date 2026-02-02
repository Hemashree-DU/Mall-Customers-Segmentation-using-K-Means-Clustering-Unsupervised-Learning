# 🛍️ Mall Customers Segmentation using K-Means Clustering

### Major Project — Internship in Machine Learning (Unsupervised Learning)

---

## 1. Introduction

Customer segmentation plays a vital role in modern marketing strategies. Businesses often deal with thousands of customers with different income levels, ages, and spending behaviors. Identifying and understanding these patterns helps in offering personalized services and improving customer satisfaction.

In this project, we apply an **Unsupervised Learning algorithm (K-Means Clustering)** to segment mall customers based on their **Age**, **Annual Income**, and **Spending Score**.  
This allows the mall management to discover distinct customer groups and design targeted marketing campaigns.

---

## 2. Objective

The main objective of this project is to analyze mall customer data and classify customers into meaningful segments using **K-Means Clustering**.

### Goals
- Load and preprocess the **Mall Customers dataset**
- Determine the **optimal number of clusters (K)** using Elbow Method and Silhouette Score
- Visualize customer clusters in 2D feature space
- Derive **business insights and marketing recommendations** for each group

---

## 3. Technologies and Libraries Used

- **Python**
- **Jupyter Notebook**

### Libraries:
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 4. Project Workflow

1. **Importing Libraries and Loading Dataset:**  
   Loaded the `Mall_Customers.csv` dataset containing 200 customer records.

2. **Exploratory Data Analysis (EDA):**  
   - Checked for missing values and data types  
   - Visualized gender distribution  
   - Analyzed relationships between Age, Income, and Spending Score  
   - Created correlation heatmaps and pair plots

3. **Data Preprocessing:**  
   - Selected features: `Age`, `Annual Income (k$)`, and `Spending Score (1–100)`  
   - Standardized data using `StandardScaler`

4. **Finding Optimal K:**  
   - Used **Elbow Method (SSE)** to identify where curve bends  
   - Calculated **Silhouette Scores** for different K values  
   - Found **optimal number of clusters: K = 6**

5. **Model Building — K-Means Clustering:**  
   - Trained model using `n_clusters=6`  
   - Assigned cluster labels to each customer  
   - Computed cluster centers

6. **Cluster Visualization:**  
   - Plotted clusters based on Age, Income, and Spending Score  
   - Visualized results using scatter plots and color-coded clusters

7. **Business Insights and Recommendations:**  
   - Interpreted each cluster behavior  
   - Suggested marketing strategies for different customer types

8. **Conclusion and Future Scope:**  
   - Summarized key findings and proposed next steps for business application

---

## 5. Results

### ✅ Optimal Number of Clusters
- Based on **Silhouette Score**, the best K value = **6**

### 🧩 Cluster Summary
| Cluster | Characteristics | Recommendation |
|----------|------------------|----------------|
| 0 | High Income, High Spending | Offer VIP rewards and loyalty programs |
| 1 | High Income, Low Spending | Personalized luxury offers to increase engagement |
| 2 | Mid Income, Moderate Spending | Regular offers and point-based rewards |
| 3 | Low Income, Low Spending | Provide affordable and combo deals |
| 4 | Low Income, High Spending | Focus on youth offers, discounts, and flash sales |
| 5 | Middle-aged, High Income, Moderate Spending | Introduce corporate tie-ups and loyalty benefits |

### 🧠 Key Observations
- Cluster 0 customers bring **maximum profit** — focus on retention.  
- Cluster 4 customers are **young and active** — potential for long-term loyalty.  
- Cluster 1 customers are **underutilized** — increase engagement through personalization.  

---

## 6. Visualizations

- Gender Distribution  
- Pair Plot (Age, Income, Spending Score)  
- Correlation Heatmap  
- Elbow Method (SSE vs K)  
- Silhouette Score Plot  
- Cluster Scatter Plots (colored by cluster labels)

---

## 7. Conclusion

The **K-Means Clustering** algorithm effectively divided mall customers into **six distinct groups** based on their demographic and behavioral attributes.  

This segmentation provides valuable insights for the mall’s marketing strategy:
- Target high-income, high-spending clusters for premium campaigns.  
- Offer budget deals for low-income, low-spending customers.  
- Retain young, high-spending customers with digital loyalty programs.  

The project successfully demonstrates how **Unsupervised Learning** can convert raw data into **actionable business intelligence**.

---

## 8. Future Scope

- Add more customer attributes (e.g., frequency of visits, preferred product categories).  
- Experiment with advanced algorithms like **DBSCAN** or **Hierarchical Clustering**.  
- Implement **PCA** or **t-SNE** for dimensionality reduction and visualization.  
- Build an interactive **dashboard (Streamlit / Power BI)** for business use.

---

## 9. How to Run the Project

1. **Install dependencies:**
pip install pandas numpy matplotlib seaborn scikit-learn

2. **Open the Jupyter Notebook:**
jupyter notebook

3. **Run all cells in `Mall_Customers_Segmentation.ipynb` sequentially.**

4. **Outputs include:**
- Optimal K determination  
- Cluster plots and visualizations  
- Final business recommendations  

---

## 10. Author

**Project by:** Hemashree D U  
**Major Project — Internship on Machine Learning (Corizo Edutech Pvt. Ltd.)**  
**Topic:** Mall Customers Segmentation using K-Means Clustering  
**Category:** Unsupervised Learning  
**Year:** 2026
