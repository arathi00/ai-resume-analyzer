# AI Resume Analyzer 🚀

A web-based tool that analyzes resumes and provides intelligent feedback using rule-based NLP techniques.

## 🔥 Features

* Resume scoring system (0–100)
* Skill detection
* Section analysis (Projects, Experience, Education)
* Suggestions for improvement
* PDF parsing

## 🛠 Tech Stack

* Python (FastAPI)
* JavaScript
* HTML/CSS
* PDFPlumber

## ⚙️ How to Run

### Backend

```bash
pip install fastapi uvicorn pdfplumber
python -m uvicorn main:app --reload
```

### Frontend

```bash
python -m http.server 5500
```

Open:
http://localhost:5500

## 💡 Description

This project simulates an AI-powered resume analyzer using rule-based logic and NLP-inspired techniques without external APIs.

## 📌 Future Improvements

* Section extraction (Skills, Projects auto detection)
* Resume keyword highlighting
* Deployment (Live demo)
