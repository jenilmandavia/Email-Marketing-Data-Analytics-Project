# Email-Marketing-Data-Analytics-Project
This project shows the email marketing analytics and covers the reasons behind unsubscribe rates. We will explore unsubscribe trends, click rates, identify pattern across categories and provide data-driven recommendation to improve customer engagement and reduce churn.  

This project focuses on analyzing email marketing performance to understand key factors contributing to user engagement and unsubscribes. The analysis answers business questions such as:

What is the overall unsubscribe rate?

Which categories or campaigns experience has highest and lowest unsubscribe rates?

How do open, click, and unsubscribe rates vary by send time?

What are the major reasons for unsubscribes?

What strategic actions can reduce subscriber churn?

This project uses:  
SQL for data analysis

Power BI for interactive dashboards

Dataset source: email_marketing.db

## **📊 Key Metrics**

Metric	Value  
Overall Open Rate	59.72%  
Overall Click Rate	18.07%  
Overall Unsubscribe Rate	5.05%  

## **🧠 Insights & Findings**

**1. Campaign Performance by Category**

Re-engagement & Newsletter campaigns had the highest open rates (~60%) and lowest unsubscribe rates which stood at (4.87%) and (4.82%)
Highest unsubscribe Rate - Promotions(5.36%), Lowest Unsubscribe Rate - Newsletter(4.82%).
Announcement emails showed moderate open but lower unsubscribe rates.

**2. Best & Worst Performing Campaigns**

Campaign 13 has the lowest unsubscribe rate(3.40%) which is a newsletter while Campaign 2 has the highest unsubscribe rate(5.87%) which is a promotion. 
Campaign 11 which is a newsletter is one of the optimal campaign as it has highest open rate (62.53%) and very low unsubscribe rate(4.13%) 
As the open rate decreases, unsubscribe rate increased. This also shows that the content and the subject line matters the most. 

**3. Send Hour Impact**

Best engagement hours: 10 AM to 12 PM, showing peak opens and clicks.
Engagement drops sharply after 2 PM, and unsubscribe counts increase slightly.

**4. Reasons for Unsubscription**

Most common unsubscribe reasons:  
Privacy Concerns  
Not Relevant  
Found better brand  
Too many emails  

These issues are especially high in promotion and newsletter categories.

**5. Category-Wise Unsubscribes**
Re-engagement emails have lower unsubscribe complaints, meaning users respond well to personalized content.


## **✅ Recommendations for Improvement**

✔ **Optimize Send Time:** Focus email campaigns between 10 AM–12 PM to maximize engagement.
✔ **Segment Users & Personalize Content:** Use behavioral data to send relevant content (especially for re-engagement and newsletter categories).
✔ **Address Privacy Concerns:** Clearly communicate data protection policies, include trust badges, and provide transparent explanations of how user data is stored and used.
✔ **Improve Subject Lines & Content Quality:** Particularly for campaigns with low clicks but high opens.
✔ **Enhance Content Relevance:** Since “Not Relevant” is the 2nd most reason for unsubscribes, segment users based on interests and demographics to send more personalized and meaningful content.

