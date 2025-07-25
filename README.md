# Deloitte-virtual-internship
"Deloitte job simulation involving data analysis and forensic technology"

# 📊 Deloitte Data Analytics Virtual Internship (Forage)

## 🏢 Company: Deloitte  
## 🗓️ Completion: July 2025  
## 🎓 Platform: Forage

---

## 📁 Overview

This repository documents the work I completed during the **Deloitte Data Analytics Virtual Internship** offered through Forage. The program provided hands-on experience with business data analysis, equality classification in Excel, and visualization using Tableau.

---

## 🎯 Objectives

- Analyze raw business and machine data
- Perform classification using Excel formulas
- Create calculated fields and dashboards in Tableau
- Generate actionable insights for business stakeholders

---

## 🔧 Tools & Technologies

- **Microsoft Excel**
- **Tableau Public**
- **JSON Data Handling**
- **Data Cleaning & Filtering**

---

## 📌 Key Tasks Completed

1. **Excel Task – Equality Score Classification**
   - Used `IF` and `ABS` functions to classify equality scores into:
     - *Fair* (±10)
     - *Unfair* (>10 or <-10)
     - *Highly Discriminative* (>20 or <-20)
   - Formula used:
     ```excel
     =IF(ABS(B2)>20, "Highly Discriminative", IF(ABS(B2)>10, "Unfair", "Fair"))
     ```

2. **Data Cleaning & Preprocessing**
   - Processed a JSON dataset simulating machine health status across factories
   - Identified records with "Unhealthy" status indicating potential downtime

3. **Calculated Field: “Unhealthy”**
   - Created a calculated field in Tableau:
     ```plaintext
     IF LOWER(TRIM([Status])) = "unhealthy" THEN 10 ELSE 0 END
     ```
   - Assigned 10 minutes of downtime for every "Unhealthy" status entry

4. **Sheet 1: Down Time per Factory**
   - Created a bar chart to summarize total downtime by factory

5. **Sheet 2: Down Time per Device Type**
   - Built a second bar chart to visualize downtime distribution across device types

6. **Interactive Dashboard**
   - Combined both charts in a dashboard
   - Enabled filter action on the factory chart to dynamically update the device type chart

7. **Insight Generation**
   - Identified the factory with the highest total downtime
   - Filtered dashboard revealed device types contributing most to the downtime

---

## 🧮 Excel Skills Demonstrated

- Logical classification using nested `IF` conditions
- Use of `ABS()` and `TRIM()` functions
- Formula-based automation for data categorization

---

## 📊 Tableau Skills Demonstrated

- Connecting to and cleaning JSON data
- Creating calculated fields
- Building multi-chart dashboards
- Adding interactivity through filters and actions
- Insight storytelling through visualization

---

> ⭐ This internship helped me strengthen my foundational skills in data analytics by applying Excel and Tableau to solve real-world business scenarios.

