# ChatGPT-Reviews-Analysis

## 📘 Project Overview

The **ChatGPT Reviews Analysis** project focuses on performing **sentiment analysis** on customer reviews of ChatGPT to understand user satisfaction and identify key themes, strengths, and areas for improvement.  

This analysis leverages **Python**, **Natural Language Processing (NLP)**, and **data visualization techniques** to extract insights from user-generated text data. The results are summarized through interactive visualizations that show sentiment distribution, subjectivity, and rating relationships.

---

## 🎯 Objectives

The main objectives of this analysis are:

- To determine the **overall sentiment** expressed by users toward ChatGPT (Positive, Neutral, Negative).  
- To evaluate the **strength of opinions** through **subjectivity analysis**.  
- To explore the **relationship between sentiment and user ratings**.  
- To identify the **most common keywords and themes** mentioned in reviews.  
- To visualize findings for easy interpretation by stakeholders.

---

## 🧩 Project Implementation

### **1. Data Collection and Loading**
- Imported the dataset containing ChatGPT user reviews from a CSV/Google Drive source.  
- Loaded data into a **Pandas DataFrame** for exploration and processing.  

### **2. Data Preprocessing**
- Cleaned and prepared the text data by:
  - Removing punctuation, stopwords, and special characters.  
  - Converting text to lowercase.  
  - Handling missing values and inconsistent data formats.  
- Tokenized text for further NLP analysis.  

### **3. Sentiment Analysis**
- Applied the **TextBlob** library to compute:
  - **Polarity** (ranges from -1 to +1) to determine sentiment.  
  - **Subjectivity** (ranges from 0 to 1) to measure opinion strength.  
- Categorized reviews as:
  - **Positive** (Polarity > 0)  
  - **Neutral** (Polarity = 0)  
  - **Negative** (Polarity < 0)

### **4. Exploratory Data Analysis (EDA)**
- Performed detailed statistical and visual exploration:
  - Distribution of ratings.  
  - Sentiment vs. Ratings comparison.  
  - Word frequency and keyword analysis.  
- Visualized data using **Matplotlib** and **Seaborn**.

### **5. Visualization and Reporting**
- Created multiple visual insights:
  - **Sentiment Distribution Chart** – proportion of positive, neutral, and negative reviews.  
  - **Sentiment vs. Ratings Boxplot** – relationship between polarity and user rating.  
  - **Word Cloud** – frequently used terms in user feedback.  
  - **Subjectivity Distribution** – shows how opinionated the reviews are.  

---

## 📊 Key Insights

- Majority of users expressed **positive sentiment**, indicating strong satisfaction with ChatGPT.  
- **Neutral reviews** reflect balanced opinions — users acknowledging both pros and cons.  
- **Negative reviews** highlighted issues like factual accuracy and limitations in creativity.  
- **Positive reviews** often mentioned helpfulness, ease of use, and conversational fluency.  
- Ratings aligned strongly with polarity — higher ratings corresponded to more positive sentiment.

---

## ⚙️ Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| NLP & Sentiment | TextBlob |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Environment | Jupyter Notebook (Google Colab) |

---
