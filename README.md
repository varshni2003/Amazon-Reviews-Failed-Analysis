# Amazon-Reviews-Failed-Analysis
Analysing whether longer Amazon reviews indicate stronger sentiment, a professional "no significant result" finding using Python, NLP and Plotly.

A data analytics project that investigates whether review length correlates with sentiment strength in 10,000 Amazon food reviews — and professionally documents the finding of **no significant correlation.**

---

## 📊 Live Dashboard
> Download `amazon_failed_analysis.html` and open it in any browser to view the full interactive dashboard.

---

## 📁 Project Structure
```
├── Amazon_Reviews_Analysis.ipynb      # Google Colab notebook
├── amazon_failed_analysis.html        # Final interactive dashboard
└── README.md
```

---

## 🔍 Hypothesis
> *"Do longer Amazon reviews indicate stronger sentiment — either very positive or very negative?"*

This replicates a common real-world business scenario where analysts invest time in a hypothesis that yields no significant result. Documenting this finding honestly is just as valuable as finding a strong pattern.

---

## 📦 Dataset
- **Source:** Kaggle — Amazon Fine Food Reviews
- **Size:** 10,000 reviews (sampled from 500,000+)
- **Key Columns:** `Score` (1–5 stars), `Text` (review content)

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| Scipy | Correlation analysis |
| Plotly | Interactive charts |
| WordCloud | Text visualisation |
| Matplotlib | Static plots |
| Google Colab | Development environment |

---

## 📈 Dashboard Features
- **Hypothesis Result Card** — correlation score and p-value displayed upfront
- **KPI Cards** — total reviews, positive, neutral, negative counts
- **Sentiment Distribution** — pie chart
- **Avg Review Length per Sentiment** — bar chart
- **Review Length vs Star Rating** — scatter plot (sample of 2,000)
- **Score Distribution** — histogram
- **Word Clouds** — Positive and Negative separately

---

## 💡 Key Finding
Review length shows a **weak correlation** with sentiment strength. Longer reviews do not reliably predict whether a review is positive or negative — disproving the initial hypothesis.

> This is a valid analytical outcome. In real business settings, knowing what does NOT drive behaviour is equally important as knowing what does.

---


## 👩‍💻 Author
**Varshini**
Aspiring Data Analyst | Tamil Nadu, India
[LinkedIn](https://www.linkedin.com/in/varshini-anburaj-530260227/) ·

---

*Project 2 of a 60-day data analytics portfolio challenge.*
