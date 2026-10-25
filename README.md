🍽️ Restaurant Online Delivery Analysis

"Python" (https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python)
"Pandas" (https://img.shields.io/badge/Pandas-Analysis-150458?logo=pandas)
"Jupyter" (https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
"Status" (https://img.shields.io/badge/Status-Analysis%20Complete-success)

A data analytics project completed as part of the Cognifyz Technologies Data Analytics Internship. This project explores restaurant online delivery availability and compares average restaurant ratings between restaurants that offer online delivery and those that do not.

📌 Project Overview

Objective: Understand online delivery availability across restaurants and investigate how average ratings differ by delivery status.

Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

📊 Key Findings

Metric| No Online Delivery| Online Delivery
Restaurant Count| 7,100| 2,451
Percentage| 74.34%| 25.66%
Average Rating| 2.47| 3.25

Key insight: Restaurants offering online delivery have an average rating approximately 0.78 points higher than restaurants without online delivery in this dataset.

This is an observed association; it does not prove that offering online delivery causes higher ratings.

📈 Visualizations

Online Delivery Availability

"Online Delivery Availability" (Online_Delivery_Percentage%20%281%29.png)

The dataset contains more restaurants without online delivery (74.34%) than restaurants with online delivery (25.66%).

Average Rating Comparison

"Average Restaurant Rating Comparison" (Online_Delivery_Rating_Comparison.png)

Restaurants offering online delivery have a higher average rating (3.25) than restaurants without it (2.47).

⚙️ Analysis Workflow

1. Load the restaurant dataset using Pandas.
2. Inspect the data and relevant columns.
3. Count restaurants with and without online delivery.
4. Calculate percentages and average ratings.
5. Create visualizations using Matplotlib.
6. Export the summary results to CSV.
7. Interpret the findings and document the conclusion.

📁 Project Files

File| Description
"Cognifyz_Online_Delivery.ipynb"| Analysis notebook and Python code
"Online_Delivery_Results.csv"| Summary metrics
"Online_Delivery_Percentage (1).png"| Online delivery availability chart
"Online_Delivery_Rating_Comparison.png"| Average rating comparison chart

▶️ How to Run

1. Install Python and Jupyter Notebook.

2. Install the required libraries:
   
   pip install pandas matplotlib jupyter

3. Place the dataset file "zomato.csv" in the same directory as the notebook. The dataset is not currently included in this repository.

4. Open the notebook and run the cells in order.

✅ Conclusion

In this dataset, only 25.66% of restaurants offer online delivery. Restaurants that offer online delivery also show a higher average rating than those that do not.

Further analysis would be needed to investigate other factors that may influence restaurant ratings.

---

Internship Organization: Cognifyz Technologies
Track: Data Analytics
Project: Online Delivery Analysis
