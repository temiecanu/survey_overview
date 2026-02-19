# Survey Overview Dashboard

## Purpose

This dashboard provides a comprehensive visual analysis of data professionals based on a global survey. It helps stakeholders:

- Understand demographics, salary trends, education levels, and tool preferences
- Evaluate satisfaction indicators such as work–life balance and salary happiness
- Support data-driven decisions for talent acquisition, compensation strategies, and retention initiatives
- Identify challenges professionals face when entering data roles

---

## Business Context

The dashboard was created to assist HR, talent acquisition, and leadership teams in quarterly or annual workforce strategy meetings. It helps evaluate market expectations, compare compensation benchmarks, and understand the overall state of the data talent landscape.

When metrics show low satisfaction scores or highlight competitive gaps, the dashboard enables quick identification of areas needing further investigation or strategic action (e.g., adjusting benefits, targeted hiring initiatives).

---

## File Structure

```
.
├── survey_overview.pbix                # Power BI report file
├── project_overview.md                 # Full business and data context
├── how_to.md                           # Internal documentation for using the dashboard
├── data.xlsx                           # Source data
└── assets/
    ├── dashboard_canvas.pptx.jpg       # Visual planning of dashboard structure
    └── survey_overview.png             # Screenshot of the final dashboard
```

---

## Key Metrics

- Number of participants
- Average age
- Average salary (by job title and education level)
- Salary happiness score
- Work–life balance score
- Most common programming language
- Most common education level
- Most common country
- Perceived difficulty of breaking into data roles

---

## Dimensions

- Job Title  
- Education Level  
- Country  
- Programming Language  
- Satisfaction scores  

---

## Data Source

- Global survey dataset with 447 responses covering demographics, salaries, satisfaction ratings, and skill preferences

Connection type: Manual import via Power BI

---

## Calculations

- Average salary and scores are calculated using DAX measures
- Drill-down functionality in bar charts allows analysis of Salary Happiness Score vs Salary by role and by education level

---

## Dashboard Structure

- KPI cards: Participants, Age, Country, Education, Programming Language
- Gauges: Work–life balance and salary happiness scores
- Bar charts: Average salary by job title and education level (with drill-down showing Salary Happiness Score vs Salary)
- Pie chart: Difficulty of entering data roles
- Treemap: Participant distribution by country

---

## Usage Guide

The project includes:

* `dashboard_canvas.pptx.jpg` for structural overview
* `project_overview.md` for full business context
* `how_to.md` for internal onboarding

---

## Author

Artemie Țurcanu — Data Analyst