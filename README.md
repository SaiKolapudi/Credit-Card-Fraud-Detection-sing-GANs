# Enhancing Credit Card Fraud Detection Using GANs

## Course Details
- Course Name: ADTA 5340 Section 002 - Discovery and Learning with Big Data (Fall 2023 1)
- Professor: Dr. Leann Boyce

## Project Overview
In this project, Meghana Patibandla, Sai Tulasi Kolapudi, and Rakesh Sarma Karra tackle the pervasive issue of credit card fraud. By integrating Generative Adversarial Networks (GANs) into our methodology, we aim to significantly improve the accuracy and reliability of fraud detection mechanisms, thereby bolstering the security framework of financial transactions.

## Dataset
The dataset employed for this project is accessible at: [Credit Card Fraud Detection Dataset 2023](link_here)

## Challenge: Class Imbalance
A significant challenge in credit card fraud detection is the disproportionate ratio of legitimate to fraudulent transactions within datasets. This imbalance can skew machine learning models towards false negatives, undermining the effectiveness of fraud detection.

## Solution: Augmented Data for Enhanced Security
To address the challenge of imbalanced data, we utilized GANs to synthesize realistic fraudulent transactions, thereby achieving a more balanced dataset. This augmentation process not only improves the dataset's diversity but also enhances the models' ability to accurately identify and adapt to emerging fraudulent patterns, leading to a more secure and robust fraud detection system.

## Methodology
### Data Preprocessing
We began with thorough data cleaning and standardization to ensure the dataset was optimally prepared for model training.

### GAN Implementation
Our team developed GANs capable of generating synthetic fraudulent transactions, effectively mitigating the issue of data imbalance.

### Model Training and Evaluation
Various machine learning models were trained and evaluated on the augmented dataset. Their performance was measured using metrics such as accuracy, precision, recall, and AUPRC.

## Key Findings
Integrating GAN-generated synthetic data proved crucial in enhancing the detection capabilities of our fraud detection models. This approach not only addresses the challenge of imbalanced data but also contributes significantly to the security of financial transaction systems by improving the accuracy and adaptability of fraud detection algorithms.

## Future Directions
We plan to extend our research by testing our models on a wider array of datasets and exploring the integration of our solutions into real-time fraud detection systems. Enhancing the models' explainability and transparency remains a key objective.

## Team Contributions
- Meghana Patibandla: Led data analysis, preprocessing, and the enhancement of Logistic Regression and SVM models.
- Sai Tulasi Kolapudi: Pioneered the development of GANs for data augmentation and contributed to the advancement of Random Forest and Naive Bayes models.
- Rakesh Sarma Karra: Specialized in evaluating XGBoost, KNN, and Decision Trees models, and oversaw project documentation and data privacy compliance.

## Acknowledgments
Special thanks to Dr. Leann Boyce for her invaluable guidance and expertise, which were instrumental in the success of this project.
