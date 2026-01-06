Zomato Restaurants Clustering & Sentiment Analysis
📌 Project Type: Unsupervised Machine Learning (Clustering) & Sentiment Analysis

👤 Contribution
Individual Project
Author: Harsh Vardhan

🔗 GitHub Repository:
https://github.com/harshvardhan328/ZOMATO-RESTAURANTS-CLUSTERING-SENTIMENT-ANALYSIS

📖 Project Summary

Zomato is an Indian restaurant aggregator and food-delivery platform founded in 2008. It provides restaurant details, menus, ratings, and customer reviews across multiple cities.

This project focuses on analyzing customer reviews and restaurant metadata to:

Understand customer sentiment using Natural Language Processing (NLP)

Segment restaurants into meaningful groups using unsupervised clustering

Extract actionable insights through data visualization

The project benefits both customers (better restaurant understanding) and businesses (market segmentation and customer perception).

🧹 Text Preprocessing

Text preprocessing plays a crucial role in NLP-based models. The following steps were applied:

Lower Casing

Tokenization

Punctuation Removal

Stop Word Removal

Stemming

Lemmatization

Removal of special characters & numbers

📊 Exploratory Data Analysis (EDA)

Key analyses performed:

Restaurant cost analysis (expensive vs affordable)

Cuisine-wise distribution and frequency

Monthly and hourly review trends

Top reviewers and their rating behavior

WordCloud visualization for cuisines and customer reviews

😊 Sentiment Analysis

Sentiment analysis was performed using TextBlob, classifying reviews into:

Positive

Negative

Neutral

Metrics Used:

Polarity (−1 to +1): Indicates sentiment strength

Subjectivity (0 to 1): Measures opinion vs factual content

📈 Visualization of polarity vs subjectivity helps identify customer opinion patterns.

🧩 Clustering
Techniques Applied:

K-Means Clustering

Elbow Method

Silhouette Score

Principal Component Analysis (PCA)

Features Used:

Average Cost

Average Rating

Cuisine Type (One-Hot Encoded)

Restaurants were grouped into 5 meaningful clusters, representing:

Budget restaurants

Mid-range restaurants

Premium restaurants

Cuisine-based segmentation

📌 Key Insights

High-cost restaurants generally receive higher ratings

North Indian and Chinese cuisines dominate most clusters

Positive sentiment dominates customer reviews

Reviews are mostly subjective, indicating opinion-driven feedback

Optimal number of clusters identified using Elbow & Silhouette methods

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn, Plotly

Scikit-learn

NLTK, SpaCy

TextBlob

WordCloud

Jupyter Notebook

🏗️ Project Architecture
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
EDA & Visualization
      ↓
Sentiment Analysis (NLP)
      ↓
Clustering (K-Means + PCA)
      ↓
Insights & Conclusions

📂 Files Included

Zomato_Restaurant_Clustering__sentiment_analysis.ipynb

Dataset files

Visualizations

README.md

✅ Conclusion

This project demonstrates how Machine Learning and NLP can be used together to analyze real-world business data, uncover customer sentiment, and segment markets effectively.
