# Sentiment-Analysis-and-Recommendations-for-Hotels

# 🏨 Sentiment Analysis and Hotel Recommendation System

This project combines Natural Language Processing (NLP) and Recommendation Logic to analyze hotel reviews, extract sentiment insights, and suggest hotels based on user preferences across languages.

---

## 📌 Project Overview

This system:
- Performs **sentiment analysis** on hotel reviews (positive and negative).
- Builds **aspect-based sentiment** summaries (e.g., cleanliness, location).
- Visualizes sentiment distribution using **word clouds** and **bar plots**.
- Recommends hotels using NLP, semantic similarity, and user tags.
- Supports **multilingual input** (English, French, Spanish).

---

## 🧠 Key Features

- 🔍 Aspect-based sentiment using VADER for each review
- 🌍 Language-aware recommendations using spaCy & langdetect
- 🧼 Text preprocessing, tokenization, and lemmatization
- 📊 Review trend visualization and hotel scoring
- 🎯 Custom recommendation based on location, description, and tags

---

## 🛠️ Tools & Libraries Used

- `Python`, `pandas`, `numpy`
- `nltk`, `TextBlob`, `VADER`
- `matplotlib`, `seaborn`, `WordCloud`
- `spaCy`, `langdetect`, `ast`
- `Jupyter Notebook`

---

## 🗂️ Files in the Repository

| File                            | Description                       |
|---------------------------------|-----------------------------------|
| `AIT526_Team4_Final_Project.ipynb` | Main project notebook             |
| `Hotel_Reviews.csv`            | Dataset used                      |
| `AIT526_Team4_sys.docx/html/txt` | Final project report (various formats) |

---

## 🔍 Example Functionalities

### 1. **Sentiment Analysis by Aspect**
Analyzed sentiments for key hotel aspects like:
- Location
- Staff
- Cleanliness
- Amenities
- Service

### 2. **Word Clouds**
Generated word clouds to visualize common words in:
- Positive reviews
- Negative reviews

### 3. **Multilingual Hotel Recommendation**
Sample queries handled:
- `"I am going for fun"` – English
- `"Je pars pour m'amuser"` – French
- `"Voy a divertirme"` – Spanish

### 4. **Hotel Scoring**
Ranked hotels by:
- Similarity to user input
- Average review score

---

## 🧪 How to Run

1. Clone the repository:
```bash
git clone https://github.com/k-Meghna/sentiment-hotel-recommender.git
cd sentiment-hotel-recommender
```

2. Install required libraries:
```bash
pip install pandas numpy nltk matplotlib seaborn wordcloud spacy langdetect
python -m spacy download en_core_web_sm
python -m spacy download fr_core_news_sm
python -m spacy download es_core_news_sm
```

3. Run the notebook:
```bash
jupyter notebook AIT526_Team4_Final_Project.ipynb
```

---

## 📊 Visual Output Samples

- **Bar plots** showing sentiment count per aspect
- **Top 25 Hotels by Average Score**
- **Word Clouds** for review sentiment

---

## 🤝 Team Members

- Meghna Kattekola
- Ramya Sri Thallapally  
- Srija Anasuri  

---

## 📚 References

1. [TheCleverProgrammer Blog](https://thecleverprogrammer.com/2021/02/13/hotel-recommendation-system-with-machine-learning/)
2. [Kaggle Hotel Reviews Sentiment Analysis](https://www.kaggle.com/code/jonathanoheix/sentiment-analysis-with-hotel-reviews)

---

## 📬 Contact

**Meghna Kattekola**  
📧 kattekola.meghna@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/meghnadk)

---
