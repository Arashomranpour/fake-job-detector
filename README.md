<div align="center">

# 🕵️ Fake Job Posting Detector

**Spot fraudulent job advertisements with NLP and a decision-tree classifier.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`i.ipynb` analyses `fake_job_postings.csv` (job title, location, description, requirements, `fraudulent` flag):

1. 📊 **EDA** - class balance of real vs. fraudulent postings, most common titles in each group, word clouds.
2. 🧹 **Text cleaning** with `re`, `string` and **spaCy** (tokenization / lemmatization / stop-word removal).
3. 🔢 **Vectorization** with `CountVectorizer` / `TfidfVectorizer` inside a scikit-learn `Pipeline`.
4. 🌳 **Decision Tree classifier** - about **96 % accuracy** on the 5 364-posting test split.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/fake-job-detector.git
cd fake-job-detector
pip install pandas numpy scikit-learn spacy seaborn matplotlib wordcloud jupyter
python -m spacy download en_core_web_sm
jupyter notebook i.ipynb
```

## 📁 Project Structure

```
.
├── i.ipynb                   # EDA, preprocessing, model
└── fake_job_postings.csv     # Dataset
```

## 🛠️ Tech Stack

`spaCy` · `scikit-learn` · `pandas` · `Seaborn` · `WordCloud`
