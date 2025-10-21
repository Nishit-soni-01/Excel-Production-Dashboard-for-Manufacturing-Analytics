# Excel-Production-Analysis-Dashboard

## Problem Statement

This project involves the creation of a dynamic dashboard in MS Excel to monitor and analyze a manufacturing production process. The primary objective is to provide a clear, at-a-glance view of key production metrics. The dashboard is designed to help managers track total production, identify the root causes of defects, compare the performance of different machines and shifts, and ultimately improve overall operational efficiency.

### Steps Followed

This dashboard was created entirely within Microsoft Excel, leveraging its powerful data aggregation and visualization tools.

-   **Step 1: Data Loading**
    -   The raw `Production Dataset.csv` was loaded into an Excel sheet.
    -   The data was immediately formatted as an Excel Table to ensure that any new data added would automatically be included in the PivotTable reports.

-   **Step 2: Data Aggregation with PivotTables**
    -   Multiple PivotTables were created on separate sheets, each designed to summarize a specific aspect of the production data.
    -   **Key PivotTables Created:**
        1.  Total Production by Machine
        2.  Total Production by Shift
        3.  Count of Defects by Defect Type
        4.  Production Volume Trend over Time (by Date)

-   **Step 3: Chart Creation**
    -   PivotCharts were created directly from the PivotTables to visualize the aggregated data.
    -   **Charts Used:**
        -   A **Bar Chart** to compare the total output of each machine.
        -   A **Pie Chart** or **Donut Chart** to show the proportion of different defect types.
        -   A **Column Chart** to compare production volume across different shifts.
        -   A **Line Chart** to track the daily or weekly production trend.

-   **Step 4: Dashboard Assembly**
    -   A new sheet named "Dashboard" was created.
    -   All the charts were moved and arranged on this sheet to create a single, comprehensive view of the production floor.

-   **Step 5: Adding Interactivity with Slicers**
    -   **Slicers** for key dimensions like `Machine`, `Shift`, and `Date` were added to the dashboard.
    -   The "Report Connections" for each slicer were configured to link to all the PivotTables, making the entire dashboard interactive and allowing users to filter all visuals simultaneously.

-   **Step 6: Adding KPIs**
    -   Key Performance Indicators (KPIs) like **Total Production Volume**, **Total Defects**, and **Overall Defect Rate (%)** were prominently displayed at the top of the dashboard for a quick summary.

---

# Dashboard Snapshot
<img width="821" height="539" alt="Screenshot 2025-10-21 135407" src="https://github.com/user-attachments/assets/bbc29f29-1b06-4250-9f42-fecd6feaea47" />



---

# Inferred Insights from the Dashboard

This interactive dashboard is designed to provide critical insights into the manufacturing process:

-   **Machine Performance:** The dashboard quickly identifies the most and least productive machines, highlighting potential maintenance needs or operational bottlenecks.
-   **Quality Control:** By visualizing the most common types of defects, the quality assurance team can focus their efforts on addressing the root causes of the biggest problems.
-   **Shift Efficiency:** The dashboard helps managers determine if there are significant performance differences between the morning, evening, and night shifts, which could point to staffing or resource issues.
-   **Production Trends:** The line chart allows for the monitoring of production volume over time, helping to spot downward trends that need investigation or upward trends that indicate successful process improvements.
