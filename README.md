# 💤 SleepScore – Predict Sleep Quality with SVR

A machine learning project that uses Support Vector Regression (SVR) to predict a person's sleep quality based on their daily habits like screen time, caffeine intake, exercise, stress level, and more.

## 🌟 Overview

Sleep is a pillar of health, yet so many of us struggle with getting quality rest. This project aims to help users understand how their daily choices influence their sleep, and provides a predictive model that can guide better habits.

---

## 🧠 Problem Statement

Can we predict a user's sleep quality (score out of 100) based on lifestyle factors such as screen time, hydration, exercise, caffeine intake, stress, and bedtime?

This project uses **Support Vector Regression (SVR)** to model the complex, non-linear relationships between habits and sleep quality.

---

## 🎯 Project Goals

- Build a predictive model using SVR
- Analyze lifestyle factors influencing sleep
- Provide meaningful visualizations
- Optionally deploy a simple dashboard with Streamlit

---

## 🗂️ Features Used

- `hours_of_sleep` – Total sleep duration in hours
- `screen_time` – Screen time before bed
- `stress_level` – Self-reported stress score (0–10)
- `caffeine_intake` – Daily caffeine (cups)
- `exercise_minutes` – Minutes of exercise
- `hydration_level` – Liters of water consumed
- `bedtime_hour` – Time user went to sleep (e.g. 22.5 = 10:30 PM)
- `mood_rating` – Overall end-of-day mood (1–5)

---

## 📊 Output

- `sleep_quality_score` (0–100)
- Plots:
  - Actual vs Predicted Scores
  - Feature Correlation Heatmap
  - Distribution of Features

---

## 🔧 How to Run

1. Clone this repo  
```bash
git clone https://github.com/yourusername/SleepScore-SVR.git
cd SleepScore-SVR
