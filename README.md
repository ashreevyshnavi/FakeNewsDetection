# Fake News Detection

This repository contains code for detecting fake news using machine learning techniques. The dataset used consists of two sets of news articles: fake news and real news. The goal is to build machine learning models that can accurately classify whether a given news article is fake or real based on its content.

## Dataset

The dataset used in this project consists of two CSV files: Fake.csv and True.csv. Each CSV file contains news articles labeled as fake or real, along with other information such as the article's text, subject, and date of publication.

## Preprocessing

Before building machine learning models, the data undergoes several preprocessing steps:
- Concatenating the fake and real datasets
- Shuffling the data
- Converting text to lowercase
- Removing punctuation and stopwords

## Basic Data Exploration

Some basic data exploration is performed to understand the distribution of articles across subjects and the balance between fake and real articles.

## Modeling

Three machine learning models are trained and evaluated for fake news detection:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine

Each model is trained using a pipeline consisting of text vectorization (CountVectorizer) and TF-IDF transformation (TfidfTransformer).

Additionally, a Support Vector Classifier (SVM) model is trained separately and evaluated for comparison.

## Evaluation

The performance of each model is evaluated using accuracy and confusion matrices. The confusion matrices provide insights into the model's ability to correctly classify fake and real news articles.

## Instructions for Use

1. Ensure you have the necessary libraries installed, such as pandas, numpy, matplotlib, seaborn, and scikit-learn.
2. Download the dataset files Fake.csv and True.csv.
3. Update the file paths in the code to point to the location of the dataset files on your system.
4. Run the code in your preferred Python environment.
5. Evaluate the performance of the trained models using the provided evaluation metrics and visualizations.

## Conclusion

Fake news detection is an essential task in combating misinformation and maintaining the integrity of news sources. By leveraging machine learning techniques, we can develop effective tools for identifying fake news articles and promoting media literacy.

For further improvements, consider experimenting with different text preprocessing techniques, exploring more advanced machine learning algorithms, or fine-tuning model hyperparameters to achieve better performance.
