# data-analyst-JayRajesh

![image](https://github.com/user-attachments/assets/8969abca-6aa8-44d4-a977-5de98c410c2d)


Project Description: Descriptive Analysis of Permit Lapse Time Change for issued building permits .

Project Title: Understanding Permit lapse time.


Objective: The primary goal of this project is to conduct a descriptive analysis of issued building permit data at City of Vancouver. Through this analysis, we aim to summarize key characteristics of Permit Elapsed Days, Project Type, Project Value and generate insights that can inform improvement  strategies 
The dataset comprises key metrics related to work types and transactional times from City of Vancouver   over the  year 2023-2024 . It provides valuable insights into transaction patterns and time changes across various work categories. Below are the key features included in the dataset:


Dataset: The dataset includes informational data of issued building permit from city of vancouver over the year 2023 and 2024, containing the following key features:

•	PermitNumber: Unique identifier for each permit

•	PermitNumberCreatedDate: explaining when the permit no. created.

•	IssueDate: explaining when the permit was issued

•	PermitElapsedDays: time requires to issue permit form the date of creation.

•	Project Value: explaining the total project cost 

•	TypeOfWork: permit issue for which type of project (e.g. demolition, salvage, new builing)

•	Address: Location of the project.

•	Project discription: Describe the details of the project.

•	Applicant name: Name of the applicant applied for the permit.

•	Applicant address: location of applicant.

•	Project discription: Describe the details of the project.

Data Collection: downloded the data from city of vancouver (https://vancouver.ca/home-property-development.aspx) for 2023 and 2024 and loaded in stored in S3 Landing zone.

Data cleaning and structuring: using Amazone Glue dataBrew to clean and restructur the data by removing missing values, deleting unnecessary columns and changing data type.
Descriptive Statistics:
To	Calculate summary statistics for key variables, including: 
	Type of Work  
	Average Elapse day in 2023
 Average Elapse day in 2024 
	Elapse Time change 
3-	Data Visualization:
	Parato chart explains that increasing trends in  Permitlapse time change while decreasing number of projects. 

4-	Customer Segmentation:

o	Segment customers based on their purchasing behavior (e.g., high-frequency vs. low-frequency buyers).

o	Analyze the purchasing patterns of different segments.

5-	Insights and Findings:

o	Summarize the insights derived from the analysis, highlighting:

	Peak shopping periods (e.g., holidays, weekends)

	Trends in product category sales over time

	Preferences in payment methods across customer segments

6-	Recommendations:

o	Analyzing the result suggest to increase number of employees or working hours of existing employees in order to compensate workload it is also suggested to change approval methodology to escalate permit issue.

Tools and Technologies:

•	Python (Pandas, Matplotlib, Seaborn) or Excel for data analysis

•	Data visualization tools (Excel ) for creating dashboards

Deliverables:

•	A detailed report summarizing the methods, findings, and recommendations.

•	Visualizations and dashboards to present key insights clearly.

•	A presentation for stakeholders to communicate important findings and suggestions for future action.

This descriptive analysis project aims to provide a comprehensive understanding of issued building permit data at City of Vancouver. Optimize its operations and enhance customer satisfaction.



