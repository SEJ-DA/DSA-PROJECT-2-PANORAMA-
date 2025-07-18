# DSA-PROJECT-2-PANORAMA-
# Palmoria Group HR Analytics Case Study

## 🚀 Overview

The Palmoria Group, a manufacturing company in Nigeria, is facing gender inequality issues across its three regions. This repository provides a full HR analytics investigation — with data cleaning, analysis, visualizations, and actionable recommendations.

## 📊 Objectives

1. *Clean and prepare* HR data as described.
2. *Analyze gender-related issues* across the organization, regions, and departments.
3. *Assess performance ratings* by gender.
4. *Investigate salary structure* for pay gaps and legal compliance.
5. *Map pay distributions* by salary band and region.
6. *Calculate and allocate bonuses* based on performance.
7. *Deliver recommendations* for management.



## ✨ How to Use This Repo

1. *Clone this repo*
2. Place your raw data in the data/ folder
3. Run the notebooks step by step (notebooks/)
4. Check the visuals/ folder for key charts and insights
5. Read the final recommendations in the [Report section](#report)

## 🔍 Analysis Steps

1. *Data Cleaning*
   - Assign “Undisclosed” as gender where missing
   - Remove exited employees (no salary)
   - Drop records with NULL departments

2. *Descriptive Analysis*
   - Gender Distribution: Overall, by region, and by department
   - Performance Ratings: By gender
   - Salary Structure & Pay Gap: By gender, dept, region
   - Salary Compliance: Identify salaries < $90,000
   - Salary Banding: In $10,000 increments, by region

3. *Bonus Allocation*
   - Apply rules from bonus_rules.csv per employee rating
   - Calculate new total pay (salary + bonus)
   - Aggregate payout by region and company

4. *Visualization*
   - Bar charts: Gender ratios, ratings, pay bands
   - Boxplots: Salary distributions by gender/department
   - Heatmaps: Regional gender gap, pay gap

## 📈 Key Findings (Sample, based on reference project)

- Gender almost equal, but gaps in specific regions/departments.
- Departmental pay gaps exist; females earn more in a few key departments.
- Majority of staff earn below new legal minimum; urgent review needed.
- Bonus allocations increase total regional payout by about 3–5%.

## 📝 Recommendations

- Close gender gaps in key departments/regions.
- Review and raise salaries below $90,000 immediately.
- Review pay gaps in departments where disparity >5%.
- Investigate why females outperform males in ratings.
- Launch mentorship, flexibility, and bias-awareness programs.
