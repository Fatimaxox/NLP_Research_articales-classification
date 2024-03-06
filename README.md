# Research Article Categorization Project 📚🔍

This repository contains the code and documentation for a research article categorization project. The project involved three main stages: preprocessing, modeling, and optimization. Each stage utilized specific techniques to enhance the effectiveness of the classification process.

## Project Overview 🌟

### Stage 1: Before Modeling 🛠️

Before training, preprocessing techniques were applied to both the title and the abstract of research articles. These techniques included:

- Stopwords removal
- Lowercasing
- Lemmatizing

For feature extraction, two main techniques were leveraged:

1. **TF-IDF (Term Frequency-Inverse Document Frequency)**:
   - **Benefit**: The weighted features derived from TF-IDF serve as input features for machine learning models, contributing to accurate and efficient document classification.

2. **Word2Vec**:
   - **Benefit**:
     - Semantic Context: Word2Vec embeddings contribute to a deeper semantic understanding of research articles.
     - Improved Generalization: The embeddings can capture general semantic context, allowing the model to generalize better to unseen data.

### Stage 2: During Modeling ⚙️

During modeling, three machine learning algorithms were employed:

- **Random Forest (RF)**:
  - **Benefit**: Its ensemble approach mitigates overfitting and provides robust predictions, making it well-suited for capturing intricate patterns and nuances present in diverse research articles.

- **Logistic Regression (LR)**:
  - **Benefit**: Computationally efficient, ensuring timely categorization without compromising accuracy.

- **Naïve Bayes**:
  - **Benefit**: Provides a probabilistic classification approach, allowing researchers to gauge the confidence level of the categorization.

### Stage 3: After Modeling - Optimization 📈

After modeling, optimization techniques were applied to improve results. One valuable technique utilized was:

- **GridSearchCV**:
  - **Benefit**:
    - Parameter Tuning: Enables precise parameter tuning by systematically searching through a predefined grid of hyperparameter combinations.
    - Improving Generalization: Helps prevent overfitting and promotes model generalization by identifying optimal hyperparameter values.
    - Efficient Hyperparameter Search: Saves time and effort by efficiently exploring various hyperparameter combinations.

## Final Result 🏆

It achieved the highest weighted average F1-Score of 78% using Logistic Regression Classifier with TF-IDF, and with Word2Vec embeddings 77% was achieved by both Logistic Regression and Random Forest. The results obtained from this study demonstrate the effectiveness of NLP and machine learning techniques for classification tasks in the research domain.

