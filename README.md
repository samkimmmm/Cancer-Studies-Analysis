# Module 5 Challenge

# Overview
In this assignment, I had generated tables and figures needed for the technical report of a clinical study regarding drug performance for tumors found in mice.

# Prepare the Data
After merging the "mouse_metadata" and "study_results" DataFrames, I removed any duplicate timepoints (g989), then created a cleaned DataFrame. 
<img width="873" alt="Screenshot 2023-12-18 at 2 43 35 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/da4b157d-af7b-4e9a-a1c9-5498ed5e37b5">

# Generate Summary Statistics
In this new DataFrame, I created a summary of the statistics including the following:
1. A row for each drug regimen, which are contained in the index column.
2. A column for each of the following statistics:
   * Mean
   * Median
   * Variance
   * Standard Deviation
   * SEM
<img width="980" alt="Screenshot 2023-12-18 at 2 44 07 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/ebb5a22e-4830-4b0e-bbce-d6df2a54e389">

# Create Bar Charts and Pie Charts
* Create two bar charts using the .plot() method and pyplot method.
<img width="853" alt="Screenshot 2023-12-18 at 2 44 28 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/29db06c6-879f-4e67-b856-d81c27b845b2">
<img width="844" alt="Screenshot 2023-12-18 at 2 44 41 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/0f2ac4dd-550d-4362-9455-6187e211ace9">

* Create two pie charts using the .plot() method and pyplot method.
<img width="677" alt="Screenshot 2023-12-18 at 2 44 54 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/3625a5ec-c15f-4920-af85-ddc3a6c566e3">
<img width="657" alt="Screenshot 2023-12-18 at 2 45 07 PM" src="https://github.com/samkimmmm/module5_challenge/assets/135805393/0cc67bde-60a3-473f-bbe8-ec7a085b6bd6">
