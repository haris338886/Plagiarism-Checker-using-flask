# 📝 Plagiarism Checker Web App

A Flask-based web application that detects plagiarism by comparing the similarity between multiple uploaded documents.

![Plagiarism Checker Screenshot](https://github.com/user-attachments/assets/77173920-59ae-47b3-b755-ac4c30dba33e)


---

## 🚀 Features

- 📄 Upload `.txt`, `.pdf`, or `.docx` files
- 🤖 Text preprocessing using spaCy (lemmatization, stopword removal)
- 📊 Similarity detection using TF-IDF and Cosine Similarity
- 💡 View percentage similarity between each pair of documents
- 🖥️ Responsive and modern user interface

---

## 🛠️ Technologies Used

- Python (Flask)
- HTML/CSS (Frontend)
- spaCy (`en_core_web_sm`)
- Scikit-learn (TF-IDF + Cosine Similarity)
- PyPDF2 (PDF reader)
- python-docx (DOCX reader)

---

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/plagiarism-checker.git
   cd plagiarism-checker
