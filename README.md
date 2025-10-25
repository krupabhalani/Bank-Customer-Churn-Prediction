# Bank-Customer-Churn-Prediction

Description: Developed a neural network model to predict customer churn for a retail bank using structured customer data, enabling proactive retention strategies and better understanding of customer behavior.

Loaded and explored the Churn_Modelling.csv dataset using pandas for initial inspection and data validation.

Dropped irrelevant identifiers (RowNumber, CustomerId, Surname) and analyzed categorical variables (Geography, Gender) for class balance.

Applied One-Hot Encoding to categorical columns with pd.get_dummies() and split data into features (X) and target (y) variables.

Divided data into training and testing sets using train_test_split and standardized features via StandardScaler for improved neural network convergence.

Built a Sequential Neural Network in TensorFlow/Keras with two hidden layers (ReLU activation) and one sigmoid output layer for binary classification.

Compiled the model using Adam optimizer and binary cross-entropy loss, and trained for 10 epochs with 20% validation split.

Evaluated model performance on unseen data, achieving 85.55% test accuracy and visualized training metrics using Matplotlib.

Tech Stack: Python, pandas, scikit-learn, TensorFlow, Keras, Matplotlib
