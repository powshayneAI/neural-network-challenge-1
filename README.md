# neural-network-challenge-1

### Challenge Overview

This challenge involves building a deep neural network model to classify data using TensorFlow and Keras, focusing on data preparation, model training, evaluation, and prediction.

###  Technologies Used

- Python Libraries:
- - pandas, tensorflow, keras
- - Dense, Sequential
- - train_test_split, StandardScaler
- - classification_report, Path

### Data Preparation

- Loaded data into a pandas DataFrame.
- Created feature datasets X (features) and y (target).
- Split the data into training and testing sets using train_test_split.
- Scaled features with StandardScaler.

### Model Creation

- Built a Sequential model with Dense layers.
- Compiled the model using:
- Loss Function: binary_crossentropy
- Optimizer: adam
- Metrics: accuracy

### Model Evaluation

- Trained the model on the training data.
- Evaluated performance using the testing data and generated a classification report.

### Predictions and Reporting

- Saved the model as a .keras file and reloaded it for predictions.
- Compiled predictions into a pandas DataFrame.
- Generated a classification report based on the predictions.

### Recommendation System for Student Loans
- Answered three questions pertaining to how I would go about creating a recommendation system for student loans.
- - What would I use?
- - Collaborative, Content-Based, or Context-Based filtering?
- - What are two real-world challenges?

