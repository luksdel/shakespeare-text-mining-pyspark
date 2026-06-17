# Shakespeare Text Mining with PySpark

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PySpark](https://img.shields.io/badge/PySpark-Apache%20Spark-orange)
![Databricks](https://img.shields.io/badge/Databricks-Data%20Platform-red)

## Overview

This project explores text mining techniques using PySpark and Databricks to analyze the complete works of William Shakespeare.

The workflow focuses on extracting meaningful information from textual data through preprocessing, tokenization, stop word removal, frequency analysis, and visualization techniques.

The objective is to demonstrate how Natural Language Processing (NLP) and distributed data processing can be combined to analyze large text datasets efficiently.

### Shakespeare Word Cloud

![Shakespeare Word Cloud](images/wordcloud_shakespeare.png)

## Objectives

- Process textual data using PySpark;
- Apply text preprocessing techniques;
- Remove stop words and irrelevant tokens;
- Perform word frequency analysis;
- Visualize textual patterns through charts and word clouds;
- Demonstrate NLP workflows in a distributed computing environment.

## Dataset

The project uses Shakespeare's literary works available through the Databricks sample datasets.

The dataset contains a large collection of plays and texts that serve as the basis for text mining and frequency analysis.

## Workflow

### Data Ingestion

- Load textual data using PySpark
- Explore dataset structure
- Validate data quality

### Text Preprocessing

- Text cleaning
- Lowercase transformation
- Punctuation removal
- Special character removal
- Tokenization

### Stop Word Removal

- Identification of common words
- Filtering of non-informative terms
- Preparation for frequency analysis

### Word Frequency Analysis

- Word counting
- Ranking of most frequent terms
- Identification of relevant vocabulary patterns

### Data Visualization

- Frequency plots
- Word Cloud generation
- Exploratory analysis of textual patterns

## Technologies

- Python
- Databricks
- Apache Spark
- PySpark
- NLTK
- WordCloud
- Matplotlib

## Skills Demonstrated

- Text Mining
- Natural Language Processing (NLP)
- Distributed Data Processing
- PySpark
- Apache Spark
- Data Cleaning
- Data Visualization
- Exploratory Data Analysis
- Big Data Analytics

## Results

The project demonstrates how text mining techniques can be applied to large textual datasets using PySpark and Databricks.

Through preprocessing, tokenization, stop word removal, and frequency analysis, it is possible to identify relevant linguistic patterns and generate visual insights from unstructured text data.

## Project Assets

- `images/shakespeare.png` — silhouette mask used to generate the custom word cloud.
- `images/wordcloud_shakespeare.png` — final word cloud generated from Shakespeare's texts.
