📊 Case Study: Exploratory Data Analysis (EDA) on Gmail Takeout Dataset

📌 Project Overview

This project is an academic case study carried out as part of my engineering coursework. The goal was to perform Exploratory Data Analysis (EDA) on personal Gmail data (exported via Google Takeout) to understand email communication patterns and gain hands-on experience with real-world unstructured data.

🎯 Objectives

Import and process raw Gmail .mbox data
Clean and transform email metadata (subject, sender, date, labels, threads)
Apply descriptive statistics and explore data distributions
Engineer new features such as:
  Day of week of emails
  Time of day of emails
  Yearly communication trends
  Visualize communication patterns with charts and word clouds

🛠️ Tools & Libraries

  Python
  Pandas – Data manipulation
  Matplotlib & Seaborn – Data visualization
  WordCloud – Text analysis and visualization
  Mailbox, CSV – Data extraction

📂 Dataset

  Data source: Google Takeout (Gmail Export)
  Format: .mbox file converted into CSV

Fields extracted:

  subject
  from
  date
  to (dropped later in preprocessing)
  label
  thread

⚠️ Note: The dataset contains personal email metadata only and is not shared publicly.

🔑 Key Steps

  Load dataset – Convert .mbox to .csv
  Data cleaning – Handle missing values, remove unused columns
  Feature engineering – Extract day, time, and year from email timestamps
  Descriptive statistics – Summarize counts and distributions
  Visualization –
      Bar charts for emails by day of week
      Comparison of sent vs. received emails
      Scatter plots for email patterns over time
      Word cloud of email subjects

📊 Sample Visualizations

  Emails by Day of Week
  Sent vs. Received Emails
  Scatter Plot (Time of Day vs Year)
  Word Cloud of Subjects

*(Insert screenshots here, e.g., ![Word Cloud](images/wordcloud.png))

📈 Key Insights

  Clear differences between sent and received email activity
  Higher communication frequency on specific days of the week
  Word cloud highlighted commonly used subject line terms
  Strong patterns visible across time-of-day and year

📚 Learnings

  Handling unstructured datasets like email metadata
  Converting .mbox files to structured CSV for analysis
  Importance of feature engineering in time-series data
  Enhancing storytelling through visualizations

🔗 Project Links

📂 Full project code:
https://github.com/Muhammad-UmarFarooq/Projects

📄 LinkedIn Post: 
https://www.linkedin.com/posts/muhammadumarfarooq584_datascience-eda-python-activity-7371908944979464192-Nx9f?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFXuX_EBav7rjCjefqZng-3_hKzLV1OCHVk
