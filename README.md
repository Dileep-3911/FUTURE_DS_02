# Customer Segmentation using K-Means Clustering

## Project Overview
This project is part of my Data Science internship. The goal is to group customers of a retail mall based on their spending habits and annual income to help the marketing team create targeted strategies.

## Dataset
The dataset contains:
* **CustomerID**: Unique ID for each customer
* **Annual Income (k$)**: Yearly income of the customer
* **Spending Score (1-100)**: Score assigned by the mall based on customer behavior

## Machine Learning Model
I used the **K-Means Clustering** algorithm. 
* **Elbow Method**: Used to determine that **5 clusters** was the optimal number for this data.
* **Final Segments**: Customers were divided into 5 groups: Careful, Standard, Target, Spendthrifts, and Sensible.

## Visualizations
The project includes a scatter plot showing the clusters, which helps identify the "Target" customers (High Income/High Spending).

## Technologies Used
* Python
* Pandas
* Scikit-Learn
* Matplotlib / Seaborn