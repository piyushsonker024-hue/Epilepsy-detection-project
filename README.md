EEG Epilepsy Detection using Machine Learning
Overview

This project focuses on detecting epileptic seizures from EEG (Electroencephalogram) signals using machine learning techniques. EEG signals capture electrical activity in the brain, and analyzing them with ML models can help identify abnormal patterns associated with seizures. Automated EEG analysis can assist clinicians by reducing manual interpretation time and improving diagnostic accuracy.

The goal of this project is to build a machine learning pipeline that processes EEG features and classifies signals into epileptic and non-epileptic categories.

Project Features

EEG data preprocessing and cleaning

Feature analysis and visualization

Machine learning model training

Model evaluation and comparison

Prediction of epileptic seizure activity

Dataset

The dataset contains EEG signal features extracted from brain recordings.

Typical EEG seizure datasets contain:

Multiple EEG recordings

Numerical features extracted from brain signals

Labels indicating seizure or non-seizure activity

These datasets are commonly used to train machine learning models for seizure classification tasks.

Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

Machine Learning Models

The following machine learning algorithms are used:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

These models are trained on EEG features to classify seizure activity.

Project Workflow

Data Loading

Data Preprocessing

Exploratory Data Analysis

Feature Scaling

Train-Test Split

Model Training

Model Evaluation

Project Structure
Epilepsy-detection-project
│
├── data
│   └── epileptic_featured_data.csv
│
├── notebooks
│   └── EEG_epilepsy_detection.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
Installation

Clone the repository:

git clone https://github.com/piyushsonker024-hue/Epilepsy-detection-project.git

Move into the project directory:

cd Epilepsy-detection-project

Create a virtual environment:

python -m venv myenv

Activate environment:

Mac / Linux

source myenv/bin/activate

Windows

myenv\Scripts\activate

Install dependencies:

pip install -r requirements.txt
Usage

Run the Jupyter notebook:

jupyter notebook

Open:

EEG_epilepsy_detection.ipynb
Results

The trained machine learning models are evaluated using metrics such as:

Accuracy

Confusion Matrix

Classification Report

These metrics help compare model performance for seizure detection.

Future Improvements

Use deep learning models (CNN / LSTM)

Real-time EEG seizure detection

Deploy model as a web application

Improve feature engineering

Author

Piyush Sonker
