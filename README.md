# Fake News Detection Project
### Overview
This project aims to detect fake news using machine learning techniques. The dataset used for training and testing the model is available on Kaggle and includes information such as data ID, title, author, text, and label.

### Dataset
The dataset consists of the following columns:

- id: Unique identifier for each data point.
- author: Name of the author.
- title: Title of the news article.
- text: Full text content of the article.
- label: Binary label indicating whether the news is fake (1) or real (0).
### Machine Learning Model
The chosen machine learning model for this project is **Logistic Regression**. Logistic Regression is a commonly used algorithm for binary classification tasks, making it suitable for the fake news detection problem.

### Project Structure
- data: Folder containing the dataset files.
  - train.csv: Training dataset.
  - test.csv: Testing dataset.
- notebooks: Jupyter notebooks used for data exploration, preprocessing, and model training.
  - data_exploration.ipynb: Notebook for exploring the dataset.
  - preprocessing.ipynb: Notebook for data preprocessing.
  - model_training.ipynb: Notebook for training the Logistic Regression model.
- src: Source code files.
  - fakenewsdetection.py: Python script containing the code for the fake news detection model.
