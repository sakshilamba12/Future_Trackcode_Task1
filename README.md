# 📊 Student Event Feedback Analysis

College fests, seminars, and workshops bring energy to campus life — but are students really enjoying them? In this project, we dive into **student feedback data** (ratings + comments) to understand satisfaction levels and find ways to make events better.

## 🎯 Objectives

- Clean and prepare feedback data from a Google Form export (CSV)
- Analyze satisfaction ratings (1–5 scale)
- Use basic **sentiment analysis** to detect moods in feedback (positive/neutral/negative)
- Visualize patterns using charts and word clouds
- Provide key recommendations for organizing better events

---

## 🧠 What You’ll Learn

- 🧼 Data cleaning & preparation using `pandas`
- 💬 Sentiment analysis using `TextBlob`
- 📊 Charting with `matplotlib` and `seaborn`
- 🌐 Word cloud creation
- 📋 Reporting insights for real-world event planning

---

## 🛠 Tools & Libraries Used

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Google Colab / Jupyter | Code execution environment   |
| pandas           | Data manipulation                |
| seaborn / matplotlib | Visualization                 |
| TextBlob         | Sentiment analysis               |
| WordCloud        | Visual feedback representation   |

---

## 🗂️ Dataset

The dataset comes from a **Google Form** where students shared feedback after attending campus events.

Key columns include:
- `Event Name`
- `Department`
- `Event Type` (Workshop, Seminar, etc.)
- `Rating` (1–5 scale)
- `Comments`

---

## 📈 Key Insights (Mini Report)

### 🔹 Ratings
- Workshops received **highest average satisfaction**
- Seminars had more mixed reviews

### 🔹 Sentiment Summary
- **Positive**: Majority of students used words like *"great"*, *"informative"*, *"fun"*
- **Negative**: Mostly around *"timing delays"*, *"too long"*, or *"technical issues"*

### 🔹 Word Cloud Highlights
- ✅ Frequent Positive Words: `interactive`, `fun`, `clear`, `helpful`
- ❌ Frequent Negative Words: `late`, `boring`, `noisy`

---

## 💡 Recommendations

- Start events on time and avoid delays
- Keep sessions short and engaging
- Encourage feedback collection using structured Google Forms
- Introduce interactive Q&A or polls
- Share event success metrics with students

---

## 📁 Folder Structure

```bash
├── Updated_Student_Satisfaction_Survey.csv
├── feedback_analysis_notebook.ipynb
├── sentiment_wordcloud.png
├── charts/
│   ├── rating_distribution.png
│   └── sentiment_pie_chart.png
├── README.md
