NYC Recycling Capture Rate Dashboard

Overview
The NYC Recycling Capture Rate Dashboard is an interactive web application that visualizes recycling performance across New York City boroughs. Users can select a borough from a dropdown menu to explore trends in average recycling capture rates over time, with the option to view the data in detailed tables.

Motivation
This project was created to analyze and communicate NYC’s recycling efficiency by borough. It enables users to understand historical trends, identify areas for improvement, and make data-driven insights about municipal recycling performance.

Key Features
	•	Interactive Borough Selection: Choose any NYC borough to view recycling trends over time.
	•	Data Visualization: Line charts displaying average recycling capture rates by year.
	•	Data Tables: View detailed yearly metrics including average capture rate.
	•	Cleaned & Processed Data: Raw municipal datasets transformed into accurate, analyzable metrics.

Tech Stack
	•	Python
	•	Streamlit for interactive web app
	•	Pandas for data cleaning, transformation, and aggregation
	•	CSV files for data storage

Data Pipeline
	1.	Load raw DSNY monthly tonnage data (monthly_tonnage_raw.csv).
	2.	Clean and filter relevant columns for analysis.
	3.	Compute recycling metrics: recyclable tons collected, total waste tons, and capture rate.
	4.	Aggregate data by borough and year to produce average capture rates.
	5.	Save cleaned and summarized data to CSV for dashboard use.

Usage
	1.	Clone the repository:

git clone <repo-url>

	2.	Install dependencies:

pip install pandas streamlit

	3.	Run the dashboard locally:

streamlit run app.py


Challenges & Learnings
	•	Managed real-world municipal datasets with missing and inconsistent data.
	•	Built a complete data pipeline from raw CSVs to an interactive dashboard.
	•	Computed domain-specific sustainability metrics (recycling capture rate) and visualized trends for multiple NYC boroughs.

Next Steps / Future Improvements
	•	Add more interactive visualizations (e.g., year-over-year comparisons).
	•	Include predictive analytics for future recycling capture rates.
	•	Deploy online via Streamlit Sharing or Heroku for public access.

About the App:
The NYC Recycling Capture Rate Dashboard is an interactive tool that tracks recycling efficiency across NYC boroughs. Built with Python and Streamlit, it allows users to explore historical trends, view data tables, and gain actionable insights into municipal recycling performance. The project demonstrates end-to-end data skills: cleaning raw datasets, computing key sustainability metrics, and presenting them in a professional, user-friendly dashboard.