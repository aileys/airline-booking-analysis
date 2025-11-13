✈️ British Airways Data Science Virtual Experience (Forage)

A two-part analytics and machine learning project exploring airline booking behavior and customer review sentiment using Python, Jupyter Notebooks, and real-world data science workflows.

📌 Overview

This repository contains my completed work from the British Airways Data Science Virtual Experience on Forage.
It includes two complementary projects:

1. Booking Completion Analysis (Structured Data)

Analyzing 50,000+ airline bookings to identify the drivers of booking completion and build predictive models.

2. Skytrax Review Sentiment Analysis (Unstructured Text Data)

Scraping, cleaning, and analyzing British Airways customer reviews to uncover sentiment patterns and common themes.

Together, these tasks demonstrate core skills in Python, machine learning, web scraping, NLP, data visualization, and exploratory data analysis.

1️⃣ Task 1 — Booking Completion Analysis

Files:

notebooks/task1_booking_eda.ipynb

notebooks/task1_booking_model.ipynb

data/customer_booking.csv

🔍 Objective

Use 50,000+ booking records to explore customer behavior and predict which bookings are likely to be completed.

🧠 Key Steps

Performed exploratory analysis using Pandas, NumPy, Seaborn

Cleaned and transformed features:

Encoded flight_day

Processed trip type and add-on preferences

Trained predictive models using scikit-learn:

One-hot encoding

Train/test split

Random Forest classifier

Evaluated model performance and extracted feature importance

⭐ Findings

Purchase lead time is a strong predictor of booking completion

Sales channel affects conversion behavior

Customer add-on interest (baggage, meals, seating) correlates with higher completion probability

2️⃣ Task 2 — Skytrax Review Sentiment Analysis

Files:

notebooks/task2_skytrax_sentiment.ipynb

notebooks/task2_skytrax_experiments.ipynb

data/BA_reviews.csv (generated via scraping)

slides/BA_customer_review_presentation.pptx

🔍 Objective

Scrape and analyze British Airways customer reviews from Skytrax to identify sentiment trends and common customer experience themes.

🧠 Key Steps

Scraped multiple pages of reviews using Requests and BeautifulSoup

Cleaned text (lowercasing, regex, stopwords, lemmatization)

Applied NLTK VADER sentiment analysis to classify reviews

Visualized insights with:

WordCloud

Matplotlib

Seaborn bar charts

Exported results for presentation in PowerPoint

⭐ Findings

Positive reviews slightly outweigh negative ones

Neutral reviews are rare — customers usually write when experiences are extreme

Common themes include:

Staff service

Comfort & seating

Delays and punctuality

Food & onboard experience
