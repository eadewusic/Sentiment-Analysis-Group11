# Sentiment Analysis-Group11

This project focuses on Sentiment Analysis using text classification models. The goal is to classify tweets into sentiment categories (Positive, Negative, Neutral) using both traditional machine learning and deep learning approaches.

## Dataset
We are using the publicly available **Twitter Entity Sentiment Analysis** dataset from Kaggle:  
🔗 [View on Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

It contains:
- twitter_training.csv - used for model training and evaluation.
- twitter_validation.csv - used for final validation.

Each record contains:
- Tweet ID
- Entity
- Sentiment Label (Positive, Negative, Neutral)
- Tweet text

## Repository Structure
Sentiment-Analysis-Group11/

│── data/ # Contains the training and validation datasets

│── notebooks/ # Contains the collab notebook for models' development

│── outputs/ # Contains the best saved models

│── README.md # Project documentation

## Instructions for Reproducing Results
Download the Datasets: The training and validation datasets are located in the data/ folder (Sentiment-Analysis-Group11/data/).

Open the Notebooks: The Colab notebooks, which contain the full workflow of both the traditional and deep learning models (preprocessing, model training, evaluation, and saving), are located in the notebooks/ folder (Sentiment-Analysis-Group11/notebooks/).

Upload the Datasets: Upload the train and validation datasets to the file browser in Colab. Alternatively, upload the datasets to your Google Drive and mount your drive to access them.

Run the code: Execute the notebooks step by step to preprocess the data, train the model, and evaluate results.
