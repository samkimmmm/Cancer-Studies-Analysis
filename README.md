# Module 5 Challenge

# Overview
In this assignment, I conducted a comprehensive analysis for a clinical study focusing on drug performance for tumors found in mice. The analysis involved data preparation, summary statistics generation, creation of various plots, and exploration of the correlation between mouse weight and tumor volume.

# Technologies
* Matplotlib
* Pandas
* SciPy

# Prepare the Data
After merging the "mouse_metadata" and "study_results" DataFrames, I removed duplicate timepoints (e.g., g989) to create a cleaned DataFrame. The resulting DataFrame serves as the foundation for subsequent analyses.
<img width="873" alt="Screenshot 2023-12-18 at 2 43 35 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/da4b157d-af7b-4e9a-a1c9-5498ed5e37b5">

# Generate Summary Statistics
The analysis includes the calculation of mean, median, variance, standard deviation, and SEM for each drug regimen. The summary statistics are organized in a DataFrame with drug regimens as the index column and relevant statistics as columns.
<img width="980" alt="Screenshot 2023-12-18 at 2 44 07 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/ebb5a22e-4830-4b0e-bbce-d6df2a54e389">

# Create Bar Charts and Pie Charts
I created bar charts to visualize the total number of measurements for each drug regimen and the distribution of male and female mice within the study. Additionally, pie charts illustrate the distribution of male and female mice in the study.
<img width="844" alt="Screenshot 2023-12-18 at 2 44 41 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/0f2ac4dd-550d-4362-9455-6187e211ace9">
<img width="657" alt="Screenshot 2023-12-18 at 2 45 07 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/0cc67bde-60a3-473f-bbe8-ec7a085b6bd6">

# Calculate Quartiles, Find Outliers, and Create a Box Plot
The analysis involves calculating quartiles and identifying potential outliers for the final tumor volume across promising regimens (Capomulin, Ramicane, Infubinol, and Ceftamin). A box plot displays the distribution of the final tumor volume for all mice in each treatment group.
<img width="717" alt="Screenshot 2023-12-18 at 2 50 00 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/7e90918f-232d-471e-82c0-756827f8b141">

# Create a Line Plot and Scatter Plot
For mice treated with Capomulin, I generated a line plot depicting tumor volume over time for a selected mouse (l509). Additionally, a scatter plot illustrates the correlation between mouse weight and average observed tumor volume throughout the entire Capomulin treatment regimen.
<img width="795" alt="Screenshot 2023-12-18 at 2 51 24 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/2e0ecd85-bf16-4bb7-b06e-12195ff5b5df">
<img width="837" alt="Screenshot 2023-12-18 at 2 52 29 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/4b419175-bfc3-490e-bfc4-413e1742017c">

# Calculate Correlation and Regression
The correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen were calculated. The regression model is visually represented over the scatter plot.
<img width="767" alt="Screenshot 2023-12-18 at 2 53 44 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/885b8080-9669-4e7e-9257-644d0556ec9b">


