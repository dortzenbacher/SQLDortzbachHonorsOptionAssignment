# Project 2 -- Dortzbach Honors Option

# Data Set:
This data set was obtained from the US Data Government Website, and the publisher of the dataset is The City of New York. This dataset is a record of traffic crashes, including details like crash date, time, location, and contributing factors. The Motor Vehicle Collisions data tables contain information from all police-reported motor vehicle collisions in NYC. The police report (MV104-AN) is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage and provides data that could be used for traffic safety analysis. This dataset could be used to analyze trends in traffic accidents, identify high-risk locations, and inform safety measures.

<img width="570" alt="Screenshot 2024-11-21 at 2 46 10 PM" src="https://github.com/user-attachments/assets/6646a8e4-7805-41cf-9630-ea3374418e5b">


# Question:
**What are the forecasted percentages of collisions attributed to alcohol and to illegal drugs separately for the years 2025 and 2026?**

Importance: Forecasting the percentages of collisions caused by alcohol and illegal drugs for 2024 and 2025 provides valuable insights into the effectiveness of current interventions targeting impaired driving, which is a behavior influenced by the driver’s choices. Tracking alcohol-related collisions separately from drug-related collisions allows for more targeted interventions, as the causes and effects of each type of impairment require different prevention strategies. It also serves as a key indicator of whether past efforts have been successful or if adjustments to strategies are needed for the future. Presenting the data as percentages, rather than raw numbers, allows for better comparisons across time periods and accounts for changes in the total number of collisions.


# Manipulations:
1. I created and used calculated fields to determine the percentages of collisions caused by these two types of impairing substances. I chose to graph the data in percentage form rather than total counts because overall collisions dropped significantly during the COVID-19 pandemic, and my focus was on analyzing how the causes of collisions were expected to shift, rather than the total number of collisions for each cause. 

2. I filtered out data before 2016 because crashes caused by illegal drugs were not recorded during that time. Including 0% for illegal drug-related crashes prior to 2016 would innapropriately skew the results.

3. I decided to aggregate the columns by year rather than by month to reduce seasonal variability and create a more standardized unit of analysis.


# Analysis:
The forecast of the percentage of collisons caused by alcohol and the percentage of collisons caused by illegal drugs showed that both are projected to increase in 2025 and 2026. 

The percentage of collisons caused by alcohol was relatively constant from 2016-2019 at around 1% of collisions. In 2020, that number started to drastically rise and is continuing to rise. It is currently sitting at just under 2% and is forecasted to be at 2.37% by the end of 2026. This may be attributed to the changes in lifestyles caused by the COVID-19 pandemic and it is clear that it is still affecting these rates today. The COVID-19 pandemic likely contributed to a higher percentage of alcohol-related collisions, driven by factors such as increased alcohol consumption as people coped with stress, isolation, and uncertainty. Restrictions have been lifted, and the numbers continued to increase and have not been diluted which suggests that the rise in percentage of alcohol-related collisions may be a lasting effect of the pandemic rather than a temporary spike. This indicates that the behaviors and habits developed during that time are still influencing driving patterns today.

The percentage of collisions caused by illegal drugs follows a similar pattern, though on a smaller scale, likely due to the fact that illegal drugs are much less prevalent in society than alcohol is. These rates remained relatively stable from 2016-2019, averaging around 0.05%, but spiked in 2020 and again in 2021 to 0.1%. However, it dropped to approximately 0.08% in 2022 and has generally remained at that level since. These fluctuations may be linked to the COVID-19 pandemic as well, as increased drug use during that time could have been a coping mechanism for lifestyle changes. While the percentage has decreased since 2021, it is expected to rise again in 2025 and 2026.

This graph illustrates that the problem, which spiked in 2020 and has not returned to pre-pandemic levels, will likely persist unless addressed. The longer this issue continues, the harder it will be to reduce these rates. Public education campaigns and policymakers should prioritize the risks of impaired driving more than ever to prevent the problem from worsening further, ensuring that fewer drivers on the road are physically impaired. Both the percentage of collisions caused by alcohol and illegal drugs have wide prediction intervals, but the predicted minimum for each still represents a noticeable increase compared to their rates in 2019, confirming the anticipated shift in societal habits.

I believe these issues should be addressed, as the decision to consume alcohol or illegal drugs is made well before the incident occurs, making these collisions easily preventable.




