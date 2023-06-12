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

Do their salaries in a large company size lager than middle and small one?

Which is the most highest mean salaries area?

Does the remote ratio affects the salaries?

Which type of experience level has the largest salary difference?

#### 5 results
Q1
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/5b165885-bfec-43cb-84e6-e0e0e91457df)
The employees which work in a large company size have a higher salary than the middle size, the small size company has the less mean wage.

Q2
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/c8235e6c-b23c-46f2-8774-cf039d720a30)
The highest paid area is IL, then PR US RU CA, the least wage is in MK.

Q3
the remote ratio in the whole dataset
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/d5c31fce-7b7c-40d9-a3e9-8fe564d182d6)
the remote ratio in US
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/1ee15546-32fa-4f1a-9a8a-597287d76d43)
Employees who work entirely offline have the highest mean salary value. Interestingly, those working remotely 100% of the time do not have the lowest average salary. This indicates that other factors may also contribute significantly to salary. The remote work arrangement, while impactful, is not the sole determinant of an individual's remuneration. Factors such as the nature of the job, the industry, years of experience, and individual skills and qualifications could also play a role in influencing salary. Thus, a more comprehensive examination of these variables is needed to gain a more accurate understanding of their impact on salaries.

Q4
![image](https://github.com/wanlidu2/wanlidu2.github.io-salary/assets/121735612/5ee11a53-708b-44f0-9129-261219ddb8eb)
The EX level have the highest level of mean salary.

#### 6 deploy
 In conclusion, it's observed that companies of larger sizes tend to pay higher average salaries than mid-sized and small companies, in that order. Regionally, IL stands out as the area with the highest mean salary. While the extent of remote work does seem to have some effect on salaries, its influence is partial and likely interwoven with other factors. In terms of experience level, the EX tier holds the highest average salary. These findings could provide important insights to individuals and businesses in their career planning and compensation strategies, respectively. It's crucial to keep in mind, however, that many factors can influence salary and these factors often interact in complex ways. 

##### Data source https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023?sort=most-comments
