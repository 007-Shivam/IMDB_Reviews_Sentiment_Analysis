# IMDB Reviews Sentiment Analysis

This project performs sentiment analysis on IMDB movie reviews, classifying them as either positive or negative. The analysis is done using various machine learning models, and the results are evaluated to identify the best performing model.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Overview
The objective of this project is to determine the sentiment (positive or negative) of movie reviews. The project involves data preprocessing, feature extraction, model training, and evaluation. This project was implemented in Python, using popular libraries such as `pandas`, `scikit-learn`, and `nltk`.

## Dataset
The dataset used for this project is the [IMDB movie reviews dataset](https://www.kaggle.com/datasets/crisbam/imdb-dataset-of-65k-movie-reviews-and-translation). It consists of 150,000 movie reviews.

## Installation
To run this project, you need to have Python installed on your machine. The following dependencies are required, make sure to install them.
1. pandas
2. numpy
3. nltk
4. scikit-learn
5. seaborn
6. wordcloud
7. prettytable
8. os

## Models Used
The following machine learning models were used for sentiment analysis:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest

## Usage
1. Clone this repository:
```
git clone https://github.com/007-Shivam/IMDB_Reviews_Sentiment_Analysis.git
cd IMDB_Reviews_Sentiment_Analysis
```
2. Install the required dependencies
3. Download the IMDB dataset from above link.
4. Run the project

## Results
After training and testing the models, the Logistic Regression model showed the highest accuracy of 89%. The results are presented in terms of accuracy, precision, recall, and F1-score.

## Conclusion
This project demonstrates that machine learning models can effectively perform sentiment analysis on large datasets like IMDB movie reviews. Logistic Regression performed the best for this particular task.
