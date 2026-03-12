# EEG Epilepsy Detection using Machine Learning

## Overview

This project focuses on detecting **epileptic seizures from EEG (Electroencephalogram) signals** using machine learning techniques. EEG signals represent electrical activity in the brain, and analyzing these signals can help identify abnormal patterns associated with epileptic seizures.

The goal of this project is to build a **machine learning pipeline** that processes EEG signal features and classifies them into epileptic and non-epileptic categories.

---

## Project Features

* EEG data preprocessing and cleaning
* Feature analysis and visualization
* Machine learning model training
* Model evaluation and comparison
* Prediction of epileptic seizure activity

---

## Dataset

The dataset contains **EEG signal features extracted from brain recordings** used to train machine learning models for seizure classification.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Machine Learning Models

The following machine learning algorithms are implemented:

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)

These models are trained to classify EEG signals into seizure and non-seizure categories.

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation

---

## Project Structure

```
Epilepsy-detection-project
│
├── data
│   └── epileptic_featured_data.csv
│
├── notebooks
│   └── EEG_epilepsy_detection.ipynb
│
├── src
│   ├── preprocessing.py
│   └── train_model.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository:

```
git clone https://github.com/piyushsonker024-hue/Epilepsy-detection-project.git
```

Move into the project directory:

```
cd Epilepsy-detection-project
```

Create a virtual environment:

```
python -m venv myenv
```

Activate the environment:

Mac / Linux

```
source myenv/bin/activate
```

Windows

```
myenv\Scripts\activate
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## Usage

Run Jupyter Notebook:

```
jupyter notebook
```

Open the notebook:

```
EEG_epilepsy_detection.ipynb
```

---

## Results

The trained machine learning models are evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

These metrics help compare model performance for seizure detection.

---

## Future Improvements

* Implement deep learning models (CNN / LSTM)
* Real-time EEG seizure detection
* Deploy model as a web application
* Improve feature engineering

---

## Author

**Piyush Sonker**


