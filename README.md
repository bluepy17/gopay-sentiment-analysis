# GoPay App Review Sentiment Analysis

## Project Overview

This project focuses on analyzing user reviews of the GoPay application collected from Google Play Store. The objective is to identify user sentiment and classify reviews into positive and negative categories using a Long Short-Term Memory (LSTM) model.

The analysis uses **Indonesian-language user reviews**, including informal words and everyday expressions commonly found in app reviews.

## Objectives

- Collect user reviews from Google Play Store using web scraping.
- Perform text preprocessing on Indonesian-language reviews.
- Handle informal words, slang, and stopwords in Indonesian text.
- Develop an LSTM-based sentiment classification model.
- Predict sentiment from user reviews.

## Language

The dataset consists of user reviews written in **Bahasa Indonesia**. Since users often use informal language, abbreviations, and slang expressions, text preprocessing includes slang normalization and stopword removal to prepare the data for sentiment classification.

## Tools & Technologies

- Python
- Google Play Store Scraping
- Pandas & NumPy
- Natural Language Processing (NLP)
- TensorFlow / Keras
- Long Short-Term Memory (LSTM)
- Jupyter Notebook

## Project Workflow

1. **Data Collection** – Scraping GoPay application reviews from Google Play Store.
2. **Text Preprocessing** – Cleaning Indonesian text, handling slang words, and removing stopwords.
3. **Model Development** – Building and training an LSTM model.
4. **Inference** – Testing the trained model on new user reviews.
5. **Sentiment Classification** – Classifying reviews into positive and negative sentiments.

## Project Structure

- `data/` – Dataset collected from Google Play Store.
- `notebooks/` – Scraping, model development, and inference notebooks.
- `models/` – Trained LSTM model and tokenizer.
- `preprocessing/` – Indonesian stopwords and slang dictionary.
- `requirements.txt` – Project dependencies.

## Example Prediction

**Input 1:**
"Aplikasi ini bagus sekali!"

**Predicted Sent
