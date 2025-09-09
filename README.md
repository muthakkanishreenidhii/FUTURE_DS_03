# FUTURE_DS_03
🔍 Project Overview

This project analyzes student feedback data from college events to uncover satisfaction levels, sentiment trends, and improvement areas. Using sentiment analysis (TextBlob) and visualizations (Matplotlib/Seaborn), we identify which events received the most positive responses and where improvements are needed.

The dashboard & analysis help organizers answer:

Which events had the highest ratings?

What is the overall sentiment distribution (Positive/Negative/Neutral)?

Which events need improvement based on feedback?

📂 Repository Structure
FUTURE_DS_03/
│── data/
│   ├── college_event_feedback.csv         # raw dataset
│   ├── college_event_feedback_clean.csv   # dataset with sentiment labels
│
│── notebooks/
│   └── feedback_analysis.ipynb            # Jupyter Notebook with code
│
│── reports/
│   ├── report.pdf                         # summary of findings & insights
│   ├── screenshots/                       # sentiment charts, heatmaps
│
│── images/
│   └── linkedin_post.png                  # LinkedIn proof of submission
│
│── README.md                              # documentation

📊 Dataset Description

The dataset (college_event_feedback.csv) contains survey responses with:

Student_ID → Unique identifier for each student

Event_Name → Event attended (Tech Fest, Cultural Night, etc.)

Rating → Numeric satisfaction score (1–5)

Feedback_Text → Open-ended student feedback

Suggestions → Student suggestions for improvement

🛠️ Tools & Libraries

Python → Data analysis

pandas → Data cleaning

TextBlob → Sentiment analysis

matplotlib & seaborn → Visualizations

Jupyter Notebook / Google Colab → Implementation

🧮 Steps Performed

Data Cleaning

Removed duplicates & empty feedbacks

Kept only relevant columns (Event_Name, Rating, Feedback_Text)

Sentiment Analysis

Used TextBlob polarity score (–1 to +1)

Classified feedback as:

Positive (score > 0.05)

Negative (score < –0.05)

Neutral (otherwise)

Visualizations

Pie Chart → Sentiment distribution

Bar Chart → Sentiment counts by Event

Heatmap → Average rating per Event

Exported Clean Dataset

Added new columns: Sentiment_Score, Sentiment_Label

Saved as college_event_feedback_clean.csv

📖 Insights & Recommendations

Most events had Positive feedback, but some events showed higher Neutral/Negative sentiment, especially regarding logistics.

Tech Fest had the highest ratings, while Sports Day had more mixed responses.

Common improvement suggestions included better scheduling, improved food quality, and more guest speakers.

Recommendations:

Focus improvements on event management & scheduling.

Enhance facilities (food, seating, logistics).

Continue successful practices from Tech Fest & Hackathon.

🎯 Deliverables

✅ Cleaned dataset with Sentiment labels

✅ Jupyter Notebook with code

✅ PDF report with charts & insights

✅ LinkedIn proof of submission
