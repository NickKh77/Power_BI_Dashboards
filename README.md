# Data Jobs Dashboard with Power BI

![Dashboard Page 1](/images/Project1_1.png)

## Introduction

This dashboard was built to solve a common problem: information about the data job market is scattered across dozens of sources and hard to grasp quickly. Using a **real-world dataset of 2024 data science job postings** (including job titles, salaries, and locations), this project provides a single, easy-to-use interface for exploring market trends and compensation.

It is aimed at **job seekers, career transitioners, and anyone curious about the data job market** — whether you're looking for your first role, switching from another field, or just trying to understand where the industry is heading.

## Skills Showcased

- **⚙️ Data Transformation (ETL) with Power Query**
  Cleaned, shaped, and prepared raw data for analysis: handled blanks, changed data types, and created new calculated columns.
- **📊 Implicit Measures**
  Built measures to derive key insights and KPIs such as `Median Yearly Salary` and `Job Count`.
- **📈 Core Charts**
  Used **Column, Bar, Line, and Area Charts** to compare job counts and track trends over time.
- **🗺️ Geospatial Analysis**
  Leveraged **Map Charts** to visualize the global distribution of job postings.
- **🔢 KPI Indicators & Tables**
  Used **Cards** for headline metrics and **Tables** for granular, sortable data.
- **🎨 Dashboard Design**
  Designed an intuitive and visually appealing layout, experimenting with both common and less common chart types to tell the data story clearly.
- **🖱️ Interactive Reporting**
  - **Slicers** — dynamically filter the report by Job Title.
  - **Buttons & Bookmarks** — create a seamless navigation experience.
  - **Drill-Through** — move from a high-level summary to a contextual, detailed view.

## Dashboard Overview

### Page 1: High-Level Market View

![Dashboard Page 1](/images/Project1_1.png)

The main page acts as a mission control for the data job market. It highlights key KPIs such as total job count, median salaries, and top job titles, giving you a quick snapshot of what's happening in the market at a glance.

### Page 2: Job Title Drill Through

![Dashboard Page 2](/images/Project_2.png)

This is the deep-dive page. From the main dashboard, you can drill through to this view to see specific details for a single job title — including salary ranges, work-from-home statistics, top hiring platforms, and a global map of job locations.

## Tools & Technologies

- **Power BI Desktop** — report building and visualization
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures and KPIs
- **Dataset** — 2024 data science job postings (titles, salaries, locations)

## Conclusion

This dashboard demonstrates how Power BI can turn raw job posting data into a practical tool for career analysis. It lets users slice, filter, and drill through the data to make more informed decisions about their career paths — and it serves as a solid example of end-to-end BI workflow, from raw data to interactive report.

## How to Use

1. Clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted, update the data source path to point to your local copy of the dataset.
4. Explore the report — use slicers to filter by job title and drill through for detailed views.

