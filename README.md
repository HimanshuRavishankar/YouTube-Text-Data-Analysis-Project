# YouTube-Text-Data-Analysis-Project
This project explores text-based and metadata insights from YouTube video datasets using Python. Through a combination of data preprocessing, sentiment analysis, emoji usage tracking, and visualization, the project aims to uncover meaningful insights about user engagement and video performance across various categories.

---

## 🔍 Project Objectives

- Load and pre-process raw YouTube data from multiple countries.
- Perform exploratory data analysis (EDA) on metadata and comment texts.
- Detect and analyse sentiments in user comments.
- Identify and visualize frequently used emojis.
- Generate word clouds for positive and negative sentiment segments.
- Evaluate engagement metrics such as like rate, dislike rate, and comment rate.
- Visualize trends using box plots and regression plots.
- Export cleaned data into CSV and JSON formats.

---

## 🗃️ Data Sources

- Raw YouTube datasets (CSV/JSON format) from multiple countries.
- YouTube video metadata including titles, tags, views, likes, dislikes, etc.
- User comments data for sentiment and emoji analysis.

## 📂 Data Access

The dataset used in this project is available on Google Drive:

🔗 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1gnFoDpP1akcyEBMOZ2oWylcHbSwY7NyE/view?usp=sharing)
---

## 📦 Technologies Used

- **Python Libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`, `textblob`, `wordcloud`, `emoji`, `os`, `warnings`, `collections`
- **Text Processing**: Sentiment analysis using `TextBlob`
- **Visualization**: Box plots, regression plots, bar charts, word clouds
- **Storage Formats**: CSV and JSON

---

## 📊 Key Analyses

### 1. 📁 Data Loading & Cleaning
- Read CSV/JSON data using `pandas`.
- Handle encoding and corrupted lines.
- Merge data from multiple countries.
- Remove duplicate entries and null values.

### 2. ✨ Sentiment Analysis
- Use `TextBlob` to calculate polarity of comments.
- Append sentiment score to the dataset.
- Handle missing or corrupt comments with `try-except` blocks.

### 3. 📌 Word Cloud Generation
- Generate word clouds for both positive and negative sentiment comments.
- Use `wordcloud` and `STOPWORDS` to highlight meaningful words.

### 4. 😂 Emoji Analysis
- Extract emojis from comments using the `emoji` library.
- Count and rank the most used emojis.
- Visualize top emojis in a bar chart using `plotly`.

### 5. 📈 Engagement Analysis
- Calculate like rate, dislike rate, and comment rate.
- Generate box plots by category to evaluate engagement.
- Use regression plots to analyze relationship between views and likes.

### 6. 🗃️ Data Export
- Save the processed dataset in:
  - CSV format
  - JSON format

---

## 📂 File Structure

```
📁 YouTube-Text-Data-Analysis/
│
├── YouTube_Analysis_Notebook.ipynb   # Main notebook with all analyses
├── visualizations/                    # Plots and word clouds
├── README.md                          # Project overview
```

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/youtube-text-data-analysis.git
   cd youtube-text-data-analysis
   ```

2. Open and run the notebook:
   - `YouTube_Analysis_Notebook.ipynb`

---

## ✅ Results & Insights

- Most commonly used emojis reflect strong positive sentiment (🖤 🥰‍ 😍).
- Sentiment analysis shows a dominant presence of positive feedback.
- Categories like Music, Comedy, and Entertainment show higher engagement rates.
- A strong linear relationship observed between views and likes.

---

## 🧠 Learnings

- Practical understanding of NLP and text preprocessing.
- Techniques for multilingual data handling and encoding.
- Real-world use of visualization tools and libraries.
- Experience with data analysis from large-scale sources.

---

## 📬 Feedback

If you have suggestions, feedback, or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

---
