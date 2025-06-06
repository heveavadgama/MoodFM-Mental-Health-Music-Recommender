# 🎧 MoodFM: Mental Health Music Recommender

> An intelligent and interactive ML-powered app that recommends music genres and real-world songs based on your mental health condition and its severity.  
> Built with 💡 Pandas, 🎨 Seaborn, and 📊 Streamlit.

---

## 🔗 Live App

👉 [Click here to try MoodFM on Streamlit]([https://YOUR-STREAMLIT-APP-LINK](https://moodfm-mental-health-music-recommender-ln6ijrp96rssnfogsp4mix.streamlit.app/))

---

## 🧠 Motivation

Music can be a powerful therapy. This project aims to explore the relationship between mental health and music preferences.  
It helps users discover genres and songs that may support their emotional well-being.

---

## 📁 Dataset

- `MentaLHealthMusicRec.csv`: Contains 736 responses with features like:
  - Demographics (age, platform)
  - Music habits (hours/day, while working, favorite genre)
  - Genre listening frequencies
  - Mental health scores (Anxiety, Depression, Insomnia, OCD)

- `genre_example_songs.csv`: Manually curated examples of songs for each genre.

---

## ⚙️ Features

✅ Select your mental condition(s) and severity  
✅ See trends between music preferences and mental states  
✅ Get recommended genres and real-world songs  
✅ Clean and interactive Streamlit UI with charts & insights

---

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Streamlit
- Jupyter Notebooks (for analysis & prep)

---

## 📊 How it Works

1. Load and clean mental health + music preference data.
2. Encode genre listening frequencies numerically (`Never`, `Rarely`, `Sometimes`, `Very frequently`).
3. Categorize mental conditions by severity (`None`, `Mild`, `Moderate`, `Severe`).
4. Visualize music trends across mental health levels.
5. Recommend genres & songs based on average frequency scores for the selected condition and severity.

---

