# Deloitte Data Analytics Virtual Experience (Forage)

This repository summarizes my work from the Deloitte Australia Data Analytics Virtual
Experience Program on Forage. The simulation focused on applying data analytics
techniques to real-world consulting scenarios involving compensation equity analysis
and operational telemetry data.

---

## Tools Used
- Microsoft Excel
- Tableau

---

## Excel Task: Compensation Equity Classification

### Objective
Analyze employee compensation equity data and classify fairness levels across job roles
and factories using predefined thresholds.

### Key Activities
- Analyzed structured data containing Factory, Job Role, and Equality Score
- Created a calculated column to classify equality scores into:
  - Fair (-10 to +10)
  - Unfair (< -10 or > +10)
  - Highly Discriminative (< -20 or > +20)
- Implemented conditional logic using absolute value checks to handle both positive and
  negative variances
- Validated results using edge-case examples to ensure accurate classification

### Outcome
Enabled consistent identification of compensation equity patterns to support further
analysis and reporting.

---

## Tableau Task: Telemetry & Downtime Analysis

### Objective
Analyze machine telemetry data to identify downtime patterns across factories and
device types using Tableau.

### Key Activities
- Imported and prepared telemetry data within Tableau
- Created a calculated measure to quantify unhealthy machine status as downtime
- Built bar charts to visualize:
  - Down Time per Factory
  - Down Time per Device Type
- Designed an interactive dashboard with cross-filtering between charts
- Identified the factory with the highest total downtime through dashboard interaction

### Outcome
Delivered an interactive Tableau dashboard that enables stakeholders to explore downtime
drivers by factory and device type for operational insights.

---

## Key Learnings
- Translating business rules into scalable data logic
- Designing interactive dashboards for exploratory analysis
- Applying data storytelling to support decision-making

---

*Note: This repository contains recreated analysis, summaries, and visual evidence only.
No proprietary Deloitte datasets or files are included.*

