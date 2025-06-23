# Indian-Railway-analytics-project

Indian Railways Ticket and Train Schedule Analysis

🔍 Overview:

*This is an end-to-end data analysis project on the Indian Railways using two datasets:

*Train schedule data (station-wise timing & distance)

*Ticket confirmation data (confirmation status, class, type, quota, etc.)


*The goal is to extract business insights and visualize trends to help optimize rail service efficiency and ticket confirmation prediction.


---

📁 Datasets Used:

1. Train Schedule Dataset (isl_wise_train_detail_03082015_v1.csv)

*Contains train numbers, station stops, arrival/departure times, distance, etc.



2. Ticket Confirmation Dataset (Railway Ticket Confirmation.csv)

*Includes PNR number, train class, booking date, quota, train type, and confirmation status.





---

🧪 Tools & Technologies:

Task	Tool

*Data cleaning & EDA	Python (Pandas, NumPy)
*Visualization	Matplotlib, Seaborn
*Environment	Google Colab
*File Handling	CSV files (local or from Kaggle)



---

🧹 Steps Performed:

1. Data Cleaning

*Renamed columns, removed whitespaces

*Converted date columns to datetime format

*Handled missing & non-numeric data


2. Exploratory Data Analysis (EDA)

*Analyzed ticket confirmation rate

*Studied most popular classes and train types

*Explored distance distribution between train stops

*Identified top 10 busiest stations


3. Visualizations

*📊 Countplots for confirmation status, class of travel, and train types

*📈 Histogram of station-wise distances

*📍 Bar chart of top 10 busiest stations



---

📊 Key Insights

*✅ Most tickets are confirmed; a smaller share are RAC or waitlisted.

*🛌 Sleeper (SL) and AC (3AC) are the most common travel classes.

*🚄 Express and Superfast trains dominate the ticket data.

*🏙️ Top stations include major cities like Delhi, Mumbai, and Vijayawada.

*🧭 The average inter-station distance is approximately 648 km.



---

📁 Project Structure

📦 indian-railways-analysis
├── 📄 isl_wise_train_detail_03082015_v1.csv
├── 📄 Railway Ticket Confirmation.csv
├── 📓 Indian_Railways_Analysis.ipynb
├── 📊 visualizations/
│   ├── confirmation_status.png
│   ├── train_type_distribution.png
│   └── ...
└── 📄 README.md


---

💡 What I Learned

*How to clean and manipulate real-world railway datasets

*Visualization best practices using Seaborn & Matplotlib

*Gained experience structuring end-to-end data projects

*Framed clear, actionable insights from messy public data



---

🔗 Future Improvements

*Integrate real-time train APIs for live data

*Build a simple ticket confirmation prediction model

*Deploy visualizations in an interactive dashboard (e.g., Plotly Dash or Tableau)



---

📬 Contact

> Muthuraj
📧 [muthurajp00@gmail.com]
