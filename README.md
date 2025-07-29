# NewsBot Intelligence System – Midterm Project
 
Gregory Livingston
ITAI 2373 Natural Language Processing
Professor Patricia MacManus

---

##  Overview

The NewsBot Intelligence System processes real-world news articles using a complete NLP pipeline. It classifies content, extracts named entities, analyzes sentiment, and visualizes insights. This project integrates all concepts from Modules 1–8.

---

##  Dataset

### 📁 Dataset Used

This project uses the **BBC News Classification Dataset** available on [Kaggle](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news).

Files included in this repository:
- `BBC News Train.csv`
- `BBC News Test.csv`
- `BBC News Sample Solution.csv` (optional)

To download the dataset directly from Kaggle via Colab, users must:
1. Get a Kaggle API key (`kaggle.json`)
2. Upload it into the notebook
3. Run the provided download cell


---

##  NLP Pipeline Modules

1. Business Case & Use Context  
2. Text Preprocessing  
3. TF-IDF Analysis  
4. POS Tagging  
5. Syntax & Dependency Parsing  
6. Sentiment & Emotion Analysis  
7. Multi-Class Classification  
8. Named Entity Recognition  

---

## Insight

- Technology articles had the most positive sentiment  
- Entity analysis revealed cross-category trends  
- Classifier accuracy: **XX%** (e.g., 92% with Logistic Regression)

---

## How to Run This Notebook in Google Colab
Upload the dataset file named newsbot_dataset.csv to your Colab session.

Open the notebook file NewsBot_Midterm.ipynb.

Run each code cell in order from top to bottom to execute the full workflow.

To run this notebook in Google Colab:
1. Upload `newsbot_dataset.csv`
2. Open `NewsBot_Midterm.ipynb`
3. Follow cells from top to bottom

---

## 


---

## Notes on NewsBot Project
Platform Used: Google Colab

Dataset Source: News article dataset from Kaggle

Main Goal: Automatically process, analyze, and classify news articles using Natural Language Processing (NLP)

Key Features:
Preprocessing: Cleaned and lemmatized text using spaCy and NLTK

Feature Extraction: Used TF-IDF to convert text into numerical features

Sentiment Analysis: Applied VADER to detect emotional tone

Classification: Trained multiple models to categorize articles

Entity Recognition: Extracted names, organizations, places, and dates using spaCy NER

Tools and Libraries:
Python, pandas, NumPy

NLTK, spaCy, Scikit-learn, Matplotlib

Google Colab for development

GitHub for version control and portfolio showcase

Future Plans:
Add automatic text summarization

Enable voice commands for interaction and dataset search

Build a website interface

Improve accuracy with advanced models

Connect to live news sources
  

