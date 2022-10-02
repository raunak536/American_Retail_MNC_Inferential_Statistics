# Problem Statement:
For an American MNC retail, analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions.


# Insights :
- There are 5891 customers in the dataset. They have collectively bought 3631 different products which can be clubbed into 20 categories of Products. 
- 75% of transactions are made by male
- There is a difference of ~1200 between the Purchase Amount mean and median
- The most common attributes of a transaction from the retail shop are : 
    - There are much more transactions by Male customers (75%) than Female (25%)
    - Most of the transactions are made by the 26-35 Age group (40%)
    - Most of the transactions are made by customers having Occupation code 4 (13%)
    - Most number of transactions are made in City Category B (40%)
    - Most of the transactions are made by customers staying in city for 1 year only (35%)
    - 60% of transactions are made by Unmarried Customers
    - Most popular product categories are : 5 (27%), 1 (25%), 8 (20%)    

- Purchase doesn't show any strong correlation with any measure (highest is 0.06 with Gender) 
- Age and Marital Status are somewhat correlated (0.31)

- There is a big difference between median and mean purchase amount signalling outliers
- There are many outlier customers who are purchasing way more on Black Friday as compared to the rest
- The nature of histogram of purchase made by single user resembles income distribution in the world (most people are poor, handful are extremely rich)
 
 
- Purchase Inferential Statistics for Gender: 
    - The more samples we take to calculate the mean the more is the difference between the 2 distributions
    - All the confidence intervals (90%, 95%, 99%) for each sample size are overlapping for males and females
    - The least overlap is seen for the 90% confidence interval with a sample size of 150 : 
        - female is 6.0L to 8.1L
        - males is 7.9L to 10.7L


- Purchase Inferential Statistics for Married/Unmarried people:
    - All the confidence intervals (90%, 95%, 99%) for each sample size are massively overlapping for married and unmarried


- Purchase Inferential Statistics for Age Group:
    - For the sampling size of 150, we can say that:
        - The 99% confidence interval for 0-17 Age bracket is 4.7L to 7.6L
        - The 99% confidence interval for 26-35 Age bracket 7.7L is to 12L
        - We can say with 99% confidence that 26-35 aged people spend more than 0-17 aged people
        - ---
        - The 90% confidence interval for 0-17 Age bracket is 5.2L to 7.1L
        - The 90% confidence interval for 18-25 Age bracket 7.3L is to 9.7L
        - The 90% confidence interval for 36-50 Age bracket 7.2L is to 9.8L
        - We can say with 90% confidence that 18-25 and 36-50 aged people spend more than 0-17 aged people
        - ---
        - The 95% confidence interval for 51+ Age bracket is 5.4L to 7.8L
        - The 95% confidence interval for 26-35 Age bracket 8.2L is to 11.1L
        - We can say with 95% confidence that 26-35 aged people spend more than 51+ aged people
        
        
# Recommnedations : 
- The US MNC Retail should continue targeting customers of both the genders on Black Friday sale, as we don't have strong evidence to suggest otherwise
- The US MNC Retail should prioritize the 26-35 Age Bracket (as they seem to spend the highest across all Age Brackets) by:
    - Build marketing campaigns focused on young and middle aged adults 
    - Keep high inventories of the most bought product categories (5,1,8) by this age group 
    - Best offers on the least brought product categories (17,9,19) by this age group to incentivize their spending on them 
- The US MNC Retail should not target its customers based on their married status, as the data doesn't show any difference in their purchasing behaviour