# French to English Translation using Seq2Seq LSTM

This project demonstrates a simple and educational implementation of a French-to-English translator using a Sequence-to-Sequence (Seq2Seq) model with LSTM layers in TensorFlow.

## Overview

- Translates French sentences into English
- Uses TensorFlow and Keras with LSTM-based encoder-decoder architecture
- Trained on a cleaned version of the Tatoeba dataset (`fra.txt`)
- Preprocessing includes punctuation removal, lowercasing, and tokenization

## Technologies

- Python 3
- TensorFlow / Keras
- NumPy
- Scikit-learn

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/french-english-translator-lstm.git
cd french-english-translator-lstm
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Download Dataset
Place fra.txt from the Tatoeba project in the project directory.


### 4. Run the Notebook
Use Jupyter or any Python environment to run:
```bash
jupyter notebook seq2seq.ipynb
```
## Model Summary

Input: Padded French sequences
Encoder: Embedding + LSTM
Decoder: RepeatVector + LSTM + Dense (softmax)
Loss: Sparse Categorical Crossentropy
Optimizer: Adam

## Future Improvements

Attention mechanism integration
BLEU score evaluation
Inference pipeline with beam search or greedy decoding


