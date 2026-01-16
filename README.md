# medicines-side-effects-analysis

Analysis of Medicines and Their Side Effects
Project Overview
This project analyzes patterns in medicines and their reported side effects to better understand risk distribution, 
therapeutic impact, and differences between habit-forming and non-habit-forming drugs.
Using SQL for data preparation and Tableau for visualization, the project follows the Google Data Analytics 
six-step framework to transform raw pharmaceutical data into clear, actionable insights.
________________________________________
Business Questions
•	Which side effects are most commonly reported across medicines?
•	Which therapeutic categories carry the highest side-effect burden?
•	Do habit-forming medicines differ from non-habit-forming ones in their side-effect profiles?
•	Which individual medicines are associated with the largest number of side effects?
________________________________________
Dataset
•	Size: 248,000+ medicines

•	Content:
o	Medicine names and IDs
o	Therapeutic, chemical, and action classes
o	Habit-forming indicator
o	Uses and substitutes
o	Up to 42 side-effect fields per medicine

•	Transformation:
o	Side-effect columns were normalized into a long format, 
creating 1.6M+ medicine–side-effect records for accurate analysis.
________________________________________
Tools & Technologies
•	PostgreSQL — data cleaning, normalization, and analysis
•	SQL — transformations and aggregations
•	Tableau Public — dashboard and visual storytelling
•	GitHub — version control and project sharing
________________________________________
Methodology (Google Data Analytics Framework)
1.	Ask — Defined business questions around medicine safety and risk patterns.
2.	Prepare — Reviewed dataset structure, size, and key fields.
3.	Process — Normalized wide side-effect columns into an analysis-ready table; optimized performance with indexing.
4.	Analyze — Explored side-effect frequency, therapeutic category burden, habit-forming comparisons, and high-impact medicines.
5.	Share — Communicated results via a Tableau dashboard and a structured case study report.
6.	Act — Translated findings into recommendations for safer prescribing and better patient communication.
________________________________________
Key Analyses
•	Most common side effects across all medicines
•	Side-effect burden by therapeutic class
•	Habit-forming vs non-habit-forming side-effect profiles
•	Differences in side effects between the two groups
•	Medicines with the highest number of side effects
(Detailed insights and recommendations are presented in the case study PDF report.)
________________________________________
Tableau Dashboard
A public dashboard visualizes the core findings, including:
•	Top side effects overall
•	Side-effect burden by therapeutic category
•	Comparison between habit-forming and non-habit-forming medicines
Dashboard link: https://public.tableau.com/views/MedicinesandSideEffectsDataAnalysis/AnalysisofMedicinesandTheirSideEffects?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
________________________________________
Case Study PDF
Report covering:
•	Project overview
•	Methodology
•	Data preparation
•	Analysis
•	Insights & recommendations
•	Conclusion and next steps
________________________________________
Key Takeaways
•	Side effects are not randomly distributed — they cluster by therapeutic category and risk profile.
•	A small number of categories account for a disproportionately high side-effect burden.
•	Habit-forming medicines show distinct neurological side-effect patterns compared to non-habit-forming drugs.
•	Certain medicines carry an exceptionally high side-effect load, making them important targets for closer monitoring.
________________________________________
Next Steps
•	Integrate dosage and severity data to refine risk assessment.
•	Add time-based analysis to explore trends.
•	Apply predictive modeling to anticipate side-effect likelihood.
•	Expand the dashboard with interactive filters for deeper exploration.
________________________________________
Author
Ioannis Karydis
Junior Data Analyst
Location:  Greece
