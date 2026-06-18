# Iris Flower Classification Using Artificial Neural Network (ANN)
### Project Overview

This project develops an Artificial Neural Network (ANN) using TensorFlow and Keras to classify Iris flower species based on their physical measurements. The model predicts whether a flower belongs to Setosa, Versicolor, or Virginica using four input features.

### Dataset Information

The project uses the Iris dataset from Scikit-Learn.

## Features:
### Sepal Length (cm)
### Sepal Width (cm)
### Petal Length (cm)
### Petal Width (cm)
## Target Classes:
Setosa
Versicolor
Virginica
Dataset Summary
Total Records: 150
Features: 4
Target Classes: 3
Missing Values: 0
Duplicate Records: 1
Project Workflow
1. Data Loading
Loaded the Iris dataset using Scikit-Learn.
Converted the dataset into a Pandas DataFrame.
2. Data Preprocessing
Checked for missing values.
Checked duplicate records.
Performed feature scaling using StandardScaler.
Applied One-Hot Encoding to target labels.
3. Train-Test Split
Training Data: 80%
Testing Data: 20%
4. Model Development

Built an Artificial Neural Network with:

Input Layer: 4 neurons
Hidden Layer 1: 10 neurons (ReLU)
Hidden Layer 2: 8 neurons (ReLU)
Output Layer: 3 neurons (Softmax)
5. Model Training
Optimizer: Adam
Loss Function: Categorical Crossentropy
Evaluation Metric: Accuracy
6. Model Evaluation
Accuracy Score
Classification Report
Confusion Matrix
7. Model Saving
Saved trained ANN model
Saved StandardScaler using Joblib
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-Learn
TensorFlow
Keras
Joblib
Results

The ANN model successfully classified Iris flower species with excellent performance.

Key Findings
No missing values were present in the dataset.
Petal measurements were the most influential features.
The model achieved high classification accuracy.
The confusion matrix showed very few classification errors.
Feature scaling improved model performance and convergence.
Project Structure
Iris-ANN-Classification/
│
├── Iris_ANN.ipynb
├── ann_model.keras
├── scaler.pkl
├── README.md
└── requirements.txt
How to Run
Install Required Libraries
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow joblib
Run the Notebook
jupyter notebook

Open the notebook and execute all cells sequentially.

Future Improvements
Hyperparameter tuning
Cross-validation
Model deployment using Streamlit
Comparison with traditional machine learning algorithms
Advanced neural network architectures
Author

Mohamed Shihad
