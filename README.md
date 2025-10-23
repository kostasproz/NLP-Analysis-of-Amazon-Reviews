# 🧠 NLP Review Analysis & Topic Modeling

This project applies **Natural Language Processing (NLP)** techniques to analyze product reviews, uncover key topics, and visualize sentiment trends. It combines classic preprocessing, topic modeling, and explainability tools such as **LIME** and **pyLDAvis** for interpretability.

---

## 📊 Project Overview

The notebook performs the following major steps:

1. **Data Loading & Cleaning**
   - Load a dataset of Amazon product reviews.
   - Remove unnecessary columns (`Id`, `ProductId`, `UserId`).
   - Handle missing values and text normalization.

2. **Text Preprocessing**
   - Tokenization and stopword removal using **NLTK**.
   - Stemming and lemmatization with **spaCy**.
   - Conversion of numbers to words.
   - HTML tag removal and punctuation cleaning.

3. **Exploratory Data Analysis (EDA)**
   - Distribution of review scores.
   - Word frequency and n-gram visualization.
   - Word clouds to highlight common terms.

4. **Topic Modeling**
   - Topic extraction using **Gensim LDA** and **Coherence Score** evaluation.
   - Interactive topic visualization using **pyLDAvis**.

5. **Explainability with LIME**
   - Interpret model predictions at the text level.
   - Visualize the words influencing each classification outcome.

---

## 🧩 Technologies Used

| Category | Libraries / Tools |
|-----------|------------------|
| **Core** | Python 3, pandas, NumPy |
| **NLP** | spaCy, NLTK, Gensim, BeautifulSoup, SpellChecker |
| **Explainability** | LIME (Local Interpretable Model-Agnostic Explanations) |
| **Visualization** | matplotlib, seaborn, plotly, pyLDAvis, wordcloud |
| **Modeling** | Word2Vec, FastText, LDA |

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
