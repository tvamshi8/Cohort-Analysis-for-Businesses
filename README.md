# Cohort-Analysis-for-Businesses

Cohort Analysis: Process We Can Follow
Cohort analysis is valuable for businesses as it allows them to understand user behaviour in a more granular and actionable way. Below is the process we can follow for the task of Cohort Analysis:

The first step is to define the cohorts based on a specific characteristic or event. For example, in an e-commerce platform, cohorts could be defined based on the month of a user’s first purchase.
Gather relevant data for analysis.
Determine the time intervals you want to analyze.
 Group users into cohorts based on the defined characteristic or event.
Choose the key performance metrics you want to analyze.
Calculate the chosen metrics for each cohort over the specified time periods.
Create visualizations to present your findings effectively.
A dataset for Cohort Analysis typically includes user or customer data, such as registration date, purchase history, engagement metrics, or any other data points relevant to the analysis. You can find the dataset here in the repository.

Cohort Analysis using Python

Now, let’s get started with the task of Cohort Analysis by importing the necessary Python libraries and the dataset:

<img width="440" alt="image" src="https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/b1cc8a78-fb35-4393-91cf-8bf250930296">

Now, let’s have a look at whether the dataset has any null values or not:

<img width="165" alt="image" src="https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/4abfe7e0-9dd9-468a-a77c-33fe492a79fc">

Now, let’s have a look at the datatypes of all the columns in the data:
<img width="202" alt="image" src="https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/20910aa2-3107-4378-9427-b4a04cb33130">

The Date column is in object (string) format. For effective analysis, especially in cohort analysis, we should convert this to a datetime format

Now, let’s have a look at the descriptive statistics of the dataset:

<img width="463" alt="image" src="https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/51ba117d-85fb-4c65-a6bb-53db4685c7ed">

The descriptive statistics provide the following insights:

New Users: The average number of new users is around 3,418 with a standard deviation of approximately 677. The minimum and maximum new users recorded are 1,929 and 4,790, respectively.
Returning Users: On average, there are about 1,353 returning users, with a standard deviation of around 247. The minimum and maximum are 784 and 1,766, respectively.
Duration Day 1: The average duration on the first day is about 208 seconds with a considerable spread (standard deviation is around 65).
Duration Day 7: The average 7-day duration is lower, around 136 seconds, with a larger standard deviation of about 97. The range is from 0 to 304.

Now, let’s have a look at the trend of the new and returning users over time:

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/915c8476-b1ce-40bf-ad99-c2913090a60b)

Now, let’s have a look at the trend of duration over time:

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/d5ed1720-56de-4ef9-b971-da7be32b4ab0)

Now, let’s have a look at the correlation between the variables:

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/ddedbf02-aa24-430f-9ff1-9db8c7c3cbd0)

Here, the strongest correlation is between the number of new and returning users, indicating a potential trend of new users converting to returning users.

Now Here’s How to Perform Cohort Analysis using Python
For the task of Cohort Analysis, we’ll group the data by the week of the year to create cohorts. Then, for each cohort (week), we’ll calculate the average number of new and returning users, as well as the average of Duration Day 1 and Duration Day 7. Let’s start by grouping the data by week and calculating the necessary averages:

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/5d6336f5-89be-4060-8638-1468ec0bb770)

Now, let’s have a look at the weekly average of the new and returning users and the duration:

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/bc8962fa-85d5-47cc-9c6b-f54323c413d5)

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/c2a234d1-385b-4c3f-a0b4-33c11af67f80)

Now, let’s create a cohort chart to understand the cohort matrix of weekly averages. In the cohort chart, each row will correspond to a week of the year, and each column will represent a different metric:

Average number of new users.
Average number of returning users.
Average duration on Day 1.
Average duration on Day 7.

![image](https://github.com/tvamshi8/Cohort-Analysis-for-Businesses/assets/153074595/13c67451-0421-410b-99e1-96f1d0ac0213)

We can see that the number of new users and returning users fluctuates from week to week. Notably, there was a significant increase in both new and returning users in Week 47. The average duration of user engagement on Day 1 and Day 7 varies across the weeks. The durations do not follow a consistent pattern about the number of new or returning users, suggesting that other factors might be influencing user engagement.

Summary
Cohort Analysis is a data analysis technique used to gain insights into the behaviour and characteristics of specific groups of users or customers over time. It is valuable for businesses as it allows them to understand user behaviour in a more granular and actionable way.


