# Sentiment Analysis of Amazon Reviews

This repository contains code for performing sentiment analysis on Amazon reviews using Python. The code uses the Pandas library for data manipulation and the NLTK library for sentiment analysis using the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon. The analysis includes categorizing reviews as positive, negative, or neutral based on their sentiment scores.

## Getting Started

To use this code, you need to have Python and Jupyter Notebook installed on your system. Additionally, you need to have the following Python libraries installed:

- pandas
- matplotlib
- nltk

You can install these libraries using pip:

```bash
pip install pandas matplotlib nltk
```

Next, you need to download the VADER lexicon from the NLTK library. You can do this by running the following command:

```python
import nltk
nltk.download('vader_lexicon')
```

## Data Loading and Sentiment Analysis

The code starts by loading a CSV file containing Amazon reviews into a Pandas DataFrame. The reviews are then subjected to sentiment analysis using the VADER lexicon. The sentiment score for each review is calculated, and the reviews are categorized as positive, negative, or neutral based on their sentiment scores.

The analysis provided in this repository addresses the following questions:

1. What is the sentiment of the review? (Positive, Negative, or Neutral)
The code uses sentiment analysis with the VADER lexicon to determine the sentiment of each review in the dataset. It categorizes the reviews as positive, negative, or neutral based on their sentiment scores.

2. Can we categorize the reviews based on their overall rating? (e.g., Positive reviews for rating 5, Negative reviews for rating 1, etc.)
The code categorizes the reviews based on their overall ratings into positive, negative, or neutral categories. It uses a threshold of sentiment scores to determine the category for each review.

3. What is the trend of overall ratings over time (based on "reviewTime")? Are there any patterns?
The code analyzes the trend of overall ratings over time by grouping the data based on the "reviewTime" column and calculating the average overall rating for each time period. It then creates a pie chart to visualize the proportion of positive, neutral, and negative ratings over time.

4. Which reviewers have the highest average rating?
The code performs an analysis of the reviewers and calculates the average rating given by each reviewer. It identifies the top N reviewers with the highest average ratings and prints their names and corresponding average ratings.

The analysis in this repository provides insights into the sentiment of Amazon reviews, the correlation between overall ratings and sentiment, the trend of overall ratings over time, and the top reviewers with the highest average ratings.
## Reviewer Analysis

The code also performs an analysis of the reviewers, calculating the average rating given by each reviewer and identifying the top N reviewers with the highest average ratings.

## Overall Ratings Over Time

The code analyzes the trend of overall ratings over time. The 'reviewTime' column is converted to datetime format, and the average overall rating is calculated for each time period. The average overall ratings are then summarized into positive, neutral, and negative categories, and a pie chart is created to visualize the proportion of each category.

## License

This code is provided under the MIT License, which allows you to use, modify, and distribute the code for both commercial and non-commercial purposes. Please refer to the LICENSE file for more details.

## Acknowledgments

The code is for educational and informational purposes and is based on various online resources and tutorials. 
Feel free to use, modify, and share this code to explore and analyze Amazon reviews sentiment. 
