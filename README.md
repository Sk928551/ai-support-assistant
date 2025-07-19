# 🤖 AI Support Assistant

Automatically classify incoming support emails using Machine Learning and NLP – built with 🐍 Python, 🎯 Scikit-learn, and ⚡ Streamlit.


---

## 🚀 Project Overview

**AI Support Assistant** is an intelligent tool designed to automate the classification of customer support tickets based on the subject and description. This helps businesses streamline support processes, auto-route issues, and improve response times.

---

## 🧠 Key Features

- 🔍 **Text Cleaning**: Custom NLP-based preprocessor
- 🧮 **TF-IDF Vectorization**: Converts text into meaningful vectors
- 🌲 **Random Forest Classifier**: Predicts categories with high accuracy
- 🎨 **Streamlit UI**: Easy-to-use web interface
- 💾 **Model + Vectorizer Saved**: Reusable with `joblib`

---

## 🏗️ Tech Stack

| Tool             | Purpose                      |
|------------------|------------------------------|
| Python           | Programming Language         |
| Pandas           | Data Processing              |
| Scikit-learn     | Machine Learning & NLP       |
| Streamlit        | Frontend Web App             |
| Joblib           | Model Persistence            |

---

## 📦 Folder Structure

ai-support-assistant/
├── app/
│ ├── predict.py # Prediction script
│ ├── streamlit_app.py # Streamlit frontend
│ └── utils/
│ └── preprocessing.py # Custom text cleaning
├── data/
│ └── tickets.csv # Support ticket data
├── model/
│ ├── email_classifier.pkl # Trained ML model
│ └── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # Python dependencies
└── README.md # Project overview

🐍 2. Install Requirements

pip install -r requirements.txt

⚙️ 3. Train the Model (optional)

python app/train_model.py

🧪 4. Run the App

streamlit run app/streamlit_app.py



🙌 Acknowledgements

Inspired by the need for better support automation
Built as part of a data engineering & AI learning journey

📬 Contact
📧 aman.kanthiwar@gmail.com
🔗 https://www.linkedin.com/in/aman-kanthiwar-272725240/


