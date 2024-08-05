# Duns-Store Data Analysis

## Table of Contents
- [Introduction](#Introduction)
- [Problem statement](#Problem-Statement)
- [Justification of Dashboard and Analysis](#Justification-of-Dashboard-and-Analysis)
   - [Data Source](#Data-Source)
   - [Data Preparation](#Data-Preparation)
   - [Model Planning and Building](Model-Planning-and-Building)
   - [Communicate Results and Operationalise](#Communicate-Results-and-Operationalise)
- [Justification of Dashboard](#Justification-of-Dashboard)
- [Recommendation and Conclusion](#Recommendation-and-Conclusion)

### Introduction

This data project of a company with multinational retailer with locations in 147 countries, including the United States will be represent as Duns Store. The company provides a variety of products, including office supplies, furniture, and technology, to consumers, corporations, and home offices. In 2014, the revenue of Dun's shop exceeded $500,000. The retail industry is characterised by a high level of competitiveness and dynamism, as businesses face numerous challenges, including shifting consumer behaviour, intensified competition, and fluctuating market trends, all of which contribute to a sales decline. To achieve growth and maintain competitiveness, businesses must analyse their sales performance effectively.

### Problem statement

Due to disparities in sales and market presence across various segments, categories, and regions, DUNs Stores faces challenges in its retail sales performance. Despite growth, there are significant disparities between product segments, geographic regions, and consumer categories in terms of sales and profit margins. Some regions, including EMEA and African regions, have negative profit margins, indicating possible inefficiencies and market penetration difficulties. 

This report will investigate how Business Intelligence can increase Duns's retail sales. Using tables, diagrams, and charts, the data visualization and reporting software Power BI generates interactive dashboards of key performance indicators such as sales revenue, profit, and margin. In addition, product categories, consumer segments, and geographic regions are examined by analyzing sales trends over time. The results of the Duns store dataset will provide valuable insights into the sales performance of a retail company, allowing for the identification of areas for advancement and the development of more effective strategies.


### Justification of Dashboard and Analysis
### Data Source

The dataset, which contains information about Duns's store product ID, category, sales, profit, and discount, was sourced from Kaggle through a search specifically targeting sales datasets.

### Data Preparation

The dataset acquired from Kaggle was accessed and loaded into Microsoft Excel for further analysis. During this stage, a new column entitled "Gross Profit" was introduced by employing the following command: (=Profit/Sales). The purpose of this operation was to calculate and record the gross profit values corresponding to the dataset entries.

### Model Planning and Building

Upon importing the dataset into Power BI, it underwent a series of transformations in the Power BI Query Editor. Subsequently, a comprehensive review was carried out to identify and rectify any errors present in the loaded datasets, ensuring data integrity and accuracy.

### Communicate Results and Operationalise

In the final step of the process, the obtained results were thoroughly validated to ensure their accuracy and reliability. The Key Performance Indicator (KPI) measurements were then prominently presented on the Power BI dashboard, culminating the data analysis and visualization phase.

### Justification of Dashboard

On Duns’s store dashboard, pie, bar, donut, funnel, area, and treemap charts are used to display the annual profit, total sales by nation, category, segment, state, and profit by segment and category.

![Duns’s store dashboard](https://github.com/user-attachments/assets/bf3a4cdf-d538-48f6-9027-81e80464e0f7)

- Slicers for Duns store

The dashboard's three categories are segments, years, and countries inorder to permit efficient and rapid data analysis.

  ![Slicers](https://github.com/user-attachments/assets/e19c29d4-327e-4d7f-b906-55979f7ad012)

- Sum of Sales by Country

The chart shows the total sales of DUNs Stores in various countries, with the United States in the lead with $2,297,354, followed by Australia and France with $925,257 and $858,949, respectively. Additionally, sales in China and Germany are substantial, indicating a robust market presence.

![Sales by Country](https://github.com/user-attachments/assets/9f36970e-3fc6-49bf-bc4e-6aab21ddde6d)

- Sum of Sales by Category

This illustrates DUNs Stores' total sales of technology, office furniture, and office supplies. Technology generates the most revenue with $4,744,691, followed by Furniture with $4,110,884 and Office Supplies with $3,783,330.

![Sales by Category](https://github.com/user-attachments/assets/b2fe591c-b909-40b8-9349-210419989cbf)

- Sum of Profit by Year

This shows the sum of DUNs Stores' annual profits over a four-year period. The graph depicts an upward trend with earnings increasing from $248,940.8115 in 2011 to $307,415.2791 in 2012, then to $408,512.7602 in 2013, and ultimately to $504,167.0805 in 2014.

![Profit by Year](https://github.com/user-attachments/assets/8bd0f677-1e0f-4578-8b30-7579fadb6f48)

- Sum of Sales by Segment

This shows the total sales for the three segments of DUNs Stores: consumer, corporate, and home office. Consumer revenue leads with $6,508,141, followed by Corporate with $3,824,808 and Home Office with $2,309,956.

![Sales by Segment](https://github.com/user-attachments/assets/5042dd8f-face-40fa-9a69-a33d5485076e)

- Sum of Profit by Segment

The Consumer segment has the highest profit of $43,835,365, followed by Corporate with $15,631,185, and Home Office with $13,721,984.

![Profit by Segment](https://github.com/user-attachments/assets/e3188aa4-9475-4631-bd07-2111da545037)

- Sum of Sales by Region

The data indicates that sales statistics in various locations vary. The Central region is in first place with $2,822,399, followed by the South with $1,600,960 and the North with $1,241,192. Oceania and Southeast Asia had significant sales of $1,100,207 and $884,438 while North Asia and EMEA exceeded $800,000. In addition, sales projections for Africa and Central Asia are $783,776 and $758,339, respectively. Canada has the lowest sales, at $66,932, compared to the East, West, and Caribbean regions.

![iSales by Region](https://github.com/user-attachments/assets/9840ab1e-abb2-4710-a784-d011f01567d3)


- Sum of Profit by Category

The leading category is Technology with $663,778.7332, followed by Office Supplies with $518,474.9443 and Furniture with $286,782.2538. DUNs Stores should diversify its electronic offerings and invest in product development to attract tech-savvy customers.

![Profit by Category](https://github.com/user-attachments/assets/e04d562e-7ea2-4c0a-9590-8c30bfd9a434)

- Average of Gross Profit Margin by Market

The United States ranks second (12.02%), followed by the European Union (11.04%). APAC (6.96%) and LATAM (6.17%) profit margins are moderate. EMEA and Africa have negative profit margins of -14.16 and -14.56%, respectively. DUNs Stores should prioritize expanding their presence in Canada and the United States in order to capitalize on opportunities.

  ![Average of Gross Profit Margin by Market](https://github.com/user-attachments/assets/81a4446b-c9b3-48d7-a7a3-162f2e3e4eb1)


### Recommendation and Conclusion

In conclusion, DUNs Stores's retail sales performance is hindered by disparities in sales and market presence across segments, product categories, and geographic regions. The analysis revealed that the Consumer segment has the highest total sales and profits, while the Corporate and Home Office segments lag behind. Limited market demand, product perception, ineffective inventory management, and inadequate customer satisfaction are identified as potential causes of the problem. To address these obstacles and improve retail sales performance, it is recommended to implement a Business Intelligence (BI) system that enables management to make organization-wide decisions based on accurate data.

Business intelligence (BI) implementation in Duns stores has the potential to improve sales performance, decision-making skills, territory optimisation, and operational efficiency. To improve sales performance and maintain a competitive edge in the retail industry, Duns Store must implement strategic measures such as market research, innovative products, customer experience management, inventory optimisation, targeted marketing campaigns, and strategic partnerships. Duns Store should implement business intelligence to assist with the prioritisation of targeted marketing, product diversification, and regional preferences in order to remain abreast of emerging industry trends and maintain a competitive advantage. Moreover, the BI dashboard will provide daily insights into the optimal allocation of DUNs Stores' expansion efforts in Canada and the United States. Furthermore, it will facilitate the optimisation of pricing strategies, supply chain operations, and the adoption of sustainable business practises. These measures will help DUNs Stores overcome sales performance obstacles, increase profitability, and maintain its competitive edge in the retail industry.
