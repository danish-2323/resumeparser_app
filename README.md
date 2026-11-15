# Resume Parser and Role Matching Tool

**Author:** Danish M

A Python desktop application that extracts selected information from PDF resumes and compares candidate skills with a chosen job role. The application uses PDF text extraction and NLP-based matching to produce a preliminary role-fit summary.

## Features
- Read text from PDF resume files.
- Extract selected contact information.
- Identify skills and relevant terms.
- Compare extracted information against configured job-role requirements.
- Produce a role-fit score and a preliminary selection indicator.
- Save parsed information and matching results to text files.
- Provide a desktop interface using Tkinter.

## Technology stack
- Python 3
- Tkinter
- pdfplumber
- spaCy
- RapidFuzz

## Prerequisites
- Python 3.9 or later
- PDF files containing machine-readable text

## Installation

~~~bash
pip install pdfplumber spacy rapidfuzz
python -m spacy download en_core_web_sm
~~~

## Run the application

~~~bash
python main.py
~~~

## Output

The application is configured to save extracted and matching information in text files, including parsed_results.txt and selection_results.txt.

## Limitations and responsible use

Resume parsing can fail when PDFs contain scanned images, unusual layouts or inconsistent formatting. Skill matching is heuristic and may overlook equivalent experience or context. The score is not a validated hiring assessment and must not be used as the sole basis for recruitment decisions. Handle resumes as confidential personal data and apply appropriate access, retention and deletion controls.

## Author

Danish M
