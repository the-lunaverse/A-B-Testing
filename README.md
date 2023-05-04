# A-B-Testing

 Explored a dataset containing consumer complaints related to financial products and services. 

Data Source: https://www.consumerfinance.gov/data-research/consumer-complaints/

- Performed some exploratory data analysis (EDA) for insights.
    -Found that most of the complaints were related to credit reporting, credit repair services, or other personal consumer reports.
 

- Conducted a T-test to compare the number of complaints submitted via the web and those submitted via phone. 
    - Found a significant difference between the two groups, with a t-statistic of -91.18 and a p-value of 0.0. 
    - Visulaized results in a bar plot to compare the two groups,showing the mean index and standard deviations.

- Conducted an ANOVA test to compare the number of complaints submitted via different methods across multiple groups (states).
    - Transformed the the 'Submitted via' column to a categorical data type and performed the ANOVA analysis.
    - Found a significant difference between the states in terms of submission methods, with an F-statistic of 319.10 and a p-value of    0.0.

In summary, the analysis revealed significant differences in the number of complaints submitted via different methods, both between web and phone complaints and across different states. This information could be useful for companies to better understand consumer preferences and improve their complaint handling processes.
