# Flood Detection Using Logistic Regression

## Table of Contents

1. Overview<br>
2. Methodology<br>
3. Results<br>
4. Technologies Used<br>
5. Setup<br>
6. Usage<br>
7. Future Work<br>
8. Contributors<br>
9. License<br>

## Overview
<br>

This project focuses on developing a flood prediction model using logistic regression. The primary goal is to predict the probability of floods based on various environmental and infrastructural factors. Accurate flood prediction can help mitigate the adverse effects of floods on people, infrastructure, and the environment.
<br>

## Abstract
<br>
This project aims to develop a predictive model for flood detection using logistic regression. By analyzing various environmental and infrastructural factors, the model forecasts the likelihood of floods, providing crucial early warning insights. The high accuracy and robust performance metrics of the model highlight its potential for real-world applications in flood risk management and disaster preparedness.
<br>

## Methodology

1. Data Collection: The dataset was obtained from Kaggle and includes various environmental and infrastructural features.
2. Data Preprocessing: Checked for null values, data types, and dropped irrelevant columns. Split the data into training and testing sets.
3. Exploratory Data Analysis (EDA): Conducted to understand the relationships between the attributes using:
   - Correlation Matrix
   - Histograms
   - Bar Plots
   - Box Plots
   - Scatterplots
   - Pie Charts
   - Count Plots
   - 3D Scatter Plots
4. Model Development: Trained a logistic regression model to predict flood probability.
5. Model Evaluation: Evaluated the model using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC curve.

## Results

- Accuracy: 88.74%
- Precision: 92.42%
- Recall: 84.84%
- F1-Score: 88.47%
- ROC-AUC Score: 92.47%

For more detailed analysis, please refer to the report.
<br>

### Technologies Used

- Programming Language: Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- Tools: Jupyter Notebook
  
## Setup

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Clone the repository:
``bash
git clone https://github.com/yourusername/flood-detection.git
cd flood-detection
``

### Create and activate a virtual environment:
``bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
``

### Install the required packages:
``bash
pip install -r requirements.txt
``

### Usage
<br>

1. Run the Jupyter Notebook for data preprocessing, EDA, and model development:
``bash
jupyter notebook notebooks/FloodDetectionModel.ipynb
``
2. Evaluate the model using the provided evaluation scripts.
<br>

## Future Work
<br>

- Implement advanced modeling techniques to improve predictive accuracy.
- Integrate the model into a real-time flood prediction system.
- Explore the use of additional features and data sources to enhance model performance.
