# salary.github.io
## A data scientist salary analysis
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/2f6d87b8-3850-4aa1-85b7-0ed0faf6c954)

The dataset is downloaded from the Kaggle Datasets updated 2 months ago, recording the Salaries of Different Data Science Fields in the Dat Science Domain. The dataset provide those information:
 
 1 work_year: The year the salary was paid.
 
 2 experience_level: The experience level in the job during the year
 
 3 employment_type: The type of employment for the role
 
 4 job_title: The role worked in during the year.
 
 5 salary: The total gross salary amount paid.
 
 6 salary_currency: The currency of the salary paid as an ISO 4217 currency code.
 
 7 salaryinusd: The salary in USD
 
 8 employee_residence: Employee's primary country of residence in during the work year as an ISO 3166 country code.
 
 9 remote_ratio: The overall amount of work done remotely
 
 10 company_location: The country of the employer's main office or contracting branch
 
 11 company_size: The median number of people that worked for the company during the year
 
 ### CRISP-DM process
 ![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/7ff197a2-90e5-4630-9caf-f18bcc81b68c)
#### 1 Business Understanding
Investigating salary trends can be beneficial for both companies and their employees, providing essential insights into the current economic climate. For businesses, a comprehensive understanding of these salary trends enables company management to strategize more effectively regarding labor expenditure. Furthermore, for employees, gaining insights into the industry's economic status can guide their career planning. Therefore, understanding salary trends is crucial for both organizational growth and individual career advancement. 

#### 2 Data Understanding
The dataset comprises information pertaining to the year of payment, experience level, employment type, job title, and salary (converted to USD for ease of comparison). Additionally, it includes details about the employee's residence, the ratio of remote work, company location, and company size. This comprehensive data collection enables a thorough analysis of various factors impacting salaries. 

#### 3 prepare data
After checking the dataset, there is no missing value. By selecting different group by country, remote ratio, experience level or company size.
company distrubution
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/797fcdb6-38db-4b85-ac66-e09e4cee1157)

#### 4 model data
This step I choose to classificate the model. I want to solve the problems:
/Do their salaries in a large company size lager than middle and small one?
Which is the most highest mean salaries area?
Does the remote ratio affects the salaries?
Which type of experience level has the largest salary difference?


#### 5 results

#### 6 deploy
 

##### Data source https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023?sort=most-comments
