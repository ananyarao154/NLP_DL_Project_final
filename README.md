# Next Word Prediction Model using LSTM

This project implements a Next Word Prediction model using LSTM in TensorFlow/Keras.

## Overview
Next-word prediction models enhance user experience in text-based applications such as:
- Text Autocompletion
- Virtual Assistants
- Speech-to-Text Systems
- Writing Assistance Tools
- Language Translation
- Personalized Recommendations

## Project Structure
- **Tokenization:** Text data is tokenized into unique words and sequences.
- **N-Gram Model:** Generated to create input-output pairs for training.
- **Padding:** Sequences are padded to ensure uniform length.
- **One-Hot Encoding:** Converts words into probability distributions.
- **LSTM Model Architecture:** Built with 150 LSTM nodes, using categorical cross-entropy for multi-class classification.
- **Training:** The model is trained over 100 epochs for accurate predictions.

## Dependencies
- TensorFlow
- Keras
- NumPy

Install them using:
```bash
pip install tensorflow keras numpy
```

## How to Run
1. Load and preprocess the text data.
2. Tokenize and create n-gram sequences.
3. Pad sequences and perform one-hot encoding.
4. Build and train the LSTM model.
5. Use the trained model for next-word predictions.

## Usage Example
```python
predicted_word = model.predict(padded_token_text)
```

## Conclusion
This model demonstrates the power of LSTM in predicting the next word in a sequence, with potential applications in various NLP tasks.

