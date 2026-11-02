# 📋 How to?

### **1. General Information**

**Title:**

Survey Overview

**Dashboard Owner:**

Artemie Țurcanu (Data Analyst)

**Purpose:**

This dashboard provides an overview of key insights from a global survey of data professionals. It enables users to:

* Understand the overall demographic and professional landscape
* Benchmark salaries by role and education level
* Evaluate satisfaction metrics such as work–life balance and salary happiness
* Analyze the perceived difficulty of breaking into data roles
* Identify distribution patterns by country and tool usage

**Primary Stakeholder:**

HR, Talent Acquisition, and Strategy Teams

**Metrics:**

* Number of participants
* Average age
* Average salary by job title and education level
* Salary Happiness Score
* Work–life Balance Score
* Most common programming language
* Most common education level
* Most common country
* Perceived entry difficulty

**Dimensions:**

* Job Title
* Education Level
* Country
* Programming Language
* Satisfaction Scores

---

### **2. Data Sources and Technical Details**

**Data Source:**

* **Survey Dataset** (single flat table): includes demographics, education, job title, salary, tool usage, and subjective satisfaction ratings

**Connection Type:**

Manual import into Power BI

**Calculation Notes:**

* Average salaries and satisfaction scores are calculated using DAX measures
* Drill-down functionality in bar charts allows analysis of Salary Happiness Score vs Salary by role and by education level

---

### **3. Frequently Asked Questions (FAQ)**

**Why does the number of participants change when filters are applied?**

Applying filters (e.g., by country or education level) dynamically recalculates participant numbers and other metrics to reflect only the filtered subset.

**Why do some visuals show blank values when drilling down?**

If certain segments lack sufficient data (e.g., few respondents in a specific role), charts may show blanks or minimal values.

---

### **4. Dashboard Structure**

* **Top section:** KPI cards (Participants, Average Age, Most Common Country, Education Level, Programming Language)  
* **Gauge charts:** Work–life Balance Score and Salary Happiness Score  
* **Bar charts:** Average salary by job title and by education level (with drill-down showing Salary Happiness Score vs Salary)
* **Pie chart:** Perceived difficulty of breaking into data roles
* **Treemap:** Participant distribution by country
