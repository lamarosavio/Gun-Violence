# Gun-Violence
Gun Violence in USA-Analysis

Career Foundry project using Python and Tableau to analyze historical gun violence data in the USA from wildfire data in Oregon from January 2013 and March 2018. It includes details such as city & state, number killed, number injured, number of participants, age groups associated, gender, and local government information. The dataset was sourced from Kaggle. This information is fictional information and contains all recorded gun violence between the aforementioned dates. According to the user, the goal of this is ‘make it easier for data scientists and statisticians to study gun violence and make informed predictions about future trends’. 

Project Overview

Gun violence remains a critical public safety issue in the United States, with thousands of incidents reported across the country. This project analyzes gun violence data from January 2013 to March 2018, encompassing 239,677 recorded incidents. The dataset includes details such as fatalities, injuries, incident locations, and firearm involvement.
Key Findings:
•	Total incidents recorded: 239,677
•	Total deaths: 60,468
•	Total injuries: 118,402
•	Number of states affected: 51 (all 50 states and D.C.)
•	State with the highest number of incidents: Illinois
•	City/county with the highest number of incidents: Chicago
This analysis aims to highlight patterns in gun-related incidents, providing insights into trends over time, geographical hotspots, and potential policy implications. The findings may help inform strategies for reducing gun violence through better law enforcement, community engagement, and policy interventions.
Key Questions

•	What states have the highest number of gun deaths
•	Which age groups are involved in the most gun violence?
•	Is there a correlation between the number of gun related incidents and age?
•	How does gun violence vary across different states and regions (urban vs. rural areas)?

Folders

Content description of project folders:
•	01 Project Management: contains the project brief that outlines the details of the project.
•	02 Data: contains two subfolders:
◦	Original Data: contains the original datasets of the project (one .csv file and one .geojson file).
◦	Prepared Data: contains the final cleaned and wrangled dataset used for analysis.
•	03 Scripts: contains Jupyter notebooks of each step of my analysis written in Python code.
•	04 Analysis-Visualizations: contains all the visualizations I created to develop and explain insights.
Data

Original data set used for this analysis and columns they contain:

•	Gun_violence: Date, state, city_or_county, address, location_description, incident_url, source_url, gun_stolen, gun_type, incident_characteristics, participant_age_group, participant_gender, participant_name, participant_relationship, participant_status, participant_type, participant_age, congressional_district, latitude, longitude, n_guns_involved, state_house_district, state_senate_district, n_killed, n_injured

•	USA_map a GeoJSON file that includes point locations for plotting maps in Python.
Tools

Code was written in Jupyter notebooks using Python and utilizing the following libraries:
•	Pandas: for data manipulation and analysis
•	NumPy: for mathematical functions
•	OS: for reading/writing files and navigating file system
•	Matplotlib.pyplot: for creating visualizations
•	Seaborn: for more advanced statistical data visualizations
•	Folium: for plotting interactive maps
•	SKLearn: used modules for various analyses such as linear regression, calculating mean_squared and r2 score, and kmeans
•	Pylab: for simplified plotting and numerical calculations
•	Statsmodels.api: for testing stationarity and autocorrelation
Tableau Storyboard

Link for my final results of analysis. Does not contain every step of analysis, only those relevant to final results.


•	Gun-violence.csv data set was accessed from https://www.kaggle.com/datasets/jameslko/gun-violence-data via Kaggle
•	Original data was sourced from gunviolencearchive.org.

![image](https://github.com/user-attachments/assets/db1c16ec-76c3-4077-af09-57585e19da96)
