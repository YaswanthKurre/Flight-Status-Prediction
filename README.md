# Flight-Status-Prediction


1. Introduction
    
  Welcome to the Flight Status Prediction project! This repository contains a machine learning model that predicts the status of flights, addressing issues related to flight delays and cancellations. Our goal is to provide accurate flight status predictions to benefit both travelers and airlines.

1.1 Business Problem

  The primary business problem we aim to solve is to predict the following aspects of flight status:
  Which flights are expected to be cancelled?
  Which flights are expected to be delayed?

1.2 Dataset

  We utilized a dataset from Kaggle for our flight status prediction model. Here are some key details about the dataset:
  
  The dataset comprises 61 features (columns) and 4,078,318 instances (rows).
  For our project, we focused on using approximately 200,000 instances.
  The "cancelled, delayed, delay time target" attribute serves as the target variable for our predictions.
  
2. Project Details
   
2.1 Classifiers

  In this project, we have implemented five different classifiers to predict flight statuses:
  
  K-Nearest Neighbor classifier
  Gaussian Naïve Bayes classifier
  Logistic Regression classifier
  Random Forest classifier
  AdaBoost classifier
  We will train the dataset using all these classifiers and select the one that achieves the highest accuracy for our flight status predictions.

3. Getting Started
   
 To get started with this project, follow the instructions below.

3.1 Prerequisites

Before running the code, ensure you have the following prerequisites installed:
Python 3.x
Required Python libraries

3.2 Installation

Clone this repository to your local machine: git clone https://github.com/your-username/Flight-Status-Prediction.git

Navigate to the project directory: cd Flight-Status-Prediction

4. Usage
   
 To use the flight status prediction model, refer to the documentation and example scripts provided in the project repository. You can run the classifier of your choice to make flight status predictions based on the trained model.
