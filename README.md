![Healthcare Analytics](https://img.shields.io/badge/Domain-Healthcare-red)
![Tableau](https://img.shields.io/badge/Tool-Tableau-blue)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

# Patient Experience Workflow Optimization Dashboard
https://public.tableau.com/authoring/PatientExperienceWorkflowOptimization/Dashboard1#1

Tableau dashboard analyzing healthcare appointment no-shows to identify patterns in scheduling, patient behavior, and reminder effectiveness.

The goal of this project is to improve appointment attendance by reducing the appointment no-show rate by 10% over a 6 month time period. To meet this goal, appointment lead times must be reduced and improved targeting of reminder interventions for high-risk patient groups must be implemented. 

# Dataset
- Medical Appointment No Show Dataset from Kaggle
- Over 110,000 observations in dataset
- Ages of the patients range from under 1 years old to 78 years old

# Key Insights
- No-show rate increases as appointment lead time increases, indicating scheduling inefficiencies. 
- Recommend reducing scheduling lead times by adjusting staffing levels.
- Patients who received SMS reminders show higher no-show rates. 
- Recommend adjusting the timing, frequency, and/or content of the SMS reminder or use live phone calls for reminders to high-risk groups. 
- Younger patients, with longer lead times, show a higher risk for missing appointments (39% no-show rate).
- Recommend targeted scheduling and reminder strategies. 


# New Challenges
- There are numerous potential factors as to why patients are missing scheduled appointments. This includes scheduling practices, patient demographics, and engagement strategies. A key challenge was designing a dashboard that balanced depth and clarity and still captured the most important insights, without overwhelming the audience. 


# If I had more time
- Conduct further analysis to include deeper segmentation of the patient population, such as exploring no-show patterns by neighborhood or reason for the appointment. These additional analyses could drive decisions pertaining to targeted interventions that would further reduce no-show rates and help meet the goal of reducing no-show rates by 10%. 

# Data Preparation
- Imported the dataset using CSV UTF-8 encoding to ensure proper character representation and maintain data integrity across systems
- Corrected spelling inconsistencies in column names to improve clarity and standardization
- Validated and standardized date-time fields to enable accurate time-based analysis
- Created calculated fields such as no-show rate, lead time, age group, weekday, and SMS group to transform raw data into meaningful features
- Reviewed the dataset for missing or null values using filtering and validation techniques to ensure data completeness and reliable analysis

# Analytical Techniques
- Exploratory analysis to identify patterns in patient no-show behavior
- Calculated key metrics such as no-show rate and average lead time to support patient behavior analysis 
- Comparative analysis with no-show rates across factors like weekday, lead time, age group, and SMS reminders
- Segmentation to better understand trends
# Data Visualization
- Tableau worksheets with color-coded bar charts, with the lightest color representing the lowest no-show rate
- Interactive Tableau dashboard with filters, to represent key findings related to patient no-show behavior and increase audience engagement
  
# Skills
- Data quality validation
- Data visualization
- Patient behavior analysis  
- Healthcare analytics

