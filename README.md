# 🧠 Plagiarism Analyzer

A **Django-based web application** that detects plagiarism by analyzing the similarity between documents using **Natural Language Processing (NLP)** techniques.  
This project helps educators, students, and researchers identify copied or highly similar content across text submissions.

---

## 🚀 Features

- 📂 Upload one or multiple text files for comparison  
- 🔍 Calculates text similarity using NLP and cosine similarity  
- 🧹 Performs preprocessing: tokenization, stopword removal, and stemming  
- 📊 Displays detailed similarity percentage between documents  
- 🧾 Generates clean and readable plagiarism reports  
- 🌐 Simple and responsive web interface built with HTML, CSS, and Django templates  

---

## 🏗️ Project Structure

PlagiarismAnalyzer/  
├── analyzer/      # Django app for text comparison logic  
├── static/       # CSS, JS, and image files  
├── templates/     # HTML templates  
├── requirements.txt  # Python dependencies  
├── manage.py     # Django management script  
└── README.md     # Project documentation  

---

## 🧩 Technologies Used

- **Python 3.x**  
- **Django Framework**  
- **NLTK (Natural Language Toolkit)**  
- **HTML, CSS (Frontend)**  
- **SQLite / MySQL (Database)**  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/vasanthan2507/PlagiarismAnalyzer.git  
cd PlagiarismAnalyzer  

### 2️⃣ Create a Virtual Environment
python -m venv env  
source env/bin/activate  # On macOS/Linux  
env\Scripts\activate    # On Windows  

### 3️⃣ Install Dependencies
pip install -r requirements.txt  

### 4️⃣ Download Required NLTK Packages
Run this in Python shell:  
import nltk  
nltk.download('punkt')  
nltk.download('stopwords')  

### 5️⃣ Run the Development Server
python manage.py runserver  

Then open your browser and go to:  
👉 http://127.0.0.1:8000/

---

## 🧮 How It Works

1. User uploads two or more text files.  
2. The system preprocesses the text (lowercasing, stopword removal, stemming).  
3. Texts are converted into vectors using token frequency.  
4. **Cosine similarity** is computed between document pairs.  
5. A similarity score (%) is displayed to indicate possible plagiarism.  

---

## 📈 Future Enhancements

- 🔸 Support for PDF and DOCX file formats  
- 🔸 Sentence-level plagiarism highlighting  
- 🔸 REST API for external integration  
- 🔸 User authentication system (Admin / Teacher / Student roles)  
- 🔸 Report export as PDF  

---

## 👨‍💻 Author

**Vasanthan**  
🎓 MCA Student, SMVEC  
💡 Passionate about Python, Data Analytics, and Machine Learning  
🌍 GitHub: [https://github.com/vasanthan2507](https://github.com/vasanthan2507)

---

## 🪪 License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

## 🖼️ Preview

*Add screenshots or demo GIFs of your web interface here to make the README more attractive.*

---

⭐ **If you like this project, give it a star on GitHub!**
