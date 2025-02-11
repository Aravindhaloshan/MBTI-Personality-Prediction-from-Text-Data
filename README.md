# MBTI Personality Classification

This project aims to classify Myers-Briggs Type Indicator (MBTI) personality types based on user-generated text data. The project utilizes Natural Language Processing (NLP) and machine learning techniques to predict personality traits based on user posts.

## Features

Data Preprocessing: Cleaning and transforming text data
Feature Engineering: TF-IDF and Count Vectorization
Model Training: Logistic Regression, Naïve Bayes, and ExtraTrees Classifier
Cross-Validation: Stratified K-Fold validation to ensure robustness
Visualization: Matplotlib, Seaborn, and Plotly for insights and result interpretation

## Dataset

mb_data.csv: Contains user posts and their associated MBTI types
output.csv: Contains additional preprocessed results
results.csv: Contains further data for analysis

## Installation

Ensure you have Python 3.x installed. Then, install the required dependencies:
pip install -r requirements.txt

## Dependencies

NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
Plotly
BeautifulSoup


## Usage

1.Clone the repository:

git clone https://github.com/Aravindhaloshan/mbti-classification.git
cd mbti-classification

2. Place the dataset files (mb_data.csv, output.csv, results.csv) in the project directory.

3. Run the script:

python Personality Prediction .ipynb

4. The model will train and predict personality types based on the given dataset.

## Model Performance

# Cross-Validation Metrics:

Accuracy, F1-score, Log Loss

# Learning Curve Analysis:

Training and validation scores over increasing dataset sizes

# Results & Visualization

Personality Distribution: Bar plots and pie charts

Feature Importance: ExtraTreesClassifier insights

Prediction Analysis: MBTI personality classification per user
