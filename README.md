# 📊 HR Data Analysis & Interactive Workforce Dashboard

<div align="center">

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-004880?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

</div>

> **Transforming raw, messy HR records into actionable strategic workforce insights through end-to-end data cleaning, ETL transformation, and an interactive dark-themed multi-page dashboard.**



## 📌 Project Overview

This repository showcases an end-to-end Data Analytics workflow designed to clean, transform, and analyze enterprise Human Resources data. The project tracks key workforce metrics, identifies turnover drivers, evaluates training ROI, and monitors employee satisfaction and engagement across departments.



## 🧰 Tools & Technologies Used

* **Data Cleaning & ETL Transformation:** 
  * **Microsoft Excel:** Advanced formatting, text cleaning, data type alignment, and formula auditing.
  * **Power Query:** Automated ETL pipeline, column type conversions, missing value handling, and attribute extraction.
* **Data Modeling & Analytics:**
  * **DAX (Data Analysis Expressions):** Custom KPI measures for average tenure, satisfaction scores, termination aggregates, and training durations.
* **Data Visualization & Dashboard Design:**
  * **Power BI / Interactive Excel Engine:** Dark-theme executive UI layout, custom side-navigation menu, dynamic slicers (`DepartmentType`, `Years ExitDate`), and interactive visual cross-filtering.
* **Documentation & Version Control:**
  * **Git & GitHub:** Source code management and markdown presentation.



## 🔄 Project Execution Phases

### **Phase 1: Raw Data Diagnostics & Assessment**
* Examined wide-format raw HR dataset records containing overflowing column errors (`###`), missing survey responses, unformatted ratings, and inconsistent currency representations (`Rs`).
* Identified primary data quality issues across dates, text casing, and inconsistent department names.

> **Phase 1 Preview (Raw Messy Data):**
> 
> ![Phase 1 - Messy Data](Messy_DatasetScreenshot.png)




### **Phase 2: Data Cleaning & ETL Transformation**
* Cleaned and structured the raw dataset into a standardized relational schema.
* Standardized date fields (`Survey Date`, `Training Date`), cleaned numeric ratings (`Engagement Score`, `Satisfaction Score`), and unified categorical categories (`Training Outcome`, `Training Type`).
* Organized employee demographics, location references, and trainer details into normalized structures.

> **Phase 2 Preview (Cleaned Data):**
> 
> ![Phase 2 - Cleaned Data](Cleaned_DatasetScreenshot.PNG)  
> *(Replace `assets/cleaned_data.png` with your Cleaned Data screenshot link/path)*



### **Phase 3: Dashboard Architecture & UI/UX Design**
Designed an interactive dark-themed dashboard with an intuitive left-side navigation panel allowing multi-page navigation across **4 core analytical views**:

#### **1. Main Overview / Dashboard**
* Highlights core KPIs: **Average Tenure (1.34 years)**, **Completed Training**, **Total Terminations (1,606)**, and **Average Satisfaction Score (3.02)**.
* Includes **Average Tenure by Department**, **Turnover Breakdown by Termination Type**, and **Turnover Trend Over Time (2018–2023)**.

> ![Dashboard Page 1 - Overview](assets/Messy_Dataset Screenshot.PNG)  
> *(Replace `assets/dashboard_pg1.png` with your Dashboard Page 1 screenshot link/path)*



#### **2. Training Analytics**
* Analyzes **Training Cost & Duration by Program**, **Training Spend by Business Unit**, and **Training Outcome Breakdown (Internal vs. External)**.

> ![Dashboard Page 2 - Training](assets/dashboard_pg2.png)  
> *(Replace `assets/dashboard_pg2.png` with your Dashboard Page 2 screenshot link/path)*



#### **3. Workforce Dynamics**
* Displays **Gender Diversity by Job Function**, **Turnover Trends by Quarter**, and **Employee Distribution by Employment Type & Department**.

> ![Dashboard Page 3 - Workforce](assets/dashboard_pg3.png)  
> *(Replace `assets/dashboard_pg3.png` with your Dashboard Page 3 screenshot link/path)*



#### **4. Performance & Satisfaction**
* Evaluates **Average Satisfaction Score vs. Engagement Score by Performance Tier** (*Exceeds*, *Fully Meets*, *Needs Improvement*, *PIP*) and **Satisfaction Rating by Pay Zone** (*Zone A*, *Zone B*, *Zone C*).

> ![Dashboard Page 4 - Performance](assets/dashboard_pg4.png)  
> *(Replace `assets/dashboard_pg4.png` with your Dashboard Page 4 screenshot link/path)*



### **Phase 4: Insights & Strategic Recommendations**
Synthesized analytical findings to deliver actionable insights for HR leadership regarding retention strategy, budget allocation, and workplace performance optimization.



## 📈 Key Insights & Findings

* **Tenure & Retention:** *Executive Office* leads in retention with the highest average tenure (~2.0 years), whereas *Software Engineering* and *Admin Offices* show shorter employment spans.
* **Training Efficiency:** *Communication Skills* and *Technical Skills* absorb the highest training budget, with *External* programs exhibiting unique completion rates compared to *Internal* training.
* **Performance vs. Satisfaction:** Employees in the *Fully Meets* category demonstrate the highest satisfaction (~3.07), while staff on *PIP* exhibit lower engagement (~2.70), marking a high-priority group for HR intervention.
* **Pay Zone Satisfaction:** Employees within **Pay Zone B** express higher satisfaction levels compared to those in Zone A and Zone C.

