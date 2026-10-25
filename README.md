# Machine Learning & Data Science Internship Projects

### Datheon Machine Learning & Data Science Internship

This repository contains four machine learning projects completed as part of my Machine Learning and Data Science Internship at Datheon.

The projects cover different areas of machine learning, including regression, binary classification, multiclass classification, and Natural Language Processing (NLP).

The main objective of these projects is to gain practical experience in data preprocessing, exploratory data analysis, model development, performance evaluation, and prediction using Python and machine learning libraries.

Each project is implemented using Jupyter Notebook, with a step-by-step approach to understanding the dataset, preparing the data, training models, and evaluating their performance.

---

## Projects Overview

| No. | Project                              | Machine Learning Type     | Objective                                                            |
| --- | ------------------------------------ | ------------------------- | -------------------------------------------------------------------- |
| 01  | Real Estate Housing Price Prediction | Regression                | Predict house prices using property-related features                 |
| 02  | Customer Churn Prediction            | Binary Classification     | Predict whether a customer will leave a service                      |
| 03  | Multiclass Classification Pipeline   | Multiclass Classification | Classify data into multiple categories and compare model performance |
| 04  | Customer Review Sentiment Analysis   | NLP Classification        | Classify customer reviews as positive or negative                    |

---

# Project 1: Real Estate Housing Price Prediction

### Overview

The Real Estate Housing Price Prediction project focuses on estimating house prices based on different property characteristics.

House prices are influenced by several factors, such as property size, location, number of rooms, and other relevant features.

The purpose of this project is to understand how regression algorithms can be used to predict continuous numerical values.

### Objectives

* Understand the fundamentals of regression.
* Explore and analyze housing data.
* Identify relevant features for price prediction.
* Prepare data for machine learning.
* Train regression models.
* Evaluate model performance using regression metrics.

### Project Workflow

**1. Data Loading**

Import the housing dataset using pandas and examine its structure.

**2. Exploratory Data Analysis**

Analyze the dataset to understand feature distributions, missing values, and relationships between variables.

**3. Data Preprocessing**

Prepare the dataset by handling missing values, converting categorical features when necessary, and selecting relevant input variables.

**4. Train-Test Split**

Divide the dataset into training and testing sets to evaluate the model on unseen data.

**5. Model Training**

Train regression models using the prepared training dataset.

**6. Model Evaluation**

Compare predicted house prices with actual values and evaluate prediction errors.

### Evaluation Metrics

The following metrics can be used to evaluate regression performance:

| Metric   | Description                                                                  |
| -------- | ---------------------------------------------------------------------------- |
| MAE      | Measures the average absolute difference between actual and predicted values |
| MSE      | Measures the average squared prediction error                                |
| RMSE     | Measures prediction error in the same units as the target variable           |
| R² Score | Indicates how well the model explains variation in house prices              |

### Key Learning

This project helped me understand how regression models work and how data preprocessing, feature selection, and evaluation metrics influence prediction performance.

It also provided practical experience in working with numerical datasets and interpreting regression results.

**Notebook:** `Real_Estate_Housing_Price_Regression.ipynb`

**Dataset:** `housing.csv`

---

# Project 2: Customer Churn Prediction

### Overview

Customer churn refers to the situation where customers stop using a company's product or service.

Predicting customer churn is an important application of machine learning because it can help businesses identify customers who may leave and take appropriate retention measures.

This project focuses on binary classification, where the model predicts whether a customer is likely to churn.

### Objectives

* Understand binary classification problems.
* Explore customer information and churn patterns.
* Handle numerical and categorical features.
* Prepare data for classification models.
* Train machine learning classifiers.
* Evaluate classification performance.

### Project Workflow

**1. Data Loading**

Load the Telco Customer Churn dataset using pandas.

**2. Data Exploration**

Examine customer information, feature distributions, missing values, and the churn target.

**3. Data Preprocessing**

Prepare the dataset by handling missing values, encoding categorical variables, and transforming features where required.

**4. Feature Selection**

Separate the independent variables from the churn target.

**5. Train-Test Split**

Divide the dataset into training and testing sets.

**6. Model Training**

Train classification models using the prepared customer data.

**7. Model Evaluation**

Evaluate model predictions using classification metrics and examine incorrect predictions.

### Evaluation Metrics

| Metric           | Description                                             |
| ---------------- | ------------------------------------------------------- |
| Accuracy         | Percentage of correctly classified customers            |
| Precision        | Proportion of predicted churn cases that actually churn |
| Recall           | Proportion of actual churn cases correctly identified   |
| F1-Score         | Harmonic mean of precision and recall                   |
| Confusion Matrix | Shows correct and incorrect predictions for each class  |

### Key Learning

This project helped me understand the importance of classification metrics beyond accuracy.

I learned how precision, recall, and the confusion matrix provide useful information about model performance, especially when the dataset contains an unequal number of customers in each class.

**Notebook:** `Customer_Churn_Classification_Completed(1).ipynb`

**Dataset:** `Telco-Customer-Churn.csv`

---

# Project 3: Multiclass Classification Pipeline

### Overview

Multiclass classification is a machine learning problem where the target variable contains more than two possible categories.

Unlike binary classification, which predicts between two classes, multiclass classification assigns observations to one of several classes.

This project focuses on building a classification pipeline and comparing machine learning models to understand their performance on a multiclass dataset.

### Objectives

* Understand multiclass classification.
* Explore datasets containing multiple target classes.
* Perform data preprocessing.
* Build a machine learning classification pipeline.
* Compare different classification models.
* Evaluate model performance across multiple classes.

### Project Workflow

**1. Data Loading**

Import the dataset and examine its features and target classes.

**2. Exploratory Data Analysis**

Understand the distribution of classes, identify missing values, and examine feature characteristics.

**3. Data Preprocessing**

Prepare the dataset by handling missing values and applying suitable transformations.

**4. Train-Test Split**

Split the dataset into training and testing sets.

**5. Model Development**

Train classification models using the prepared dataset.

**6. Model Comparison**

Compare the performance of different models using consistent evaluation methods.

**7. Performance Evaluation**

Analyze classification metrics and identify differences in performance across individual classes.

### Evaluation Metrics

| Metric            | Description                                              |
| ----------------- | -------------------------------------------------------- |
| Accuracy          | Measures overall classification accuracy                 |
| Precision         | Measures the correctness of predictions for each class   |
| Recall            | Measures how effectively each class is identified        |
| F1-Score          | Combines precision and recall                            |
| Confusion Matrix  | Displays classification results across multiple classes  |
| Macro F1-Score    | Calculates the average F1-score across classes equally   |
| Weighted F1-Score | Calculates the average F1-score based on class frequency |

### Key Learning

This project improved my understanding of multiclass classification and model comparison.

I learned that overall accuracy does not always represent the performance of every class. Evaluating individual class results is important when comparing classification models.

**Notebook:** `Multi class benchmark classification pipeline.ipynb`

---

# Project 4: Customer Review Sentiment Analysis Using TF-IDF

### Overview

Sentiment analysis is a Natural Language Processing (NLP) technique used to identify opinions or emotions expressed in text.

This project focuses on classifying customer reviews into positive and negative sentiments using text preprocessing, TF-IDF feature extraction, and machine learning algorithms.

The main goal is to understand how textual information can be converted into numerical features and used for classification.

### Objectives

* Understand the basics of NLP.
* Perform text cleaning and preprocessing.
* Remove unnecessary characters and stopwords.
* Convert text into numerical features using TF-IDF.
* Train sentiment classification models.
* Compare model performance.
* Predict sentiment for new customer reviews.

### Dataset Description

The dataset contains 10 customer reviews with the following sentiment distribution:

| Sentiment | Number of Reviews |
| --------- | ----------------- |
| Positive  | 5                 |
| Negative  | 4                 |
| Neutral   | 1                 |
| **Total** | **10**            |

Since this project focuses on binary sentiment classification, the neutral review is excluded from model training.

The remaining nine reviews are used to demonstrate the sentiment classification workflow.

### Project Workflow

**1. Import Libraries**

Import the required Python libraries, including pandas, scikit-learn, and regular expressions.

**2. Load Dataset**

Read the customer review dataset using pandas.

**3. Text Preprocessing**

Clean the review text by:

* Converting text to lowercase.
* Removing HTML tags.
* Removing unnecessary punctuation and special characters.
* Removing common English stopwords.

**4. Feature Extraction**

Use Term Frequency-Inverse Document Frequency (TF-IDF) to convert the cleaned text into numerical features.

TF-IDF helps represent the importance of words within a document relative to the collection of documents.

**5. Train-Test Split**

Divide the prepared dataset into training and testing sets.

**6. Model Training**

Train and compare two machine learning algorithms:

* Multinomial Naive Bayes
* Logistic Regression

**7. Model Evaluation**

Evaluate both models using accuracy and classification reports.

**8. Sentiment Prediction**

Create a prediction function to classify new customer reviews as positive or negative.

### Example Prediction

```python
predict_sentiment("The product quality is excellent")
```

```python
predict_sentiment("Very disappointing experience")
```

The function returns the predicted sentiment label based on the trained model.

### Evaluation Metrics

| Metric    | Description                                                |
| --------- | ---------------------------------------------------------- |
| Accuracy  | Measures the percentage of correctly predicted reviews     |
| Precision | Measures how many predicted reviews in a class are correct |
| Recall    | Measures how many actual reviews in a class are identified |
| F1-Score  | Provides a balance between precision and recall            |

### Important Note

This project uses a very small dataset containing only nine reviews after excluding the neutral category.

Therefore, the model evaluation results are not sufficient to establish reliable performance on real-world customer reviews.

The primary purpose of this project is to understand the NLP workflow and implement a basic sentiment classification system.

### Key Learning

This project helped me understand how machine learning algorithms can work with textual data.

I learned how to clean text, convert words into numerical features using TF-IDF, and train classification models to predict sentiment.

It also helped
