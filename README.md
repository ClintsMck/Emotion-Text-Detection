# MATH 6373 Deep Learning and Artificial Neural Networks
This is a course is focused on Artificial Neural Networks and in particular on Deeep Neural Networks and theiraplications. The lectures will present the main types of deep learning architectures and the basic algorithmicprinciples underlying automatic learning.
Topics of the course include: multi-layer perceptrons, autoencoders, convolutional neural networks and a number ofapplications to illustrate aspectes of their implementation and performance on real data. 

This respository will consist of projects done during my time throughout the Deep Learning course. Topics that I thought were intersting, and ones, that I would like to see improved upon. 
The "Deeplearn_lstm_bid" Jupyter Notebook
"Classifying Text-Based Emotions" outlines a deep learning project by Clinton McKenzie, Jesse Mercado, and Dhruv Suryavanshi, focusing on emotion detection from text using Natural Language Processing (NLP). Here's a summary of the key points:
**Background:**
The project explores the evolution of Artificial Intelligence (AI) and NLP, particularly in emotion detection—a subset of sentiment analysis. Emotion detection aims to identify emotions such as happiness, sadness, and anger from human language, improving Human-Computer Interactions (HCI).
**Dataset:**
The dataset used is the ISEAR (International Survey of Emotion Antecedents and Reactions), which contains emotional labels like joy, sadness, fear, anger, guilt, disgust, and shame. It is based on a cross-cultural study across 37 countries.
**Inspiration:**
The inspiration comes from a study using Logistic Regression for text-based emotion classification, which showed superior performance compared to rule-based methods. However, deep learning techniques like Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) were suggested to improve accuracy.
**Models Used:**
Bidirectional LSTM RNN: This model incorporates pre-trained GloVe word embeddings to process text sequences and was evaluated for 20 epochs, with no improvement after 10 epochs.
**Training & Evaluation:**
Both models were evaluated using precision, recall, F1 score, and accuracy. The Text CNN showed early promise but overfitted quickly, while the BiLSTM generalized better to unseen data.
**Comparison of Models:**
The Text CNN tended to overfit after some epochs, while the BiLSTM demonstrated better generalization, making it more suitable for complex sequence data.
**Conclusion:**
The project concludes that BiLSTM models show better performance for emotion detection tasks, and future research could combine CNN and LSTM features for improved results. The findings are important for enhancing AI-driven emotion detection systems in practical applications.
This project highlights the challenges of text-based emotion detection and compares various deep learning approaches to find optimal solutions.
