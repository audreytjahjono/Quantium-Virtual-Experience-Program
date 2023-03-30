# Quantium Virtual Experience Program
Studied customer behavior, tested store layouts, and created reports.

## Note
All these code files were my personal submissions for this program. Except for the data files which were assigned by Quantium.

## Introduction
Quantium is a leading data science and AI firm founded in Australia in 2002. In this project, I am part of Quantium's retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to understand better the types of customers who purchase Chips and their purchasing behavior within the region. The insights from my analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

## Task 1 : Data Preparation and Customer Analytics
Analyzed the client's transaction dataset and identified customer purchasing behaviors to generate insights.

**Main goals of this task are :**
1. Examine transaction data - check for missing data, anomalies, outliers and clean them
2. Examine customer data - similar to above transaction data
3. Data analysis and customer segments - create charts and graphs, note trends and insights
4. Deep dive into customer segments - determine which segments should be targetted

### Findings

- The top 3 total sales contributor segments are:
1. Older families (Budget) $156,864
2. Young Singles/Couples (Mainstream) $147,582
3. Retirees (Mainstream) $145,169
- Young Singles/Couples (Mainstream) has the highest population, followed by Retirees (Mainstream). Which explains their high total sales.
- Despite Older Families not having the highest population, they have the highest frequency of purchase, which contributes to their high total sales.
- Older Families followed by Young Families have the highest average quantity of chips bought per purchase.
- The Mainstream category of "Young and Mid-age Singles/Couples" have the highest spending of chips per purchase. And the difference between the non-Mainstream "Young and Mid-age Singles/Couples" are statistically significant.
- Chips brand Kettle is dominating every segment as the most purchased brand.
- Observing the 2nd most purchased brand, "Young and Mid-age Singles/Couples" is the only segment with a different preference (Doritos) as compared to others' (Smiths).
- The most frequent chip size purchased is 175gr followed by the 150gr chip size for all segments.

### Recommendations

- Older Families: Focus on the Budget segment. Strength 1: Frequent purchases. We can give promotions that encourage more frequency of purchase. Strength 2: High quantity of chips purchased per visit. We can give promotions that encourage them to buy more quantity of chips per purchase.
- Young Singles/Couples: Focus on the Mainstream segment. This segment is the only one with Doritos as their 2nd most purchased brand (after Kettle). To specifically target this segment it might be a good idea to collaborate with Doritos merchants to do some branding promotion catered to the "Young Singles/Couples - Mainstream" segment. Strength: Population quantity. We can spend more effort on making sure our promotions reach them, and it reaches them frequently.
- Retirees: Focus on the Mainstream segment. Strength: Population quantity. Again, since their population quantity contributes to the high total sales, we should spend more effort to ensure our promotions reach as many of them as possible and frequently.
- General: All segments have Kettle as the most frequently purchased brand, and 175gr (regardless of brand) followed by 150gr as the preferred chip size. When promoting chips in general to all segments, it is good to take advantage of these two points.

## Task 2 : Experimentation and Uplift Testing
Tested the impact of the trial store layouts on customer sales.

This can be broken down by:
- total sales revenue
- total number of customers
- the average number of transactions per customer

Create a measure to compare different control stores to each trial store. To do this, write a function to reduce having to re-do the analysis for each trial store. 
- period before trial: 07/2018 to 02/2019 (8 months)
- trial period: 03/2019 to 06/2019 (4 months)

**The main areas of Focus are :**
1. Select-control stores – Explore data, define metrics, visualize graphs
2. Assessment of the trial – insights/trends by comparing trial stores with control stores
3. Collate findings – summarize and provide recommendations.

### Findings

- Trial store 77 sales for Feb, March, and April exceed the 95% threshold of the control store. The same goes to store 86 sales for all three trial months.
1. Trial store 77: Control store 233
2. Trial store 86: Control store 155
3. Trial store 88: Control store 40
- Both trial stores 77 and 86 showed a significant increase in Total Sales and Number of Customers during the trial period. But not for trial store 88. Perhaps the client knows if there's anything about trial 88 that differs from the other two trials.
- Overall the trial showed positive significant results.

## Task 3 : Visualization Report
Used analytics and insights and prepared a report for the Category Manager.

**The main goals of the task are:**
1. The data literacy level of your audience
2. Table of contents/agenda
3. Problem statement/purpose
4. Overview and context
5. Content balance
6. Layout and content display
7. Summary / next steps

