📄 Resume Screening System using Machine Learning & NLP
🔍 Project Overview

The Resume Screening System is a Machine Learning and NLP-based project designed to automate the process of screening resumes for specific job roles.
It helps recruiters and HR teams reduce manual effort by intelligently classifying resumes based on skills and job descriptions.

🎯 Problem Statement

Recruiters receive thousands of resumes for a single job opening.
Manual screening is:

Time-consuming

Prone to human bias

Inefficient

This project solves the problem by using Natural Language Processing (NLP) and Machine Learning to automatically classify resumes into relevant job categories.

🧠 Solution Approach

Clean and preprocess resume text

Convert text data into numerical form using TF-IDF

Train ML models to classify resumes

Predict job category for new/unseen resumes

🗂️ Dataset Information

Total Records: 10,174

Data Type: Text (object)

Columns used:

Resume

Job_Description

Decision / Category (Target)

⚙️ Technologies Used

Programming Language: Python

Libraries:

Pandas

NumPy

Scikit-learn

NLTK

Matplotlib

ML Algorithms:

Logistic Regression

Naive Bayes

Support Vector Machine (optional)

Vectorization: TF-IDF

🔁 Project Workflow

Data Loading

Text Cleaning & Preprocessing

Feature Extraction using TF-IDF

Train-Test Split

Model Training

Model Evaluation

Resume Category Prediction

📊 Model Output

Example Prediction:

Predicted Category: Data Scientist


The model classifies resumes into roles such as:

Data Scientist

Web Developer

HR

Finance

Software Engineer

🧪 How to Run the Project

Clone the repository

Install required libraries

Open resume_screening.ipynb

Run all cells

Test with new resume text

📌 Sample Code Snippet
predict_resume(
    "Python, Machine Learning, NLP, SQL, Data Analysis",
    "Looking for a Data Scientist with ML experience"
)

✅ Results

Accurate resume classification

Reduced manual screening effort

Scalable for large datasets

🚀 Future Enhancements

Resume ranking system

ATS-style dashboard

Deep Learning (BERT)

Streamlit web application

Skill gap analysis

🧑‍💼 Use Cases

HR Automation

Applicant Tracking Systems (ATS)

Recruitment Agencies

Campus Hiring

📎 Author

Rahul Paswan
Machine Learning & Data Science Enthusiast
📍 India

⭐ If you like this project

Give the repo a ⭐ and feel free to fork it!
