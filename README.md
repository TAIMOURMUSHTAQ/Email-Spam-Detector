Spam Detector using Machine Learning

This project is a Spam Classification Model that identifies whether a given SMS/email message is spam or ham (not spam) using Natural Language Processing (NLP) and Machine Learning techniques. It leverages TF-IDF Vectorization for feature extraction and a Naive Bayes classifier for prediction.

🚀 Features

Preprocessing of raw text data (removes numbers, punctuation, converts to lowercase).

Uses TF-IDF (Term Frequency–Inverse Document Frequency) for transforming text into numerical vectors.

Trains a Multinomial Naive Bayes model, optimized for text classification.

Evaluates model performance with accuracy score, confusion matrix, and classification report.

Saves the trained model as a .pkl file for later use.

📊 Dataset

This project uses the SMS Spam Collection Dataset from UCI / Kaggle
.

Columns:

label: (ham = not spam, spam = spam message)

message: the text message content

🛠️ Tech Stack

Python 3

Libraries: pandas, numpy, scikit-learn, joblib

Model: Multinomial Naive Bayes

📌 How to Run

Clone the repository:

git clone https://github.com/your-username/spam-detector-ml.git
cd spam-detector-ml


Install dependencies:

pip install -r requirements.txt


Run the script (or notebook) to train and evaluate the model.

The trained model will be saved as spam_classifier_model.pkl.

✅ Output

Accuracy of classification

Confusion Matrix

Classification Report

📈 Future Improvements

Deploy as a Flask/Django web app or Streamlit UI.

Extend to email spam detection.

Experiment with advanced models (SVM, Random Forest, Deep Learning).

🙋‍♂️ Author Taimour Mushtaq 🎓 BSCS Student at Federal Urdu University of Arts,Science and Technology, Islamabad Pakistan 🔗 https://www.linkedin.com/in/taimourmushtaq/ |https://github.com/TAIMOURMUSHTAQ
