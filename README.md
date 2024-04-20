# Sentimental-Analysis-using-NLP

This project focuses on sentiment analysis using Natural Language Processing (NLP) techniques. The objective is to classify text data into positive or negative sentiments.

## Overview

This Jupyter Notebook was originally created in Google Colab. It imports necessary libraries, installs additional packages if needed, and utilizes various tools for data processing, feature extraction, model building, and evaluation.

## Setup

Before running the notebook, ensure you have the required libraries installed. If not, you can use the `pip install` command to install them.

```bash
pip install wordcloud
pip install scikit-plot
```

## Data

The dataset used for training, validation, and testing can be found on Kaggle. The data is split into three parts: train, validation, and test. It consists of text samples labeled with corresponding sentiments.

- Train data: Contains labeled text samples for model training.
- Validation data: Additional data for model evaluation and hyperparameter tuning.
- Test data: Unseen data to evaluate the final model performance.

## Usage

1. **Data Preprocessing**: The notebook preprocesses the text data by removing special characters, converting text to lowercase, tokenizing, removing stopwords, and lemmatizing the words.

2. **Exploratory Data Analysis (EDA)**: Basic exploratory analysis is performed to understand the distribution of sentiments in the dataset.

3. **Feature Extraction**: Bag of Words (BOW) model is used to convert text data into numerical features.

4. **Model Building**: A Random Forest classifier is trained on the extracted features. Hyperparameter tuning is performed using GridSearchCV to optimize the model performance.

5. **Model Evaluation**: The trained model is evaluated on the test data using accuracy, confusion matrix, and classification report.

6. **Custom Input**: Users can input their text data for sentiment analysis using the trained model.

## Conclusion

This project demonstrates the process of sentiment analysis using NLP techniques. By following the steps outlined in the notebook, users can build and evaluate their sentiment analysis models.
