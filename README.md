# Sentimental-Analysis-of-IMDb-Reviews-Using-Bidirectional-LSTM
## Overview
This project applies a Bidirectional Long Short-Term Memory (BiLSTM) network to perform sentiment analysis on 50,000 movie reviews from the IMDb dataset. Our goal is to accurately classify reviews as positive or negative by capturing long-term dependencies in the textual data, showcasing the power of advanced NLP techniques.

## Key Features
**Bidirectional LSTM Architecture**: Leverages the sequential nature of text for deeper understanding and improved prediction accuracy.
**Pre-trained Word Vectors**: Utilizes word vector representations to encode semantic information of words efficiently.
**Data Standardization**: Ensures consistent input data length through truncation and zero-padding, optimizing the network's performance.
**Dynamic Memory Management**: Implements a generator function for batch processing, enhancing memory efficiency and scalability.
**Regularization with Dropout**: Employs dropout layers to prevent overfitting, making the model more robust.
**Optimized Training Strategy**: Configured with a specific learning rate, Binary Cross-Entropy loss, and Adam optimizer for effective learning.
**High Model Performance**: Achieves a ROC AUC score of nearly 0.94 and a test accuracy of approximately 87%, demonstrating strong predictive capabilities.

## Methodology
**Data Preprocessing**: Standardize review lengths to 258 words using truncation and zero-padding.
**Vectorization**: Convert words to vectors using a pre-trained model.
**Batch Processing**: Use a generator function to handle data in batches, optimizing memory usage.
**Model Architecture**: Construct a BiLSTM model with dropout layers for regularization.
**Training**: Train the model over five epochs with a fine-tuned learning rate and Adam optimizer.
**Evaluation**: Assess model performance using ROC AUC score and test accuracy.

## Results
Our BiLSTM model showcased excellent capability in distinguishing between positive and negative sentiments, with a ROC AUC score just below 0.94 and a test accuracy of close to 87%. These results affirm the effectiveness of our approach in handling complex sentiment analysis tasks.



