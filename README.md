#                                          Automated Resume Parser 

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*92buYZAjvbugrZHlRBCTKw.png" alt="Resume Parser Banner" style="max-width: 100%; height: auto; width: 400px;">
</p>

<h1 align="center">🔍 Automated Resume Parser Project 🚀</h1>
<p align="center">
  <b>Internship Project for <a href="http://codectechnologies.in/">Codec Technologies</a></b><br>
  <b>Extract structured data from unstructured resumes automatically!</b> ⚡<br>
  Upload resumes in PDF/DOCX format and parse useful information like Name, Skills, Experience, Education, etc.<br>
  <sub>Tech Stack: Python, Flask, HTML/CSS, JSON</sub>
</p>

---

### 🧠 Introduction

This **Automated Resume Parser** was developed as part of my internship at **Codec Technologies**. The system reads uploaded resumes, parses important information using Python and Natural Language Processing (NLP), and converts it into structured JSON format. This can help recruiters automate the initial screening process.

---

### 📦 Features

* 📤 **Upload Resumes** – Supports `.pdf` and `.docx` formats
* 📑 **Parse Key Fields** – Name, Email, Phone, Skills, Experience, Education
* 📁 **Save Parsed Data** – Automatically saves output in JSON format
* 🌐 **Web Interface** – Simple frontend using HTML & CSS
* 🧠 **Text Processing** – Smart parsing using keyword and pattern matching

---

### 🛠️ Technologies Used

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON">
</p>

---

### 🚀 How to Run the Project?

#### ✅ Prerequisites:

* Python 3.8+
* `pip` (Python package manager)

#### 🛠️ Setup:

```bash
# Clone the repo
git clone https://github.com/CodeWithTanim/automated-resume-parser.git
cd automated-resume-parser

# (Optional) Create virtual environment
python -m venv venv
# Activate venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask server
python run.py
```

---

### 🌐 Access the Web App

Once the server is running, open your browser and go to:

```
http://localhost:5000/
```

---

### 🗂️ Project Structure

```
automated-resume-parser/
│
├── app/
│   ├── __init__.py
│   ├── database.py
│   ├── parser.py
│   ├── routes.py
│   └── utils.py
│
├── parsed_data/
|
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── uploads/               ← Stores uploaded resumes temporarily
|
├── config.py              ← Configuration settings (if any)
├── run.py                 ← Flask app entry point
├── requirements.txt       ← Python dependencies
└── README.md
```

---

### 🌟 Key Learnings (Internship)

* Applied file handling and text parsing techniques in Python
* Built a full-stack web app using Flask, HTML, CSS
* Gained experience in extracting structured data from unstructured documents
* Improved understanding of backend routes, JSON formatting, and deployment basics

---

### ✍️ Developer

> [MOHAMMAD IMTIAZ AHMED](https://github.com/Imtiazsalaf-01)
> Intern at [Codec Technologies](http://codectechnologies.in/)
> 🔗 [GitHub](https://github.com/Imtiazsalaf-01) | [LinkedIn](www.linkedin.com/in/imtiaz786)

---

### 📜 Acknowledgments

* Thanks to [Codec Technologies](http://codectechnologies.in/) for this opportunity
* Inspired by modern HR automation tools
* Flask & Python community for support and resources

---

### 🤝 Contribute

Feel free to fork the repo and submit pull requests if you have ideas to improve the parser or UI.

---

### 📄 License

This project is licensed under the **MIT License** – See the [LICENSE](https://github.com/Imtiazsalaf-01/Automated-Resume-Parser?tab=MIT-1-ov-file) file for details.

