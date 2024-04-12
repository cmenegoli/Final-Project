# Airline Passenger Satisfaction Prediction

## Project Overview
This project involves the development of a machine learning model to predict airline passenger satisfaction based on various features such as age, gender, class, type of travel, service ratings, and flight delays. We use a dataset containing records of airline passenger surveys to train a Random Forest classifier.

## Dataset
The dataset includes details about passengers' flight experience, which encompasses demographic data, ratings for services, and flight delay timings. It consists of approximately 25,976 entries with 25 columns, including a target column that indicates satisfaction.

## Model
A Random Forest classifier was chosen for this task due to its robustness and efficacy in handling both categorical and numerical data. The model predicts whether a passenger was satisfied or neutral/dissatisfied with their flight experience.

## Results
The model achieved an accuracy of about 95.09% on the test set, with high precision and recall across both categories of satisfaction. This demonstrates the model's ability to effectively predict passenger satisfaction.

## Setup and Installation
To run this project, you will need Python installed on your machine, along with the following packages:
- Pandas
- Scikit-learn

### Steps to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have the necessary Python packages installed by running:
   ```bash
   pip install pandas scikit-learn