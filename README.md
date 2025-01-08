Clustering || RFM Analysis || Machine Learning || Python
# Online Retail Customer Segmentation

This repository contains a machine learning project on **Online Retail Customer Segmentation**, where customers are grouped into different segments based on their purchasing behavior.

## Project Overview
Customer segmentation is a key task in marketing, allowing businesses to better understand customer behavior and tailor their strategies accordingly. In this project, we apply clustering techniques to segment online retail customers using transaction data.

## Dataset
The dataset used for this project is provided as an Excel file (`Customer Segmentation Dataset.xlsx`). It contains information about transactions made by customers in an online retail store.

### Features in the Dataset
- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Product code.
- **Description**: Product description.
- **Quantity**: Number of products purchased.
- **InvoiceDate**: Date of the transaction.
- **UnitPrice**: Price per product.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country of the customer.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd online-retail-customer-segmentation
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Online Retail Customer Segmentation.ipynb
   ```
4. Follow the steps in the notebook to load the dataset, preprocess the data, and apply clustering.

## Requirements
- Python 3.8+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Methodology
1. **Data Preprocessing**:
   - Handling missing values.
   - Removing outliers.
   - Feature engineering to create relevant variables such as total revenue and purchase frequency.

2. **Clustering**:
   - K-means clustering is used to group customers based on Recency, Frequency, and Monetary (RFM) values.
   - The optimal number of clusters is determined using the Elbow method.

## Results
The notebook provides:
- Visualizations of customer segments.
- Insights into the characteristics of each segment.

## Future Improvements
- Experiment with different clustering algorithms such as DBSCAN or hierarchical clustering.
- Include more features for segmentation, such as customer demographics.
- Integrate the segmentation results with marketing campaigns.
