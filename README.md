# Ai_Chatbot
# LSTM-Based Chatbot

This repository contains the code for an LSTM-based chatbot. The chatbot utilizes a Long Short-Term Memory (LSTM) neural network to understand user input and generate context-aware responses.

## Features

- **Natural Language Processing (NLP):** Uses NLP techniques to preprocess input data.
- **LSTM Network:** Leverages an LSTM neural network for context-based response generation.
- **Pretrained Word Embeddings:** Supports pretrained word embeddings for better language understanding.
- **Customizable Responses:** Allows fine-tuning of responses through training with specific datasets.
- **Scalable:** Suitable for expanding to larger datasets and real-world conversations.

## Prerequisites

- Python 3.7+
- GPU support (optional but recommended for training)
- Libraries: TensorFlow, Keras, NumPy, Pandas, scikit-learn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/lstm-chatbot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd lstm-chatbot
    ```
3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### 1. Data Preparation
Prepare a training dataset in the form of input-response pairs, which the chatbot will learn from. Use the following folder structure:

### 2. Training the Model
To train the LSTM model with your dataset:
```bash
python train.py --data_path data/training_data.json --epochs 50
