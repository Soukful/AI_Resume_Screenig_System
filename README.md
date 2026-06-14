📄 AI Resume Screening & ATS Analyzer
🔍 Overview

AI Resume Screening & ATS Analyzer is a Machine Learning and Natural Language Processing (NLP) based web application designed to automate the resume screening process.

The system evaluates resumes against job descriptions, generates ATS compatibility scores, extracts key skills, identifies skill gaps, and provides personalized improvement suggestions for candidates.

This project aims to reduce manual HR effort and improve candidate-job matching efficiency using AI.

🚀 Features
📊 Resume vs Job Matching
Compares resume with job description using NLP techniques
Computes semantic similarity score (ATS score)
🧠 Skill Extraction
Extracts key skills from resume text
Identifies technical and non-technical competencies
📉 Skill Gap Analysis
Detects missing skills required for target job roles
Suggests improvements for candidates
🏆 Resume Ranking System
Compares multiple resumes for a single job description
Ranks candidates based on relevance score
🌐 Web Application
Upload resume and job description
Get instant analysis results via Flask dashboard
🛠️ Tech Stack
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn
NLP Techniques: TF-IDF, Sentence Embeddings (optional upgrade)
Backend: Flask
Frontend: HTML, CSS
ML Concepts: Text Similarity, Feature Extraction, Classification
🏗️ System Architecture
Resume Input
     │
     ▼
Text Preprocessing (Cleaning, Tokenization)
     │
     ▼
Feature Extraction (TF-IDF / Embeddings)
     │
     ▼
Similarity Engine (Resume ↔ Job Description)
     │
     ▼
ATS Score Generator
     │
     ▼
Skill Extraction & Gap Analysis
     │
     ▼
Flask Web Dashboard
📂 Project Structure
ai-resume-screening/
│
├── data/
│   ├── resumes/
│   ├── job_descriptions/
│
├── notebooks/
│   ├── eda.ipynb
│   ├── model_experimentation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_extraction.py
│   ├── similarity_engine.py
│   ├── skill_extraction.py
│   ├── ats_scoring.py
│
├── app/
│   ├── templates/
│   ├── static/
│   └── app.py
│
├── models/
│
├── requirements.txt
└── README.md
⚙️ Workflow
User uploads resume
Job description is provided
System preprocesses both texts
NLP model converts text into feature vectors
Similarity score is calculated
ATS score is generated
Skill gap is analyzed
Results displayed on web dashboard
📈 Future Improvements
Integration with BERT / Transformer-based embeddings
Advanced resume parsing (PDF to structured data)
Multi-resume bulk screening
AI-based interview question generator
LinkedIn profile analysis integration
🚧 Project Status

Status: In Progress

Current Progress:
✔ Problem definition completed
✔ System architecture designed
✔ Folder structure setup
✔ Basic preprocessing module
⏳ Model training in progress
⏳ Flask integration pending
⏳ Deployment pending
🎯 Key Impact
Automates resume screening process
Reduces manual HR workload
Helps candidates improve skill alignment
Improves hiring efficiency using AI
📌 Author

Jyotsana Verma
B.Tech Computer Science Engineering
Interested in Machine Learning, NLP & Data Science
