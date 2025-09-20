# Job Description NLP & Embeddings Project

## 🚀 Overview
This project processes job postings, cleans the text, preprocesses it using NLP techniques, and generates embeddings for AI-powered applications like job recommendations or semantic search.

---

## 🛠 Technologies Used
- **Python 3.x**
- **Pandas** – for data manipulation
- **spaCy** – for text preprocessing (lemmatization, stopword removal)
- **SentenceTransformers** – for generating sentence embeddings
- **re (Regular Expressions)** – for text cleaning

---

## 📝 Project Workflow
1. **Load raw dataset** – Read the CSV file containing job postings.  
2. **Clean dataset** – Remove duplicates, missing descriptions, HTML tags, and special characters.  
3. **Preprocess text** – Convert to lowercase, remove stopwords, and lemmatize.  
4. **Generate embeddings** – Use `SentenceTransformer` to convert descriptions into vector representations.  
5. **Save data** – Store the cleaned dataset and embeddings for further use.

---


## Install required packages:
1)**pip install pandas spacy sentence-transformers**
2)**python -m spacy download en_core_web_sm**
3)**python job_nlp_embeddings.py**

## 📌 Author
MUJAHAD AHMED – Passionate about NLP & Data Science


💻 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/job-nlp-embeddings.git

