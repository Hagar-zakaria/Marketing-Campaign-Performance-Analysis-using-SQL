![image](https://github.com/user-attachments/assets/b3a1385c-96ad-4315-af1b-d6cd30b44dfd)# Marketing-Campaign-Performance-Analysis-using-SQL
This article analyzes marketing campaign data using SQL, evaluating performance across Facebook, Instagram, and Pinterest. It identifies insights on campaign effectiveness, channel ROI, and device performance, providing recommendations to optimize strategies. The analysis uses Microsoft SQL Server and Tableau Desktop.

## Introduction
This article provides an analysis of a fictitious company's marketing campaign. The company ran multiple campaigns on Facebook, Instagram, and Pinterest, collecting data on impressions, clicks, spend, conversions, and engagement. As a data analyst, I used the six stages of data analysis to evaluate the campaign's effectiveness and suggest improvements.

## Ask
**Problem Statement:** Analyze the data to gain insights, optimize ad spend, and improve future strategies.

## Prepare
**Data Description:** The dataset has 9,900 rows and 18 columns, including campaign names, dates, cities, channels, devices, impressions, CTR, clicks, CPC, spend, conversions, and engagement metrics.

## Process
**Tool Used:** Microsoft SQL Server Management Studio (SSMS). The dataset was clean with no duplicates or missing values.

# Analyze and Share
**Tools Used:** Microsoft SQL Server and Tableau Desktop

**Key Questions and SQL Queries:**

1. **Campaign Performance:**

- Highest impressions, clicks, and conversions:
  
![image](https://github.com/user-attachments/assets/28289b20-dad9-4f6a-8ead-3117c6b65ede)

- Analysis: The Fall campaign had the highest impressions, clicks, and conversions.

2. **Average CPC and CTR:**

- Cleaning and converting the CTR column:

![image](https://github.com/user-attachments/assets/06cdf866-d96e-4059-970f-e83ae0b7496c)


- Calculating average CPC and CTR:

![image](https://github.com/user-attachments/assets/5cee1001-d7ee-4d62-8b24-bb76593bd9eb)

- **Analysis:** The Fall campaign had the highest average CPC and CTR.
- 
3.**Channel Effectiveness:**

  - Highest ROI:
    
![image](https://github.com/user-attachments/assets/d2bdc50b-b6d4-4229-a2a1-05502e8b6b36)

- **Analysis:** Pinterest had the highest ROI, followed by Instagram.

4. **Geographical Insights:**

- Highest engagement rates:

![image](https://github.com/user-attachments/assets/d552fb43-ebac-45cf-8a10-4efa10c70a6a)

5. **Device Performance:**

- Comparing ad performance across devices:

![image](https://github.com/user-attachments/assets/39f34378-3579-49a7-8ad3-32debf204551)

- **Analysis:** Mobile devices had the highest clicks and impressions, with Instagram showing the highest conversions.

6. **Ad Performance:**

- Best-performing ads:

  ![image](https://github.com/user-attachments/assets/56e30ab2-501d-4b46-bb67-7e1cd860b3ae)

- **Analysis:** Discount Ads had the most clicks, while Collection Ads had higher impressions and conversions.

7. **ROI Calculation:**

- ROI for each campaign, channel, and device:

![image](https://github.com/user-attachments/assets/a86f5922-8f56-44bc-8b13-ab1ab3543616)

- **Analysis:** Highest ROI was via Pinterest, during the Summer campaign, and on desktop devices.

8. **Spend vs. Conversion:**

- Correlation between spend and conversion value:

![image](https://github.com/user-attachments/assets/1c192534-6007-46b2-b894-5df66d8f9f55)

- **Analysis:** Spend positively correlates with conversions, peaking during the Fall campaign.

# Act
# Recommendations:

- Reassess and improve the Spring campaign strategy to boost conversions.
- Investigate Facebook's low conversion rate despite high impressions and clicks.
- Focus more on Instagram for better engagement and conversions.

By following these steps, the company can enhance their marketing strategies and achieve better performance in future campaigns.
