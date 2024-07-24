# Student Loan Risk Prediction with Deep Learning

## Overview
This project involves the development of a neural network model to predict the risk of student loan default. Using TensorFlow and Keras, the model assesses the likelihood that a borrower will repay their loan based on historical data. The project is structured to prepare data, build a neural network, evaluate its performance, and discuss the implementation of a recommendation system for student loans.

## Dataset
The dataset used in this project contains various financial and academic attributes of students who have taken out loans. It is publicly available and can be accessed via the following URL: https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv


## Installation
To run this project, you need to have Python installed along with the following libraries:
- Pandas
- TensorFlow
- Scikit-Learn

You can install the required packages using pip:
```bash
pip install pandas tensorflow scikit-learn

## Usage
To execute the project:

1. Clone the repository to your local machine.
2. Navigate to the directory containing the project files.
3. Run the notebook Student_Loan_Risk_with_Deep_Learning.ipynb in Google Colab at https://colab.research.google.com/ or Jupyter notebook. I used Google Colab.

git clone <repository-url>
cd <repository-directory>
jupyter notebook Student_Loan_Risk_with_Deep_Learning.ipynb

## Structure
* Student_Loan_Risk_with_Deep_Learning.ipynb: This Jupyter notebook contains all the code and documentation for the project.
* data/: This directory stores the CSV data file.
* models/: This directory will contain the trained model files.

## Features
The project includes the following steps:

* Data Preprocessing: Load and prepare the data for modeling.
* Model Building: Construct a neural network using TensorFlow's Keras API.
* Model Evaluation: Assess the model's performance on test data.
* Prediction: Make predictions on new data and evaluate the results.
* Discussion: Analyze the potential for a recommendation system based on the model.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your enhancements.

## License
This project is open source and available under the MIT License.
