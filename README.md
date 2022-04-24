# pyspark_sentiment
Sentiment Analysis on Financial News Data (200k news headlines) using PySpark

**Objective & Process:** The aim of this project is to accuratly identify sentiments in news titles that stem from financial news. Therefore, an annotated corpus of 200,000 headlines is used to train a variaty of classification model types using the PySpark Library. Beyond that, different approaches of text pre-processing and feature generation are explored to maximize performance. The process is designed as follows:

- Visual Data Exploration
- Data Pre-Processing (Tokenization, Count Vectorization, Word2Vec Embedding)
- Model Training & Evaluation

**Data Source:** The dataset used for this project contains 92,382 positive and 108,118 negative texts that were scraped from the news portals Economic Times, Money Control, Livemint, Business Today, Financial Express,NY Times, WSJ, and Washington Post between Jan 1, 2017 and April 15, 2021 (Data Source Link https://www.kaggle.com/datasets/harshrkh/india-financial-news-headlines-sentiments)

**Findings:**
- Best performance found with Count Vectorization and Support Vector Machine (0.77 Accuaracy)
- Low class separability found when applying word2vec embedding in 3D Space
