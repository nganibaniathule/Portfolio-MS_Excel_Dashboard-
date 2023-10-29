# Data Visualization Mastery: Excel Pivot Tables, Dynamic Graphs, and Interactive Dashboards
## Introduction
This project centres on exploring and visualizing the same dataset employed for a bank customer churn prediction project using machine learning. Our primary objective is to gain profound insights into this dataset by leveraging Excel's data manipulation and visualization capabilities. Through this project, we aim to delve deeper into the data, extracting valuable information concerning factors such as credit scores, age groups, gender, and geographic locations and their potential impact on customer churn.

By creating pivot tables, dynamic graphs, and an interactive dashboard, we seek to unlock the hidden patterns and correlations within the data. This analytical approach not only facilitates a comprehensive understanding of the dataset but also paves the way for well-informed decision-making. Our project demonstrates how effective data visualization can be in revealing key trends and patterns and shedding light on the factors that contribute to customer churn in the banking industry.

Through this exploration, we hope to provide a rich and intuitive interface for stakeholders to gain actionable insights from the data, ultimately assisting in the formulation of strategies to mitigate churn and enhance customer retention.


## Data Preparation


For this project, I utilized the same dataset employed in the bank customer churn prediction project using machine learning. To enhance its suitability for data exploration in Excel, several key data preparation steps were undertaken:

**_Credit Score Grouping:_** To gain a deeper understanding of the influence of credit scores, a new column was created. I introduced a new column that grouped credit scores into categories such as "Poor credit score (300-579)". This enables a more structured analysis of the data.

**_Age grouping:_** The ages were classified into distinct categories to delve deeper into the impact of ageing. To accomplish this, I introduced a new column indicating age groups. For instance, individuals aged 0-2 years were designated as "Baby," and so forth.

**_Categorical Conversion:_** To ensure that binary values were more intuitive in the dashboard, I converted 0's and 1's to meaningful labels, thus enhancing the interpretability of the data.

### Pivot Tables

Pivot tables were a cornerstone of this project, enabling a more structured examination of the data.

**_Credit Score vs. Estimated Salary:_** A pivot table was created to investigate the relationship between credit scores and estimated salaries concerning churn. This sheds light on the potential impact of creditworthiness.


**_Credit Card vs. Activity:_** Another pivot table was crafted to assess the bank balance of customers with and without credit cards according to their active status. This offered insights into the behaviour of different customer segments.

**_Age Group and Estimated Salary vs. Churning:_** A third pivot table was employed to explore the effects of age groups and estimated salaries on churn. This provides a comprehensive view of how these variables interact.


### Dynamic Graphs
In order to visually represent the data, dynamic line graphs and bar graphs were generated. These graphs played a vital role in discerning trends within the dataset and facilitating a more intuitive understanding of the information.

### Dashboard
Not all categorical columns could be accommodated in the graphs. To address this limitation, an interactive dashboard was developed. This dashboard allowed for a holistic assessment of the effects of those categorical variables that were not directly included in the graphs. Users can effortlessly explore the impact of various categorical attributes on customer churn, providing a comprehensive view of the dataset and its key insights.

Through these data preparation steps, pivot tables, dynamic graphs, and the interactive dashboard, this project unveils hidden patterns and relationships within the data, contributing to a deeper understanding of the factors influencing customer churn in the banking sector.

## Results and Insights
The figure below represents an interactive dashboard created as part of the project, offering a visual gateway to the project's key findings. With user-friendly navigation, it enables stakeholders to explore the intricate relationship between credit scores, estimated salaries, age groups, and credit card usage, and their influence on customer churn. The dashboard provides a dynamic platform for data-driven decision-making, empowering organizations to target retention strategies with precision.

<img width="1066" height = "639" alt="Bank_Customer_Churn_Dashboard" src="https://github.com/nganibaniathule/Portfolio-MS_Excel_Dashboard-/assets/129146143/f4c16a82-c6d1-4afa-ae77-7b854e0bd88d">





The data exploration and visualization efforts yielded several noteworthy findings, shedding light on the complex dynamics of customer churn in the context of credit scores, estimated salaries, age groups, and credit card usage:

**_Credit Score and Churning:_** Contrary to expectations, a high credit score does not guarantee that a customer won't churn. However, we observed that among those with high credit scores who did churn, the average estimated salary was notably lower compared to those who did not churn. This suggests that creditworthiness alone does not always deter churn, with other factors at play.


**_Credit Score and Estimated Salary:_** The group with the highest average estimated salary consisted of customers with poor credit scores who churned. This finding challenges the assumption that a poor credit score is synonymous with a lower income. It implies that individuals with high incomes do not necessarily rely on credit, highlighting the intricacies of financial behaviour. Notably, customers with exceptional credit scores had the highest average estimated salary among those who did not churn. This suggests that exceptional credit scores may be associated with higher income levels and financial stability.


**_Credit Card Usage and Bank Balance:_** Active members of the bank who had credit cards maintained a lower average bank balance than those who did not possess credit cards. Conversely, non-active members had higher average bank balances compared to their active counterparts. This insight may indicate that credit cardholders are more likely to manage lower bank balances.


**_Age Groups and Estimated Salary:_** The average estimated salary for young adults who churned was lower than for those in the middle and old age groups who churned. This pattern indicates a potential correlation between age, income, and churn. Additionally, as age increases, the average estimated salary generally increases until the middle age group, after which it declines.

These findings underscore the multifaceted nature of customer churn, emphasizing that it cannot be solely attributed to one variable, such as credit score or income. Instead, a combination of factors, including credit behaviour, age, and financial stability, influence customer decisions to stay with or leave the bank. These insights offer valuable information for the bank to refine strategies aimed at customer retention and provide a foundation for further analysis and decision-making.

## Benefits

This project offers significant benefits to banks and organizations concerned about retaining their customers and optimizing their retention strategies:


**_Enhanced Customer Retention:_** By delving into the dataset to identify key factors influencing customer churn, this project equips banks and organizations with insights to better understand their customers. This understanding allows for the development of more effective and precisely targeted retention strategies.

**_Informed Decision-Making:_** The interactive dashboard provides stakeholders with a user-friendly interface to explore and analyze data, facilitating data-driven decision-making. This empowers organizations to make informed choices regarding customer retention strategies and resource allocation.

**_Reduced Churn Rates:_** The insights derived from this project, combined with machine learning-based churn prediction, offer organizations a comprehensive toolkit to reduce customer churn. By identifying at-risk customers early and tailoring retention efforts to their specific needs, organizations can proactively reduce churn rates.

**_Resource Optimization:_** With a clearer understanding of which customer segments are most likely to churn and which factors are most influential, organizations can allocate resources more efficiently. This ensures that retention strategies are well-targeted and cost-effective.

**_Competitive Advantage:_** The ability to retain customers effectively and provide a personalized approach to customer retention gives organizations a competitive edge in the market. Satisfied and loyal customers are more likely to stay and engage with the organization's products or services.

**_Improved Customer Relationships:_** The insights gained from these projects enable organizations to foster stronger relationships with their customers. By addressing specific pain points and needs, organizations can create a more positive customer experience, further reducing churn.

**_Long-Term Sustainability:_** By actively managing customer churn and continuously refining their retention strategies, organizations can build a foundation for long-term sustainability and growth. Retaining existing customers is often more cost-effective than acquiring new ones.

In summary, this project empowers banks and organizations to better understand their customer base, reduce churn, and optimize their retention efforts. It facilitates data-driven strategies that improve customer relationships and contribute to long-term business success, making it a valuable asset in today's competitive market.

## Conclusion

In conclusion, this project represents a pivotal step toward comprehending and proactively addressing customer churn in the banking and organizational context. Through meticulous data exploration, the creation of insightful dashboards, and the integration of machine learning for churn prediction, we have unlocked a wealth of knowledge.

The findings from this project reveal that customer churn is a nuanced phenomenon, influenced by factors such as credit scores, estimated salaries, age groups, and credit card usage. High credit scores do not always deter churn, and the relationship between creditworthiness and income is intricate. Furthermore, age plays a vital role in understanding churn behaviour.

The project's value extends beyond mere analysis; it equips banks and organizations with the tools and insights to reduce churn and target retention strategies more effectively. By optimizing resource allocation and fostering stronger customer relationships, organizations can gain a competitive edge and foster long-term sustainability.

In a landscape where customer loyalty and satisfaction are paramount, this project stands as a valuable asset, guiding stakeholders toward informed decisions and enhanced customer retention. It reaffirms the power of data-driven insights in shaping successful strategies and securing the future of businesses.
