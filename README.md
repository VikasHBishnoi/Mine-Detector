**Sonar Object Classification using Logistic Regression**<br>
This repository contains a logistic regression-based machine learning model that classifies objects as either stones or mines based on sonar details.

**Dataset**<br>
The dataset used for training and testing the model consists of 208 instances and 60 features. Each instance represents sonar readings of an object, and the features represent different aspects of the sonar data.

The dataset was sourced from the Kaggle website and is provided in the data.csv file, where each row corresponds to an instance, and the columns represent the features and the target variable (stone or mine).

**Dependencies**<br>
The following dependencies are required to run the code:
Python (latest version)
NumPy (latest version)
Pandas (latest version)
Scikit-learn (latest version)
You can install the required dependencies using the following command:
pip install -r requirements.txt

**Usage**<br>
To use the logistic regression model for object classification, follow these steps:
Clone this repository or download the source code.
Make sure you have the required dependencies installed.
Run the Mine_Detector.ipynb Jupyter Notebook file to train the logistic regression model on the provided dataset.
After training, you can use the trained model to classify new objects by running the notebook cells and providing the necessary input.
The predicted class (stone or mine) for each object will be displayed as the output.

**Results**<br>
The logistic regression model achieved an accuracy of 0.7619 (76.19%) on the test data. This indicates the proportion of correctly classified objects out of the total number of objects in the test set.

**Acknowledgments**<br>
The dataset used in this project was sourced from Kaggle.
The logistic regression implementation is based on the Scikit-learn library.
