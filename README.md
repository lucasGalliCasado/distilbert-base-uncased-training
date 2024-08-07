# Training Distilbert Base Uncased for Sentiment Analysis

The dataset used for training can be found at:
https://huggingface.co/datasets/FinGPT/fingpt-sentiment-train

In this notebook we process the original data found at the above link and use Low-Rank Adaptation(LoRA) to train a sentiment analysis model. The maximum input size is 512 characters and the possible labels are 'neutral', 'moderately negative', 'positive', 'mildly positive','negative', 'moderately positive', 'mildly negative','strong positive' and 'strong negative'
