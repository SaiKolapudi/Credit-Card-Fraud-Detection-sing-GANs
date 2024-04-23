# Enhancing Credit Card Fraud Detection Using GANs

## Project Overview
This project addresses the critical issue of credit card fraud by incorporating Generative Adversarial Networks (GANs) to improve the accuracy and reliability of fraud detection systems. The integration of GANs enhances the security framework of financial transactions, providing a robust solution to a growing concern in the financial sector.

## Dataset
The Credit Card Fraud Detection Dataset 2023, hosted on [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023), is comprised of over 550,000 credit card transactions made by European cardholders. It contains anonymized data to maintain cardholder privacy while providing rich features for analysis. Each transaction is uniquely identified, with 28 anonymized features (V1-V28) that represent various transaction attributes such as time and location, along with the transaction amount ('Amount') and a binary class label ('Class') indicating fraudulent or non-fraudulent transactions. This dataset is invaluable for developing and testing fraud detection algorithms, analyzing merchant category risks, and understanding transaction type vulnerabilities.

### Key Features:
- **id**: Unique identifier for each transaction.
- **V1-V28**: Anonymized features that encapsulate diverse transaction attributes.
- **Amount**: The transaction amount, providing insights into transaction volume.
- **Class**: Binary classification where '1' indicates a fraudulent transaction and '0' indicates a non-fraudulent transaction.

### Use Cases:
- **Credit Card Fraud Detection**: Develop machine learning models to detect and preemptively prevent fraud.
- **Merchant Category Analysis**: Investigate correlations between merchant categories and fraudulent transactions.
- **Transaction Type Analysis**: Analyze the susceptibility of different transaction types to fraud.

## Challenge: Class Imbalance
The dataset suffers from a severe imbalance with a ratio of approximately 400,000 non-fraudulent to 150,000 fraudulent transactions, initially posing a challenge to accurate fraud detection due to model bias towards the majority class.

## Solution: Augmented Data for Enhanced Security
To combat this challenge, the project utilizes GANs to generate synthetic fraudulent transactions, thus balancing the dataset. The augmented dataset enables effective model training and substantially improves detection accuracy.

## Methodology

### Data Preprocessing
Initial steps involved standardizing the 'Amount' feature and converting 'Time' from seconds to hours to reflect transaction trends. Outliers were specifically analyzed as they often represent genuine fraud cases, contributing to more accurate fraud detection.

### GAN Implementation
GANs were implemented to generate high-quality synthetic fraudulent transactions. The generator synthesized realistic samples, while the discriminator refined their quality, ensuring the synthetic data closely mimics real transaction patterns.

### Model Training and Evaluation
Models deployed include Logistic Regression, Random Forest, XGBoost, KNN, Naive Bayes, SVM, and Decision Trees. These models were evaluated using metrics such as accuracy, precision, recall, and AUPRC (Area Under the Precision-Recall Curve), ensuring robust validation of the models' effectiveness.

## Key Findings
- **Model Efficacy**: Advanced models like Random Forest, XGBoost, and Decision Trees demonstrated high efficacy, with perfect scores in accuracy, precision, and recall.
- **Importance of Outliers**: Including outliers in the analysis significantly enhanced the detection of fraudulent transactions.
- **Effectiveness of GANs**: The use of GANs for data augmentation was pivotal in balancing the dataset and improving the performance of machine learning models.

## Future Directions
Future work will involve further validation of the models on diverse datasets and integration into real-time fraud detection systems. A continuous focus will be maintained on enhancing the models' explainability and transparency, essential for deploying in sensitive environments.

## Acknowledgments
We acknowledge the guidance and expertise provided by industry experts, which have been instrumental in advancing this project.
