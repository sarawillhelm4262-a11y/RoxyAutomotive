
# Funnel Analysis of Roxy Automotive
## Executive Overview
For this analysis, I used Power BI to import data, created a star schema model to create measures and a dual page report to analyze the health of my fictitious company, Roxy Automotive. After creating a funnel analysis of the various stages of the loans, I determined that the company was in an unhealthy position and needed to take these immediate action steps: 
1. Release cash to any contract in the Tier 1/Low Risk Category.
2. Freeze independent approval authority for Underwriter 45.
3. Issue contractual warnings to Midwest Logistics.
## Business Problem
Roxy Automotive, a commercial automotive floorplan lender, wants to know why their active portfolio is shrinking and interest revenue is stagnant. How can we determine where the problem exists in our pipeline?

<img width="844" height="276" alt="Image" src="https://github.com/user-attachments/assets/46bef6d1-82e9-404c-8fa0-92dd747e0a30" />

## Methodology
1. Generated random messy data with the help of python, stored in .csv files.
2. Used Power Query to import, clean, and transform the data, using standard ETL practices.
3. Used Power BI Desktop to model the data using a star schema and generate the dual page report.

## Data Volume & Sampling Disclosures
To get a realistic data set for this market, I asked AI to generate the Python to randomly generate data for my tables. I specifically asked for messy data to showcase my cleaning skills. Because the dataset is small (1000 rows in the fact table), the dispersement of dates did not reach all months, creating zero drops and broken trends. Date slicers and values were intentionally left out of the reports. They focus instead on categorical value rankings and proportional risk concentrations.

## Skills
Power BI: DAX, functions, ETL, tooltips, calculated columns, data visualization, data modeling
## Results & Business Recommendation
The grand totals of our numbers show a high delinquency rate. Further analysis revealed Underwriter 45 carrying the brunt of that, especially when drilling down to the Midwest Region.

The funnel analysis shows that overall, across all regions, Stage 3 has less contracts than Stage 4. We have more contracts closing than we have cash coming in. 

<img width="1276" height="711" alt="Image" src="https://github.com/user-attachments/assets/20a0b575-1e7d-4ba0-a065-79759bb5b1d7" />

When drilling down to the Midwest Region, our visuals revealed a delinquency rate of 8.38% for Underwriter 45 as shown below:



<img width="1270" height="716" alt="Image" src="https://github.com/user-attachments/assets/103101e0-6c47-4fc6-82c2-581c2af13c18" />



Our vendor that handles getting the vehicles to the lots once the loans have been approved, Midwest Logistics Partners, has a Service Level Agreement of 5 days, as shown below. They are in breach of their SLA Agreements, averaging 23.35 days behind. Those are valuable days that Roxy Automotive could be collecting interest, but the dealerships don't have the cars on their lots.



<img width="1200" height="709" alt="Image" src="https://github.com/user-attachments/assets/45b0ef7a-a73a-43e1-992f-f607af31c71b" />

As stated, the following recommendations should be followed:
1. Immediately release cash wire transfers of any loan applicants in the Tier 1/Low Risk Category. While our delinquency rates are high, these are low risk clients that could be immediate revenue.
2. Freeze independent approval authority for Underwriter 45, and audit Underwriter 45's criteria for approving borrowers in the Midewest territory. Reroute Underwriter 45's contracts currently in Stage 2 to Underwriter 102 for review.
3. Issue contractual warnings to Midwest Logistics to remind them of their 5-day transit cycle threshold. If they fail to comply, begin shifting volume to local transit networks to transport them to their destinations.
