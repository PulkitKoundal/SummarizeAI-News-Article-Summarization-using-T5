# SummarizeAI: News Article Summarization using T5

## Overview
SummarizeAI is a project that leverages the T5 (Text-To-Text Transfer Transformer) model to generate concise summaries of news articles. The project is implemented using Python and popular libraries such as PyTorch, Hugging Face Transformers, and Datasets. The goal is to provide a tool that can automatically summarize long articles, making it easier for users to quickly grasp the main points.

## Features
- **T5 Model**: Utilizes the T5-small model for text summarization.
- **Dataset**: Uses the CNN/DailyMail dataset for training and evaluation.
- **Evaluation Metrics**: Implements ROUGE and BLEU scores to evaluate the quality of the generated summaries.
- **Training**: Includes a training loop with customizable hyperparameters.
- **Inference**: Provides a pipeline for generating summaries from new articles.

## Result:
The model's performance is evaluated using the following metrics:

1.ROUGE-1: 0.333

2.ROUGE-2: 0.120

3.ROUGE-L: 0.243

4.BLEU: 0.038

5.Perplexity: 4.105
