
## **Exploring the Dynamics of Social Media Marketing for a Technology Store**
## *A case study of a technology store named Krest_Tech*

## **Introduction**
**In today's digital age, businesses have discovered an influential avenue for reaching their target audience: social media platforms.** Among these platforms, Facebook stands out as a powerhouse, offering businesses the opportunity to engage with potential customers in innovative ways. This data analysis project delves into the realm of social media marketing using a dataset from a technology store specializing in gadgets such as phones, accessories, and laptops.


## **Description**
This project analyzes a dataset from a technology store's Facebook ad campaigns. We investigate how these campaigns, targeting gadgets like phones and laptops, influence user engagement, demographic responses, and conversion rates.

By examining impressions, clicks, and conversion metrics, we aim to uncover actionable insights for enhancing the store's social media marketing strategy and overall business success.


## Understanding Social Media Marketing:
Social media marketing refers to the strategic use of social media platforms to promote products, services, or brands, with the ultimate goal of driving customer engagement, brand visibility, and conversion rates. In the context of our project, the technology store has leveraged Facebook as its chosen social media platform. This involves creating and sharing compelling content, targeting specific demographics, and measuring the effectiveness of campaigns through various metrics.

## Importance to Business Success:
The significance of social media marketing in today's business landscape cannot be overstated. It offers a unique blend of accessibility, reach, and personalization that traditional marketing methods struggle to replicate. Through targeted advertising, businesses can connect with their intended audience more effectively than ever before. Moreover, the interactive nature of social media fosters real-time engagement, enabling businesses to build relationships with customers, address concerns promptly, and gather valuable feedback.

## Business Objectives
### The business objectives of this project are as follows:

1. Optimize Campaign Performance: This aim to identify the most successful ad campaigns in terms of impressions, clicks, and conversions. This will help stakeholders understand which strategies effectively engage our target audience and generate positive outcomes.

3. Refine Demographic Targeting: By analyzing demographic data, we intend to pinpoint age and gender groups that show the highest response rates. This knowledge will in tailoring future campaigns to specific audience segments for maximum impact.

4. Enhance Conversion Rates: The goal is to delve into the correlation between ad engagement metrics and conversion rates. This will allow us to uncover patterns and insights that can be leveraged to increase the effectiveness of our campaigns in driving conversions.

5. Measure ROI: Assessing the return on investment (ROI) for each ad campaign by comparing the advertising expenditure to the achieved conversions. This analysis will provide a clear picture of the cost-effectiveness of our social media marketing efforts.

6. Informed Decision-Making: By interpreting the data, equiping clients with actionable insights that can guide strategic decision-making. These insights will enable them to adapt  social media marketing tactics, allocate resources efficiently, and maximize the value delivered to the business.

## Business Questions
## Here are some key business questions that can be addressed through this project:
1. Are there specific age or gender segments that show higher engagement or conversion rates?
2. Are there any correlations between ad engagement metrics and specific user interests?
3. What is the engagement of the ad campaign?
4. Which audience demographics(age, gender) were most engaged with the ads?
5. What is Use click-through rate (CTR) of the ad campaign? 
6. What is the conversion rate of the ad campaign?
7. What is Use cost per click (CPC) and cost per impression (CPM) of the ad campaign?
8. Are there any correlations between ad engagement metrics and specific user interests?
9. What is the relationship between impressions, clicks, and conversion rates across various ad campaigns?








## Dataset Overview:
This analysis focuses on a dataset comprising various parameters related to Krest Tech store's Facebook ad campaigns. These parameters include the ad campaign IDs, audience demographics (age and gender), user interests, impressions, clicks, advertising expenditure (spent), and different types of conversions (total and approved). By scrutinizing this dataset, we aim to uncover insights into the effectiveness of the ad campaigns, the impact of demographic targeting, and the correlation between various metrics and conversions.


## Data Cleaning and Preparation
The dataset comprises of 1143 records of data gotten from kaggle website.
Data cleaning procedures implemented on the datset inculdes: 
1. Renamaing columns
2. Changing columns datatype
3. Column Value Mapping

The dataset was further normalised into to two tables to adhere to the principles of data modelling. The data tables include:
- Marketing
- Products

Marketing Table             |           Products Table
:--------------------------:|:------------------------:
![](marketing.png)          |         ![](products.png)

## Data Modelling Design

![Data Modelling](data_model.png)

<br/>

## Business metrics and KPIs
These metrics and KPIs provide insights into various aspects of the ad campaigns' performance, engagement, conversion rates, and return on investment. They can guide decision-making and strategy refinement for the technology store's social media marketing efforts.

### 1. Click-Through Rate (CTR):
- CTR = (Clicks / Impressions) * 100

This metric indicates the percentage of users who clicked on the ad after viewing it.

### 2. Conversion Rate:
- Conversion Rate = (Total_Conversion / Clicks) * 100

This measures the percentage of users who took the desired action (conversion) after clicking on the ad.

### 3. Approved Conversion Rate:
- Approved Conversion Rate = (Approved_Conversion / Clicks) * 100

This calculates the percentage of users whose conversions were approved.


### 4. Cost per Click (CPC):
- CPC = Spent / Clicks

This metric shows the average cost incurred per click on the ad.

### 5. Cost per Conversion:
- Cost per Conversion = Spent / Total_Conversion

This indicates the average cost required to achieve each conversion.


### 6. Return on Ad Spend (ROAS):
- ROAS = (Approved_Conversion Value / Spent) * 100

This KPI measures the revenue generated per unit of ad spend.


### 7. Cost per Mille (CPM):
- CPM = (Spent / Impressions) * 1000

This metric calculates the cost of reaching 1000 users (impressions).


### 8. Conversion Value per Click:
- Conversion Value per Click = (Approved_Conversion Value / Clicks)

This represents the average value generated by each click in terms of conversions.


### 9. Conversion Value per Cost:
- Conversion Value per Cost = (Approved_Conversion Value / Spent)

This metric measures the value generated for each unit of ad spend.


### 10. Conversion-to-Click Rate:
- Conversion-to-Click Rate = (Total_Conversion / Clicks) * 100

This KPI shows the percentage of users who converted after clicking on the ad.


### 11. Engagement Rate:
- Engagement Rate = ((Clicks + Total_Conversion) / Impressions) * 100

This measures the overall interaction and engagement with the ad.


### 12. Gender-Based Conversion Rate:
- Gender-Based Conversion Rate = (Total_Conversion for a Gender / Total Clicks for that Gender) * 100

This shows the conversion rate for each gender group.

