# Resume Classifier Based On Random Forest Classifier

This project aims to build a resume classifier using a Random Forest Classifier. The goal is to automatically categorize resumes into different job categories based on their content.

## Project Overview

- **Importing Modules**: The project begins by importing the necessary Python libraries, including pandas, numpy, matplotlib, seaborn, nltk, gensim, and others.

- **Data Loading**: The dataset containing resumes is loaded into a pandas DataFrame. Unnecessary columns, such as 'ID' and 'Resume_html', are dropped to focus on the relevant data.

- **Data Preprocessing**: The text data in the 'Resume_str' column is preprocessed to prepare it for classification. This preprocessing includes converting text to lowercase, removing non-English characters, punctuation, numbers, tokenization, removing stopwords, and stemming.

- **Exploratory Data Analysis (EDA)**: EDA is performed to understand the dataset better. It includes analyzing the distribution of resume categories, visualizing the distribution, and exploring the most common words in each category.

- **Data Cleaning**: The data is cleaned by removing stopwords and words with less than 2 characters to improve the quality of the text data.

- **Model Training**: A Random Forest Classifier is trained on the preprocessed text data. Grid search is used to find optimal hyperparameters for the classifier.

- **Model Evaluation**: The trained model is evaluated on a test dataset, and various classification metrics, including precision, recall, F1-score, and accuracy, are calculated and reported.

This project demonstrates the use of natural language processing (NLP) techniques and machine learning to automate the classification of resumes into different job categories, which can be useful for job recruitment and talent management.

The project provides insights into the distribution of resume categories and the most common words in each category, helping users understand the dataset better and make data-driven decisions.
