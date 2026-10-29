# SmartCart – E-commerce Customer Segmentation System

## Project Overview

SmartCart is an unsupervised machine learning project that groups e-commerce customers by their demographic information and purchasing behavior. The goal is to understand different customer segments and identify insights that may support targeted marketing.

## Dataset

- The dataset contains 2,240 customer records and 22 original attributes.
- The notebook expects a CSV file named `smartcart_customers.csv` in the same directory as the notebook.
- The dataset is not included in this repository yet. Add it only if its license permits redistribution. Otherwise, provide the original dataset source and instructions for obtaining it.

## Project Workflow

1. **Data cleaning:** Checked missing values and handled selected outliers.
2. **Feature engineering:** Created features such as `Age`, `Customer_Tenure_Days`, `Total_Spending`, and `Total_Children`; grouped selected education and marital-status categories.
3. **Exploratory data analysis (EDA):** Used visualizations and a correlation heatmap to explore relationships between customer attributes and purchasing behavior.
4. **Categorical encoding and scaling:** Prepared categorical and numerical features for clustering.
5. **Dimensionality reduction:** Used Principal Component Analysis (PCA) to explore the data in lower dimensions.
6. **Clustering:** Compared K-Means and Agglomerative Clustering. The final customer-profile analysis uses Agglomerative Clustering with four clusters.
7. **Cluster interpretation:** Compared customer segments by income, spending, age, family size, campaign response, website visits, and purchasing behavior.

## Key Insights

- Customer segments show different income and spending patterns.
- Some higher-spending segments have more store and catalog purchases and fewer website visits than lower-spending segments.
- The clusters differ in family size and campaign response.
- These are patterns observed in this dataset; they do not prove that one attribute causes another.

## Tools and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Kneed
- Jupyter Notebook

## How to Run

1. Download or obtain the dataset you are permitted to use.
2. Place `smartcart_customers.csv` and `SmartCart_Customer_Segmentation_GitHub.ipynb` in the same folder.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn kneed jupyter
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `SmartCart_Customer_Segmentation_GitHub.ipynb` and run the cells from top to bottom.

## Notes

This is an exploratory customer-segmentation project, not a supervised prediction model. Cluster patterns and interpretations depend on the dataset, feature preparation, and clustering settings.
