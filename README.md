This is a sample project to showcase Excel and Power BI skills.

This data is from kaggle.com and includes records from 2022 - 2023.

Data Source: https://www.kaggle.com/datasets/missionjee/car-sales-report

<img width="1406" height="790" alt="image" src="https://github.com/user-attachments/assets/e5497212-8239-4377-903c-6dc9cc9dbe5b" />


GOAL: 

1. Use MS Excel skills to manipulate data in preparation for visualization
2. Use Power BI skills to effectively visualize data for meaningful data-driven decisions.


The question we want to answer:

1. Which company gives the highest sales in USD?
2. Which dealer gives a highest sales in USD?
3. Which region gives a highest GWT?
4. Which body type gives negative GWT rate?
5. Which car color gives a highest sales in USD?

Data:

It is about the Car Sales made between 2022 - 2023. Made this data based on my experience in Data and Business Reporting Analyst.

<img width="1690" height="977" alt="image" src="https://github.com/user-attachments/assets/fa9228c2-3127-4682-8a5d-f5a72b3d878f" />


Data Cleaning and Processing:

1. Standardize and trim the header to ensure correct alignment and remove unnecessary spaces.

<img width="1911" height="226" alt="TRIM" src="https://github.com/user-attachments/assets/f7b430e0-fb59-4a65-9415-328fae68a393" />

2. Load in Power BI and add new date column in Model view for relationship and also to maintain proper sequence by month.

<img width="1318" height="457" alt="ADD NEW TABLE DATE" src="https://github.com/user-attachments/assets/45764613-606c-4785-9090-0b1e653b0d15" />

3. Create relationship

<img width="681" height="771" alt="CREATE RELATIONSHIP" src="https://github.com/user-attachments/assets/7f92ace0-21ec-4cd5-b7c7-856d8ace6ade" />

4. Sorting month by month number to maintain proper sequence (etc. Jan, Feb, Mar)

<img width="1669" height="604" alt="SORT MONTH BY NUMBER" src="https://github.com/user-attachments/assets/9b456ab6-4c7f-45d6-ac0b-e9fcbd522163" />

5. Rename column 'Price' - 'Sales' in Power Query to easily recognize the column of the sales and also for DAX preparation.

<img width="1731" height="489" alt="RENAME COLUMN" src="https://github.com/user-attachments/assets/58470599-060f-464b-9207-6279e4e0c9e2" />

6. Create DAX sum total sales

<img width="779" height="34" alt="SUM TOTAL SALES" src="https://github.com/user-attachments/assets/9b7763de-3469-44af-adba-ecd255c6f2fa" />

8. Create DAX calculate total sales by 2022

<img width="758" height="35" alt="CALCULATE TOTAL SALES 2022" src="https://github.com/user-attachments/assets/6d1ffcf4-11e0-4cee-a610-eb29281a4712" />

8. Create DAX calculate total sales by 2023

<img width="783" height="34" alt="CALCULATE TOTAL SALES 2023" src="https://github.com/user-attachments/assets/02cba745-667a-4479-ad94-c9778d6897a5" />

9. Create DaX count total customer.

<img width="573" height="25" alt="image" src="https://github.com/user-attachments/assets/4d6f6fbf-88bb-4761-976b-f8ff5a81d9df" />

10. Create DAX percent contribution sales by gender.

<img width="621" height="120" alt="GENDER CONTRI" src="https://github.com/user-attachments/assets/bf6aab47-804a-4f2d-910a-a5ca06256aa5" />

11. Create DAX percent growth this is to easily assess if a specific category is performing better or not.

<img width="627" height="35" alt="% GWT" src="https://github.com/user-attachments/assets/db52a18f-2838-44c0-8d3b-3d0b2f9f2092" />

Findings: 

1. Which company gives the highest sales in USD? --> Chevrolet (answer may vary if filtered per year)

<img width="486" height="251" alt="image" src="https://github.com/user-attachments/assets/ac12dff2-08f2-44d1-b1e9-9e1db23e266b" />


2. Which dealer gives a highest sales in USD? --> Rabun Used Car Sales this is the top 1 from the highest sales by dealer.

<img width="403" height="249" alt="image" src="https://github.com/user-attachments/assets/a03e85d1-9edc-4186-80a6-82f5bd27b84c" />


3. Which region gives a highest GWT? Scottsdale has a highest Gwt vs PY 

<img width="380" height="154" alt="image" src="https://github.com/user-attachments/assets/89b6a337-eff7-44d3-b7ae-ade5aba40890" />


4. Which body type gives negative GWT rate? --> Hatchback has a negative GWT vs PY

<img width="366" height="160" alt="image" src="https://github.com/user-attachments/assets/734a99e4-cc3a-4eae-b660-efa341c9936a" />


5. Which car color gives a highest sales in USD? --> Pale white has a highest sales by color

<img width="388" height="128" alt="image" src="https://github.com/user-attachments/assets/f5a05f7b-b8af-4822-8848-caf00ad66062" />




Recommendation:

1. The analysis shows strong, healthy business with 24% sales growth (2023 vs 2022).
2. The -1% negative growth in the Hatchback body type represents a critical drag on the 24% aggregate growth. This has to be investigate.

<img width="690" height="127" alt="image" src="https://github.com/user-attachments/assets/38a91e46-d0fe-4a56-8618-483d29fd4eae" />

<img width="366" height="160" alt="image" src="https://github.com/user-attachments/assets/734a99e4-cc3a-4eae-b660-efa341c9936a" />




   





















