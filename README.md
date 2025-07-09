# **Data Analyst Job Posting Projects**
**Sebastian Ortuno Barrero**

This project looks at job ads for Data Analyst jobs using Python. The goal is to learn about the job market, such as popular job titles, where most jobs are, what skills are needed, and how much money the jobs pay.

The dataset has 2,253 job and 15 columns.

We cleaned the data by working with each columns' needs.

The project shows:

- How many job openings are by job title.
- How salaries change and if they connect to company ratings.
- Which cities and states have the most Data Analyst jobs.
- What kinds of companies and industries offer these jobs.
- The most wanted skills like SQL, Excel, Python, R, Tableau and Excel.
### **1 Import the packages and read the csv file**  
### **2  . Exploring the data Information**
- Looking at the data we have a lot of work to do. We will clean the data step by step starting in the next point.
- Above we can observe there are 15 columns. Float64(1), int64(1), object(13).
- Our table has 2253 rows and 15 columns.
- ## **3. Preparing the data for the EDA**
-  Looking for the missing values.
-  Duplicate values.
-  Create new columns for city and state from location.
-  delete unneeded values from columns.
-  Extract skill requirements from job description.
-  Data Organization: Selecting and Refining Key Features.
  ### **5. Exploratory Data Analysis**
  #### **5.1 Number of job opening by job titles.**
  ![image](https://github.com/user-attachments/assets/351a4bd7-10ff-4afb-9656-1db43b9a901f)


**Comments:**
- The "Data Analyst" title dominates the job market with 405 job openings.
- Out of 2,252 total job listings, most job titles specify particular skills or requirements that make each role unique.
- There is moderate demand for senior and junior roles, suggesting a career path.
- Specialized analyst roles exist but represent a small slice of the market.

 #### **5.2. Distribution of salaries according to ratings.**
 ![image](https://github.com/user-attachments/assets/532e6394-7d69-4982-8f0d-bb85aa87021a)
![image](https://github.com/user-attachments/assets/d5e8b1c9-6320-43e5-bc5d-26971724ac1c)
![image](https://github.com/user-attachments/assets/c647ab94-b958-4e9f-a0ad-dea4b7fea413)
![image](https://github.com/user-attachments/assets/85c1de80-cf26-4580-a7b4-d61906f3e682)


**Comments**
- Higher-rated companies (closer to yellow) are scattered across all salary levels, showing no strict correlation between rating and salaries.
- Higher ratings do not guarantee higher salaries, and vice versa.
- Most of the minimun salary are between 40k-60k.
- Most of the maximun salary are between 65k-105k.
- The average salary for data analyst positions are between 50k-80k.

  
#### **5.3. Count Plots for Top 10 Categorical Variables**

![image](https://github.com/user-attachments/assets/c5758075-3220-444f-8de8-ad53547caa41)
![image](https://github.com/user-attachments/assets/4cb6e1c5-4641-4713-8292-8c5e03d4ee1b)
![image](https://github.com/user-attachments/assets/c5886659-ea28-4f6a-8a5d-414ee6619c1a)
![image](https://github.com/user-attachments/assets/f162a792-05b4-4ad9-b262-eb06328f9521)
![image](https://github.com/user-attachments/assets/1feb2573-6af4-4cb3-b663-cdbf1c365d3e)

**Coments**
- Data Analyst roles are most common in large cities like New York, Chicago, and San Francisco.
- The top hiring states are California, Texas, and New York.
- Most jobs are offered by private companies, especially in the IT Services and Staffing & Outsourcing industries.
- The leading sector for data analyst roles are Information Technology, business services, and finance.

#### **5.4 Most skills needed in job listing.**

![image](https://github.com/user-attachments/assets/233a811f-a4ae-4701-a076-058382bffcbe)
![image](https://github.com/user-attachments/assets/43c86aa8-b012-4ab0-9b9c-316ee6fa945b)
![image](https://github.com/user-attachments/assets/57314aaf-eb6f-4bed-9e23-5fab9200d915)

**Comments**
- SQL and Excel are clearly the most demanded skills for data analyst positions.
- Over 50% of job listings require proficiency in SQL or Excel.
- Python is also an important skill, though it’s not as commonly required as SQL and Excel.
- Among visualization tools, Tableau is more frequently requested than Power BI.
- A combination of skills like SQL, Excel, Python, R, Tableau, and Power BI helps candidates stand out for data analyst roles.
- Focusing on these popular skills can greatly improve your chances of getting hired.

### **6. Final Conclusion**

- Data Analyst jobs are most common in big cities like New York, Chicago, and San Francisco. The states with the most job offers are California, Texas, and New York. Most of these jobs are in private companies, especially in Information Technology, Business Services, and Finance.

- The "Data Analyst" title dominates the job market with 405 job openings. Out of 2,252 total job listings, most job titles specify particular skills or requirements that make each role unique.

- Even though many jobs have the same title, each one may ask for different skills. The most needed skills are SQL and Excel, followed by Python, R and Tableau. Tableau is more requested than Power BI for data visualization. 

- Most average salaries are between 50k  and  80k. A high company rating does not always mean a higher salary.

- To find a good job as a Data Analyst, it is helpful to learn tools like SQL, Excel, Python, R, Tableau, and Power BI, and focus on the locations and industries with the most openings.



