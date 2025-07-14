# Resume Analyzer 🧠📄

An intelligent Resume Analyzer tool built using **Machine Learning** and **Natural Language Processing (NLP)** that can automatically categorize resumes based on job domains like Data Science, Web Development, DevOps, HR, and more.

---

## 🔍 Features

- 📄 Upload and analyze resumes in PDF format  
- 🧠 Pre-trained ML model (Logistic Regression + TF-IDF)  
- 📊 Real-time prediction with domain classification  
- 🖥️ Simple and fast UI using **Streamlit**  
- ⚡ Instant feedback without backend deployment  
- 🪶 Lightweight and easy to use

---

## 🛠️ Tech Stack

| Layer       | Technologies Used                            |
|-------------|-----------------------------------------------|
| Frontend    | Streamlit (Python-based UI framework)         |
| Backend     | Python, scikit-learn, pandas, numpy           |
| File Parsing| PyPDF for PDF text extraction                 |
| ML/NLP      | TF-IDF vectorizer + Logistic Regression model |

---

## 📁 Folder Structure

Resume-Analyzer/
├── app.py # Main Streamlit app
├── tfidf.pkl # Saved TF-IDF vectorizer
├── logisticmodel.pkl # Trained ML model
├── requirements.txt # Python dependencies
├── .gitignore
└── README.md

yaml
Copy code

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Aditya121raj/Resume-Analyzer.git
cd Resume-Analyzer
2. Create and activate virtual environment
bash
Copy code
python -m venv venv
venv\Scripts\activate    # For Windows
3. Install dependencies
bash
Copy code
pip install -r requirements.txt
4. Run the Streamlit app
bash
Copy code
streamlit run app.py
📊 How It Works
Upload a resume in PDF format

The app extracts text using PyPDF

Preprocesses and vectorizes the content using TF-IDF

Predicts the category using a Logistic Regression model

Displays the predicted job role/domain

🧠 Model Training (Optional)
Model is pre-trained, but if you want to retrain:

python
Copy code
# Sample code snippet
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LogisticRegression
👨‍💻 Author
Aditya Raj
📬 LinkedIn
💻 GitHub

📝 License
This project is licensed under the MIT License — free for personal & academic use.
