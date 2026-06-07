# DBSCAN Customer Segmentation

An interactive Jupyter Notebook project that applies **DBSCAN clustering** on wholesale customer spending data to identify customer groups, spending patterns, and outliers.

---

## Project Overview

This project walks through an unsupervised machine learning workflow:

- Loading and exploring the wholesale customer dataset
- Visualizing relationships between spending categories
- Analyzing customer distribution by channel and region
- Scaling numerical features using `StandardScaler`
- Applying DBSCAN clustering to detect dense customer groups
- Identifying outliers based on DBSCAN cluster labels
- Comparing spending patterns across detected clusters
- Visualizing normalized cluster profiles using heatmaps

---

## Dataset

The project uses a CSV file named:

```text
wholesome_customers_data.csv
```
The dataset contains wholesale customer spending data where:

- Each row represents one customer
- Spending columns represent annual spending in different product categories
- Channel represents the customer purchase channel
- Region represents the customer region

## Recommended repo structure:
```text
DBSCAN-Customer-Segmentation/
├── DBSCAN.ipynb
├── data/
│   └── wholesome_customers_data.csv
├── README.md
├── requirements.txt
└── .gitignore
```
## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
  
## Key Concepts Covered
- DBSCAN Clustering
- Unsupervised Machine Learning
- Customer Segmentation
- Outlier Detection
- Feature Scaling
- Cluster Profiling
- Data Visualization
- Exploratory Data Analysis

## Installation
Clone the repository:
```text
git clone https://github.com/your-username/dbscan-customer-segmentation.git
cd dbscan-customer-segmentation
```
Install the required libraries:
```text
pip install -r requirements.txt
```
## How to Run
Open the notebook:
```text
jupyter notebook DBSCAN.ipynb
```
Make sure the dataset path inside the notebook is:
```text
df = pd.read_csv("data/wholesome_customers_data.csv")
```
Then run all cells from top to bottom.

## Output Visualizations
The notebook generates:

- Scatter plots of customer spending patterns
- Histograms grouped by customer channel
- Correlation heatmaps of spending categories
- Pair plots colored by channel and region
- DBSCAN outlier percentage line plot
- Cluster scatter plots using DBSCAN labels
- Heatmaps of cluster-level spending averages
- Normalized heatmaps for comparing cluster profiles
## Project Workflow
```text
Load Dataset
     ↓
Explore Customer Spending Data
     ↓
Visualize Feature Relationships
     ↓
Scale Features
     ↓
Tune DBSCAN Epsilon
     ↓
Apply DBSCAN Clustering
     ↓
Identify Outliers
     ↓
Analyze Cluster Profiles
     ↓
Visualize Results
```
## Requirements
```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```
Testing pull request
## Author
Protyay Saha

- GitHub: rivu-intel45
- LinkedIn: Protyay Saha
