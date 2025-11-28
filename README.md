# Basic-My-Introduction-app
# Personal Introduction Web App

A simple Flask web application that collects a user's name, age, and hobby and displays a personalized introduction message. This project demonstrates Flask routing, HTML templating, static file usage, and form handling.

---

## Project Structure
```
project-folder/
│
├── app.py
│
├── static/
│   └── style.css
│
└── templates/
    ├── index.html
    └── result.html
```

---

## Features
- Clean and simple user interface  
- Handles user input through Flask  
- Dynamic output on a separate results page  
- External CSS styling  
- Beginner-friendly code structure  

---

## 📦 Requirements
Install Flask before running:

```bash
pip install flask
```

---

## ▶️ How to Run the App
Start the Flask application:

```bash
python app.py
```

Then open this URL in your browser:

```
http://127.0.0.1:5000/
```

---

## How It Works
1. User enters **name, age, and hobby** in the form.  
2. Flask receives the submitted form data.  
3. `generate_output()` builds a customized introduction message.  
4. The result is displayed on `result.html`.  

---

## 🛠️ Technologies Used
- Python  
- Flask  
- HTML  
- CSS  

---

## 🎯 Purpose of This Project
This project helps beginners understand:
- Flask routing  
- Handling POST forms  
- Linking HTML templates  
- Organizing static files  
- Building a simple interactive web application  

