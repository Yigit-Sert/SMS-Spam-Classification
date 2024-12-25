# SMS Spam Classification Project

This project focuses on classifying SMS messages as spam or ham (non-spam) using a deep learning model enhanced with Transformer-based attention mechanisms.

---

## Overview
The goal of this project is to build a binary classification model to identify spam messages using the **SMS Spam Collection Dataset**. The model leverages modern deep learning techniques, including LSTM and Multi-Head Attention, for improved accuracy and understanding of sequential data.

---

## Key Steps
1. **Setup Environment**: Install required libraries such as TensorFlow, Keras, pandas, and kagglehub.
2. **Dataset Preparation**: Download the dataset programmatically, load it into a pandas DataFrame, and preprocess it for modeling.
3. **Data Splitting**: Split the data into training, validation, and test sets to ensure robust evaluation.
4. **Text Preprocessing**: Tokenize and pad SMS messages to prepare them for model input.
5. **Model Building**: Construct a deep learning model with an embedding layer, Transformer-based attention, LSTM, and dense layers.
6. **Model Training**: Train the model on the dataset and validate its performance across multiple epochs.
7. **Evaluation and Analysis**: Test the model on unseen data, visualize performance metrics, and analyze the results (e.g., confusion matrix and classification report).
8. **Overfitting Analysis**: Monitor training and validation performance to identify and address overfitting.

---

## Results
- The model achieves high accuracy in distinguishing spam and ham messages.
- Evaluation includes metrics like accuracy, precision, recall, F1-score, and confusion matrix visualizations.

---

## Future Improvements
- Experiment with advanced text preprocessing techniques.
- Explore Transformer-only models like BERT for potentially better performance.
- Perform hyperparameter optimization to enhance model results.
- Handle class imbalance using oversampling or undersampling techniques.

---

## Conclusion
This project demonstrates the effectiveness of combining traditional LSTM-based sequential modeling with Transformer-based attention layers for SMS spam classification. It provides a foundation for further experimentation with advanced NLP techniques.
