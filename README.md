# 📰 News Recommendation System

A **content-based news recommendation system** that suggests news articles similar to a given headline using **cosine similarity**.

## 📌 Project Overview
This project implements a news recommendation engine leveraging **Natural Language Processing (NLP)** techniques. It computes cosine similarity between news article texts (headlines and short descriptions) to identify and recommend contextually similar articles.

The system is built in Python and includes:
- Data preprocessing
- Exploratory Data Analysis (including WordCloud visualizations)
- A recommendation function based on cosine similarity

---

## ✨ Features
- Content-based filtering using cosine similarity on news text data  
- Supports multiple news categories for better contextual recommendations  
- Interactive Jupyter Notebook for step-by-step development & visualization  
- WordCloud visualizations for keyword insights per category  
- Easy to extend with more advanced NLP models or hybrid methods  

---

## 🛠 Technologies Used
- **Python 3.x**
- Pandas, NumPy  
- Scikit-learn (cosine similarity, TF-IDF)  
- Matplotlib & WordCloud  
- Jupyter Notebook  

---

## 📂 Dataset
Dataset used: [Kaggle News Dataset](https://www.kaggle.com/)  
Contains headlines, descriptions, and categories for thousands of news articles.

---

## 📊 Project Workflow

1. **Dataset Load** – Read the news CSV file (headline, short description, category).
2. **Data Preprocessing** – Clean text, remove stopwords, lowercase, tokenization.
3. **Feature Extraction** – Convert text into numerical vectors using TF-IDF.
4. **Cosine Similarity Calculation** – Measure similarity between articles.
5. **Recommendation Function** – Select top-N similar articles.
6. **Visualization** – WordCloud for keyword insights.
7. **Output** – List of recommended news articles.



---

## 🔍 Example Output 

**Input Headline:** "NASA plans new mission to explore Mars in 2026"

**Top 3 Recommended Articles:**
1. **"Mars Rover Sends Back Stunning Images of the Red Planet"** – Space category
2. **"New SpaceX Rocket Design Announced for Future Missions"** – Science category
3. **"Astronomers Discover Water Traces in Mars Crater"** – Space category

---




▶️ Usage
Run the Jupyter Notebook
jupyter notebook news_recommendation.ipynb


📄 Requirements
pandas
numpy
scikit-learn
matplotlib
wordcloud
jupyter


📬 Contact
Author: Swati Nain
📧 Email: swatinain@gmail.com
🔗www.linkedin.com/in/swati-nain-366b32322


## ⚙️ Installation
```bash
git clone https://github.com/yourusername/news-recommendation-system.git
cd news-recommendation-system
pip install -r requirements.txt

---



