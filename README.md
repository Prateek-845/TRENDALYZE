# 🌟 TRENDALYZE: Smart E-Commerce Recommender System 🔍🛒

**TRENDALYZE** is a content-based recommendation system built using Flask, MySQL, HTML/CSS (Bootstrap), and Machine Learning techniques like TF-IDF and Cosine Similarity. It recommends trending and relevant products to users, with a polished, interactive frontend.

---

## 📸 Live Preview

> 🎬 Screenshots of the working project are available in the `Demo Images/` folder.

---

## ✨ Features

✅ User-friendly interface with animated video background  
✅ Real-time user authentication (Sign Up / Sign In)  
✅ Displays top **Trending Products**  
✅ Product detail modal with **image, price, brand, reviews, rating**  
✅ **Smart product recommendations** based on TF-IDF & Cosine Similarity  
✅ Theme customization: Light/Dark Mode  
✅ Zoom In/Out settings  
✅ Dynamic UI with modals (Bootstrap 4)

---

## 🧠 How It Works

**Recommendation Logic**:

- Each product is tagged with keywords in a `Tags` column.
- TF-IDF vectorization is used to transform tags into numerical vectors.
- Cosine similarity is applied to find products most similar to the searched one.
- Top N similar products are shown as recommendations.

---

## 🛠️ Tech Stack

| Layer       | Technology Used                           |
| ----------- | ----------------------------------------- |
| 🧠 ML Logic | `Pandas`, `Scikit-learn (TF-IDF, Cosine)` |
| 🌐 Backend  | `Flask`, `SQLAlchemy`, `MySQL`            |
| 🎨 Frontend | `HTML`, `CSS`, `Bootstrap 4`, `jQuery`    |
| 🗃️ Database | `phpMyAdmin`, `MySQL`                     |

---

## 🚀 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/TRENDALYZE.git
cd TRENDALYZE
```
