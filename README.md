# Enhancing Credit Card Fraud Detection Using GANs

## Project Overview
This project addresses the pressing issue of credit card fraud using advanced machine learning techniques, with a focus on the innovative application of Generative Adversarial Networks (GANs). The main objective is to enhance fraud detection methods by synthesizing high-quality, realistic transaction data to address the problem of data imbalance in fraud detection datasets.

## Dataset
The project utilizes the ["Credit Card Fraud Detection Dataset 2023" on Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023), which includes detailed transaction data made by European cardholders. Key dataset characteristics include:
- **Total Transactions**: Over 550,000
- **Fraudulent Transactions**: 492
- **Non-Fraudulent Transactions**: Approximately 284,315
- **Features**: 30 (including 'Time', 'Amount', and 28 anonymized PCA features)
- **Imbalance Ratio**: Approximately 1 fraudulent transaction per 577 legitimate transactions

## Detailed Methodology

### Data Preprocessing
Preprocessing steps included:
- **Normalization**: Application of `StandardScaler` to the 'Amount' feature.
- **Time Conversion**: Conversion of 'Time' from seconds to hours to better analyze transaction patterns.

### Generative Adversarial Networks (GANs)
The project employs a GAN framework to generate synthetic data to balance the dataset:
- **Generator**: Creates data points from a 100-dimensional latent space.
- **Discriminator**: Distinguishes between real and synthetic transactions.
- **Training Dynamics**: Trained over 10,000 epochs, enhancing the quality of generated samples.

### Machine Learning Model Deployment
Models and evaluation included:
- **Training Split**: 80-20 train-test split.
- **Metrics**:
  - **Logistic Regression**: AUPRC of 0.8687, accuracy of 97.09%.
  - **Random Forest and XGBoost**: Perfect scores in AUPRC, accuracy, recall, and precision.

## Comprehensive Results
Results highlight the effectiveness of the data augmentation through GANs:
- **Synthetic Data Impact**: Over 20,000 synthetic fraudulent transactions were generated.
- **Model Performance**:
  - **Detection Improvements**: Enhanced detection capabilities across the models.
  - **Precision and Recall**: Notable improvements, reducing false positives and false negatives.

## Theoretical Framework
The project aligns with key theoretical principles:
- **Imbalanced Learning**: Addressed through synthetic data generation.
- **Anomaly Detection**: Focus on detecting outliers, which often represent fraudulent transactions.

## Future Directions
Future enhancements will include:
- **Real-time Application**: Integration into live transaction processing systems.
- **Cross-validation and Robustness**: Further testing with different datasets to ensure model robustness.

## Conclusion
This project marks a significant advancement in the capability to detect and prevent credit card fraud by leveraging machine learning techniques and synthetic data to address data imbalances, setting a promising path forward for financial security technologies.
