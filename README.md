# Project 2025 Analysis Toolkit
## Combatting Bigotry with Text Analysis

This toolkit is designed to analyze and counteract bigoted stances in the "Project 2025" document. It utilizes Python scripts equipped with advanced NLP technologies from `spaCy`, Hugging Face's `transformers`, and OpenAI's GPT-4. These tools are specifically tailored to detect and analyze biased or discriminatory language and sentiments.

## Features

- **Keyword-Based Text Summarization**: Identify and extract key sentences related to specific bigoted or discriminatory themes from the "Project 2025" document, summarizing the context using GPT-4.
- **Sentiment Analysis**: Assess the sentiment of extracted sentences to determine negative, neutral, or positive tones, using a fine-tuned DistilBERT model, with a focus on detecting harmful biases.

## Requirements

- Python 3.8+
- PyTorch
- spaCy
- openai
- transformers
- IPython
