# Homework IV - Text Mining Analysis

[Download Full Analysis (PDF)](./HW4.pdf)

## Overview

This analysis demonstrates comprehensive text mining and natural language processing techniques applied to Reuters news articles. The study encompasses:

- **Text Preprocessing**: Cleaning and standardization including tokenization, stop word removal, stemming, and special character handling
- **Term Frequency Analysis**: Identifying the most common and important terms in the corpus
- **Word Cloud Visualization**: Visual representation of term prominence and distribution
- **Sentiment Analysis**: Multi-lexicon sentiment scoring using Syuzhet, AFINN, Bing, and NRC lexicons
- **Document-Level Sentiment**: Analyzing sentiment patterns across individual documents
- **Text Clustering**: K-means clustering with elbow method optimization to identify document groups
- **Cluster Interpretation**: Extracting and analyzing representative terms for each cluster

## Key Findings

The analysis reveals distinct clusters within the Reuters corpus with varying sentiment profiles. Sentiment analysis across multiple lexicons provides robust validation of emotional tone patterns in financial news reporting.

## Methods

This project demonstrates best practices in text mining including:
- Handling namespace conflicts between R packages (tm vs. httr)
- Sparse matrix optimization for computational efficiency
- Multi-method validation approaches for sentiment classification
- Unsupervised learning for document discovery

---

*Note: Due to external corpus package dependencies, this analysis is provided as a PDF. The complete R code for preprocessing, analysis, and visualization is included in the document.*