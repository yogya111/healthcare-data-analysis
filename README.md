# healthcare-data-analysis
A Python-based analysis of healthcare data to uncover patterns in patient demographics, billing trends, and medical conditions using Pandas and Matplotlib.
What’s This Project About?
This project analyzes a synthetic healthcare dataset (healthcare_dataset.csv) with 55,500 patient records to find patterns in demographics, billing costs, and conditions like Obesity and Diabetes. Using Python, Pandas, and Matplotlib, I cleaned the data, ran exploratory data analysis (EDA), and visualized key trends to uncover actionable insights.
Dataset: Sourced from platforms like Kaggle 
# Tools:
Python for scripting.
Pandas for data wrangling.
Matplotlib for plotting trends.
# Steps:
Loaded and explored the dataset.
Cleaned data to ensure accuracy (minimal missing values here).
Analyzed billing and patient trends by age and condition.
Created a bar chart to show billing by age group.
Summarized findings for healthcare applications.
# Features
Data Cleaning: Ensured the dataset was tidy by handling any missing values.
Exploratory Analysis: Grouped data to study billing patterns and patient demographics.
Visualization: Built a bar chart to visualize average billing by age group.
Insights: Highlighted key trends, like high billing for certain conditions.
# What I Discovered
While analyzing the healthcare dataset in Healthcare_dataset.ipynb, I uncovered some intriguing patterns:
The 41-60 age group dominates the dataset, representing the largest share of patients, likely reflecting common healthcare needs in this age range.
Surprisingly, the 0-20 age group had the highest average billing costs—I didn’t expect this, possibly due to specialized pediatric treatments or urgent care needs!
Obesity stood out as the medical condition with the highest average billing, highlighting its significant cost impact on healthcare systems.
Getting Started
Want to try this yourself? Here’s how to set it up:
git clone https://github.com/yogya111/healthcare-data-analysis.git
cd healthcare-data-analysis
# Get the Dataset:
Download healthcare_dataset.csv from a source like Kaggle and place it in the project folder.
# Set Up Your Environment:
Make sure you have Python 3.x installed.
Install the libraries I used (Pandas for data analysis, Matplotlib for visualizations):
pip install pandas matplotlib
Or use the requirements.txt file:
pip install -r requirements.txt
# Run the Notebook:
Open Jupyter Notebook:
jupyter notebook Healthcare_dataset.ipynb
Run the cells to see the data cleaning, analysis, and visualizations in action.
Dataset Overview
Columns: Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results.
Rows: 55,500 entries.
Note: The dataset is synthetic and anonymized—no real patient data here.
 # Why This Matters
This project shows how data analysis can help:
Hospitals: Identify high-cost patient groups for better resource planning.
Policymakers: Optimize healthcare costs based on billing trends.
Researchers: Explore links between age, conditions, and expenses.
 # Next Steps
I’m planning to take this project further by:
Adding more visuals, like heatmaps or admission date trends.
Running statistical tests to back up the findings.
Creating an interactive dashboard with Streamlit or Dash.
Digging into other variables, like admission types or test results.
This project is licensed under the MIT License.
# About Me
Name: Yogya Bandaru
Email: yogyabandaru@gmail.com
LinkedIn: Yogya Bandaru
GitHub: yogya111
I’m passionate about using data to solve real-world problems. Drop me a message if you have feedback or want to collaborate!
# Acknowledgments
Inspired by healthcare data challenges on Kaggle.
Thanks to the Pandas and Matplotlib communities for their awesome tools.
