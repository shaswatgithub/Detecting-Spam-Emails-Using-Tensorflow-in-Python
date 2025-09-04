📧 Spam Email Detection using TensorFlow
🛠️ Tech Stack

Language: Python 🐍

Libraries:

TensorFlow 🤖

NLTK 📚

Pandas, NumPy 🧮

Matplotlib, Seaborn 📊

Scikit-learn 🎯

WordCloud ☁️

🧠 Goal

To build a deep learning model that classifies emails as:

📩 Ham (Not Spam)

🚫 Spam

🔍 What We Did

Loaded Dataset 📁 (CSV file with emails and labels)

Balanced Data ⚖️ (Downsampled ham to match spam)

Cleaned Text 🧼

Removed stopwords

Removed punctuation

Removed subject line clutter

Visualized Words ☁️ using WordCloud for spam and ham

Tokenized & Padded Text 🔢

Built LSTM Model 🧠 using Keras (with Embedding + LSTM layers)

Trained Model 🏋️‍♂️ with callbacks (EarlyStopping + ReduceLROnPlateau)

Evaluated Performance 📈

Achieved ~97% accuracy

Plotted training vs validation accuracy
