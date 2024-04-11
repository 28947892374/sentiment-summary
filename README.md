# sentiment-summary
# Text Analysis Toolkit

This toolkit provides a set of Python scripts for analyzing text documents. It offers functionalities such as keyword-based text summarization and sentiment analysis. It utilizes NLP models from `spaCy` and Hugging Face's `transformers` library, and leverages OpenAI's GPT-4 for generating summaries.

## Features

- **Keyword-Based Text Summarization**: Extract sentences containing a specified keyword from a text document and summarize the context using GPT-4.
- **Sentiment Analysis**: Perform sentiment analysis on sentences containing a specified keyword using a fine-tuned DistilBERT model.

## Requirements

- Python 3.8+
- PyTorch
- spaCy
- openai
- transformers
- IPython

## Installation

Before running the scripts, ensure you have the required packages installed:

```bash
pip install pytorch spacy openai transformers ipython
