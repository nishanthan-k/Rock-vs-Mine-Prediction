# Rock vs Mine Prediction using Logistic Regression

This repository contains a machine learning project for predicting whether an object detected underwater is a rock or a mine. The project utilizes logistic regression as the classification algorithm.

## Dataset

The dataset used for this project consists of features extracted from sonar signals that were bounced off various objects. The dataset contains 208 observations, each with 60 numerical attributes and a corresponding label indicating whether the object is a "rock" or a "mine".

The dataset can be found at [UCI Machine Learning Repository](https://drive.google.com/file/d/1Ia0H1mer0kRDyQ1IdhCouvQc5sk1DHOO/view).

## Requirements

### To run this project, you need the following dependencies:

    Python 3.x
    NumPy
    Pandas
    Scikit-learn

## The script will perform the following steps:

    1. Load the dataset.
    2. Preprocess the data by splitting it into features and labels, and performing any necessary data transformations.
    3. Split the data into training and testing sets.
    4. Train a logistic regression model on the training data.
    5. Evaluate the model's performance on the testing data.
    6. Print the accuracy of the model.

## Results

The script will output the accuracy of the logistic regression model on the testing data. 

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

This project is based on the "Connectionist Bench (Sonar, Mines vs. Rocks)" dataset from the UCI Machine Learning Repository. Special thanks to the creators of the dataset for making it available for research purposes.
