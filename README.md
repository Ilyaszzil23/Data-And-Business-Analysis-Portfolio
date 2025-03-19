# Ilyas Mohamed - Data / Business Analyst Portfolio

## Hi, I hope you enjoy reading my Portfolio Project!

## About

I am Ilyas, an ambitious individual with a strong background in Business and Mathematics (Joint Honours). With a passion for data analysis and problem-solving, I am currently 
expanding my expertise through Business Intelligence courses on Udemy.

My journey in programming has equipped me with essential skills such as Python, Data Visualisation, Forecasting, and Mathematical Concepts. Alongside technical skills, I have
also developed strong Business Analysis capabilities, including defining business problems, gathering and analysing data, and effectively communicating insights to stakeholders.

In my current role as a Part-time Assistant Accountant, I help clients navigate financial challenges, such as Tax Returns, Business Registrations, and Tax Assessments.
I am enthusiastic about exploring emerging technologies and advancing my skills in programming. 

My ultimate goal is to become a professional Freelance Data & Business Analyst, supporting businesses in driving innovation and improving their impact on society.
I believe that with dedication, continuous learning, and perseverance, I can help businesses unlock their full potential for a better world.

My CV in [pdf](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/Ilyas_Mohamed_CV.pdf).

This is a repository to showcase skills, share projects and track my progress in Data & Business Analytics related topics.

## Table of contents
 - [About](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#About) 
 
 - [Portfolio Projects](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#Portfolio-Projects)

   - Python:

     - [Basketball Free Throws](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#Basketball-Free-Throws)
 
 
     - [World Trends](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#World-Trends)

   - SQL:

     - [The SQL Case Statement in Employees](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#The-SQL-Case-Statement-in-Employees)


     - [The LAG and LEAD Value Window Function in Employees](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#The-LAG-and-LEAD-Value-Window-Function-in-Employees)


   - Business Analysis

     - [Enchancing Customer Experience at Primark](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#Enchancing-Customer-Experience-at-Primark)


 - [Education](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#Education)


 - [Certificates](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#Certificates)


 - [Contact](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/README.md#Contact)



## Portfolio Projects

In this section I will list data and business analytics projects briefly describing the technology stack and business technique used to solve cases.

## Basketball Free Throws

**Goal statement:** The objective to  analyse basketball free throws performance and player scoring tendencies using the  provided data. This will involve creating two matrices from the given vectors to generate three key visual insights:

1. Free Throw Attempts per Game - To assess player's frequency of attempting free throws.
2. Free Throw Accuracy - To evaluate players' efficiency in coverting free throws.
3. Player Playing Style Analysis - To identify player's scoring preferences between 2-point and 3-point shots, excluding free throws.

 This analysis aims to provide actionable insights into player performance and strong strategies.

**Code:** ['Basketball Free Throws.ipynb'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Basketball%20Free%20Throws.ipynb)

**Raw Data:** ['BasketBall free throws-Dataset.pdf'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/BasketBall%20free%20throws-Dataset.pdf)

**Description:** This project applied matrix manipulation techniques in Python to create visual insights about player performance. Leveraging NumPy, data was transformed into matrices representing shot attempts and success rates. Visualisation libraries such as Matplotlib were used to present clear and insightful visualisations, enhancing the understanding of player tendencies and performance.

**Skills:** data visualisation, data cleaning, matrix, computation,

**Tools:** Jupyter Notebook, Visual Studio Code (Offline), Matplotib, NumPy

## World Trends

**Goal statement:** The objective is to analyse and visualise the relationship between Life Expectancy and Fertility Rate across countries, categorised by region. Using Data from 1960 and 2013, the analyse will inovlve:

1. Creating Scatterplots for each year to illustrate the corrlation between Life Expectancy (y-axis) and Fertility Rate (x-axis).
2. Ensuring data manipulations are conducted in Python for auditability.
3. Providing insights into how these metrices have evolved over time, highlighting regional trends, and significant changes.

This analysis aims to support the World bank's understanding of global health and demographic shifts.

**Code:** ['World Trends.ipynb'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/World%20Trends.ipynb)

**Raw Data:** ['Demographic-Data World trends.csv'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Demographic-Data%20World%20trends.csv)

**Description:** This project utilised Python libraries such as Pandas for data manipulation and Matplotlib/Seaborn for data visualisation. Scatterplots were generated to reveal insights into how global health metrics have changed over time, while colour-coding by region provided clear visual distinctions for comparative analysis. Key insights into demographic trends were highlighted to support informed policy recommendations.

**Skills:** data visualisation, data frame, statistical application, Extract-Transform-Load (ETL)

**Tools:** Jupyter Notebook, Visual Studio Code (offline), matplotib, numpy, Seaborn, Pandas, Excel


## The SQL Case Statement in Employees

**Goal statement:** The objective is to write an  SQL query that extracts the employee number, first name, and last name for the first 100 employees from the database. Additionally, ac calcuated column called "Current - employee" will be included indicating.

 - "Is stiil employed" for active employees.
 - "Not an employee anymore" for former employees.

This query aims to efficiently retrieve and present employee status information for streamlined reporting and analysis.

**Code:** ['Employees CASE Statement.sql'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Employees%20-%20CASE%20Statement.sql)

**Raw Data:** ['Employees raw data'](https://www.dropbox.com/scl/fi/cs4nvueufh97f1oi9592t/employees.sql?rlkey=im4n5ff00ik69g2nfugrwdhk4&e=1&dl=0)

**Skills:** Analysis, database management, SQL queries, JOIN operations, aggregation functions, conditional logic.

**Tools:** MYSQL server, PostgreSQL, SQL case statement

## The LAG and LEAD Value Window Function in Employees

**Goal statement:** The objective is to write an SQL query that extracts and analyses salary data from the "employee" database for employees numbered between **10500** and **10600** (inclusive). This query will:

1. Display salary values in asceding order.
2. Include a column showing the previous salary in the ordered list.
3. Include a column showing the subsequent salary in the ordered list.
4. Calculate and display the difference between the current salary and the previous salary.
5. Calculate and display the difference between the next salary and the current salary.
6. Fliter results to include only salary values greater than $80,000.
7. Ensure data is partitioned by employee numbers to produce meaningful insights.

This query aims  to provide a comprehensive view of salary progression for the specificed employees, facilitating trend analysis and informed decision-making.

**Code:** ['Employees The LAG and LEAD Value Window Functions.sql'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Employees%20-%20The%20LAG()%20and%20LEAD()%20Value%20Window%20Functions.sql)

**Raw Data:** ['Employees raw data'](https://www.dropbox.com/scl/fi/cs4nvueufh97f1oi9592t/employees.sql?rlkey=im4n5ff00ik69g2nfugrwdhk4&e=1&dl=0)


**Skills:** Subsquries, SQL Window Function, data partitioning, database management, Analystical SQL, Data Analysis with SQL, Advanced SQL Queries.

**Tools:** MYSQL, SQL Window function

## Enchancing Customer Experience at Primark (Business Analysis Fundementals)

Please see in my [CV](https://github.com/Ilyaszzil23/Data-And-Business-Analysis-Portfolio/blob/main/Ilyas_Mohamed_CV.pdf) for my work experience at Primark

**Goal statement:** To improve customer statisfaction and shopping experience by identifying key issues, analysing feedback data, and recommending actionable solutions

**Defining the problem:** While working at Primark, I identified that customer satisfaction levels were inconsistent, particularly among international shoppers. Challenges included language barriers, inefficient store layout, and customer service gaps.

**Gathering and Analysing Requirements:** To understand the root causes:
-  I actively engaged with international customers using **translation apps**, ensuring clear communication and identifying language as a barrier to customer experience.
-  I analysed **customer feedback surveys**, identifying recurring themes such as difficulty navigating the store and product placement issues.
-  documented customer pain points and categorised feedback to highlight trends, enabling me to prioritise key issues for improvement.


**Insights and Recommendations:** Based on the data analysis, I identified that poor navigation was a major factor impacting satisfaction. I proposed:
-  Adjusting the **store layout** to improve product visibility and streamline customer flow.
-  Enhancing multilingual signage to better guide international customers.
These changes contributed to a **60% increase in customer satisfaction** scores.


**Communicating insights to Stakeholders:** I effectively presented my findings to store management, providing data-backed insights that influenced key operational decisions. Additionally:
-  I collaborated with team leaders to implement my proposed layout changes.
-  By improving customer service strategies, I contributed to a **15% increase in repeat customers.**


**Results & Conclusion:**
The successful implementation of these strategies resulted in a measurable improvement in both customer satisfaction and repeat business. This experience reinforced my ability to:
-  Identify business challenges through data analysis,
-  Develop actionable insights aligned with business goals,
-  Effectively communicate solutions to key stakeholders.

This project demonstrates my ability to combine data analysis, customer insights, and problem-solving to drive positive business outcomes.

**Key Skills Demonstrated:**

-  Data Analysis (using feedback data for insights) ✅  
-  Problem Solving (identifying and addressing customer pain points) ✅  
-  Stakeholder Communication (presenting insights to management) ✅  
-  Customer-Centric Approach (enhancing the overall shopping experience) ✅


## Education

**BSc (Joint Honours) in Business and Mathematics (2:1)**
University of Hertfordshire - Graduated in 2021

**Relevant Modules for Tech/Programming Roles:**

- Mathematics Techniques level 1 & 2
- Linear Algebra
- Differential Equations
- Number Theory
- Nonlinear Theory
- Nonlinear Systems
- Combinatorics

**Relevant Modules for Business Analysis/Data-Driven Roles:**
- Business Analysis Tools
- Quantitative Methods for Business
- Financial Analysis Techniques
- Management Science in Business
- Performance Strategy
- Principles of Operations Management

**Key skills:**
- Analytical Thinking & Problem-Solving
- Data Analysis & Visualisation
- Financial Modeling & Business Strategy
- Mathematical Optimisation & Statistical Techniques

This combination of skills and knowledge allows me to bridge the gap between **technical development** and **business insights**, ensuring data-driven decision-making and effective problem-solving.


## Certificates

To support my academic background, I have also completed several certifications that demonstrate my practical skills in data analysis, business analysis, and programming. Here are my certifications in reverse-chronolgoical order:

- [Excel (Nov 2021)](https://www.udemy.com/certificate/UC-eecbc119-e324-4e76-8471-b8acc234cd4d/)
- [Python (Mar 2022)](https://www.udemy.com/certificate/UC-baf8f1d5-a867-43fc-bc35-3a4f0a5db8ab/)
- [The SQL Bootcamp (Apr 2022)](https://www.udemy.com/certificate/UC-7bcc7ceb-432a-4879-b336-eaee35b5264b/)
- [Power BI - Data Analytics (Jun 2022)](https://www.udemy.com/certificate/UC-102aa202-6dfc-46ee-97ca-69e4d627ead7/)
- [Business Analysis fundamental (Apr 2024)](https://www.udemy.com/certificate/UC-9b0193bd-a00b-48ee-843a-67d8fe2dfd1e/)



## Contact

- LinkedIn: [Ilyas88](https://www.linkedin.com/in/ilyas88)
- Email:  ilyasM23@outlook.com


