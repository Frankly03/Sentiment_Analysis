# Sentiment Analysis Project

This project performs sentiment analysis on customer reviews using Natural Language Processing (NLP) techniques. The goal is to classify reviews as positive, negative, or neutral.

The project uses the Hugging Face Transformers library with a Roberta Pretrained Model fine-tuned on the dataset.

It contains 57,000 rows and 10 columns, including the review text and sentiment labels. The data was preprocessed by removing special characters, stopwords, and performing tokenization.


Compared between Vader Sentiment scoring model and Roberta Pretrained Model.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-project.
   git:
   cd sentiment-analysis-project

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt

3. Download the dataset from Kaggle and place it in the data/raw/ folder.