# Health Insurance Premium Prediction

This project is aimed at developing a machine learning model to predict health insurance premiums for individuals based on their demographics, lifestyle habits, and medical history. The model is trained on a dataset that contains information on various factors that influence the cost of health insurance.

## Dataset
The dataset used for this project is sourced from Kaggle and can be found at https://www.kaggle.com/mirichoi0218/insurance. It contains 1338 rows and 7 columns, including:

age: age of the individual <br>
sex: gender of the individual <br>
bmi: body mass index (a measure of body fat based on height and weight) <br>
children: number of children covered by the individual's health insurance plan <br>
smoker: whether the individual is a smoker or not <br>
region: the individual's residential area in the US <br>
charges: individual's medical insurance costs billed by the insurance company <br>


## Model
The model is built using Python and scikit-learn, a popular machine learning library. The following steps are taken to build the model:

## Data cleaning and preprocessing:
The dataset is cleaned and missing values are imputed. Categorical variables are encoded using one-hot encoding.
Feature selection: Relevant features are selected using feature importance scores.
Model selection and tuning: Several machine learning models are trained and tuned using grid search cross-validation. The best model is selected based on its performance on the validation set.
Model evaluation: The selected model is evaluated on the test set and its performance is compared to other models.
The final model is deployed as a Flask web application that takes in user input and predicts their health insurance premium.

## Usage
To run this project, you can follow these steps:

Clone the repository to your local machine. <br>

``` git clone https://github.com/prince0310/Health_insurance_premium_prediction.git ``` <br><br>

Install the required packages using  <br>

```pip install -r requirements.txt.```





