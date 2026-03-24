# 🇧🇩 Bangla Sentiment Analyzer

**Analyzing Public Sentiment during the July 2024 Student-People Mass Uprising using Bangla NLP**

## 📋 Project Overview
I built a machine learning model that can read Bangla comments from Facebook, YouTube, and Twitter and tell whether the comment is **Positive**, **Negative**, or **Neutral**.

- **Dataset**: 4,200 real Bangla comments from the 2024 July Uprising  
- **Model Accuracy**: **80.24%**  
- **Live Demo**: Interactive web app using Gradio

This project shows my ability to work with **low-resource language (Bangla)** and real social issues — something I can proudly talk about in my scholarship applications.

## 🛠️ Technologies Used
- Python 3.11
- scikit-learn (for model)
- pandas, matplotlib, seaborn
- NLTK (text processing)
- Gradio (live web demo)
- Joblib (saving model)

## 📁 Folder Structure

bangla-sentiment-analysis/
├── README.md
├── requirements.txt
├── bangla_sentiment_model.ipynb     ← Main notebook
├── models/                          ← Saved model files
└── student_people_mass_uprising_public_sentiments_dataset/   ← Original data
text


## 🚀 How to Run This Project

1. Clone or download this repository
2. Open Terminal and go inside the folder
3. Activate environment:
   ```bash
   conda activate ml-beginner
## Install packages:Bash
   pip install -r requirements.txt
## Open Jupyter Notebook:
   jupyter notebook
## Open bangla_sentiment_model.ipynb and run the last cell to see the live demo.

📊 Results

Accuracy: 80.24%
Best class: Neutral (F1 = 0.89)
Live Gradio Demo available

💡 Why This Project Matters

Works with Bangla language (very few tools exist for Bangla)
Uses real data from a historic event in Bangladesh
Shows practical AI skills for social good


👨‍💻 About Me:
Tahsin Ahmed Rafi|
4th Year CSE Student, Premier University, Chattogram
Passionate about AI/ML for low-resource languages and social impact.

Made with ❤️ for Bangla NLP
