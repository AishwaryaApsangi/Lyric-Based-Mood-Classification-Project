# Lyrics Mood Classification Project (Research Project)

This project focuses on building and evaluating models for mood classification of song lyrics using both traditional machine learning and deep learning techniques. The project includes various stages such as data collection, preprocessing, feature extraction, model training, and evaluation.

## Project Overview

- **Data Collection**: Downloads song lyrics and metadata from multiple sources, including the Genius Lyrics API.
- **Data Preprocessing**: Cleans and processes lyrics to prepare them for machine learning models.
- **Feature Extraction**: Uses NLP techniques such as TF-IDF and word embeddings (Word2Vec) for feature extraction.
- **Model Training**: Compares various machine learning models (Naive Bayes, Logistic Regression, SVM) and deep learning models (CNN).
- **Evaluation**: Evaluates model performance using metrics such as accuracy, ROC-AUC, and confusion matrices.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed along with the following libraries:

- `lyricsgenius`
- `langdetect`
- `datasets`
- `gdown`
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `tensorflow`
- `gensim`
- `nltk`

You can install these dependencies using the following commands:

```bash
pip install lyricsgenius langdetect datasets gdown pandas numpy matplotlib scikit-learn tensorflow gensim nltk
