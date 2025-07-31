# FUTURE_DS_03
This is my third task for the Future Intern Internship in **Data Science and Analytics**

# 🎓 College Event Feedback Analysis

This project analyzes student feedback from various campus events to uncover satisfaction trends, visualize sentiments, and suggest improvements based on survey responses.

## 📂 Dataset

**Filename:** `Student_data.csv`  
**Columns:**
- `Student_ID`: Unique ID of the student
- `Event_Name`: Name of the event
- `Department`: Student's academic department
- `Year`: Academic year (1st, 2nd, etc.)
- `Date`: Date of event
- `Speaker_Rating`: Rating for speaker quality (1–5)
- `Content_Rating`: Rating for content relevance (1–5)
- `Overall_Satisfaction`: Overall satisfaction rating (1–5)
- `Would_Recommend`: Whether the student would recommend the event
- `Comments`: Open-ended feedback

## 🧪 Tasks Performed

### ✅ Data Cleaning
- Converted date fields to datetime
- Removed or handled missing data
- Standardized categorical fields

### 📊 Data Analysis
- Average speaker, content, and satisfaction scores
- Department-wise and event-wise satisfaction
- Monthly satisfaction trends

### 💬 Sentiment Analysis
- Performed polarity scoring on open-ended comments using `TextBlob`
- Classified comments as **Positive**, **Negative**, or **Neutral**

### ☁️ Word Clouds
- Word cloud for all comments
- Separate word cloud for **liked** feedback

### 📈 Visualizations
- Bar charts for satisfaction
- Pie chart for recommendation rate
- Line chart for monthly satisfaction
- Word clouds of feedback
- Sentiment distribution bar chart

## 🧰 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- TextBlob


## 🚀 How to Run
1. Clone this repo or download the files
2. Run the Colab notebook
3. Install required libraries:
    ```bash
    pip install pandas matplotlib seaborn wordcloud textblob
    python -m textblob.download_corpora
    ```

## 📌 Project Outcome
- Identified top and bottom-rated events
- Detected patterns in satisfaction across time and departments
- Visualized student sentiment and recurring feedback themes
- Suggested data-driven improvements for future events

---

> This project was created as part of a data science internship and is intended to demonstrate real-world data analysis and visualization skills.

