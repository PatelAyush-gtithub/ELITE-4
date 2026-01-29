# 🏋️‍♂️ AI Fitness & Diet Assistant

An intelligent, interactive web application that acts as a personalized **Expert Fitness Trainer**. Built with **Streamlit** and powered by **Google Gemini AI**, this tool generates customized workout routines, diet charts, and health metrics based on individual user profiles.

---

## 📝 GitHub Profile Summary
**Project Title:** AI Fitness & Diet Assistant  
**Core Model:** Powered by **Gemini 1.5 Flash** (via the `google-generativeai` SDK).  
**Short Bio:** An end-to-end Fitness Coach app that transforms user biometrics into actionable health data. It leverages Large Language Models (LLMs) to provide tiered workout plans and tailored nutrition schedules, showcasing expertise in **Python**, **API Integration**, and **Data Visualization**.

---

## 🚀 Features

* **Custom User Profiling:** Input weight, height, age, activity levels, and dietary preferences.
* **AI-Powered Plans:** Generates structured workout routines for **Beginner**, **Intermediate**, and **Advanced** levels.
* **Nutrition Tracking:** Provides a detailed Markdown table for daily meals (Breakfast, Lunch, Dinner, Snacks).
* **Health Metrics:** Calculates BMI, BMR, TDEE, and daily Macro requirements.
* **Real-time Q&A:** A dedicated section to ask the AI specific fitness or nutrition questions.
* **Dynamic Model Routing:** Automatically detects and uses the best available Gemini model (Pro or Flash) to ensure reliability.

---

## 🛠️ Tech Stack & Extensions

* **Frontend Framework:** [Streamlit](https://streamlit.io/) (UI/UX)
* **AI Model:** [Google Gemini API](https://ai.google.dev/) (LLM reasoning)
* **Language:** Python 3.9+
* **Core Libraries:** * `google-generativeai`: Content generation.
    * `pandas`: Data manipulation.
    * `matplotlib`: Data visualization.

---

## 📂 Project Structure
```text
.
├── app.py                # Main Streamlit application code
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation (this file)
