# Data Science Job Salaries Exploration
## by Morris Mensah


## Dataset

The data consists of information regarding 607 data science professionals, including salaries, company location, and other variables that can influence the salaries of the professionals. The dataset can be found at https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries.


## Summary of Findings

In the exploration, I found that the salary distribution was skewed to the left with majority of salaries concentrated/densed below $200000. It was evident in the exploration that strong relationship existed between the salary_in_usd and the experience_level when plotted with box plot. The relationship was also clear in the multivariate exploration session when I wanted to discover the interaction between the expeerience_level, company_size, and salary_in_usd. It was clear that the average salary_in_usd across different company sizes(S, M, L) when one get more experienced. 
When I sub-selected some company location and plotted against salary_in_usd, it was seen that stronger economies tend to pay high salary with USA(US) and Canada(CA) being the spotlight.

Other variables like employment_type and remote_ratio did not hold any relationship and had no influece on salary so decided not to further investigate these features.



## Key Insights for Presentation

For the presentation, I focus on just the influence of experience level, company size, and company location on the salaries(USD). I start by introducing the individual distribution of the salary(USD) and that of the experience level. I further investigated the interaction of salary(USD) and the experience level using box plot and found out that there was linear relationship between these two variables.

Afterwards, I use the box plots of experience level and company size across salary to investigate the interactions that existed among these varibles. I further looked at salary by experience level and company location using swarm plot. I selected some company locations for the purpose of the investigation to avoid over plotting. Using all the company locations in the data will lead to difficulty in interpretations.