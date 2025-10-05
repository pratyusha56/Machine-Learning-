# 🧠 Customer Segmentation Using Sentiment Analysis  

> **Analyzing Yelp Restaurant Reviews using NLP and Clustering**  

---

## 📘 Overview  

This project explores how **Natural Language Processing (NLP)** and **Unsupervised Learning** can uncover customer insights from restaurant reviews.  
By applying **Sentiment Analysis** and **K-Means Clustering** to Yelp reviews, customers are segmented into **Positive**, **Neutral**, and **Negative** sentiment groups — enabling data-driven business decisions.  

---

## 🎯 Objectives  

- Automate extraction and analysis of customer opinions from Yelp reviews  
- Quantify emotions in text using sentiment polarity scores  
- Cluster customers into sentiment-based segments  
- Visualize and interpret sentiment distribution  

---

## 🧩 Methodology  

### 1. **Dataset**  
- **Source:** Yelp Open Academic Dataset  
- Focused on reviews under the **"Restaurants"** category  
- Used `business.json` and `review.json` files  

### 2. **Preprocessing**  
- Filtered restaurant-related reviews  
- Cleaned text (tokenization, stop-word removal)  
- Extracted sentiment polarity using **TextBlob**  

### 3. **Sentiment Scoring**  
- Polarity range:  
  - `-1` → Very Negative  
  - `0` → Neutral  
  - `+1` → Very Positive  
- Examples:  
  - “Amazing food!” → `0.8`  
  - “Just okay.” → `0.2`  
  - “Horrible service.” → `-0.6`  

### 4. **Customer Segmentation**  
- Applied **K-Means Clustering** with 3 clusters  
- Labelled clusters based on average sentiment:  
  - Cluster 0 → Negative  
  - Cluster 1 → Neutral  
  - Cluster 2 → Positive  

### 5. **Visualization**  
- Histogram of sentiment polarity values  
- Color-coded clusters to represent sentiment groups  

---

## 📊 Results & Insights  

- Analyzed **20,000+ Yelp restaurant reviews**  
- Majority of reviews were **neutral (0.1–0.3 polarity)**  
- Positive segment: high satisfaction, strong repeat-customer potential  
- Negative segment: fewer in number but crucial for retention improvement  
- Helps restaurants **identify dissatisfied customers** and **enhance service quality**  

---

## 🧠 Key Findings  

| Sentiment | Polarity Range | Insights |
|------------|----------------|-----------|
| **Positive** | > 0.5 | Excellent food & service; loyal customers |
| **Neutral** | 0.1 – 0.3 | Mixed reviews; balanced feedback |
| **Negative** | < 0.1 | Complaints; opportunity for improvement |

---

## 🛠️ Technologies Used  

- **Python**  
- **TextBlob** – Sentiment Analysis  
- **Pandas / NumPy** – Data Processing  
- **K-Means (Scikit-Learn)** – Clustering  
- **Matplotlib / Seaborn** – Visualization  
- **Jupyter Notebook** – Analysis environment  

---

## 📈 Impact  

- Reduced manual review effort by **>80%**  
- Provided actionable insights for **targeted marketing and service optimization**  
- Framework adaptable for **real-time sentiment tracking** or **integration with CRM systems**  

---

## 🔍 Future Enhancements  

- Integrate **aspect-level sentiment analysis** (food, service, ambiance)  
- Deploy as an **interactive dashboard** using Streamlit or Power BI  
- Extend to **multi-language sentiment models (BERT, RoBERTa)**  
- Time-series tracking of sentiment trends per restaurant  

---

## 📚 References  

1. Sahayak, V. et al. *Sentiment Analysis on Twitter Data.* **IJIRAE**, 2015.  
2. Mehta, P. & Pandya, S. *A Review on Sentiment Analysis Methodologies, Practices and Applications.* **IJSTR**, 2020.  

---

## 👩‍💻 Author  

**Uma Pratyusha Putcha**  
Master’s in Mathematics and Statistics (Advanced Data Analytics), University of North Texas  
📧 [umaputcha9@gmail.com](mailto:umaputcha9@gmail.com)  
🔗 [GitHub Profile](https://github.com/pratyusha56)
