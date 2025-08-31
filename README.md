# bimo_sentiment_analysis
This project analyzes Algerians' opinions and sentiments about **ChatGPT** using social media data.  
The workflow includes **data collection, preprocessing, sentiment classification, and visualization**.  

---

## 📂 Project Structure  
- `data/` → contains the dataset of Algerians' opinions about ChatGPT  
- `notebook.ipynb` → Jupyter Notebook with the full analysis  
- `requirements.txt` → required libraries  

---

## 🔍 Steps in the Analysis  

1. **Data Collection**  
   - Social media data (text posts/comments) was scraped and stored.  

2. **Preprocessing**  
   - Cleaning text (removing punctuation, links, stopwords).  
   - Handling Arabic text (normalization).  

3. **Sentiment Analysis**  
   - Each text was classified into **positive** or **negative** sentiment.  

4. **Visualizations**  
   - **Word Cloud** → shows the most frequent words.  
   - **Pie Chart** → distribution of positive vs. negative opinions.  

---

## 📊 Example Results  

- Majority sentiment was **positive/negative** (depending on your results).  
- WordCloud highlighted frequent terms like _"شات جي بي تي"_, _"ذكاء اصطناعي"_, etc.  

---

## ⚙️ Installation  

Clone the repo:  
```bash
git clone https://github.com/yourusername/chatgpt-sentiment-algeria.git
cd chatgpt-sentiment-algeria
