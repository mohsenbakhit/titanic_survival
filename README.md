# Titanic Survival Predictor

This Jupyter notebook contains code for predicting the survival of Titanic passengers based on the Kaggle challenge dataset. The dataset provides information about various passengers including their age, gender, class, fare, and whether or not they survived the Titanic disaster.The model predicts the survival of passengers with an accuracy of 76%.


## Prerequisites

Before running the notebook, make sure you have the following libraries installed:

- Pandas
- Tensorflow
- 
## Dataset

The dataset used in this notebook is provided by Kaggle and can be found [here](https://www.kaggle.com/c/titanic/data). It consists of two CSV files: `train.csv` and `test.csv`. The `train.csv` file is used for training the machine learning model, while the `test.csv` file is used for making predictions.

## Notebook Contents

1. Data Loading and Exploration: In this section, we load the dataset and explore its contents. We analyze features such as age, gender, class, fare, and survival rate.
2. Data Preprocessing: This section involves handling missing values, generating dummy variables, encoding categorical variables, and feature engineering.
3. Model Building: We train several machine learning models on the training data and evaluate their performance using gradient-boosted random forest trees.
4. Model Evaluation: We select the best-performing model based on evaluation metrics such as accuracy and regressive loss.
5. Making Predictions: Finally, we use the selected model to make predictions on the test data and generate a submission file for Kaggle.

## Usage

To run the notebook:

1. Clone this repository
2. Launch the cells sequentially.

## Author

[Mohsen Bakhit](https://github.com/mohsenbakhit)

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/mohsenbakhit/titanic_survival/blob/main/LICENSE) file for details.
