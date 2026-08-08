# Policy Market Analytics-Consumer Trends Segmentation


An Exploratory Data Analysis (EDA) and RFM Segmentation using "E-Commerce Data" dataset from Kaggle. Evaluating a customer value based on Recency (R), Frequency (F) and Monetary (M).

How recently a customer made a purchase, how often and and much did they spend. 


E-Commerce Customer Segmentation (RFM & K-Means)
I built this project to bridge the gap between theoretical market analysis and practical Python data wrangling. Using a raw Kaggle e-commerce dataset containing over 500,000 retail transactions, I developed an automated pipeline to segment customers based on their actual purchasing behavior rather than static demographics.

What this project does:

Data Cleaning & Wrangling: Handled a messy, real-world dataset by removing incomplete records, filtering out canceled orders, and engineering total revenue features.

RFM Feature Engineering: Collapsed hundreds of thousands of individual receipts into a clean, user-level summary calculating Recency (days since last order), Frequency (total unique orders), and Monetary value (total spend).

Outlier Handling & Clustering: Filtered out the top 5% of extreme wholesale spenders to prevent algorithmic skew, scaled the metrics, and applied an unsupervised K-Means algorithm to naturally identify three distinct market segments: High-Value/Loyal, Standard/Recent, and Inactive/Churned.

3D Visualization: Built an interactive 3D scatter plot using Plotly to visualize the results. This was crucial for demonstrating how the hidden "Recency" dimension separates customer groups that otherwise look identical on a standard 2D revenue chart.

Tech Stack: Python, pandas (Data Manipulation), scikit-learn (Standardization & K-Means Clustering), plotly (Interactive 3D Visualization).

<img width="814" height="312" alt="image" src="https://github.com/user-attachments/assets/ea835f7e-3bbf-44de-af95-1f99d76b1aa3" />

