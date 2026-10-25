🍽️ Online Delivery & Restaurant Rating Analysis

Cognifyz Technologies — Data Analytics Internship

""Python" (https://img.shields.io/badge/Python-Analysis-blue?logo=python)" (https://www.python.org/)
""Pandas" (https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)" (https://pandas.pydata.org/)
""Jupyter" (https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)" (https://jupyter.org/)

📌 Project Overview

This project investigates online food delivery availability across restaurants and examines how restaurant ratings differ according to delivery status. Using Python and Pandas, the analysis summarizes delivery availability, calculates the percentage of restaurants in each category, and compares average aggregate ratings.

The project transforms restaurant data into measurable insights and visual summaries to support a clearer understanding of online delivery adoption and its relationship with customer ratings.

🎯 Objectives

- Measure the availability of online delivery services across the restaurants in the dataset.
- Calculate restaurant counts and percentages for each delivery category.
- Compare average aggregate ratings between restaurants with and without online delivery.
- Communicate the findings through clear visualizations and a structured results file.

🛠️ Tools & Technologies

Tool| Purpose
Python| Analysis and calculations
Pandas| Data loading, grouping and aggregation
Matplotlib| Data visualization
Jupyter Notebook| Interactive analysis and documentation

📊 Executive Summary

The analysis covers 9,551 restaurants.

Performance Metric| No Online Delivery| Online Delivery
Restaurant Count| 7,100| 2,451
Share of Restaurants| 74.34%| 25.66%
Average Aggregate Rating| 2.47| 3.25

Key Insights

- Delivery availability: Online delivery is available at 25.66% of the restaurants analyzed.
- Limited adoption: 74.34% of the restaurants in this dataset do not offer online delivery.
- Rating comparison: Restaurants offering online delivery have an average aggregate rating of approximately 3.25, compared with 2.47 for restaurants without delivery.
- Observed difference: The average rating gap is approximately 0.78 points.

These findings describe patterns in the dataset. They do not establish that online delivery causes higher restaurant ratings.

📈 Visualizations

1. Online Delivery Availability

"Online Delivery Availability" (../../Online_Delivery_Percentage%20%281%29.png)

This chart compares the proportions of restaurants that offer online delivery with those that do not.

2. Average Restaurant Rating by Delivery Status

"Average Restaurant Rating Comparison" (../../Online_Delivery_Rating_Comparison.png)

This chart compares the average aggregate ratings of restaurants across the two delivery categories.

⚙️ Methodology

1. Loaded the restaurant dataset into Pandas.
2. Inspected the relevant delivery and aggregate-rating columns.
3. Counted restaurants with and without online delivery.
4. Calculated each category's share of the total.
5. Grouped restaurants by delivery status and calculated average ratings.
6. Created comparison charts using Matplotlib.
7. Exported the summary metrics to a CSV results file.
8. Interpreted the results and documented the main findings.

💡 Recommendations

- Investigate delivery expansion: Evaluate locations and restaurant segments where online delivery could be introduced or expanded.
- Study customer experience: Examine ratings, customer feedback and service quality to understand what may contribute to rating differences.
- Analyze additional factors: Compare cuisine, city, pricing and other available characteristics before making business decisions.
- Measure outcomes over time: Track delivery adoption and customer ratings over time to evaluate changes more reliably.

These are potential next steps; the current analysis does not test their outcomes.

📁 Project Files

File| Description
"Cognifyz_Online_Delivery.ipynb"| Python analysis notebook
"Online_Delivery_Results.csv"| Summary metrics by delivery status
"Online_Delivery_Percentage (1).png"| Delivery availability chart
"Online_Delivery_Rating_Comparison.png"| Average rating comparison chart

▶️ How to Run

1. Install Python and Jupyter Notebook.

2. Install the required libraries:
   
   pip install pandas matplotlib jupyter

3. Place the original "zomato.csv" dataset in the directory expected by the notebook. The dataset is not currently included in this repository.

4. Open "Cognifyz_Online_Delivery.ipynb" in Jupyter Notebook.

5. Run the notebook cells in order to reproduce the analysis and charts.

✅ Conclusion

In this dataset, approximately one-quarter of the restaurants offer online delivery. Restaurants in the online-delivery category also have a higher average aggregate rating than restaurants in the non-delivery category.

Further analysis is needed to assess whether the rating difference is associated with other restaurant characteristics or service factors.

---

Organization: Cognifyz Technologies
Internship Track: Data Analytics
Project: Online Delivery & Restaurant Rating Analysis
