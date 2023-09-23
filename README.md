# Customer Churn Prediction with Deep Learning - IIITD

Predict customer churn using deep learning models. This repository houses the code and assets required to build a robust deep learning model to forecast customer churn based on a variety of demographic and account-specific factors.

## About the Dataset
The dataset, available on Kaggle as [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), covers:

- **Churn Information**: Details on customers who left in the last month.
  
- **Subscribed Services**: Phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV, and movies.
  
- **Account Information**: Tenure as a customer, contract type, payment method, paperless billing, monthly charges, and total charges.
  
- **Demographics**: Gender, age range, partnership status, and dependents.

## Getting Started

To get started, clone the repository to your local machine:

### 1. Clone the Repository

```bash
git clone git@github.com:Ananyapam7/Customer-Churn-Prediction-IIITD.git && cd Customer-Churn-Prediction-IIITD
```

### 2. Setup Environment
Depending on your setup, choose between Conda and Pip:

- **Conda**: 
    ```bash
    conda env create -f environment.yml
    ```

- **Pip**: 
    ```bash
    pip3 install -r requirements.txt
    ```

### 3. Dependencies
Ensure the following packages are installed:

```
numpy == 1.24.3
pandas == 2.1.1
scikit-learn == 1.3.1
TensorFlow == 2.13.0
matplotlib == 3.8.0
```

### 4. Repository Structure

Here's a brief overview of the structure of this repository:

```
├── data
├── models              
├── plots
├── notebooks                                       
├── LICENSE
└── README.md
```

---

## Exploratory Data Analysis and Machine Learning (R)

Dive into a comprehensive analysis and machine learning tasks using R. In this section, we:

- **Data Preprocessing**:
  - Explore the dataset
  - Data Imputation
  - Outlier Detection
  - Data Manipulation
  - Visualize distributions of different features
  
- **Analysis and Insights**:
  - Study the most popular products by ranking
  - Market Basket Analysis: Discover products/plans often purchased together
  
- **Modeling and Predictions**:
  - Recommender System
  - Cluster Analysis
  - Correlation Analysis
  - Dimensionality Reduction
  - Churn Prediction

🔗 [Access the R HTML page](https://students.iiserkol.ac.in/~ad18ms075/notebooks/notebook-eda.html) for detailed code snippets, visualizations, and insights.

---

## Deep Learning and Transformers (Python)

Venture into the realm of deep learning and transformers using Python. In this section, we discuss:

- **Modeling and Predictions**:
  - Churn Prediction using Artificial Neural Networks (ANN)
  
- **Deep Dive into Transformers**:
  - Reasons why a Transformer-based model might not be ideal
  - Observations during model training
  - Confusion Matrix Analysis

🔗 [View the Jupyter Notebook](https://students.iiserkol.ac.in/~ad18ms075/notebooks/notebook-deep-learning.html) for a closer look into the methodologies and results.
