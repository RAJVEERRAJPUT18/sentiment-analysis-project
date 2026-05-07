Sentiment Analysis on Amazon Food Reviews
Project Overview

This project performs sentiment analysis on Amazon Fine Food Reviews using the TextBlob library in Python. The goal of the project is to analyze customer reviews and classify them into Positive, Negative, and Neutral sentiments based on text polarity scores.

The project also includes data cleaning, preprocessing, duplicate handling, exploratory data analysis (EDA), and sentiment visualization.

Dataset Information
Dataset: Amazon Fine Food Reviews
Records Used: 5,000 reviews
Features Used:
Review Text
Review Score
Technologies Used
Python
Pandas
NumPy
Matplotlib
TextBlob
Jupyter Notebook
Project Workflow

Data Collection
Loaded Amazon review dataset using Pandas.

Data Cleaning
Removed missing values
Removed duplicate reviews
Selected required columns
Sentiment Analysis
Used TextBlob polarity scores to classify reviews into:

Positive
Negative
Neutral
4. Data Visualization

Created:

Pie Chart for sentiment percentage
Bar Chart for sentiment distribution
Rating vs Sentiment comparison chart
5. Insights Generation

Analyzed customer sentiment patterns and review behavior.

Sentiment Classification Logic
Polarity > 0.2 → Positive
Polarity < 0.1 → Negative
Otherwise → Neutral
Project Results

After analyzing 5,000 Amazon food reviews:

Positive Reviews: 58.27%
Negative Reviews: 22.81%
Neutral Reviews: 18.92%

The analysis shows that most customers had positive experiences with the products.
