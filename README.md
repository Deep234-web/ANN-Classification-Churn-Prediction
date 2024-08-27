# Customer Churn Prediction Using ANN

This project aims to predict customer churn using an Artificial Neural Network (ANN) model. The dataset includes various customer features, and the goal is to determine whether a customer is likely to churn based on these features.

## Overview

Customer churn is a critical issue for businesses, and predicting churn allows companies to take proactive measures to retain customers. This project builds a churn prediction model using an Artificial Neural Network (ANN) and deploys it as a web application using Streamlit.

### Key Features of the Project:

- **Data Preprocessing**: Handled missing data, performed feature scaling, and encoded categorical variables using Label Encoding and One-Hot Encoding.
- **Model Building**: Developed an ANN model using TensorFlow and Keras.
- **Model Evaluation**: Evaluated the model's performance on a test dataset.
- **Deployment**: Deployed the model using Streamlit for real-time churn prediction.

## Data Preprocessing

1. **Label Encoding**:
   - The `Gender` feature was encoded using `LabelEncoder`. This converts categorical labels into numeric form, essential for feeding into the ANN model.
2. **One-Hot Encoding**:
   - The Geography feature was one-hot encoded using OneHotEncoder. This prevents the model from misinterpreting the ordinal relationship in categorical features.
3. **Feature Scaling**:
   - Applied feature scaling using StandardScaler to ensure all features contribute equally to the ANN model.
  
## Model Building

**Architecture**:
   - The ANN model was built using TensorFlow and Keras. The architecture includes input, hidden, and output layers designed to capture complex relationships in the data.
**Compilation**:
   - The model was compiled with an appropriate loss function and optimizer, typically binary_crossentropy and adam for binary classification tasks.
**Training**:
   - The model was trained on the preprocessed dataset, and various metrics such as accuracy and loss were monitored during training.

## Model Deployment
   - The trained model was deployed using Streamlit, a powerful framework for creating interactive web applications. Users can input various customer details to predict the likelihood of churn.
- **Deployment Link**: [Customer Churn Prediction App](https://ann-classification-churn-prediction-pfrkb7vdbubvqs9fgcsrx6.streamlit.app/)

     
