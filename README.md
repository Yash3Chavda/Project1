# AI-Powered Resume Screening and Ranking System

## Overview
The AI-Powered Resume Screening and Ranking System is designed to automate the process of reviewing and ranking job applicants' resumes. Using Natural Language Processing (NLP) and Machine Learning (ML), the system extracts key information from resumes, compares them with job requirements, and provides a ranked list of candidates based on relevance.

## Features
- *Automated Resume Parsing*: Extracts key details such as skills, experience, education, and certifications.
- *Keyword Matching*: Matches resume content against job descriptions.
- *Ranking System*: Assigns scores based on relevance to job requirements.
- *Machine Learning Models*: Uses NLP-based ML models to analyze and rank resumes.
- *User Dashboard*: Provides an interface for recruiters to upload and review ranked resumes.

## Technologies Used
- *Backend*: Python (Flask/Django)
- *NLP & ML*: spaCy, NLTK, TensorFlow, scikit-learn
- *Database*: PostgreSQL/MongoD

### Steps
1. Clone the repository:
   sh
   git clone https://github.com/Yash3Chavda/AI-powered-Resume-Screening-and-Ranking-System
   cd ai-resume-screening
   
2. Set up a virtual environment:
   sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   
3. Install dependencies:
   sh
   pip install -r requirements.txt
   
4. Set up the database:
   sh
   python manage.py migrate  # Django
   
5. Start the backend server:
   sh
   python app.py  # Flask
   
6. Navigate to the frontend directory:
   sh
   cd frontend
   npm install
   npm start
   

## Installation
### Prerequisites
- Python 3.x
- Node.js & npm (for frontend)
- PostgreSQL or MongoDB

## Usage
1. Upload resumes in PDF or DOCX format.
2. Provide a job description for matching.
3. View ranked candidates based on AI-driven analysis.
4. Download or shortlist top candidates.
