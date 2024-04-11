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

Before running the scripts, ensure you have Python 3.8 or newer installed. Then, install the required packages using the following pip command:

```bash
pip install torch spacy openai transformers ipython
