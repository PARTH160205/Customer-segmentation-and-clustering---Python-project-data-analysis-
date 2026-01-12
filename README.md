# 🧩 Customer Segmentation using K-Means Clustering

## 📄 Project Description  
This project aims to perform **customer segmentation** using **K-Means Clustering**, an unsupervised machine learning technique. The goal is to group customers based on their **Annual Income** and **Spending Score**, allowing businesses to understand customer behavior and target specific segments effectively.

The analysis includes **data visualization**, **feature exploration**, and **cluster analysis** to identify meaningful patterns that can drive marketing and product decisions.

## 📊 Dataset  
The dataset contains customer information such as:
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)

You can find similar datasets on [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-dataset).

## 🧠 Project Workflow  

### 1. Data Preparation  
- Imported libraries: `pandas`, `matplotlib`, `seaborn`, and `sklearn`.  
- Loaded dataset and explored it using `.head()` and `.describe()`.  
- Checked for missing values and data types.

### 2. Exploratory Data Analysis (EDA)  
- Visualized data distributions using **histograms** and **KDE plots**.  
- Compared gender-based income and spending patterns using **boxplots**.  
- Generated a **heatmap** to view correlations between numerical features.

### 3. Clustering  
- Applied **K-Means Clustering** on the "Annual Income" and "Spending Score" columns.  
- Used the **Elbow Method** to determine the optimal number of clusters.  
- Created new cluster labels for segmentation analysis.  
- Visualized the clusters using scatter plots to understand group characteristics.

### 4. Insights  
- Identified distinct customer groups such as:
  - High-income, low-spending customers  
  - Low-income, high-spending customers  
  - Balanced income and spending group  

These clusters can help businesses design **targeted marketing strategies**.

## 🧰 Tools & Libraries Used  
| Category | Libraries |
|-----------|------------|
| Data Handling | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn |
| Environment | Jupyter Notebook / VS Code |

## 📈 Key Visualizations  
- Distribution of income and spending score  
- KDE plots comparing income distribution by gender  
- Correlation heatmap  
- Cluster visualization using K-Means  

## 📌 Future Improvements  
- Include additional demographic or behavioral features.
- Try advanced clustering algorithms (DBSCAN, Hierarchical Clustering).  
- Build a dashboard to visualize segments interactively.
  
## 🧑‍💻 Author
**Parth Inamdar**  
[LinkedIn](https://www.linkedin.com/in/parthinamdar/) | [Kaggle](https://www.kaggle.com/parthinamdar1625)

Live Dashboard Link - https://app.powerbi.com/view?r=eyJrIjoiMGFiYmNhODUtMjAyMi00ODg0LTg1MzAtMzcwZDlmNDI4ODQ0IiwidCI6ImM4ZTQyNDhjLTcxNzQtNGIwZS04Y2Q4LTUzNGFhMDhkZjM5NSJ9
