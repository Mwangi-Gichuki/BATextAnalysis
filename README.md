# Airline Customer Reviews Analysis

## Overview

This repository contains an analysis of customer reviews for British airways. This analysis aims to gain insights into customer sentiments, identify key topics, and highlight areas for improvement. The analysis includes sentiment analysis, topic modeling, and word cloud generation.

## Table of Contents

- [Dataset](#dataset)
- [Analysis Steps](#analysis-steps)
- [Findings](#findings)
- [Data Cleaning](#data-cleaning)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)

## Dataset

The dataset consists of customer reviews for British airways. It includes various attributes such as review text, verification status, and sentiment labels. The data is source thorugh scrapping the airline review website Skytrax

## Analysis Steps

1. **Sentiment Analysis**: The reviews were analyzed to determine their sentiment. Positive, negative, and neutral sentiments were identified, and their distribution was examined.

2. **Data Cleaning**: To ensure accurate analysis, the dataset underwent several preprocessing steps:
   - Removal of verification status.
   - Expansion of contractions (e.g., "don't" to "do not").
   - Removal of punctuation and normalization of case.
   - Elimination of Unicode characters.
   - Removal of stop words.
   - Lemmatization to standardize words.

3. **Topic Modeling**: The reviews were subjected to topic modeling techniques to identify recurring themes and topics within the reviews.

4. **Word Cloud Generation**: Word clouds were created to visually represent frequently mentioned terms in the reviews.

## Findings

- The sentiment distribution in the dataset is as follows:
  - Positive: ~1250 reviews
  - Negative: ~750 reviews
  - Neutral: < 50 reviews
![image](https://github.com/Mwangi-Gichuki/BATextAnalysis/assets/64706339/25cc3b52-9ac7-4601-b70f-130fa76e6ad9)

- Prominent topics identified include flight experience, service quality, seating, timing, and staff interactions.

## Data Cleaning

The data cleaning process was crucial to ensure the accuracy of the analysis. By removing noise and standardizing text, we were able to extract meaningful insights from the reviews.

## Visualizations

Visual representations included:
- Sentiment distribution bar chart.
- Word cloud highlighting frequent terms.

## Conclusion

This analysis provides valuable insights into customer sentiments and preferences. Addressing the key topics identified in the analysis can contribute to enhancing customer satisfaction and overall service quality.

## Usage

Feel free to use this analysis as a reference for understanding customer sentiment analysis and its application in improving services. The code and explanations can serve as a starting point for your own analysis.
