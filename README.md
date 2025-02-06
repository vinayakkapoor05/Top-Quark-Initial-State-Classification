## Top Quark Initial State Classification

This project aims to classify quark-antiquark initial state top-quark anti-top-quark events from gluon-gluon fusion initial states using machine learning techniques.

## Project Overview

### Overview
The study utilizes machine learning approaches, specifically **XGBoost** and **Deep Neural Networks (DNN)**, to distinguish between different initial states of top-quark production.

### Project Components
- **Dataset**: Simulated collision data containing features distinguishing quark-antiquark from gluon-gluon initial states.
- **Modeling Approaches**:
  - **XGBoost Classifier (Attempt 1)**: Used default hyperparameters with a learning rate of 0.001 and a maximum depth of 7.
  - **XGBoost Classifier (Attempt 2 - Higher-Dimensional Input)**: Increased learning rate to 0.01 and adjusted regularization parameters.
  - **Deep Neural Network (Attempt 3 - L1 Norm Regularization)**: Implemented a fully connected neural network with L1 norm regularization to enhance classification performance.
- **Evaluation Metrics**: The models were evaluated based on accuracy, precision, recall, and ROC-AUC scores.

### Results
- The XGBoost models provided a strong baseline classification, with the second attempt improving due to higher-dimensional input and optimized hyperparameters.
- The DNN model introduced regularization techniques to further refine classification accuracy.

## Code

This repository includes Python scripts and Jupyter Notebooks for:
- **Training XGBoost classifiers** on simulated top-quark event data.
- **Applying higher-dimensional input** to improve model performance.
- **Developing and training a Deep Neural Network (DNN)** for classification.
- **Visualizing model performance** using standard evaluation metrics.
