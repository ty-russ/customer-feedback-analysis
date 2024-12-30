# Customer Feedback Analysis for the Hospitality Industry

## Overview

This project focuses on analyzing hotel reviews to uncover valuable insights for the hospitality industry, specifically for a new company, AfriDusky Tours and Travel Agency, entering the Kenyan market. The analysis aims to understand customer satisfaction, identify areas of improvement, and highlight strengths to help AfriDusky establish itself as a customer-centric organization.

## Objectives

### Research Questions

- What aspects of the hotel experience most influence customer satisfaction or dissatisfaction?

- How does sentiment vary across different review categories (e.g., cleanliness, service, location)?

- What are the most common compliments and complaints from guests?

### Expected Benefits

- Enhance Guest Satisfaction: Address customer priorities and complaints.

- Inform Marketing Strategies: Showcase frequently praised features.

- Drive Data-Driven Decisions: Optimize resources and operational strategies.

- Build Brand Loyalty: Establish a strong foothold in the hospitality sector.

# Data

## Sources

Hotel reviews scraped from publicly available platforms.

## Structure

The dataset includes:

- Textual Data: Reviews written by guests.

- Metadata: Rating, sentiment (Positive, Neutral, Negative), location, review category, and guest nationality.

## Processing

- Text Cleaning: Tokenization, lemmatization, and removal of stopwords.

- Feature Extraction: TF-IDF and Count Vectorization.

- Sentiment Classification: Topic modeling using NLP techniques.

## Tools and Technologies

- Programming Languages: Python (pandas, NumPy, Matplotlib, Seaborn)

- NLP Libraries: Scikit-learn, NLTK, spaCy

- Visualization: Matplotlib, WordCloud

## Data Management: Jupyter Notebook

## Key Features

- Data Analysis

- Sentiment Analysis: Classification into Positive, Neutral, or Negative.

- Topic Modeling: Using LDA and NMF to identify themes in reviews.

- Correlation Studies:

  - Relationship between staff feedback and ratings.

  - Impact of hotel features on overall satisfaction.

## Visualizations

- Word Clouds: For positive, neutral, and negative reviews.

- Bar Charts: Average ratings by country and sentiment distribution by categories.

- Scatter Plots: Relationship between review length and sentiment.

## Insights and Recommendations

### Positive Highlights:

- Guests frequently praise staff friendliness, cleanliness, and ambiance.

### Areas for Improvement:

- Negative sentiment often relates to poor service and uncomfortable rooms.

### Targeted Improvements:

- Mid-range hotels (ratings 7.0-8.0) should address neutral feedback to improve ratings.

- Focus on high-demand amenities like Wi-Fi, breakfast, and customer service.

# How to Use

Clone the Repository:

git clone https://github.com/yourusername/hotel-reviews-analysis.git

Install Dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

Open the notebook file in a Jupyter environment.

Execute the cells sequentially to reproduce the analysis.

## Future Work

Dynamic Scraper: Automate scraping for real-time review updates.

Advanced NLP: Incorporate deep learning models for sentiment analysis.

Regional Comparisons: Expand analysis to other markets beyond Kenya.

# License

This project is licensed under the MIT License. See the LICENSE file for details.

# Contact

For questions or collaboration, feel free to reach out:

Name: Tirus Wagacha

Email: kimtirus@gmail.com

GitHub: ty-russ

