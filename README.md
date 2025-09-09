📊 Student Feedback Analysis – Power BI & Python Project

This project is part of my Data Science & Analytics Internship (Task 3) with Future Interns.
The aim was to analyze student event & course feedback (ratings + comments) and turn it into actionable insights that can help improve teaching practices, course structure, and overall campus experience.

🚀 Project Overview

Processed and analyzed 1,001 student feedback responses.

Converted raw survey data into clean, structured datasets.

Identified top strengths (subject expertise, concept clarity).

Pinpointed weak areas (assignment clarity, doubt-solving, relevance).

Built visual insights: histograms, boxplots, averages, and heatmaps.

Generated recommendations for course improvements.

📂 Dataset

Original File: student_feedback.csv

Cleaned Outputs:

cleaned_feedback.csv

cleaned_feedback.xlsx

Aggregated Results:

question_averages.csv

overall_rating_distribution.csv

correlation_matrix.csv

Columns include:
✔ Well versed with the subject
✔ Explains concepts clearly
✔ Use of presentations
✔ Assignment difficulty
✔ Doubt-solving support
✔ Course structuring
✔ Relevance & recommendation

🛠 Tools & Libraries

Python (Colab / Jupyter Notebook)

pandas → Data cleaning & stats

matplotlib / seaborn → Charts & plots

wordcloud → Text feedback visuals

nltk / VADER / TextBlob → Sentiment analysis (optional)

📈 Key Insights

Average overall rating: 5.92 / 10

Top-rated:

Subject knowledge → 7.50

Concept clarity → 6.08

Lowest-rated:

Doubt-solving support → 5.47

Assignment clarity → 5.43

Course relevance → 5.60

📊 Rating Distribution

High (8–10): 32.4%

Mid (5–7): 36.2%

Low (1–4): 31.4%

💡 Recommendations

Simplify assignments & improve clarity.

Provide more doubt-solving support.

Reinforce strengths: subject expertise & concept clarity.

Introduce interactive teaching methods.

Collect & analyze feedback monthly to track improvements.

📌 Deliverables

📂 Cleaned Datasets → cleaned_feedback.csv, cleaned_feedback.xlsx

📊 Aggregated Results → question_averages.csv, overall_rating_distribution.csv, correlation_matrix.csv

🖼 Visuals → hist_per_question.png, avg_by_question.png, boxplots_by_question.png, correlation_heatmap.png

👩‍💻 How to Run

Clone the repo or open in Google Colab / Jupyter Notebook.

Install requirements:

pip install pandas matplotlib seaborn nltk vaderSentiment wordcloud textblob openpyxl


Upload student_feedback.csv.

Run notebook cells → generates cleaned files + visualizations.

🎓 Learning Outcomes

Data cleaning & preprocessing

Statistical survey analysis

Visualization (bar plots, boxplots, heatmaps)

Sentiment analysis for text comments

Translating data into recommendations

✨ This project shows how data science can give students a stronger voice — by turning feedback into real improvements for academic life.
