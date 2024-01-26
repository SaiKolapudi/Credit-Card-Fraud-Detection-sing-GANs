# Enhancing Credit Card Fraud Detection Using GANs

## Course Details
- Course Name: ADTA 5340 Section 002 - Discovery and Learning with Big Data (Fall 2023 1)
- Professor: Dr. Leann Boyce

## Project Overview
This project, undertaken by Meghana Patibandla, Sai Tulasi Kolapudi, and Rakesh Sarma Karra, focuses on the critical issue of credit card fraud detection. Utilizing Generative Adversarial Networks (GANs), our goal is to significantly enhance the accuracy of fraud detection systems, contributing to the security and reliability of financial transactions.

## Dataset
The dataset used in this project can be found at the following link: [Credit Card Fraud Detection Dataset 2023](link_here)

## Challenge: Imbalanced Data
The primary challenge addressed in this project is the class imbalance present in the credit card transaction dataset, where legitimate transactions significantly outnumber fraudulent ones. This imbalance poses a significant challenge for machine learning models, potentially leading to a high rate of false negatives.

## Solution: Data Augmentation with GANs
To overcome the issue of imbalanced data, we employed GANs to generate synthetic but realistic fraudulent transactions, thereby balancing the dataset. This approach not only aids in balancing the dataset but also enriches the training data, enhancing the model's ability to detect fraudulent transactions more accurately.

## Methodology
### Data Preprocessing
Initial data cleaning and standardization were performed to prepare the dataset for effective model training.

### GAN Implementation
We developed and trained GANs to create synthetic fraudulent transactions, addressing the issue of data imbalance.

### Model Training and Evaluation
A variety of machine learning models were trained and evaluated on the augmented dataset, using metrics such as accuracy, precision, recall, and AUPRC to assess their performance.

## Key Findings
The use of GAN-generated synthetic data was a key factor in improving the performance of fraud detection models, demonstrating the effectiveness of data augmentation techniques in machine learning, especially in scenarios involving imbalanced datasets.

## Future Work
Our future work includes applying our models to different datasets and exploring real-time fraud detection applications. We also aim to focus on enhancing the explainability and transparency of our machine learning models.

## Team Contributions
- Meghana Patibandla: Led the data analysis, preprocessing, and optimization of Logistic Regression and SVM models.
- Sai Tulasi Kolapudi: Focused on the development and refinement of GANs for data augmentation, and worked on Random Forest and Naive Bayes models.
- Rakesh Sarma Karra: Concentrated on the evaluation of XGBoost, KNN, and Decision Trees models, and managed documentation and data privacy aspects.

## Acknowledgments
We express our sincere gratitude to Dr. Leann Boyce for her expert guidance and support throughout this project. Her insights were invaluable in steering the project towards success.
