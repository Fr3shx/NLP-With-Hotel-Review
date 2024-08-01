# NLP With Hotel Reviews

## By: Robby Khoutsaysana

### Project Overview

This project is divided into two parts, where we explore Natural Language Processing (NLP) techniques to analyze and model sentiment from hotel reviews. The project includes data exploration, data augmentation, machine learning model development, and iteration over model improvements.

---

### Part 1: Exploratory Data Analysis and Data Preparation

#### Introduction

In the first part of this project, we begin by performing Exploratory Data Analysis (EDA) on a hotel reviews dataset. This step involves understanding the data structure, identifying key patterns, and preparing the data for further analysis.

#### Steps Covered:

1. **Data Exploration**: Initial examination of the dataset, including distribution analysis, handling missing values, and feature selection.
2. **Data Augmentation**: Combining the text data from the `Positive_Review` and `Negative_Review` columns with numerical features to create a comprehensive dataset for modeling.
3. **Data Cleaning**: Preprocessing the text data by removing noise, tokenization, and vectorization using a count vectorizer.
4. **Feature Engineering**: Creation of new features by combining textual and numerical data to enhance model performance.

#### Conclusion

In this part, we successfully cleaned and prepared the dataset for modeling. The count vectorizer was used to transform text data into a format suitable for machine learning models, setting the stage for model development in the next phase.

---

### Part 2: Sentiment Analysis Model Development

#### Introduction

In the second part of this project, we focus on building and optimizing machine learning models to predict the sentiment of hotel reviews. Our target is the "rating" column, which is binary—1 for positive ratings and 0 for negative ratings.

#### Steps Covered:

1. **Data Preparation**: Utilizing a preprocessed and cleaned dataset, which is a subset of the Hotel Reviews dataset from Kaggle.
2. **Model Development**: Creation of baseline models and exploration of different algorithms to classify sentiment.
3. **Model Optimization**: Tuning hyperparameters, experimenting with different feature sets, and selecting the best-performing model.
4. **Model Evaluation**: Interpretation of results using metrics such as confusion matrix, accuracy score, precision, and recall.

#### Conclusion

In this part, we built and optimized a machine learning model that can predict the sentiment of hotel reviews with an accuracy of 76%. The project demonstrates the process of model creation, optimization, and evaluation, showcasing a practical approach to NLP and sentiment analysis.

---

### Getting Started

To run this project on your local machine, follow these steps:

1. **Clone the Repository**: `git clone [repository_url]`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Download the Data**: 
   - For Part 1: Download the dataset [here](link_to_dataset).
   - For Part 2: Download the preprocessed dataset [here](link_to_dataset).
4. **Run the Notebooks**: Execute the Jupyter notebooks provided in each part to follow along with the analysis and model development.

### Acknowledgments

This project is based on the Hotel Reviews dataset from Kaggle. More information on the original dataset can be found [here](link_to_original_dataset).
