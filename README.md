# Cohort Analysis: Analyze User Retention (Based on time)
## I. INTRODUCTION 
### 1. Cohort Analysis
#### What is Cohort? 
A cohort is a collection of users who have something in common. A traditional cohort, for example, divides people by the week or month of which they were first acquired. When referring to non-time-dependent groupings, the term segment is often used instead of the cohort.

#### Why Cohort Analysis is important? 
To measure user engagement over time. It helps to know whether user engagement is actually getting better over time or is only appearing to improve because of growth. Customers are divided into mutually exclusive cohorts, which are then tracked over time. Vanity indicators don’t offer the same level of perspective as cohort research.

#### Three major types of Cohort:
* Time cohorts: customers who signed up for a product or service during a particular time frame.
* Behavior cohorts: customers who purchased a product or subscribed to service in the past.
* Size cohorts: refer to the various sizes of customers who purchase the company’s products or services.

#### For this project:
* Focus on Time cohorts.
* Customers will be divided into acquisition cohorts depending on the month of their first purchase.
* The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction.

### 2. Business question:
* Using Python to analyze transaction data from KPMG and creating a cohort that allows stakeholders to assess user engagement starting from their first transaction.

## II. Data Visualization with Python
* MoM Retention Rate for Customer Transaction Data
<img width="473" alt="image" src="https://github.com/nguyenhieuhp96/-Cohort-Analysis/assets/135586659/c5ff345d-4ea9-4d79-b4e1-1c2896538c61">

## III. Insights
* Customers who register and place their first order in July 2017 have a high retention rate (up to 48.1%) after 5 months of operation.
* Customers who register and place their first order in April 2017 have a stable and relatively high retention rate: 45.1% (4th month), 42.1% (5th month) ), and 42.7% (7th month).
* Customers who register and place their first order in May 2021 also have a fairly high and stable retention rate: 40.4%,39%, and 41.3% in the 2nd, 3rd and 4th-month activities.
* Looking at the above insights, we can see that customers who start ordering from mid-year 4,5,6,7,8 tend to order stable, and relatively higher than the rest months of the year.
* Customers who place orders at the beginning of January and February only show stability, nothing special.
* KPMG's year-to-date retention rate is quite good, all 30% or more (except 1st month at 25.5%).

## IV. Recommendations
* There should be attractive preferential policies for customers in the first months of the year to increase the order rate (retention) over the months.
* The Mid-year months have higher retention rates than other months -> need to dive into why (with relevant data, and visualization of other data) to apply to other months of the year.

