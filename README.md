This is a sample project to showcase Excel and Power BI skills.

This data is from kaggle.com and includes records from 2022 - 2023.

Data Source: https://www.kaggle.com/datasets/missionjee/car-sales-report

<img width="1513" height="850" alt="image" src="https://github.com/user-attachments/assets/3457214d-89e6-4f8a-9782-18e2b1e55227" />





GOAL: 

1. Use MS Excel skills to manipulate data in preparation for visualization
2. Use Power BI skills to effectively visualize data for meaningful data-driven decisions.



Problem Statement:

The organization lacks a centralized system to monitor car sales performance across regions, body type, company, models, and dealers. Leading to delayed insights and inefficient performance tracking.

Because of this:

 * Management has limited visibility into overall sales performance and Sales Growth.

 * Identifying top-performing and underperforming car models, regions, body type and dealers.

Objective:

The objective of this project is to identify which companies are performing well and which are underperforming in terms of car sales. 
Based on these insights, the dashboard will help evaluate whether existing business strategies are effective or if corrective actions are needed to improve performance.


The question we want to answer:

1. Which company gives the highest sales in USD?
2. Which region gives a highest GWT rate?
3. Which body type gives negative GWT rate?
   

Data:

It is about the Car Sales made between 2022 - 2023. Made this data based on my experience in Data and Business Reporting Analyst.

<img width="1690" height="977" alt="image" src="https://github.com/user-attachments/assets/fa9228c2-3127-4682-8a5d-f5a72b3d878f" />


Methodology:


Data Cleaning and Processing

1. Load in Power BI and add new date column in Model view for relationship and also to maintain proper sequence by month.

<img width="1318" height="457" alt="ADD NEW TABLE DATE" src="https://github.com/user-attachments/assets/45764613-606c-4785-9090-0b1e653b0d15" />

2. Create relationship date column to ensure correct filtering across table and enable time-based analysis.

<img width="681" height="771" alt="CREATE RELATIONSHIP" src="https://github.com/user-attachments/assets/7f92ace0-21ec-4cd5-b7c7-856d8ace6ade" />

3. Sorting month by month number to maintain proper sequence in visualization (etc. Jan, Feb, Mar)

<img width="1669" height="604" alt="SORT MONTH BY NUMBER" src="https://github.com/user-attachments/assets/9b456ab6-4c7f-45d6-ac0b-e9fcbd522163" />

4. Rename column 'Price' - 'Sales' in Power Query to easily recognize the column of the sales and also for DAX preparation.

<img width="1731" height="489" alt="RENAME COLUMN" src="https://github.com/user-attachments/assets/58470599-060f-464b-9207-6279e4e0c9e2" />

5. Create DAX sum total sales

<img width="779" height="34" alt="SUM TOTAL SALES" src="https://github.com/user-attachments/assets/9b7763de-3469-44af-adba-ecd255c6f2fa" />

6. Create DAX calculate total sales by 2022 to know sales comparison of the year.

<img width="758" height="35" alt="CALCULATE TOTAL SALES 2022" src="https://github.com/user-attachments/assets/6d1ffcf4-11e0-4cee-a610-eb29281a4712" />

7. Create DAX calculate total sales by 2023 to know the sales comparison of the year vs PY.

<img width="783" height="34" alt="CALCULATE TOTAL SALES 2023" src="https://github.com/user-attachments/assets/02cba745-667a-4479-ad94-c9778d6897a5" />

8. Create DAX percent growth this is to easily assess if a specific category is performing better or not.

<img width="627" height="35" alt="% GWT" src="https://github.com/user-attachments/assets/db52a18f-2838-44c0-8d3b-3d0b2f9f2092" />





Findings: 

1. Which company gives the highest sales in USD? --> Chevrolet (answer may vary if filtered per year)

<img width="486" height="251" alt="image" src="https://github.com/user-attachments/assets/ac12dff2-08f2-44d1-b1e9-9e1db23e266b" />


2. Which region gives a highest GWT rate? Scottsdale has a highest Gwt vs PY 

<img width="380" height="154" alt="image" src="https://github.com/user-attachments/assets/89b6a337-eff7-44d3-b7ae-ade5aba40890" />


3. Which body type gives negative GWT rate? --> Hatchback has a negative GWT vs PY

<img width="366" height="160" alt="image" src="https://github.com/user-attachments/assets/734a99e4-cc3a-4eae-b660-efa341c9936a" />





Conclusions:

* The car sales performance dashboard successfully addressed the lack of a centralized and reliable reporting system by providing clear visibility into company performance.
* It enabled the identification of high-performing and underperforming companies, supported data-driven decision-making, and provided a foundation for continuous performance improvement and strategic planning.


Recommendation:

* The -1% negative growth in the Hatchback body type represents a critical drag on the 24% aggregate growth. This has to be investigate.
* Continous Performance Review - conduct periodic performance reviews using the dashboard to monitor progress, evaluate the effectiveness of implemented strategies,
   and take corrective actions where performance gaps persist.
* Optimize Product and Model Mix - Focus on high-demand and high-margin car models while reviewing or discontinuing consistently underperforming models.
*  Scale Best Practices from Top Performers - Analyze high-performing companies to understand successful strategies. Replicate these best practices across underperforming companies where applicable.

<img width="690" height="127" alt="image" src="https://github.com/user-attachments/assets/38a91e46-d0fe-4a56-8618-483d29fd4eae" />

<img width="366" height="160" alt="image" src="https://github.com/user-attachments/assets/734a99e4-cc3a-4eae-b660-efa341c9936a" />




   





















