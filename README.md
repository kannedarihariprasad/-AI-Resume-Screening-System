# -AI-Resume-Screening-System
AI-powered Resume Screening System using NLP, TF-IDF, and Cosine Similarity to rank resumes based on job description matching.
# AI Resume Screening System (NLP)

## Project Overview

The AI Resume Screening System is a Natural Language Processing (NLP) project that automates the resume shortlisting process. It compares candidate resumes with a given job description and ranks them based on their similarity score, helping recruiters identify the most relevant candidates quickly.

## Features

* Loads and processes resume datasets.
* Cleans and preprocesses resume text using NLP techniques.
* Converts text into numerical vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)**.
* Calculates resume-job similarity using **Cosine Similarity**.
* Ranks candidates based on matching percentage.
* Displays the top matching resumes.
* Visualizes resume matching scores using Matplotlib.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Regular Expressions (Regex)

## NLP Techniques

* Text Cleaning
* TF-IDF Vectorization
* Cosine Similarity

## Workflow

1. Load the resume dataset.
2. Clean and preprocess resume text.
3. Create a job description.
4. Convert resumes and the job description into TF-IDF vectors.
5. Calculate cosine similarity scores.
6. Rank resumes based on match percentage.
7. Display and visualize the top matching candidates.

## Project Outcome

The system automatically ranks resumes according to their relevance to a job description, reducing manual screening effort and improving the efficiency of the recruitment process.

## Future Enhancements

* Support direct PDF resume uploads.
* Build a web application using Flask or Streamlit.
* Integrate transformer-based models such as BERT for semantic matching.
* Recommend missing skills to candidates based on job requirements.
