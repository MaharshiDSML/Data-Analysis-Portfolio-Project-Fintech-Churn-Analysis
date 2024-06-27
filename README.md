# <mark>Fintech-Churn-Analysis</mark>

## <mark>Business Problem Statement:</mark>

- In the rapidly evolving banking sector, customer retention has become a critical concern.
- Banks are increasingly seeking to understand the factors that influence customer decisions to stay with or leave their banking service provider.
- This project focuses on analyzing a dataset containing various attributes of bank customers to identify key predictors of customer churn.
- By leveraging data analytics, we aim to uncover patterns and insights that could help devise strategies to enhance customer retention and reduce churn rates.

## <mark>Data description:</mark>

Dataset link:https://drive.google.com/file/d/1xh7D0NDmxdg6IXTFzi_T-Oc5D-GtI44W/view?usp=sharing

- RowNumber—corresponds to the record (row) number and has no effect on the output.
- CustomerId—contains random values and has no effect on customer leaving the bank.
- Surname—the surname of a customer has no impact on their decision to leave the bank.
- CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
- Geography—a customer’s location can affect their decision to leave the bank.
- Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.
- Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
- Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
- Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
- NumOfProducts—refers to the number of products that a customer has purchased through the bank.
- HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
- IsActiveMember—active customers are less likely to leave the bank.
- EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
- Exited—whether or not the customer left the bank.
- Complain—customer has complaint or not.
- Satisfaction Score—Score provided by the customer for their complaint resolution.
- Card Type—type of card hold by the customer.
- Points Earned—the points earned by the customer for using credit card.

## <mark>Approach and Solution Methodology:</mark>

1. **Descriptive Statistics-**
- Basic Statistics: Calculate mean, median, and mode for numerical columns like CreditScore, Age, Balance, NumOfProducts, EstimatedSalary, and Points Earned.
- Distribution Analysis: Analyze the distribution of key numerical variables using histograms and box plots to understand the spread and central tendency.

2. **Exploratory Data Analysis (EDA)-**
- Correlation Analysis: Explore the correlation between numerical features and the Exited variable to identify potential predictors of churn.
- Customer Profile Analysis: Segment customers based on key demographics (Age, Geography, Gender) to identify which groups are more likely to churn.

3. **Comparative Analysis-**
- Churn by Geography: Compare churn rates across different geographical locations to see if certain regions have higher churn rates.
- Gender Differences in Churn: Analyze churn rates between different genders to explore if gender plays a significant role in churn.

4. **Behavioral Analysis-**
- Product and Services Usage: Examine how the number of products (NumOfProducts) a customer uses affects their likelihood to churn.
- Activity Level Analysis: Investigate the relationship between being an IsActiveMember and customer churn.

5. **Financial Analysis-**
- Balance vs. Churn: Analyze how customer balance levels correlate with churn rates.
- Credit Card Ownership: Determine if owning a credit card (HasCrCard) impacts customer loyalty.

6. **Customer Satisfaction and Feedback-**
- Complaint Analysis: Study the impact of having a complaint (Complain) on customer churn.
- Satisfaction and Churn: Explore how the Satisfaction Score relates to churn, especially among those who have filed complaints.

7. **Card Usage Analysis-**
- Impact of Card Type on Churn: Examine if different Card Types have different churn rates.
- Loyalty Points Analysis: Investigate whether Points Earned from credit card usage influence customer retention.

8. **Salary Analysis-**
- Salary and Churn: Analyze the relationship between EstimatedSalary and customer churn, focusing on how financial well-being might influence churn decisions.

9. **Insights and Recommendation-**
- Please add all the insights that you got from the data and recommendations that you have for reducing churn

## <mark>Actionable Insights and Recommendations to retain users:</mark>

- **Expand Marketing Efforts in Germany and Spain:** Since 50% of customers are from France, focus marketing campaigns on Germany and Spain to boost customer acquisition in these regions.
- **Develop Targeted Offers for Female Customers:** Introduce specific products or offers aimed at attracting more female customers to balance the customer demographics.
- **Enhance After-Sales Service:** Address the fact that almost 99% of customers who filed complaints have left the bank by significantly improving the after-sales service experience.
- **Create Retention Strategies for Multi-Product Holders:** Implement targeted retention strategies for customers with three or more products, as they have a higher churn rate.
- **Engage Zero Balance Account Holders:** Investigate why approximately 3,000 accounts have zero balance and develop offers or incentives to engage these customers and encourage account usage.
- **Financial Counseling for At-Risk Customers:** Analyze factors influencing customer exit versus retention and offer financial counseling to customers in vulnerable salary brackets to reduce churn.
- **Product Optimization:** Analyze usage patterns of users with multiple products and customize offerings to better meet their needs and preferences. Conduct user surveys to gather feedback and identify areas for product improvement or feature development.
- **Localized Marketing Campaigns:** Develop region-specific marketing strategies tailored to address unique needs identified through geographical analysis. Utilize localized events or cultural insights to create targeted campaigns aimed at retaining users in high-churn regions.
- **Personalized Engagement:** Implement personalized incentives or loyalty rewards based on demographic, financial, and activity-related characteristics to encourage user retention. Offer tailored financial management tools or advisory services to users with low balances or credit scores to enhance engagement with the service.
- **Community Engagement Initiatives:** Foster a sense of community among users through localized events, forums, or online communities, particularly in regions with high churn rates. Encourage user participation and feedback to better understand regional challenges and adapt retention strategies accordingly.
- **Continuous Monitoring and Adaptation:** Regularly monitor churn metrics and conduct ongoing analysis to identify changing trends or patterns. Maintain open communication channels with users to address concerns promptly and demonstrate a commitment to customer satisfaction.
- **Localized Customer Support:** Establish dedicated customer support teams or resources for users in high-churn regions to provide personalized assistance and address issues effectively.
