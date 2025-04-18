# SummarizeAI: News Article Summarization using T5

## Overview
SummarizerAI is an NLP-based project that implements text summarization using the T5 transformer model. It processes news articles from the CNN/DailyMail dataset to generate concise summaries. The model is fine-tuned using Hugging Face's transformers library and evaluated with ROUGE and BLEU metrics.

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
