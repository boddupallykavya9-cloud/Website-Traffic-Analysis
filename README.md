# Web Traffic Data Analysis - Week 2

**Overview**
This repository contains a dataset representing web traffic metrics collected over a 15-day period in October 2025. The data tracks key website performance indicators such as site visits, bounce rate, and session duration.

**Data Description**
The dataset is stored in the Excel file `week2.xlsx` and consists of two sheets:

*   **Sheet1:** Daily web traffic data with columns:
    *   `Date`: The date of the recorded data (YYYY-MM-DD)
    *   `Site Visits`: Number of visits to the website on that date
    *   `Bounce Rate`: Percentage of visitors who left the site after viewing only one page
    *   `Session Duration (min)`: Average duration of each visitor session in minutes
*   **Sheet2:** A summary pivot table aggregating the data by date with sums of site visits, bounce rates, and session durations.

**Summary Statistics**
*   Average site visits per day: ~127
*   Average bounce rate: 48.6%
*   Average session duration: ~2.67 minutes
*   Maximum bounce rate observed: 55%
*   Minimum bounce rate observed: 43%

**Potential Uses**
*   Analyze daily trends in website traffic and engagement
*   Identify days with unusually high or low site performance
*   Develop visualizations or predictive models based on visitor metrics

**Usage**
To use this dataset for analysis:

1.  Download the `week2.xlsx` file.
2.  Load the data in your preferred tool (Python pandas, Excel, etc.).
3.  Explore the daily metrics or use the summary sheet for quick aggregation.
