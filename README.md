# 🎓 Student Study Habit Recommender

StudyTrack AI is a Python-based system that analyzes student study behavior and automatically generates personalized study habit recommendations to support better learning outcomes.

---

## Features

- Analyzes student study behavior data
- Groups students using clustering techniques
- Automatically generates personalized study recommendations
- Simple and interpretable rule-based logic
- End-to-end automated workflow

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Libraries:** Pandas, Scikit-learn, Matplotlib  
- **Techniques:**
  - Exploratory Data Analysis (EDA)
  - Feature Scaling
  - KMeans Clustering
  - Rule-Based Recommendation System

---

## 📂 Project Structure

Student-Study-Habit-Recommender/
│
├── recommendation_engine.py     # Rule-based recommendation logic
├── main.py                      # Script to generate recommendations
├── Preprocess&Model.ipynb       # Data preprocessing & clustering
├── output/
│   ├── processed_for_recommendation.csv
│   └── student_recommendations.csv
└── README.md

---

## ▶️ How to Run

1. Run `Preprocess&Model.ipynb` to preprocess data and generate clusters.
2. Run the following command in the terminal:
   ```bash
   python main.py
3. Check the output file:
   `output/student_recommendations.csv` 
