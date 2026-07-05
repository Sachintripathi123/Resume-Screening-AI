# 📄 Resume Screening AI (Version 1)

## 📌 Project Overview

Resume Screening AI is a Machine Learning project that ranks candidates based on the similarity between their skills and a selected job description.

The project uses **TF-IDF Vectorization** and **Cosine Similarity** to calculate similarity scores and rank resumes.

---

## 🚀 Features

- Extract candidate skills from resume dataset
- Select a job description using Job ID
- Calculate similarity using TF-IDF and Cosine Similarity
- Rank resumes based on similarity score
- Display ranked candidates

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

---

## 📂 Project Workflow

1. Load Resume Dataset
2. Load Job Description Dataset
3. Extract Resume Skills
4. Extract Required Skills
5. Calculate Similarity
6. Rank Resumes
7. Display Results

---

## ▶️ How to Run

1. Clone or download this repository.
2. Install the required libraries.
3. Open `Resume_Screening_AI_V1.ipynb` in Google Colab or Jupyter Notebook.
4. Run all the cells.
5. Enter the Job ID when prompted.
6. View the ranked resumes.

---

## 📈 Future Improvements

- PDF Resume Parsing
- OCR Support for Scanned Resumes
- Skill Matching
- Missing Skill Detection
- Sentence-BERT Embeddings
- Streamlit Web Application

---

# 🚀 Version 2 Updates

Resume Screening AI has been upgraded with a more modular and ATS-style architecture.

## ✨ New Features

- Converted resume skills into sets for efficient comparison.
- Converted job description skills into a required skill set.
- Implemented skill matching using set intersection (`&`).
- Implemented missing skill detection using set difference (`-`).
- Calculated ATS-style match percentage for each resume.
- Generated a detailed result table including:
  - Candidate Name
  - Matched Skills
  - Missing Skills
  - Match Percentage
- Ranked candidates based on match percentage.
- Refactored the project into reusable and modular functions.

## 📊 Sample Output

| Name | Matched Skills | Missing Skills | Match Percentage |
|------|----------------|----------------|-----------------:|
| Rahul Sharma | {python} | {docker, tensorflow, deep learning} | 25.0 |
| Rohit Mishra | {python, docker, tensorflow, deep learning} | {} | 100.0 |
---
## 🔮 Future Improvements (Version 3)

- Experience Matching
- Education Matching
- Certification Matching
- Project Matching
- Weighted ATS Score
- Resume PDF Upload Support
- NLP-based Skill Extraction
- Streamlit Web Application
---

## 👨‍💻 Author

**Sachin Tripathi**

AI & Machine Learning Enthusiast
