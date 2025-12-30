 + AI-Powered Task Management System

An intelligent task management application that uses Machine Learning and Natural Language Processing (NLP) to automatically analyze and categorize tasks based on their descriptions. The system integrates a Flask backend, a trained ML model, and a web-based frontend for efficient task organization.

 + Features

Automatic task categorization using NLP

Machine learning model (TF-IDF + Logistic Regression)

Flask-based REST API

Interactive web frontend

Dataset-driven model training and evaluation

Real-time task category prediction

   + Project Structure
AI-Powered_task_management_system/
│
├── app.py
├── train.py
├── train.ipynb
├── requirements.txt
├── ai_powered_task_management_dataset.csv
│
├── frontend/
│   ├── index.html
│   ├── script.js
│   └── styles.css
│
└── README.md

 + Machine Learning Workflow

Text preprocessing

TF-IDF feature extraction

Logistic Regression classification

Task category prediction

 + Installation & Usage
Clone the repository
git clone https://github.com/your-username/AI-Powered-task-management-system.git
cd AI-Powered-task-management-system

Install dependencies
pip install -r requirements.txt

Train the model (optional)
python train.py

Run the Flask app
python app.py


Server runs at:

http://127.0.0.1:5000

 +  Web Interface

Open frontend/index.html in a browser

Enter a task description

Get the predicted task category instantly

📊 Dataset

File: ai_powered_task_management_dataset.csv

Contains task descriptions and labels

Used for supervised learning

🛠️ Technologies Used

Python

Flask

Scikit-learn

Pandas, NumPy

HTML, CSS, JavaScript

📌 Applications

Smart task management systems

Productivity tools

NLP and ML learning projects

📜 License

This project is open-source and intended for educational and research purposes.
