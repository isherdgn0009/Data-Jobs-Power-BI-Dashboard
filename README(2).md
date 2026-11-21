# Data Jobs Dashboard with Power Bi

![Dashboard Page 1](Images/Screenshot%202026-11-13%20210800.png)

## Introduction

This dashboard was created for **Job Seekers, Job Transitioners, and Job Swappers** to solve a common problem: information about the data job market is scattered and hard to grasp. Using a *real-world dataset of 2024 data science job postings* (including titles, salaries, and locations), this project provides a single, easy-to-use interface to explore market trends and compensation.

## Skills Showcased

- **⚙️ Data Transformation (ETL) with Power Query:** Cleaned, shaped, and prepared the raw data for analysis by handling blanks, changing data types, and creating new columns.

- **🧮 Implicit Measures:** Formulated measures to derive key insights and KPIs like `Median Yearly Salary` and `Job Count`.
- **📊 Core Charts:** Utilized **Column, Bar, Line,** and **Area Charts** to compare job counts and track trends over time.
- **🗺️ Geospatial Analysis:** Leveraged **Map Charts** to visualize the global distribution of jobs.
- **🔢 KPI Indicators & Tables:** Used **Cards** to display key metrics and **Tables** to provide granular, sortable data.
- **🎨 Dashboard Design:** Designed an intuitive and visually appealing layout, exploring both common and uncommon chart types to best tell the data story.
- **🖱️ Interactive Reporting:**
  - **Slicers:** To dynamically filter the report by Job Title.
  - **Buttons & Bookmarks:** To create a seamless navigation experience.
  - **Drill-Through:** To navigate from a high-level summary to a contextual view.

  ## Dashboard Overview

###  High-Level Market View

![Dashboard Page 1](<Images/Screenshot 2026-11-13 210800.png>)

This page gives a quick, high-level look at the data job market. Cards at the top show headline numbers like total job count and median yearly salary. The charts below compare job counts across titles and locations and track how postings change over time. The Job Title slicer filters the whole page, and drill-through lets you jump into a detailed view of any role.

###  Job Title Drill Through

![Dashboard Page 2](<Images/Screenshot 2026-11-13 211431.png>)

This is the deep-dive page. From the main dashboard, you can drill through to this view to get specific details for a single job title, including salary ranges, work-from-home stats, top hiring platforms, and a global map of job locations.

## Conclusion

This dashboard showcases how Power BI can transform raw job posting data into a powerful tool for career analysis. It allows users to slice, filter, and drill through data to make informed decisions about their career paths.

## Other Pages

Beyond the main dashboard, this project includes a set of pages where I practiced and tested individual Power BI features. A Home page with a page navigator links to every page, and each page has a home button to jump back.

### Home Page and Home Button

![Home Page](<Images/Screenshot 2026-11-13 224347.png>)

**What it does:** The Home page is the starting point of the report. A page navigator lists every page as a button, so you can jump to any page in one click. Every practice page also has a home button that takes you straight back here.

**Functions:**
- **Page navigation:** One click on any button opens that page.
- **Return to Home:** The home button on each page brings you back to the main menu from anywhere in the report.
- **Hint for users:** An information button on the Home page explains how to use the buttons (hold Ctrl while clicking in Power BI Desktop).

**How it eases the user interface:**
- **Easier to explore:** The report reads like a simple app menu, so you never have to hunt through page tabs.
- **Less clicking:** Any page is at most two clicks away, one back to Home and one to the next page.
- **Consistent layout:** The home button sits in the same spot on every page, so users always know where to find it.
- **Easy for new users:** Even someone who has never opened the report can find their way around from the first screen.

### Column and Bar Charts

![Column and Bar Charts](<Images/Screenshot 2026-11-13 221709.png>)

Compares salaries by job title, by country, and by whether a posting mentions a degree. A Job Title slicer filters the page, and two bookmarks (Filtered and Unfiltered) let you flip between views with a button.

### Line Graphs

![Line Graphs](<Images/Screenshot 2026-11-13 221747.png>)

Tracks job postings over time with a stacked area chart and a line chart with min and average reference lines. A combo chart puts monthly job postings next to average hourly salary.

### Pie Charts and Scatterplot

![Pie Charts and Scatterplot](<Images/Screenshot 2026-11-13 221811.png>)

Shows what share of postings are work from home and what share don't mention a degree. A treemap breaks down schedule types such as full-time, contractor, and internship. A scatterplot compares hourly and yearly salary by job title.

### Other Charts

![Other Charts](<Images/Screenshot 2026-11-13 221930.png>)

Explores less common visuals: a ribbon chart of median yearly salary over time, a waterfall chart for a data analyst salary breakdown, and a funnel chart of applicants by stage.

### Cards and KPIs

![Cards and KPIs](<Images/Screenshot 2026-11-13 222150.png>)

Highlights key figures with card visuals, gauges for median yearly salary, and a KPI visual that tracks yearly median salary over time.
