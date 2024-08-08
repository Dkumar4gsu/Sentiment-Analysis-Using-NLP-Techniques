**Overview**

This project is focused on analyzing the sentiment of product reviews by applying various Natural Language Processing (NLP) techniques. The primary goal is to classify product reviews into positive and negative sentiments using deep learning models, specifically LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) networks.

Sentiment analysis is a crucial task in understanding customer feedback, and this project aims to build a robust pipeline that preprocesses text data, builds necessary features, and trains machine learning models to predict sentiment. The approach combines traditional NLP methods with deep learning to achieve accurate sentiment classification.

**Key Features**

**Data Preprocessing:** The project involves several preprocessing steps to clean and prepare the textual data for modeling. These steps include:

**Tokenization:** Splitting text into individual words or tokens using the NLTK library.
**Stop Word Removal:** Eliminating common words (like "and", "the", "is") that do not contribute much to the meaning of the text.
**Stemming:** Reducing words to their base or root form (e.g., "running" becomes "run") to standardize the vocabulary.
**Vocabulary Building:** After preprocessing, a vocabulary is created from the cleaned text data. This vocabulary serves as the basis for feature extraction and model input. The vocabulary is essential for converting text data into numerical format, which deep learning models can process.

**Sentiment Classification:** The core of the project is building and training LSTM and GRU models to classify the sentiment of reviews. These models are well-suited for handling sequential data like text, as they can capture context and dependencies between words over time. The project explores the use of these models to predict whether a given review is positive or negative based on its content.

**Model Training and Evaluation:** The project includes training LSTM and GRU models on the processed data. It also involves evaluating the models using metrics such as accuracy, precision, recall, and F1-score to determine their effectiveness in sentiment classification.

**Technologies Used**

**Python:** The primary programming language used for the entire project.
**NLTK (Natural Language Toolkit):** Used extensively for various NLP tasks, including tokenization, stop word removal, and stemming.
**Pandas:** A powerful data manipulation library that is used for handling and processing the review data.
**Keras/TensorFlow:** These deep learning libraries are used to implement and train LSTM and GRU models. Keras provides a high-level interface for building neural networks, while TensorFlow serves as the backend engine.
**Jupyter Notebook:** The project is developed and documented using Jupyter Notebooks, making it easy to visualize and interact with the code and results.
