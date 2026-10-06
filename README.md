# Resume Parser and Job Description Matching System

A Python project that extracts key details from a resume and compares them with a job description to calculate a skill match score.

## Features
- Reads resumes from text and PDF formats
- Extracts name, email, phone, skills, education, experience, projects, certifications and languages
- Compares resume skills with job description skills
- Calculates match score and gives a recommendation (Strong / Moderate / Low Match)
- Saves results as CSV files and shows a bar chart

## Technologies Used
- Python
- spaCy
- PyPDF2
- pandas
- Regular expressions (regex)
- matplotlib
- ReportLab

## How to Run
1. Clone this repository
2. Install the libraries: `pip install spacy PyPDF2 python-docx pandas matplotlib reportlab`
3. Download the spaCy model: `python -m spacy download en_core_web_sm`
4. Open `Resume_Parser_Job_Matching_Project.ipynb` in Jupyter Notebook or Google Colab and run all cells

## Author
Harshitha S
