# Online-Fraud-detection-using-machine-learning


## Overview
This project focuses on fraud detection in financial transactions using a dataset loaded with transaction details. It involves exploratory data analysis, correlation insights, and the implementation of a Decision Tree Classifier for predictive modeling.

## Prerequisites
- Python 3.x
- Libraries: pandas, numpy, plotly, scikit-learn

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection.git

   
1. Install the required dependencies:
   pip install -r requirements.txt
2. Run the Jupyter Notebook or Python script:
   python fraud_detection.py

Project Structure
fraud_detection.py: Main script for data preprocessing, analysis, and model training.
data/: Directory to store the dataset (fraud.csv).
results/: Directory to store visualizations and model outputs.
Data Exploration
The dataset is loaded using pandas, and initial insights are gained through exploratory data analysis.
Missing values are handled, and the distribution of transaction types is visualized using Plotly Express.
Feature Engineering
Transaction types are mapped to numerical values for model compatibility.
The target variable "isFraud" is mapped to "No Fraud" (0) and "Fraud" (1).
Machine Learning Model
Features (type, amount, oldbalanceOrg, newbalanceOrig) and target variable (isFraud) are extracted for training.
A Decision Tree Classifier is implemented using scikit-learn.
The model is trained and evaluated on a test set, providing accuracy metrics.
Predictions
A sample transaction is provided to showcase real-time predictions for fraud likelihood.
Results
Visualizations, correlation insights, and model accuracy are discussed in the project documentation.
Contributions
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

License
This project is licensed under the MIT License.
