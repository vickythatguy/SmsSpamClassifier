# SMS Spam Classifier 📩🚫

This is a Streamlit-based web app that uses a machine learning model to classify SMS or email messages as **Spam** or **Not Spam**.

## 🔍 How it works:
- Preprocesses your input message (lowercasing, stopword removal, stemming)
- Transforms it using a trained TF-IDF vectorizer
- Predicts the class using a Voting Classifier model
- Displays result in a simple, user-friendly interface

## 🛠️ Built With:
- Python 🐍
- Streamlit 🌐
- scikit-learn ⚙️
- NLTK 🧠

## 📦 Files Included:
- `app.py`: Main Streamlit app
- `vectorizer.pkl`: Saved TF-IDF vectorizer
- `voting_classifier.pkl`: Trained classifier model
- `spam.csv`: Dataset (optional)
- `requirements.txt`: Dependencies for deployment

## 🚀 Try it out!
Deployed on [Streamlit Cloud](https://smsspamclassifier-vignesh.streamlit.app/)

---

## 📬 Example Use:
> Input: "Congratulations! You've won a free ticket to Bahamas. Text WIN to 80808."
> Output: 🚫 Spam

---

## 🤝 Contribute
Feel free to fork and improve — add more models, preprocessing, or UI polish!
