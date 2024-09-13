Vanguard A/B Test Project
Project Overview
This project involves analysing the results of an A/B test conducted by Vanguard, a US-based investment management company. The test aimed to evaluate if a redesigned user interface (UI), with added in-context prompts, improves user experience and leads to higher process completion rates compared to the old interface. The analysis includes data exploration, performance metrics evaluation, hypothesis testing, and visualization

Project Structure
1.Data Exploration and Cleaning
•	Three datasets were used:
o	Client Profiles (df_final_demo)
o	Digital Footprints (df_final_web_data)
o	Experiment Roster (df_final_experiment_clients)
•	The datasets were merged and cleaned to ensure data quality for analysis.
2.Key Performance Metrics (KPIs)
•	Completion Rate: Analysed for both Control and Test groups.
•	Time Spent on Each Step: Measured by comparing timestamps between steps.
•	Error Rates: Instances of users going backward through steps were recorded as potential errors.
 3.Hypothesis Testing
•	Mean Completion time for each step.
•	Mean Completion time by age.
•	Mean Completion time by Gender.

4.Experiment Evaluation
•	The experiment was overall well-structured as it had equal number of steps for each group.
•	Gender groups were equally represented in Test and Control.
•	Clients were not equally distributed into Test and Control.

•	3 months is a short amount of time to have a proper experimental evaluation.

5. Visualizations
•	Interactive dashboards were created using Tableau to display key insights about user behaviour, demographics and KPI outcomes.

Deliverables
•	Code: Analysis performed using Python and Jupyter notebooks.
•	Tableau Dashboard: Visual representation of key findings.
•	Presentation: Insights and findings presented using Google Slides.

Data Sources
1.	Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients.
2.	Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2. It’s recommended to merge these two files prior to a comprehensive data analysis.
3.	Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment.
Conclusion
•	The Error Rate and Mean Completion Time were higher in the Test Group but the Completion Time should be prioritized. There was no statistical difference in mean time spent in each step. The experiment was well structured the clients were divided into Test and Control group with more clients (30 thousand) in Test Group. Gender was equally represented in each group. Age distribution was very varying in both groups. Experiment time should be extended to at least 6 months for proper UI evaluation

