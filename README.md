# Bank Client Classification Project 🏦

## Overview 📊
This project implements a machine learning classification model to predict if a client will subscribe to a bank's term deposit. The analysis includes data preprocessing, exploratory data analysis (EDA), and model implementation using various classification techniques.

## Dataset 📑
The dataset contains information about bank client data and their response to previous marketing campaigns. Key features include:

### Client Data:
- Age
- Job type
- Marital status
- Education level
- Credit default status
- Housing loan
- Personal loan

### Campaign Information:
- Contact communication type
- Last contact month
- Last contact day of week
- Campaign duration
- Number of contacts
- Previous campaign outcome

### Target Variable:
- Term deposit subscription (yes/no)

## Methods 🔬
The project implements:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model development using:
  - Random Forest Classifier
  - Decision Tree Classifier
- Model evaluation and metrics analysis

## Dependencies 🛠️
```python
python = "^3.11"
numpy = "^2.3.3"
pandas = "^2.3.2"
matplotlib = "^3.10.6"
seaborn = "^0.13.2"
scikit-learn = "^1.7.2"
scipy = "^1.16.2" ```

## Installation ⚙️
``` python
# Clone the repository
git clone https://github.com/cruchau/bank-client-classification.git

# Navigate to project directory
cd bank-client-classification ```

## Usage 🚀
``` python
# Install dependencies using Poetry
poetry install

# Activate virtual environment
poetry shell

# Run the main analysis script
python main.py ```
