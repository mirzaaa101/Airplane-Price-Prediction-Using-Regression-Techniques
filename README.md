# Airplane-Price-Prediction-Using-Regression-Techniques

## Overview

This project aims to predict the prices of planes based on various features using regression techniques. The dataset, sourced from Kaggle, includes information about different planes and their corresponding prices. By leveraging machine learning regression models, I intend to build a predictive model that accurately estimates the price of a plane given its characteristics.

## Dataset

The dataset used for this project is obtained from Kaggle and can be found [here](https://www.kaggle.com/datasets/rafsunahmad/plane-price-prediction). It contains essential features such as the model, manufacturer, year of manufacture, and other specifications related to various planes. The target variable is the price of each plane.

## Project Steps

1. **Data Exploration and Visualization:**
   - Understand the structure of the dataset.
   - Numerical Attributes Exploration
   - Categorical Attributes Exploration

2. **Feature Engineering:**
   - Create new features if necessary.
     
3. **Data Cleaning and Preprocessing:**
   - Split the dataset into training and testing sets.
   - Handle categorical variables using techniques like one-hot encoding.
   - Scale numerical features using standardization or normalization.
   - Filling missing with imputation techniques

4. **Model Selection,Training, and Evaluation on Training Data:**
   - Evaluate the performance of each model using appropriate metrics (e.g., Root Mean Squared Error (RMSE)).
   - Try to understand overfitting and underfitting using learning curves.
   - Apply regularization techniques to mitigate overfitting and enhance model generalization.
       - L1 Regularization (Lasso):Introduce sparsity in feature selection.
       - L2 Regularization (Ridge): Control the complexity of the model and prevent overfitting.
       - Early Stopping: Halt training when the model's performance on the validation set starts to degrade.
    
         
5. **Fine-Tune Model**
    - Select the best model, and fine-tune hyperparameters to improve model performance

6. **Model Evaluation on Testing Data:**
   
   - RMSE: Evaluate model performance on test data using Root Mean Squared Error.
   - Confidence Interval: Assess the precision of model predictions with confidence intervals.
     
7. **Save Model**


## Author Name and Contact
  - Mirza Abbas Uddin (mirzaabbasuddin2@gmail.com)

## Contributions

Contributions to the project are welcome! Feel free to submit pull requests or open issues if you have ideas for improvement or if you encounter any challenges.

## License

This project is licensed under the [MIT License](LICENSE).

