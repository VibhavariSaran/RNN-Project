# RNN-Project 
🎬 Sentiment Analysis on IMDB Reviews using RNN and BiLSTM Welcome to the repository for a deep learning project that explores the power of Recurrent Neural Networks (RNN) and Bidirectional LSTM (BiLSTM) for sentiment analysis. Using the popular IMDB dataset, this project builds, trains, and evaluates neural network models to classify movie reviews as positive or negative.

📌 Project Objective

Build a sentiment classification model using RNN and BiLSTM.

Improve accuracy and generalization by applying advanced text preprocessing techniques.

Demonstrate effective model training, evaluation, and comparison using deep learning architectures.

🧠 Key Features

Data Source: IMDB movie reviews dataset (50,000 reviews labeled as positive or negative).

Preprocessing Enhancements:

Removal of stopwords, special characters, and noise.

Lemmatization for reducing words to their base form.

Customized tokenization beyond Keras’s built-in tokenizer.

Model Architectures:

Vanilla RNN with Embedding and Dropout layers.

BiLSTM model with stacked LSTM layers for richer contextual understanding.

Regularization:

Dropout layers and early stopping used to prevent overfitting.

📈 Results & Performance

RNN Model:

Test Accuracy: ~81.22%

Balanced performance across both sentiment classes.

BiLSTM Model:

Test Accuracy: 88.64%

Improved generalization and robustness to varied review structures.

Classification Reports:

Precision, recall, and F1-scores consistently above 0.88 for BiLSTM.

Minimal performance gap between training and validation suggests model reliability.

📊 Visualizations

Training vs. Validation Accuracy plots.

Classification report insights.

Confusion matrix for error analysis.

💡 Managerial Insights

High prediction accuracy makes the model ideal for real-world applications like sentiment-driven recommendations, customer feedback monitoring, and brand reputation analysis.

Model transferability demonstrated via testing on cross-domain datasets like Metacritic, showcasing reusability with minor tuning.

Enhanced tokenization significantly boosted accuracy by reducing noise and vocabulary complexity.

✅ Conclusion This project proves that deep learning—when paired with thoughtful data preprocessing and advanced architectures like BiLSTM—can yield powerful results for sentiment classification. With 88%+ accuracy, the model is well-suited for production use cases and forms a strong foundation for future enhancements such as attention mechanisms or transformer-based models.

Contributors

Saumya Raghuvanshi
Vibhavari Saran
