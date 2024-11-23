# India Job Survey

This repository analyzes the differences between government and private sector jobs in India. The insights are based on a survey dataset, highlighting key factors such as employment background, sector preference, degree influence, and ideal yearly income expectations.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Visualization](#visualization)
- [Findings](#findings)
- [Usage](#usage)
- [Future Scope](#future-scope)
- [Acknowledgments](#acknowledgments)

---

## Overview

The **India Job Survey** aims to compare and contrast various aspects of government and private sector jobs in India. The analysis focuses on the following:

- Employment sectors (Government vs. Private)
- Impact of educational qualifications (Degree vs. No Degree)
- Expected yearly income across technical, non-technical, and arts backgrounds
- Preferred number of ideal workdays

---

## Dataset

The dataset, `JobSurveyIndia.csv`, contains anonymized survey responses regarding job preferences, income expectations, and workday preferences.

---

## Visualization

A detailed Tableau visualization has been created using the dataset. The primary chart showcases the **ideal number of workdays** categorized by:

1. Employment Sector (Government vs. Private)
2. Educational Degree (Yes vs. No)
3. Employment Background (Technical, Non-Technical, Arts)
4. Yearly Income Range

![India Job Survey Chart](India_Job_Survey.png)

**Key Features of Visualization:**
- Blue bars represent individuals without a degree.
- Orange bars represent individuals with a degree.
- Data is grouped by employment sector and yearly income range.

---

## Findings

### Government vs. Private Sector
1. **Income Expectations:**
   - Individuals with degrees tend to aim for higher income ranges across all sectors.
   - Government sector employees with technical backgrounds expect more than ₹1,200,000 annually more frequently than private sector employees.

2. **Workdays:**
   - Government sector jobs tend to align with a higher ideal number of workdays, especially for those without degrees.
   - Private sector employees, particularly in the non-technical field, exhibit a balanced preference across different income brackets.

3. **Educational Impact:**
   - Degree holders show a clear preference for higher income brackets, especially in technical jobs.
   - Non-degree holders generally settle for a lower yearly income in both sectors.

---

## Usage

### How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/India-Job-Survey.git
   ```
2. Open the Tableau workbook file (`India Job Survey.twbx`) for an interactive view of the visualization.

3. Analyze the CSV dataset (`JobSurveyIndia.csv`) for further data exploration using Python, R, or Excel.

---

## Future Scope

- Add more granular analysis, such as age and gender breakdown.
- Extend the dataset to include regional or city-specific job preferences.
- Implement machine learning models to predict sector preferences based on background and qualifications.

---

## Acknowledgments

- The survey responses were collected anonymously.
- Visualization was developed in **Tableau**.
- Analysis inspired by job market trends in India.

--- 
