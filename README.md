### Sentiment-Analysis-with-NLTK-Transformer

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)&nbsp;
![DataScience](https://img.shields.io/badge/DataScience-3776AB?style=for-the-badge)&nbsp;
![Transformer](https://img.shields.io/badge/Transformer-3776AB?style=for-the-badge)&nbsp;
![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=for-the-badge)&nbsp;


**Overview**:
This project performs sentiment analysis on a given dataset using two different models: VADER (Valence Aware Dictionary and sEntiment Reasoner) and RoBERTa (Robustly optimized BERT approach). The project involves data preprocessing, exploratory data analysis (EDA), and a comparison of the results obtained from both models.

**Table of Contents**:
- Introduction
- Project Structure
- Installation
- Data
- Exploratory Data Analysis
- Sentiment Analysis Models
- VADER
- RoBERTa
- Conclusion
- Contributing

**Introduction**:
Sentiment analysis is a natural language processing (NLP) technique used to determine the sentiment or emotion expressed in a piece of text. This project compares the performance of two sentiment analysis models, VADER and RoBERTa, on a given dataset.

<!-- **Project Structure**
├── data
│   ├── sampled_reviews.csv   
├── analysis.ipynb
│   ├── EDA
│   ├── VADER_sentiment_analysis
│   └── RoBERTa_sentiment_analysis
├── README.md
└── requirements.txt -->

**Installation**:
To get started with this project, clone the repository and install the required packages:
- git clone https://github.com/shakyaanjil/Sentiment-Analysis-with-NLTK-Transformer.git
- cd Sentiment-Analysis-with-NLTK-Transformer
- pip install -r requirements.txt

**Data**:
The dataset used in this project consists of Amazon reviews. The dataset includes various fields that provide information about the reviews and reviewers.

**Exploratory Data Analysis**:
The EDA was performed to understand the distribution and characteristics of the data. This involved visualizing the sentiment distribution, word frequencies, and other relevant statistics. 

### Sentiment Analysis Models
**VADER**:
VADER is a lexicon and rule-based sentiment analysis tool specifically attuned to sentiments expressed in social media.

**RoBERTa**:
RoBERTa is a transformer-based model that improves upon BERT by optimizing its hyperparameters and training with larger mini-batches and learning rates.

**Conclusion**:
This project demonstrates the effectiveness of both VADER and RoBERTa in performing sentiment analysis. While VADER is simpler and faster, RoBERTa provides more nuanced and accurate results due to its advanced architecture.

**Contributing**:
Contributions are welcome! Please feel free to submit a Pull Request.



