<h1 align="center">📱 Play Store Sentiment Analysis of User Reviews 📊</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue?logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
  <img src="https://img.shields.io/badge/Project-Type-EDA%20%26%20NLP-brightgreen" />
</p>

---

## 📌 Overview

This project performs a **comprehensive sentiment analysis** of user reviews and app statistics from the **Google Play Store**, covering:

- Exploratory Data Analysis (EDA)
- Sentiment classification using Natural Language Processing (NLP)
- Data visualization for patterns across categories, installs, ratings, etc.

We uncover hidden insights that help understand user feedback and app performance across the Android marketplace.

---

## 📁 Dataset Description

The analysis is based on two primary datasets:

- `apps.csv`: Contains metadata about 10,000+ apps (ratings, installs, size, type, etc.)
- `user_reviews.csv`: Contains 100+ user reviews per app, labeled with sentiment (`Positive`, `Negative`, `Neutral`)

---

## 🚀 Project Pipeline

```
Data Collection
       ↓
  Data Cleaning
       ↓
        EDA
       ↓
Sentiment Preprocessing
       ↓
Text Vectorization (TF-IDF)
       ↓
Modeling & Visualization
```

---

## 📊 Exploratory Data Analysis (EDA)

✔️ Distribution of app categories  
✔️ Relationship between size, reviews, and installs  
✔️ Impact of pricing on ratings  
✔️ Rating trends across genres

Sample Visualization:
![Category Distribution](https://user-images.githubusercontent.com/placeholder-category-chart.png)

---

## 🧠 Sentiment Analysis (NLP)

**Steps:**
- Clean and preprocess review text (stopwords, lowercasing, lemmatization)
- Convert reviews into numerical vectors using **TF-IDF**
- Use sentiment labels (provided) to train a classifier

🧪 Output:

| Sentiment | Sample Review |
|-----------|----------------|
| Positive | "Love this app, it's super helpful!" |
| Negative | "Keeps crashing after the update." |
| Neutral  | "It’s okay, nothing special."        |

---

## 📌 Technologies Used

- **Python** 🐍
- **Pandas** for data wrangling
- **Matplotlib & Seaborn** for EDA
- **NLTK** for text preprocessing
- **Scikit-learn** for vectorization & modeling
- **Jupyter Notebook** for experimentation

---

## 📈 Insights & Takeaways

- Free apps generally get more downloads but don’t always have the best ratings.
- Larger apps (in MB) tend to have lower ratings due to performance concerns.
- User reviews with negative sentiments often reference crashes and ads.
- Sentiment analysis can be a powerful tool for real-time feedback interpretation.

---

## 📂 How to Run

1. Clone this repository  
```bash
git clone https://github.com/your-username/playstore-sentiment-analysis.git
cd playstore-sentiment-analysis
```

2. Install requirements  
```bash
pip install -r requirements.txt
```

3. Launch the notebook  
```bash
jupyter notebook
```

---

## 🧠 Author

**Safal Swayam**  
📘 MCA @ KIIT | 🧠 AI Enthusiast | 🤖 Data Analyst & NLP Explorer  
📫 [LinkedIn](https://www.linkedin.com/in/safal-swayam/) • 🌐 [Portfolio](https://your-portfolio-link.com)

---

## 📌 License

This project is under the [MIT License](LICENSE).

---

> ⭐ If you found this repo useful, feel free to star it and follow for more ML & NLP projects!
