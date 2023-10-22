

# Amazon Book Reviews Classification

This project focuses on classifying Amazon Book Reviews as either positive or negative based on their textual content. We experiment with three different feature engineering techniques: Bag of Words (BoW), TF-IDF Vectorization, and Word2Vec embeddings. We use two classification models for our experiments: Naive Bayes and Support Vector Machine (SVM).

## Getting Started

### Prerequisites

- Python 3.x
- pip (Python Package Installer)

### Installation


**Install Dependencies**:
   Use the provided `requirements.txt` to install necessary dependencies.
   ```
   pip install -r requirements.txt
   ```

### Downloading the Data

The dataset is a subset of Amazon Book Reviews available on Kaggle.

To download the dataset:
1. Visit [this Kaggle link](https://www.kaggle.com/mohamedbakhet/amazon-books-reviews) or use the Kaggle API command:
   ```
   kaggle datasets download -d mohamedbakhet/amazon-books-reviews
   ```

2. Extract the downloaded `.zip` file to the project directory.

## Overview

1. **Data Preprocessing**:
   - Extract relevant columns: `review/text`, `review/score`, `Title`, and `review/summary`.
   - Create a binary classification dataset: Reviews with a score of 4 or higher are considered positive, while those with a score of 2 or lower are considered negative. We ignore reviews with a score of 3.

2. **Feature Engineering**:
   - Bag of Words (BoW)
   - TF-IDF Vectorization
   - Word2Vec Embeddings

3. **Model Training & Evaluation**:
   - Train and evaluate models using the aforementioned feature engineering techniques.
   - Evaluate performance using accuracy and F1 score metrics.


# Authors
Parsa Mazaheri, October 2023