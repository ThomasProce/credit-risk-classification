# Credit Card Approval Project

## Overview
This project focuses on credit card approval using machine learning techniques. It involves working with a strong class imbalance in the dataset, where the number of good payer's and bad payer's applications varies significantly. Despite several modeling attempts, the prediction quality remains close to randomness, highlighting the complexity of this problem. Additionally, the dataset is substantial, containing over 500,000 records without oversampling and nearly 1 million records with oversampling, making model training often very long and tedious (especially when searching for the best hyper-parameters)

## Project Structure

## Data Visualization Before Preprocessing

Before diving into data preprocessing and modeling, it's crucial to visualize the dataset to gain insights into its structure and characteristics. We use a variety of visualization techniques to explore both continuous and discrete variables.

### Data Preprocessing
In this section, we tackle the challenge of working with an imbalanced dataset. We explore techniques such as oversampling and undersampling to balance the classes and prepare the data for modeling. We also handle missing values, outliers, and categorical variables during this phase.

### Feature Engineering
Feature engineering is crucial for improving model performance. In this section, we create new features, transform existing ones.
The goal is to provide the models with informative features for better predictions.

### Model Selection
To address the credit card approval problem, we experiment with various machine learning models. We explore traditional models like Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.

### Model Training and Evaluation
Each model undergoes a comprehensive training and evaluation process. We split the data into training and testing sets and employ appropriate evaluation metrics such as precision, recall, F1-score, and ROC-AUC to assess model performance. Detailed results and model comparisons are provided in this section.

### Hyperparameter Tuning
To fine-tune the models, we perform hyperparameter optimization using techniques like Random Search. This step aims to maximize the predictive power of our models.

### Conclusion
Despite the extensive efforts made to address the credit card approval problem, the results have been challenging. The strong class imbalance of the dataset pose significant hurdles. This project serves as a valuable learning experience, highlighting the importance of data preprocessing, feature engineering, and model selection in tackling real-world imbalanced datasets.

## Future Work
While the current results are not optimal, there are several avenues for future improvement:

- Exploring advanced anomaly detection techniques.

- Collecting additional features or external data sources to enhance model performance.

- Investigating alternative machine learning algorithms or deep learning architectures.
---

**Note:** Due to the complexity of the problem and the limitations of the current dataset, achieving high-quality predictions may be challenging. The goal of this project is to explore various techniques and methodologies for dealing with credit card approval in an imbalanced dataset scenario.
