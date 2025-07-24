# 🏨 Booking.com Review-Based Sentiment Modelling

![Project Banner](assets/A_banner_displayed_at_the_top_of_the_image_present.png)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![NLP](https://img.shields.io/badge/Technique-NLP-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![SPSS](https://img.shields.io/badge/Tool-Orange-lightgrey)

---

## 📘 Overview

This project explores 1,500 hotel reviews from Booking.com to extract insights into customer sentiment. Using Natural Language Processing (NLP) techniques like **sentiment scoring**, **topic modeling (LDA)**, and **geospatial analysis**, we uncover themes that impact guest satisfaction and provide actionable business recommendations.

---

## 📊 Dataset Summary

- 📍 **Hotel:** La Veranda Hotel, Larnaca, Cyprus  
- 🧾 **Reviews:** 1,500 guest reviews from Booking.com  
- 🗂️ **Source:** [Kaggle – Booking.com Hotel Reviews](https://www.kaggle.com/datasets/michelhatab/hotel-reviews-bookingcom/data)

---

## 🔍 Analytical Workflow

### ✅ 1. Sentiment Analysis

- Compound sentiment scores calculated using NLP tools
- Majority of reviews are strongly positive  
- Negative sentiments correlate with cleanliness, noise, and check-in issues

![Sentiment Distribution](assets/image_3.png)

---

### 🧠 2. Topic Modeling (LDA)

Extracted themes using LDA (Latent Dirichlet Allocation):

| Theme | Positive Keywords | Negative Keywords |
|-------|-------------------|-------------------|
| Service | staff, friendly, helpful | rude, slow |
| Room | clean, spacious, quiet | dirty, small, noisy |

![Positive Topics](assets/image_21.png)
![Negative Topics](assets/image_20.png)

---

### 🌍 3. Geospatial & Cultural Analysis

- Guests from Europe/North America showed high satisfaction
- Certain cultural groups expressed concerns around amenities or communication

![Geographic Map](assets/image_25.png)

---

## 🎯 Business Impact & Recommendations

| Area | Recommendation |
|------|----------------|
| Cleanliness | More frequent audits & cleaning |
| Noise | Soundproof rooms and night policy |
| Check-in | Add kiosks and streamline process |
| Marketing | Highlight top positives in listings |
| Cultural Fit | Offer multilingual check-in info |

---

## 🛠 Tools & Technologies

- **Python**: NLTK, spaCy, Seaborn
- **Orange**: Visual workflow for NLP & LDA
- **Geopy**: Geo-tagging countries
- **Matplotlib**: Custom plots & heatmaps

---

## 📁 Repository Structure

```
📦 Review-Based-Sentiment-Modelling/
├── data/
│   └── booking_reviews.csv
├── assets/
│   ├── A_banner_displayed_at_the_top_of_the_image_present.png
│   ├── image_3.png
│   ├── image_20.png
│   ├── image_21.png
│   └── image_25.png
├── notebooks/
│   └── analysis_workflow.ipynb
├── README.md
```

---

## 👤 Author

**Ramanav Bezborah**  
🎓 International MBA – Business Analytics  
📫 [LinkedIn](#) • [Email](#)

---

## 📚 References

- [Booking.com Reviews Dataset – Kaggle](https://www.kaggle.com/datasets/michelhatab/hotel-reviews-bookingcom/data)

---

*This project was completed as part of the INFS 5131 curriculum at the University of South Australia.*
