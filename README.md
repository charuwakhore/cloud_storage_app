# ☁️ Cloud Storage App

A simple **Flask-based Cloud Storage App** that allows users to **upload and delete files** easily.

---

## 🚀 Features
- Upload files to a secure folder  
- View uploaded files in the browser  
- Delete unwanted files  
- Lightweight and easy to use  

---

## 🧠 Tech Stack
- **Python**
- **Flask**
- **HTML / CSS (Jinja templates)**
- **Git & GitHub**

---

## 📂 Project Structure
loud_storage_app/
│
├── app.py ───▶ Main file that runs the Flask app
│ └── Controls routes like upload, view, delete
│
├── templates/ ───▶ HTML pages shown in browser
│ ├── index.html ───▶ Home page (upload form)
│ └── files.html ───▶ Displays uploaded files
│
├── static/ ───▶ Contains CSS, JS, and images used by templates
│ └── style.css ───▶ Basic page styling
│
├── uploads/ ───▶ Stores uploaded files (ignored in Git)
│
└── README.md ───▶ Documentation for the project
