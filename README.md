Smart Resume Parser 🧠📄

A simple Python-based tool that reads PDF resumes and checks if the applicant is a good fit for a selected job role using AI and NLP.

💡 Features

Upload and read PDF resumes

Extract name, email, and phone number using NLP

Match skills and programming languages for roles like:

Developer

Data Analyst

Manager

Gives a score out of 100 and selection status

Saves the results in .txt files

Easy-to-use GUI with Tkinter

🚀 How to Run

1. Install the required packages:

pip install pdfplumber spacy rapidfuzz
python -m spacy download en_core_web_sm


2. Run the app:

python main.py

📁 Output Files

parsed_results.txt – full resume data

selection_results.txt – name, role, score, and result (Selected / Not Selected)

🛠 Built With

🌟 Python 🐍
🌟 Tkinter 🖼️
🌟 spaCy 🔍
🌟 pdfplumber 📄
🌟 rapidfuzz 🔧

🎥 Here's a video reference 

https://drive.google.com/file/d/1OxzUVgo_WFUqvzwdm4KKnBZLSCa1Fqrx/view?usp=drivesdk
