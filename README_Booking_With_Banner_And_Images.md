# 🏨 Booking.com Hotel Review Sentiment Analysis

![Project Banner](A_banner_displayed_at_the_top_of_the_image_present.png)

## 📘 Project Overview

This project analyzes 1,500 hotel reviews from Booking.com to uncover insights that can enhance hotel management and marketing strategies. By applying **sentiment analysis**, **topic modeling**, and **geographic filtering**, we identify what guests love or dislike, using real textual feedback and metadata.

---

## 🎯 Business Questions

- ✅ What factors contribute to **positive guest experiences**?
- 🚫 What issues are highlighted in **negative reviews**?
- 🌍 Are there **geographic or cultural trends** in satisfaction?
- 🤝 How can insights guide **marketing and operations**?

---

## 📊 Dataset Description

- **Source:** [Kaggle – Booking.com Hotel Reviews](https://www.kaggle.com/datasets/michelhatab/hotel-reviews-bookingcom/data)
- **Hotel:** La Veranda Hotel, Larnaca, Cyprus
- **Size:** 1,500 reviews during the first year of operation

### 🔧 Preprocessing Steps

- 🔄 Combined review columns into one
- 🧼 Cleaned text (punctuation, stopwords, case)
- 🗓️ Standardized date formats
- 🌐 Geocoded guest countries

---

## 🧠 Key Analyses & Findings

### 1. 📈 Sentiment Analysis

- ✅ **Positive reviews dominate**: Staff, cleanliness, location
- ⚖️ **Neutral sentiment** also common (e.g., compound score ~0)
- ❌ **Negative reviews** are rare but highlight:
  - Dirty bathrooms
  - Noise issues
  - Slow check-in

![Sentiment Distribution](extracted_images/image_3.png)

📌 *Business Impact:* Improve cleanliness, reduce noise, streamline check-in—especially during peak seasons.

---

### 2. 🗂️ Topic Modeling (LDA)

#### Positive Themes
- Keywords: “friendly staff”, “spacious room”, “great location”

#### Negative Themes
- Keywords: “dirty bathroom”, “slow service”, “noisy”

![Positive Themes](extracted_images/image_21.png)
![Negative Themes](extracted_images/image_20.png)

📌 *Business Impact:* 
- Emphasize strong points in marketing.
- Operational focus on weak spots.

---

### 3. 🌍 Geographic & Cultural Trends

- 📈 **High ratings**: Europe & North America
- ⚠️ **Lower ratings**: Guests with cultural/language mismatch
- 🗺️ Sentiment maps and corpus viewers filtered reviews by country

![Geographic Insights](extracted_images/image_25.png)

📌 *Business Impact:* Personalize service for underrepresented guest groups with culturally aware training and multilingual content.

---

## ✅ Business Recommendations

| Area              | Recommendation                                 |
|-------------------|------------------------------------------------|
| 🧼 Cleanliness     | Increase frequency of room audits             |
| 🔕 Noise Control   | Improve soundproofing, especially at night     |
| ⏳ Check-in Speed  | Introduce self check-in options                |
| 🌐 Cultural Fit    | Train staff, offer multilingual materials      |
| ⭐ Marketing       | Highlight staff, cleanliness, location         |

---

## 🛠️ Tools & Technologies

- 🐍 Python: NLTK, spaCy (sentiment & text cleaning)
- 📦 Orange: Topic modeling, filtering, visualization
- 📊 Matplotlib, Seaborn: Graphs and heatmaps
- 🌍 Geopy: Coordinate embedding from guest countries

---

## 📁 Project Structure

```
booking-review-analysis/
├── data/
│   └── booking_reviews.csv
├── notebooks/
│   └── sentiment_topic_analysis.ipynb
├── extracted_images/
│   └── image_*.png
├── README.md
```

---

## 👤 Author

**Ramanav Bezborah**  
🎓 International MBA – Business Analytics  
📧 [LinkedIn](#) • [Email](#)

---

## 📚 References

- [Kaggle: Hotel Reviews Booking.com](https://www.kaggle.com/datasets/michelhatab/hotel-reviews-bookingcom/data)

---

*All data used is publicly available and anonymized. This project was completed as part of the INFS 5131 course — Advanced Machine Learning Project.*
