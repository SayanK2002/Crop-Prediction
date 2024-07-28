## Crop Prediction

This repository contains a machine learning project focused on predicting the type of crop based on various environmental and soil features. The project includes data preprocessing, model training, evaluation, and prediction steps. The project's main aim is to develop a model that accurately predicts which crops can be grown using the provided soil and weather specifications and also provide us with a list of crops that can be grown in the given weather and soil conditions. This will aid the agriculture industry in determining the crops that can be grown with given conditions and chemicals in the soil.

## Introduction

Crop prediction is crucial for farmers and agricultural planners to make informed decisions about crop management. This project utilizes machine learning techniques to predict the type of crop based on features such as temperature, humidity, soil pH, and rainfall.

## Dataset

The dataset used in this project contains various environmental and soil features along with the corresponding crop labels. The data is preprocessed and used to train several machine learning models. The dataset is in a CSV file named `crops.csv`.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

You can install the required libraries using the following command:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Preeray/crop-prediction.git
   cd crop-prediction
   
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Crops.ipynb
   
3. Run the cells in the notebook to preprocess the data, train the model, and make predictions.

## Model

The notebook includes the implementation of these machine-learning models:
- Logistic Regression (using Logistic Regression we predicted which crop could be grown in a given soil condition)
- K-Means (using K-Means we determined all the crops that can be grown in the respective soil and weather conditions in the dataset)

The models are trained and evaluated using the given dataset. The best-performing model is selected based on accuracy and other evaluation metrics.

# Results
The results of the model evaluations are summarized in the notebook. The final model achieves high accuracy in predicting the type of crop based on the input features.

# Contributing
Contributions are welcome! If you have any improvements or new features to add, please fork the repository and submit a pull request.




