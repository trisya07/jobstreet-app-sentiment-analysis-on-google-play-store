# 📱 Jobstreet App Sentiment Analysis on Google Play Store

This project aims to analyze user sentiment toward the **Jobstreet** app based on reviews from the Google Play Store. The analysis includes data scraping, text preprocessing, and sentiment analysis using Python.

---

## 📂 Project Structure
```
📁 jobstreet-app-sentiment-analysis-on-google-play-store/
├── Kode scraping data jobstreet via google play.ipynb <- Notebook for scraping reviews from Google Play
├── kode_analisis sentimen.ipynb <- Notebook for preprocessing & sentiment analysis
├── kode testing.ipynb <- Notebook for testing sentiment classification model
├── requirements.txt <- Python dependencies list
├── hasil_scraping_jobstreet.csv <- (optional) Scraped review data in CSV format
```
---

## 🛠️ Technologies & Libraries

- Python
- BeautifulSoup / Google Play Scraper
- Pandas, NumPy
- Scikit-learn
- NLTK / Sastrawi (for Indonesian text)
- Matplotlib / Seaborn / WordCloud
- Jupyter Notebook

---

## 🔍 Features

- Scraping reviews of the Jobstreet app from Google Play Store.
- Text cleaning and preprocessing (normalization, stopword removal, etc.).
- Sentiment labeling (positive, negative, neutral) automatically or manually.
- Sentiment visualization and word clouds.
- Sentiment classification testing (if implemented).

---

## 📈 Output

- Sentiment distribution visualized through charts.
- Word clouds for each sentiment category.
- Simple classification model (if included) to predict sentiment from review text.

---

## ▶️ How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/trisya07/jobstreet-app-sentiment-analysis-on-google-play-store.git
   cd jobstreet-app-sentiment-analysis-on-google-play-store
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt

## 📁 Dataset
The scraped reviews are saved as ulasan_aplikasi.csv and used in further analysis steps.
