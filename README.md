# Geo-Sentiment-Mapping
Geo-Sentiment Mapping of Public Events Project Overview:

This project focuses on analyzing tweets and news headlines to visualize sentiment and emotion trends across different regions using geospatial data. The objective is to perform:

Exploratory Data Analysis (EDA) to quickly understand the dataset structure, distributions, and check for missing or inconsistent values.

Generating interactive visualizations to explore sentiment and emotion patterns across regions, time, and content sources like Twitter and News.

Incorporating Machine Learning
In addition to visual analysis, this project applies supervised machine learning techniques to:

Train predictive models that automatically classify sentiment and emotion based on event features such as text content, location, time, and geospatial coordinates.
Evaluate model performance using metrics like Accuracy, F1-Score, and Confusion Matrices.
Build feature-based models (using encoded columns).
End Goal
By combining data visualization and machine learning, this project aims to provide insights into how sentiment and emotions surrounding global events evolve over time and space, offering valuable information for researchers, policymakers, and organizations.

Dataset Source: Kaggle

Dataset Overview
The dataset used in this project contains information related to online content such as tweets and news articles, enriched with sentiment analysis and location-based details. It includes various attributes such as:

Text and Sentiment Information: The raw text content, sentiment labels (e.g., Positive, Negative,Neutral), and sentiment scores generated using tools like VADER.
Location and Time Details: Latitude, longitude, and location columns indicating the geographical source of the content, along with date and time components extracted from timestamps.
Source and Emotions: Information about the source of the content (e.g., Twitter or News) and detected emotions such as Anger, Anticipation, Disgust, etc.
This dataset provides a comprehensive view of textual data combined with location, sentiment, and emotional context, allowing for deeper analysis of how different emotions and sentiments are distributed across sources and locations.
The dataset can be used for tasks like sentiment trend analysis, emotion detection, geospatial insights, and preparing data for machine learning models.

Library Imports and Purpose
In this section, we are importing the essential Python libraries required for data analysis, preprocessing, visualization, and machine learning:

pandas: Used for reading, manipulating, and analyzing structured data (tabular format).
sklearn.preprocessing.LabelEncoder: Helps convert categorical variables (text labels) into numeric form, which is essential for applying machine learning models.
numpy: Provides support for numerical operations and handling arrays, useful for computations and data manipulation.
matplotlib.pyplot: A popular plotting library to create basic visualizations like bar charts, line plots, etc.
seaborn: Built on top of Matplotlib, it provides enhanced, attractive, and easier-to-create visualizations, especially for statistical graphics like heatmaps or correlation plots.
plotly.express (px): A high-level library for creating interactive visualizations like scatter plots, geo maps, and bar charts with built-in hover features and zooming capabilities.
folium: A Python library for creating interactive leaflet maps that can be easily embedded into notebooks and web apps.
folium.plugins.MarkerCluster: Adds a marker clustering feature to the map, automatically grouping nearby data points for a cleaner and more readable visualization.
wordcloud: A library used to generate word clouds, which are visual representations of text data where the size of each word reflects its frequency or importance. It's useful for quickly understanding the most common words in headlines, tweets, or any textual content.
Additional Libraries for Machine Learning:
sklearn.model_selection.train_test_split: Splits the dataset into training and testing subsets to evaluate model performance effectively.
sklearn.ensemble.RandomForestClassifier: A powerful ensemble-based machine learning algorithm that builds multiple decision trees and combines their results for more accurate classification.
sklearn.metrics: Provides essential functions like classification_report, confusion_matrix, and accuracy_score to evaluate and interpret model performance.
These libraries enable us to not only explore and visualize the data but also build, train, and assess predictive models.
