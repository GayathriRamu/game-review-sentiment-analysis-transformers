# Game Review Sentiment Analysis using DistilBERT and RoBERTa

## ⭐️Project Overview

Sentiment analysis is one of the most widely used Natural Language Processing (NLP) applications. In this project, I fine-tuned two pre-trained Transformer models, DistilBERT and RoBERTa, to classify game reviews based on their sentiment.

The project demonstrates the complete NLP pipeline, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Transformer tokenisation
- Dataset preparation
- Fine-tuning pre-trained models
- Model evaluation and comparison


## ⭐️Dataset

The dataset consists of game reviews and their corresponding sentiment labels.

#### Dataset Characteristics

- User-generated game reviews
- Binary sentiment classification


## ⭐️Project Workflow

<img width="400" height="600" alt="image" src="https://github.com/user-attachments/assets/b9f859f4-18fc-4562-884b-d78a94da04e5" />


## ⭐️Models

#### DistilBERT

- Lightweight version of BERT
- Faster training
- Lower computational requirements

#### RoBERTa

- Improved BERT architecture
- Dynamic masking
- Better language understanding
- Higher computational cost


## ⭐️Results

| Model | Best Validation Accuracy |
|---------|---------|
| DistilBERT | 90.07% |
| RoBERTa | 92.24% |

#### Key Finding

RoBERTa achieved the highest validation accuracy, outperforming DistilBERT by approximately 2.17%.

The results demonstrate that larger and more robust Transformer architectures can provide better contextual understanding for sentiment classification tasks.


## ⚡️Try it yourself!
If you'd like to explore or build upon this work, feel free to fork the repository and run it locally.


Fork the repository
Create your feature branch
Make your changes
Submit a pull request

Contributions, suggestions, and improvements are welcome.
