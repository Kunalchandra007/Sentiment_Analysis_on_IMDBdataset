Sentiment Analysis on IMDB Movie Reviews

📌 Project Overview

This project performs Sentiment Analysis on IMDB movie reviews using Deep Learning techniques. The goal is to classify reviews as positive or negative based on their textual content.

🚀 Technologies Used

Python 🐍

TensorFlow/Keras 🔥

Natural Language Processing (NLP) 🗣️

LSTM (Long Short-Term Memory) Networks

Scikit-learn 📊

Pandas & NumPy 📉

Gradio for UI Integration 🎭

📂 Dataset

The dataset used for this project is the IMDB Large Movie Review Dataset, which contains 50,000 labeled movie reviews (25,000 for training and 25,000 for testing).
datasetlink-https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

🔧 Project Workflow

Data Preprocessing

Tokenization & Padding

Text vectorization

Splitting dataset into training & testing sets

Model Building

Using LSTM layers for sequential text processing

Embedding layer for word representations

Fully connected layers for sentiment classification

Model Training & Evaluation

Training on 80% of the dataset

Evaluation using accuracy & loss metrics

Deployment

Gradio UI for interactive user input & real-time predictions

🖥️ How to Run the Project

Clone the repository

Install dependencies:

pip install -r requirements.txt

Run the model:

python app.py

Open the Gradio interface in your browser and test the sentiment analysis.

📈 Results-:
Achieved an accuracy of ~85% on test data.

The model effectively differentiates between positive and negative sentiments in reviews.

📝 Future Improvements

Improve accuracy with Bidirectional LSTMs

Experiment with Transformers (BERT, GPT, etc.)

Expand dataset for better generalization

Enhance UI/UX for better user interaction

💡 Conclusion

This project demonstrates the power of Deep Learning in Natural Language Processing (NLP). By leveraging LSTMs, we successfully classify movie reviews based on sentiment.
