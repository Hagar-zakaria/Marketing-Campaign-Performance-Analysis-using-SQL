![image](https://github.com/user-attachments/assets/ea082bc4-291f-48b3-a94f-adad5b2ed7c9)


# Marketing-Campaign-Performance-Analysis-using-SQL
This article analyzes marketing campaign data using SQL, evaluating performance across Facebook, Instagram, and Pinterest. It identifies insights on campaign effectiveness, channel ROI, and device performance, providing recommendations to optimize strategies. The analysis uses Microsoft SQL Server and Tableau Desktop.

## Introduction
This article provides an analysis of a fictitious company's marketing campaign. The company ran multiple campaigns on Facebook, Instagram, and Pinterest, collecting data on impressions, clicks, spend, conversions, and engagement. As a data analyst, I used the six stages of data analysis to evaluate the campaign's effectiveness and suggest improvements.

## Ask
**Problem Statement:** Analyze the data to gain insights, optimize ad spend, and improve future strategies.

## Prepare
**Data Description:** The dataset has 9,900 rows and 18 columns, including campaign names, dates, cities, channels, devices, impressions, CTR, clicks, CPC, spend, conversions, and engagement metrics.

The CSV file, with total rows 9,900, has 18 columns which include the following:

- Campaign: Name of the marketing campaign.
- Date: Date for daily ad performance metrics.
- City/Location: Cities that were targeted by the campaign.
- Latitude: Latitude for the cities.
- Longitude: Longitude for the cities.
- Channel: Channel where ads were displayed (Facebook, Instagram, Pinterest).
- Device: Device from which ads were viewed.
- Ad: Ads used within a campaign.
- Impressions: Daily impressions (times ad was shown to a viewer) for each ad.
- CTR, %: Daily average click-through rate for each ad.
- Clicks: Daily clicks for each ad.
- Daily Average CPC: Daily average cost-per-click for each ad.
- Spend, GBP: Total daily amount of advertising spending for each ad, in GBP.
- Conversions: Total daily purchases attributed to a specific ad.
- Total conversion value, GBP: Total amount in GBP received from purchases attributed to a specific ad.
- Likes: Total daily likes (or other reactions) per ad.
- Shares: Total daily shares per ad. For simplicity, each Pin on Pinterest is counted as a share.
- Comments: Total daily comments per ad.
  
## Process
**Tool Used:** I used Microsoft SQL Server Management Studio for this analysis.

When I looked at the data, I found it to be clean and ready for analysis. There were no major issues like duplicates, missing values, or incorrect data types. The data was consistent and accurate, and there were no outliers that could affect the results. So, no further cleaning or transformation was needed.

# Analyze and Share
**Tools Used:** Microsoft SQL Server and Tableau Desktop

**Key Questions and SQL Queries:**

1. **Which campaign generated the highest number of impressions, clicks, and conversions?**

- Highest impressions, clicks, and conversions:
  
![image](https://github.com/user-attachments/assets/28289b20-dad9-4f6a-8ead-3117c6b65ede)

![image](https://github.com/user-attachments/assets/7b69e227-6263-45b0-a095-1af5dc35beae)

- **Analysis:** According to the data, the total clicks, impressions, and conversions are all highest during the Fall campaign, followed by the Summer campaign. All of these are at least during the Spring campaign.

2. **What is the average cost-per-click (CPC) and click-through rate (CTR) for each campaign?**

- Cleaning and converting the CTR column:

![image](https://github.com/user-attachments/assets/06cdf866-d96e-4059-970f-e83ae0b7496c)

![image](https://github.com/user-attachments/assets/021197cb-396d-400c-89f7-267f345b6e84)


- Calculating average CPC and CTR:

![image](https://github.com/user-attachments/assets/5cee1001-d7ee-4d62-8b24-bb76593bd9eb)

- **Analysis:** the average cost per click and the average click through rate was at peak during the Fall campaign. Followed closely by the Summer campaign.
- 
3.**Channel Effectiveness:**
 **Which channel has the highest ROI?**
  
  - Highest ROI:
    
![image](https://github.com/user-attachments/assets/d2bdc50b-b6d4-4229-a2a1-05502e8b6b36)

![image](https://github.com/user-attachments/assets/895fbadf-7ca1-4241-b52f-a7e1d82555c1)


- **Analysis:** The highest ROI was from Pinterest followed by Instagram. The ROI is least in Facebook.
- 
**How do impressions, clicks, and conversions vary across different channels?**

![image](https://github.com/user-attachments/assets/0b804e16-6a0b-4ba5-b724-abb403af17b6)

![image](https://github.com/user-attachments/assets/f11e24c0-7d86-4c33-b464-13a3be0e4beb)

4. **Geographical Insights:**

**Which cities have the highest engagement rate (likes, shares, comments)?**

- Highest engagement rates:

![image](https://github.com/user-attachments/assets/d552fb43-ebac-45cf-8a10-4efa10c70a6a)

![image](https://github.com/user-attachments/assets/7f096af3-fada-4116-bd89-589473d7266e)

- **Analysis:** Across all the channels, Facebook has the highest clicks and impressions, but interestingly, Instagram has the highest conversion.
  
5. **Device Performance:**

- Comparing ad performance across devices:
  
**How do ad performances compare across different devices (mobile and desktop)?**

![image](https://github.com/user-attachments/assets/39f34378-3579-49a7-8ad3-32debf204551)

![image](https://github.com/user-attachments/assets/3f9ecb46-8cf8-4d96-b3c2-d5c80297f232)

- **Analysis:**  comparing the performance of Ads across different devices, the total click and the total impression peak on mobile, but interestingly, Instagram has the highest conversion.

6. **Ad Performance:**

**Which specific ads are performing best in terms of engagement and conversions ?**

- Best-performing ads:

  ![image](https://github.com/user-attachments/assets/56e30ab2-501d-4b46-bb67-7e1cd860b3ae)

![image](https://github.com/user-attachments/assets/6e29210a-7018-4ae2-8de4-80cf0f952a60)

- **Analysis:** Discount Ads had the most clicks, while Collection Ads had higher impressions and conversions.

7. **ROI Calculation:**

- ROI for each campaign, channel, and device:

![image](https://github.com/user-attachments/assets/a86f5922-8f56-44bc-8b13-ab1ab3543616)

![image](https://github.com/user-attachments/assets/4abd8d0d-b7c5-4028-a41c-bb5a178f450b)

- **Analysis:** analysis reveals that Discount Ad has more clicks, but impressions and conversions are higher in Collection Ad.

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
