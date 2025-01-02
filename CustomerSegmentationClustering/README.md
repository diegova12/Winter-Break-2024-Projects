# Mall Customer Segmentation with Clustering

This project performs customer segmentation on the [Mall Customer Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python) available on Kaggle. The segmentation is achieved using clustering machine learning algorithms, along with exploratory data analysis to derive insights from the dataset.

## Project Overview

The objective of this project is to identify distinct groups within the customer base by analyzing the relationships between various features such as **Age**, **Annual Income**, and **Spending Score**. By applying univariate, bivariate, and multivariate clustering techniques, actionable insights are derived for better marketing strategies and customer targeting.

## Dataset Description

The dataset contains 200 records with the following columns:
- **CustomerID**: Unique ID for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer behavior and spending nature.

## Key Steps

1. **Exploratory Data Analysis (EDA)**:
   - Investigated data distribution and relationships between features.
   - Visualized data using various plots like histograms, scatter plots, and pair plots.

2. **Clustering Algorithms**:
   - Applied K-Means clustering to segment customers.
   - Evaluated cluster quality using metrics like the elbow method and silhouette scores.

3. **Univariate, Bivariate, and Multivariate Analysis**:
   - Segmented customers based on individual features (univariate), two features (bivariate), and all features combined (multivariate).

## Results

- Identified key customer segments with similar spending behaviors and income levels.
- Provided actionable recommendations for marketing strategies based on cluster characteristics.

## Technologies Used

- **Python**: For data preprocessing, analysis, and modeling.
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed along with the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
