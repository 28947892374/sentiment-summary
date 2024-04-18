# Project 2025 Text Analysis Toolkit

This toolkit provides a set of Python scripts designed for analyzing the "Project 2025" document, focusing on extracting and summarizing content related to specific keywords. It utilizes advanced NLP technologies from `spaCy`, Hugging Face's `transformers`, and OpenAI's GPT-4, which help in extracting pertinent information from large text documents. I wanted to provide a tool that highlighted anti-LGBTQ sentiments that occurred in this document as well as highlight certain portions of the document to combat misinformation.

## Features

- **Keyword-Based Text Summarization**: Extract sentences containing a specified keyword from the "Project 2025" document and summarize the context using GPT-4. This feature is particularly useful for highlighting references that could be analyzed further for biases.

- **Sentiment Analysis**: Perform sentiment analysis on sentences containing a specified keyword. This analysis helps identify the tone of the discussions related to the keywords, using a fine-tuned DistilBERT model.

## Requirements

- Python 3.8+
- PyTorch
- spaCy
- openai
- transformers
- IPython

## Installation

Ensure you have Python 3.8 or newer installed. Then, install the required packages using the following pip command:

```bash
pip install torch spacy openai transformers ipython
