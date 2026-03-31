# 🚀 AI Life Assistant for Students

## Overview
This project builds an **AI-powered student wellness system** combining **Prolog logic programming** and **Machine Learning** to analyze daily routines, detect procrastination patterns, assess mental health risks (stress/burnout), predict wellness scores, and generate personalized study plans. The interactive Colab dashboard provides real-time analysis with live charts.

**Fundamentals of AI/ML Course Project (BYOP)** - Implements CO1-CO5 syllabus concepts.

## Features
- 🧠 **Procrastination Detector** - Prolog rules identify risky study patterns
- 😰 **Mental Health Analyzer** - Stress & burnout risk assessment via knowledge representation
- 🏆 **Wellness Score Predictor** - ML model (Linear Regression) gives 0-10 score
- 📱 **Interactive Dashboard** - Sliders + real-time analysis with ipywidgets
- 📊 **Live Visualizations** - Bar charts + pie charts showing routine balance
- 📚 **Smart Study Planner** - Personalized 9AM-5PM schedules with break recommendations

## Technologies / Tools Used
- Python 3 + Google Colab
- **SWI-Prolog** + pyswip (AI logic programming)
- **scikit-learn** (LinearRegression for wellness prediction)
- **ipywidgets** (interactive UI)
- **Matplotlib** (live charts)
- **pandas, NumPy** (data processing)

## Steps to Install & Run the Project
1. Open `ai_life_assistant.ipynb` in [Google Colab](https://colab.research.google.com)
2. **Run 4 cells sequentially** (top to bottom):
   - **Cell 1**: Install SWI-Prolog + dependencies (~30s)
   - **Cell 2**: Load Prolog KB + train ML model (~2s)
   - **Cell 3**: (Streamlit backup - skip)
   - **Cell 4**: Launch interactive dashboard
3. 🎉 **Dashboard appears** - adjust sliders and click **ANALYZE**!

## Screenshots
# 1. Interface
![Basic Interface](https://github.com/user-attachments/assets/f4d1073e-88a5-49bd-bed5-c7c22ba554a6)

# 2. Charts
![Study Plan Charts](https://github.com/user-attachments/assets/0ef830e4-59b3-4f57-b737-1235157892d1)
