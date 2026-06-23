# amazon-product-substitute-classification
Amazon Product Substitute Classification

Machine learning classification project developed using Python, pandas, scikit-learn, and PyTorch.

Overview

This project predicts whether two Amazon products can serve as substitutes for one another using tabular product data. The workflow includes exploratory data analysis, feature engineering, data preprocessing, neural network training, and model evaluation.

Technologies Used

* Python
* pandas
* NumPy
* scikit-learn
* PyTorch
* Jupyter Notebook

Methodology

* Performed exploratory data analysis and data cleaning
* Processed numerical and categorical features using scikit-learn pipelines
* Applied feature scaling and one-hot encoding
* Built and trained a neural network using PyTorch
* Evaluated model performance using validation metrics including F1 score and ROC-AUC
* Optimized classification thresholds to improve predictive performance

Results

The final model achieved a validation F1 score above 0.70 after threshold optimization and was used to generate predictions on unseen product pairs.

Dataset

The dataset files are not included in this repository. The notebook expects `training.csv` and `public_test_features.csv` to be available locally in the project directory.
