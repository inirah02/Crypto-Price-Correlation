# An Empirical Study of Financial BERT Models for Sentiment Analysis and Cryptocurrency Price Correlation

## Overview
This project presents the findings of a study conducted on various sentiment analysis tools and their application in the cryptocurrency market. The research was presented at the 2024 IEEE 9th International Conference for Convergence in Technology [I2CT](https://ieeepune.i2ct.in/) in Pune, India, from April 5-7, 2024. The paper focuses on the correlation between social media sentiment and cryptocurrency prices, particularly Bitcoin.

## Use Case
Cryptocurrency trading has become a significant financial domain with a market capitalization exceeding one trillion USD. The market is highly influenced by social media sentiment, making it essential for traders and investors to leverage sentiment analysis to enhance trading models. This study aims to identify the most effective sentiment analysis tool and explore the relationship between sentiment and cryptocurrency prices.

## Problem Statement
As the cryptocurrency market continues to grow, understanding the factors that influence price fluctuations becomes increasingly important. Social media has a substantial impact on market sentiment, which in turn affects cryptocurrency prices. This study investigates how advanced sentiment analysis models can be used to analyze social media sentiment and predict cryptocurrency price movements.

## Tech Stack
- **CryptoBERT**: A transformer model fine-tuned for cryptocurrency-related sentiment analysis.
- **FinBERT**: A BERT-based model fine-tuned for financial sentiment analysis.
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: A lexicon and rule-based sentiment analysis tool.
- **SenticNet**: A concept-level sentiment analysis tool that uses a knowledge base to understand the semantics of text.
- **DistilBERT**: A smaller, faster, and cheaper version of BERT, fine-tuned for the study to understand the correlation between sentiment and cryptocurrency prices.
- **Python**: Programming language used for implementing and running the models.
- **PyTorch**: Deep learning framework used to fine-tune transformer models.

## Solution Implementation
1. **Data Collection**: Gathered a dataset of social media posts related to cryptocurrencies, particularly Bitcoin, from various platforms.
2. **Preprocessing**: Cleaned and preprocessed the text data to make it suitable for analysis.
3. **Model Comparison**: Applied CryptoBERT, FinBERT, VADER, and SenticNet to the dataset to perform sentiment analysis. Evaluated the effectiveness of each model in identifying sentiment accurately.
4. **Sentiment-Price Correlation**: Fine-tuned DistilBERT on the dataset to analyze the correlation between the sentiment scores and Bitcoin prices. Calculated the correlation coefficient to quantify the relationship.
5. **Results**: Found that the sentiment scores derived from the models had a strong correlation with Bitcoin price movements, with a correlation coefficient of 0.88.

## Conclusion
The study demonstrates that advanced sentiment analysis tools, particularly those based on BERT architecture, can effectively capture social media sentiment and predict cryptocurrency price movements. The findings highlight the potential of integrating sentiment analysis into trading models to enhance decision-making in the cryptocurrency market.

## Keywords
Cryptocurrency, Bitcoin, Sentiment Analysis, DistilBERT, CryptoBERT, FinBERT, SenticNet, VADER Analysis

## Links
- Paper: [An Empirical Study of Financial BERT Models for Sentiment Analysis and Cryptocurrency Price Correlation](https://drive.google.com/file/d/1bywYg1eqc__76JgR-nk3wrSNMRGg7yWC/view?usp=sharing)
- Code: [Notebook](https://colab.research.google.com/drive/1wJQ124P_a3kuAFzXhJ5fpC81bYQ_Ox1n?usp=sharing)

