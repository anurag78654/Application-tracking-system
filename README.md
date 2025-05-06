# 🧠 AI Resume Analyzer

A Streamlit-powered AI project that analyzes a candidate's resume and recommends personalized resources (courses, tutorials, certifications, and videos) to improve their skills for targeted job roles.

---

## 📌 Project Overview

This AI Resume Analyzer is designed to:
- Analyze uploaded resumes using **NLP**.
- Automatically identify candidate skills, experience, and strengths.
- Recommend personalized **learning resources** for career paths like:
  - Data Science
  - Web Development
  - Android/iOS Development
  - UI/UX Design
- Suggest **resume-building** and **interview preparation** videos.
- Provide instant feedback through a simple and interactive **Streamlit web app**.

---

## 🚀 How It Works

1. Upload your resume (in `.pdf` format).
2. The app scans and parses the text using `PyMuPDF`.
3. Based on the content, it recommends:
   - Relevant learning platforms and courses.
   - Career improvement videos.
   - Tips for your selected domain.

---

## 🧰 Tech Stack

- **Python 3.x**
- **Streamlit** – Frontend interface
- **PyMuPDF (fitz)** – PDF parsing
- **Pandas** – Data management
- **Regex** – Keyword filtering

---

## 📚 Supported Domains

| Domain         | Recommendations |
|----------------|-----------------|
| Data Science   | Courses from Google, Udemy, Coursera, etc. |
| Web Development| Django, React, Node, Flask |
| Android        | Kotlin, Flutter, Java |
| iOS            | Swift, Xcode |
| UI/UX          | Design Thinking, Adobe XD, UX Principles |

---

## 📝 Files Description

| File          | Description |
|---------------|-------------|
| `App.py`      | Main Streamlit app that handles PDF upload, analysis, and UI. |
| `Courses.py`  | Contains categorized lists of online courses and video URLs. |

---

## ▶️ Demo

> (Optional) Add screenshots or a video link here if you've hosted or recorded a demo.

---

## 🔧 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/anurag78654/Application-tracking-system.git
cd Application-tracking-system

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run App.py
