# Comparative Performance Analysis of Neural Architectures for Poem Generation

## Introduction
This project explores the **comparative performance analysis of different neural architectures** for poetry generation. The models analyzed include **Bi-LSTM, Vicuna-1B, and GPT-2**, evaluated based on their ability to generate coherent and stylistically rich poetry. The study aims to determine the effectiveness of these architectures in capturing poetic structure, rhythm, and meaning.

## Dataset Information
- **Dataset Name**: Poem Foundation Dataset
- **Description**: The dataset consists of a curated collection of poems from various sources, categorized based on genre, style, and era.
- **Preprocessing**: Tokenization, cleaning, and structuring into training-ready format.



## Preprocessing Steps
1. **Text Cleaning**: Remove special characters, extra spaces, and unwanted symbols.
2. **Tokenization**: Convert text into sequences of tokens for model training.
3. **Padding & Sequence Formatting**: Standardize input lengths for better processing.
4. **Embedding Preparation**: Utilize word embeddings for input representation.



## Models Used
- **Bi-LSTM (Bidirectional Long Short-Term Memory)**: Captures sequential dependencies for structured poem generation.
- **Vicuna-1B**: A transformer-based large language model fine-tuned for poetry generation.
- **GPT-2 (Generative Pretrained Transformer 2)**: Pretrained autoregressive model with fine-tuning on poetry datasets.



## Workflow
1. **Data Preprocessing**: Prepare and clean input poetry data.
2. **Model Training**: Train Bi-LSTM, Vicuna-1B, and GPT-2 on poetry data.
3. **Poem Generation**: Generate poems using trained models.
4. **Evaluation**: Compare results using NLP evaluation metrics.
5. **Visualization & Analysis**: Compare outputs using BLEU and ROUGE scores.


## Model Evaluation
- **BLEU Score**: Measures how closely the generated poem matches reference poetry.
- **ROUGE Score**: Evaluates recall-based similarity between generated and reference texts.
- **Perplexity**: Measures how well the model predicts poetry sequences.

## Results
- **Bi-LSTM**: Generates structured poetry with limited creativity.
- **Vicuna-1B**: Produces contextually rich and coherent poetic verses.
- **GPT-2**: Shows the best balance between structure and creativity.



## Conclusion
This study demonstrates the strengths and weaknesses of different neural architectures for poetry generation. While Bi-LSTM captures structure effectively, transformer-based models like Vicuna-1B and GPT-2 provide superior fluency and creativity. Future improvements could involve fine-tuning with specialized poetry datasets and optimizing hyperparameters for better results.

