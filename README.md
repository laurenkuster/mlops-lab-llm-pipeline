# mlops-lab-llm-pipeline
MLOps LLM Data Pipeline Lab

This lab demonstrates a basic data preprocessing pipeline for language model training.  
The pipeline includes:

- Loading a text dataset (WikiText)
- Tokenizing text using a GPT-2 tokenizer
- Grouping tokens into fixed-length training sequences
- Creating batches for model training

## Modification Made

The data pipeline was modified by increasing the token block size during the sequence grouping step.

Original block size: 128 tokens  
Modified block size: 256 tokens  

This change affects how the dataset is segmented into training sequences, allowing each sequence to contain more context before being passed into the model.
