# Unequal Costs, Unseen Burdens: A Deep Dive into America's Hospitals

In the vast landscape of American healthcare, not all hospitals are created equal. Some serve bustling urban centers with cutting-edge medical advancements, while others stand as lifelines in remote rural areas, often struggling to keep their doors open. But beneath the surface of patient care lies an untold story—a story of financial strain, charity care, and the ever-growing burden of hospital costs.

Our journey begins with a simple question: __How do different types of hospitals across the U.S. manage their costs, charity care expenses, and patient discharges? And more importantly, how do these financial realities vary between urban and rural settings?__

# The Data Behind the Story

To uncover these hidden truths, we turned to the __CostReport_2021_Final__ dataset from the Centers for Medicare & Medicaid Services (CMS). This dataset, consisting of 6,035 hospitals and 117 financial indicators, offered a wealth of insights into hospital spending, debt, and patient care. Also, we’ve not only captured the snapshot of 2021 performance but also integrated it with the broader __2017-2021 trends__, providing you with a detailed view of healthcare's evolving landscape.

At the heart of our investigation were five key variables:

__Total Costs__ – How much hospitals spend annually

__Charity Care Costs__ – The amount hospitals provide in free or reduced-cost care

__Total Discharges__ – The number of patients treated and released

__Bad Debt Expenses__ – Unpaid patient bills that hospitals must absorb

__Cost per Discharge__ – A metric to measure hospital efficiency

But numbers alone couldn’t tell the full story. We needed to dive deeper—examining how these factors varied across regions, facility types, and urban vs. rural hospitals.

# Analytical Approach

To ensure a structured analysis, we followed a three-step approach:

__1️⃣ Data Cleaning & Preparation:__

- We cleaned and filtered the data to focus on key financial indicators.

- Identified missing values and standardized hospital classifications.

__2️⃣ Data Visualization:__

- Created interactive dashboards to visually analyze cost distributions, charity care expenses, and financial trends.

- Used scatter plots, heatmaps, and bar charts to uncover correlations between cost efficiency and patient discharges.

__3️⃣ Comparative Analysis of Urban vs. Rural Hospitals:__

- Segmented hospitals by location (urban/rural) and region (South, Northeast, Midwest, West).

- Analyzed bad debt, charity care, and cost per discharge to pinpoint inefficiencies.

This methodology allowed us to go beyond raw numbers and tell a compelling story through data.

# Findings from 2021: A Year in Review

After meticulous data preparation, we performed Exploratory Data Analysis (EDA) to uncover key trends and disparities.

__1. Total Costs by Facility, Region & Rural vs. Urban__

 •	The South region has the highest total costs, driven by both urban and rural areas, with urban South seeing the highest costs at 214.1B in 2017.

 •	Urban facilities consistently have higher costs compared to rural ones across all regions.

 •	Midwest and Northeast regions maintain similar cost levels, with 111.0B (Urban Midwest) and 105.9B (Urban Northeast) in 2017.

 •	The West has lower costs than the South, but still substantial at 125.9B (Urban) and 75.7B (Rural) in 2017.

 •	Short-term hospitals (STH) drive the majority of costs in all regions.
 
 ![image](https://github.com/user-attachments/assets/6476627f-a04f-44a6-bb5d-da273ee726eb)


__2. Total Discharges by Facility, Region & Rural vs. Urban__

 •	South leads with the highest discharges, reaching 8,407.1K in 2017.

 •	Urban facilities consistently have more discharges than rural ones across all regions.

 •	STH facilities dominate discharges in every region.

 •	The West outperforms the Northeast in both urban and rural discharge rates.

 •	CAH and PH show notable rural-urban variation, with LTCH contributing more in urban South.

 ![image](https://github.com/user-attachments/assets/35de2804-7cf4-4ee1-a92a-bcae7c582a78)


__3. Charity Care by Facility, Region & Rural vs. Urban__

 •	The South provides the highest charity care, with 11.0B (Urban) and 4.6B (Rural) in 2017.

 •	Urban facilities outperform rural in charity care across all regions.

 •	Northeast has minimal charity care contributions, with negligible amounts in both urban and rural settings.

 •	Short-term hospitals (STH) are the primary contributors to charity care across all regions.

 •	West and Midwest show minimal charity care contributions compared to the South.
 
![image](https://github.com/user-attachments/assets/3244a441-f060-4c91-8a1b-4cd3b1d4bb5b)


__4. Cost Per Discharge by Facility, Region & Rural vs. Urban__

 •	Psychiatric hospitals (PH) have the highest cost per discharge at 1,248.12M in 2017.

 •	Urban facilities account for 64.4% of total costs per discharge.

 •	The West region has the highest cost per discharge at 312.4M in 2017.

 •	STH and CH contribute significantly to high cost per discharge figures.
 
![image](https://github.com/user-attachments/assets/2a6ad89e-c63d-4e78-92c3-c790b003acdb)  ![image](https://github.com/user-attachments/assets/e097294c-ec00-4d77-be87-f15e0c71ce6f)  ![image](https://github.com/user-attachments/assets/e87e164a-ddfa-4690-b4c8-1640f9f72365)

__5. Bad Debt by Facility, Region & Rural vs. Urban__

 •	South leads in bad debt with 18.4B (Urban) and 8.7B (Rural) in 2017.

 •	Urban areas consistently face higher bad debt than rural ones.

 •	Northeast has minimal bad debt contributions, with only 0.1B in both urban and rural settings.

 •	Short-term hospitals (STH) contribute significantly to bad debt across all regions.

 •	Midwest and West regions have relatively low bad debt compared to the South.

![image](https://github.com/user-attachments/assets/35e49d1e-111b-4d7d-9d00-2ba788610102)

# Expanding the Lens: 2017-2021 Trends

To get a broader perspective, we combined 2017-2021 data and analyzed overarching trends through a dashboard visualization for dynamic exploration of trends by year, facility type, and geography.

The analysis focused on:

- Tracking the total costs and charity care expenses over time

- Understanding the impact of bad debt across different facility types

- Identifying regional variations in costs and discharges

- Calculating cost per discharge, a key efficiency metric

# Dashboard Insights

__1. Text Table of Key Variables__

The summary table provided a bird’s-eye view of essential metrics. For instance:

 • Total Costs: $4.55T

 • Total Charity Care: $132.7B

 • Total Bad Debt: $275.8B

 • Cost Per Discharge: $27,653

These figures revealed the staggering scale of hospital operations and the economic burden of uncompensated care.

![image](https://github.com/user-attachments/assets/427291ca-8339-4a80-94e5-6bed91a72e04)

__2. Trends of Key Variables Across 5 Years__

Our line chart illustrated how key variables evolved from 2017 to 2021. Key takeaways included:

 • Stable total costs, despite fluctuations in discharges

 • A slight decline in total bad debt after peaking in 2019

 • Charity care costs remained steady, suggesting consistent financial aid
 
![image](https://github.com/user-attachments/assets/e6eec264-9b95-4b6b-b9a8-bb18e0744618)

__3. Facility Type Trends__

Breaking down costs by facility type, we found that:

 • Specialty hospitals (STH) had the highest total costs, exceeding $913.7B

 • Rehabilitation & mental health centers (RNMHC) had lower costs, around $245.5K

 • The cost per discharge varied significantly, reflecting operational disparities
 

__4. Geographic Trends__

Examining regional patterns, we observed:

 • Higher bad debt and charity care expenses in urban areas

 • Consistent discharge rates across most regions

 • Some states experienced a decline in bad debt, indicating better patient payment compliance


# Policy Recommendations: A Path to Sustainable Healthcare

Based on our analysis, we propose six key solutions:

✔ Expand Medicaid Coverage – Reduce uninsured patients and hospital bad debt.

✔ Introduce Sliding Scale Payment Models – Make care more affordable based on income.

✔ Increase Rural Healthcare Funding – Keep small hospitals financially viable.

✔ Promote Affordable Insurance Programs – Lower the charity care burden.

✔ Expand Telehealth Services – Reduce pressure on rural hospitals.

✔ Implement Value-Based Care Models – Reward hospitals for outcomes rather than services performed.

By implementing these policies, we can bridge the financial gap between hospitals, ensuring that quality healthcare is accessible to all—regardless of location.

# The Final Takeaway

Behind every dollar of hospital spending, every unpaid bill, and every discharged patient, there is a human story—of people seeking care, of hospitals struggling to balance budgets, and of a healthcare system that is both vital and vulnerable.

Our Tableau dashboards and data analysis revealed that:

📌 Rural hospitals face extreme financial challenges despite serving large populations.

📌 Urban hospitals have higher costs but are more financially stable.

📌 Short-Term Hospitals (STH) dominate in both urban and rural settings, but rural hospitals have fewer resources per patient.

📌 The South is the most financially strained region, needing urgent policy interventions.

This gap highlights the urgent need for better financial support for rural healthcare facilities.

This project was more than just an analysis—it was an exploration of America’s healthcare reality. The financial health of hospitals directly impacts patient care, and without reform, millions risk losing access to critical medical services.

It’s time to make hospital financial stability a national priority—because a hospital’s survival should never determine a patient’s fate.
