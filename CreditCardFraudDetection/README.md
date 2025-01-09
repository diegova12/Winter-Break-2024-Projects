# Credit Card Fraud Detection

This project demonstrates the implementation of a machine learning pipeline for detecting fraudulent credit card transactions using the `creditcard.csv` dataset.

## Project Overview
Fraudulent credit card transactions pose a significant challenge to financial institutions. This project aims to evaluate the performance of various machine learning models in detecting fraudulent transactions, comparing results between unbalanced and balanced datasets.

## Features of the Project
- Implementation of multiple machine learning models, including:
  - Logistic Regression
  - Random Forest Classifier
  - Shallow Neural Network
  - Support Vector Classifier (SVC)
- Comparative analysis of model performance on unbalanced vs. balanced datasets.
- Evaluation metrics such as accuracy, precision, recall, and F1-score.

## Dataset
The `creditcard.csv` dataset contains transaction records with the following attributes:
- **Time**: Seconds elapsed between the transaction and the first transaction in the dataset.
- **V1 to V28**: Anonymized features resulting from a PCA transformation.
- **Amount**: Transaction amount.
- **Class**: Target variable (1 for fraudulent, 0 for legitimate).

The dataset is highly imbalanced, with fraudulent transactions constituting a small fraction of the total.

## Prerequisites
To run this project, you need:
- Python 3.8 or higher
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/diegova12/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
4. Follow the notebook instructions to train the models, compare their performance, and evaluate the impact of dataset balancing.

## Results
Key insights and results of the project include:
- Comparative performance metrics for each model on unbalanced and balanced datasets.
- Visualizations highlighting the impact of data balancing on model performance.

## Future Improvements
- Experiment with additional balancing techniques, such as undersampling or ensemble methods.
- Test deep learning architectures for further improvement.
- Explore feature selection methods to identify the most influential attributes.
