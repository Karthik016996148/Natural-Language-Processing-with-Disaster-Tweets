# Natural Language Processing with Disaster Tweets

## Project Overview
This project utilizes advanced NLP techniques to classify tweets as disaster-related or not. By employing state-of-the-art models such as LSTM, BERT, Advanced BERT, and RoBERTa, we aim to accurately discern relevant tweets that can significantly aid emergency response and disaster management efforts.

## Features
- **Tweet Classification**: Classify tweets to determine if they are related to actual disasters.
- **Advanced NLP Models**: Utilize models like BERT and RoBERTa for high accuracy.
- **Data Preprocessing**: Includes cleaning tweets by removing URLs, special characters, and tokenization.
- **Embedding Techniques**: Use GloVe and BERT embeddings to represent text data.

## Technology Stack
- **Python**: Programming language
- **PyTorch, TensorFlow**: For modeling and computations
- **Transformers**: Library for transformer models like BERT and RoBERTa
- **NLTK, spaCy**: For text preprocessing
- **Pandas, NumPy**: For data manipulation
- **Matplotlib, Seaborn**: For data visualization

## Data
The data used in this project comes from a Kaggle competition and includes:
- `train.csv`: Labeled tweet data for training
- `test.csv`: Unlabeled tweet data for model testing
- **Data Columns**: id, keyword, location, text, target

## Models
1. **LSTM**: Long Short-Term Memory networks for baseline models.
2. **BERT**: Bidirectional Encoder Representations from Transformers for context understanding.
3. **Advanced BERT**: Optimized BERT with better hyperparameter tuning.
4. **RoBERTa**: Robustly Optimized BERT Approach with enhanced pre-training.

## Evaluation
Models are evaluated based on accuracy, precision, recall, and F1-score to ensure robustness in real-world application.
