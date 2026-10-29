# SmartCart – E-commerce Customer Segmentation System

## About the Project
SmartCart is a minor project focused on analyzing e-commerce customer data and identifying different customer groups based on their income, spending habits, and purchasing behavior. The aim is to understand how customers differ and how these insights can help businesses plan better marketing strategies.

## Dataset
The dataset contains 2,240 customer records with information about income, age, family size, product spending, purchases, and campaign responses.

## Work Done
- Cleaned the data and handled missing values and outliers.
- Created new features such as age, customer tenure, total spending, and total children.
- Performed Exploratory Data Analysis (EDA) using charts and a correlation heatmap.
- Applied One-Hot Encoding to categorical features and scaled numerical features.
- Used PCA for dimensionality reduction.
- Applied and compared K-Means and Agglomerative Clustering.
- Analyzed the resulting customer groups to understand their characteristics.

## Key Findings
- Identified four customer segments with different income and spending patterns.
- Customers with higher income generally showed higher spending.
- Customers with fewer children tended to have higher spending in the identified segments.
- The clusters differed in campaign response, website visits, and store and catalog purchasing behavior.

## Tools and Libraries
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Files
- `SmartCart_Customer_Segmentation_GitHub.ipynb` – Complete notebook containing the analysis, visualizations, clustering, and findings.

## Conclusion
This project helped me practice data cleaning, feature engineering, visualization, dimensionality reduction, and clustering. It also helped me understand how unsupervised learning can be used to explore customer behavior and support marketing decisions.
