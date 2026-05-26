# IBM Data Analytics Capstone Project
### *Aijie Rama*
### *May 19, 2026*

## Table of Contents
- [Executive Summary](#executive-summary)
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Results](#results)
  - Visualization - Charts
  - Dashboard
- [Discussion](#discussion)
  - Findings & Implications
- [Conclusion](#conclusion)

### Executive Summary
**Point 1: Dominant Tech Ecosystem**
- JavaScript, TypeScript, React, and PostgreSQL heavily dominate both current 
developer usage and future career aspirations.

**Point 2: Highly Credentialed, Young Talent**
  - **Sub Point 1**: Core demographic is early-to-mid career, with 41.3% aged 25–34.
  - **Sub Point 2**: The talent pool is highly educated, consisting predominantly of 
Bachelor's and Master's degree holders.
  - **Sub Point 3**: Recruitment and benefits must align with continuous learning and 
workplace flexibility to attract this group.

**Point 3: Shifting Geographic Job Hubs**
-  While the talent pool is US-centric, job postings are heavily centralized in unexpected 
hubs like Washington D.C. and Detroit, sharply outpacing legacy hubs like San 
Francisco and Austin.

**Point 4: Infrastructure & Pipeline Alignment**
- Organizations must aggressively standardize tech stacks around JS/TS and 
PostgreSQL to ensure long-term project viability and a seamless hiring pipeline.

**Point 5: Strategic Recruitment & Sourcing**
-  Businesses should establish physical recruitment near active East Coast/Midwest 
hubs or capture remote talent in low-competition, high-talent markets like Austin and 
San Francisco.

### Introduction
The purpose of the report is to analyze the distribution of developer's current usage of 
programming language stack, database, and frameworks and their future preferences. This also 
includes the demographics of the respondents.

The target audience of the report are the following:
1. Academic institution
2. Government
3. Tech company & businesses

Key Value Metrics:
- Talent Pipeline: Align curriculum and hiring with high-demand stacks (JS/TS, PostgreSQL).
-  Geographic Strategy: Target high-demand hubs (D.C./Detroit) or leverage remote talent in 
competitive markets (SF/Austin).
- Retention & Culture: Adapt to a young demographic by offering flexibility and upskilling.

### Methodology
**Primary Data Sources**
- [Naukri.com](https://www.kaggle.com/datasets/promptcloud/jobs-on-naukricom) Job Postings dataset (Kaggle)
- [Popular Programming Languages](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/datasets/Programming_Languages.html) dataset (via IBM Skills Network)

**Dashboard Dataset**
  - Leveraged the processed survey_data_updated.csv file for final visualizations.

**Data Wrangling and Handling**
  - Preserved missing values in the raw dataset to maintain data integrity.
  - Dynamically filtered/excluded null values during the pivot table and dashboard 
creation stages.

### Results
**Job Postings**

*Instruction*: In Module 1 you have collected the job posting data using Job API in a file named 
“job-postings.xlsx”. Present that data using a bar chart here. Order the bar chart 
in the descending order of the number of job postings.

<img width="533" height="396" alt="Job Postings" src="https://github.com/user-attachments/assets/5f36d4eb-c44a-4ced-8c0e-ffa9e05e4a2c" />


**Popular Languages**

*Instruction*: In Module 1 you have collected the job postings data using web scraping in a file 
named “popular-languages.csv”. Present that data using a bar chart here. Order 
the bar chart in the descending order of salary.

**Programming Language Trends**

**PROGRAMMING LANGUAGE TRENDS - FINDINGS AND IMPLICATIONS**

**Findings**
-  The combination of HTML/CSS, JavaScript, and 
TypeScript is currently the most popular tech stack 
and remains heavily represented in future desires.
- Python takes a great shift as programmer prefer this 
language in the future.
- Database management via SQL remains highly 
consistent, appearing regularly across both current 
and future stacks, usually paired with web 
technologies.

**Implications**
- C# shows gradual decrease in programmer's 
language.
- Python will be more likely used as the primary 
programming language as data science, machine 
learning, and automation continue to grow, 
developers are prioritizing standalone Python 
proficiency alongside traditional web development.
- Future developers will be expected to be highly 
versatile, blending traditional frontend 
(HTML/CSS/JS) with backend/data languages 
(Python, SQL, C#) in their daily workflows.

**DATABASE TRENDS**

**DATABASE TRENDS - FINDINGS AND IMPLICATIONS**

**Findings**
- PostgreSQL remain currently the most popular 
database worked with and by far the most desired 
database developers want to work with.
- Microsoft SQL Server is the second most popular 
choice. However, in the future, interest shifts away 
from SQL Server and overwhelmingly toward 
PostgreSQL.
- The trends shows developers is now working with 
combinations of different databases to get their jobs 
done.

**Implications**
- PostgreSQL is becoming the industry standard.
- Although not required, developers have the initiative 
and shift their preference to use different databases 
together to show their flexibility and secure their 
competency.
- Microsoft SQL Server will face a threat over time 
because developers are less likely to choose this 
database, meaning it must take progressive actions 
to stay relevant.

**DASHBOARD**

**DASHBOARD TAB 1: Current Technology Usage**

**DASHBOARD TAB 2: Future Technology Trends**

**DASHBOARD TAB 3: Demographics**

**Discussion**

The combination of HTML/CSS, JavaScript, and TypeScript is the most widely 
used, as well as the most highly anticipated and desired programming 
language stack among respondents , followed closely by combinations that 
include C# and SQL.

PostgreSQL is a major highlight, showing a strong and unwavering preference 
among respondents both currently and for the future.

Additionally, Spring Boot and React stand out as the top web frameworks, 
being both popularly used and the most desired frameworks developers want 
to work with.

Based on demographics, the developer community is heavily dominated by 
young professionals in the 25–34 age bracket. The vast majority of 
respondents hold a Bachelor’s degree, followed by those with a Master’s 
degree. Lastly, while respondents come from many different locations globally, 
the highest concentration of users is from the United States

**OVERALL FINDINGS & IMPLICATIONS**

**Findings**

The tech stack combinations of HTML/CSS, JavaScript, and 
TypeScript dominate both current developer usage and future 
career aspirations. This web-centric ecosystem is strongly 
complemented by PostgreSQL, which stands alone as the 
single most heavily preferred database system currently used 
(994 responses) and most desired for the future (1,265 
responses).

The developer demographic is overwhelmingly early-to-mid 
career, with young professionals aged 25–34 making up the 
largest slice of the pie at 41.3%. Furthermore, this 
demographic is highly educated: individuals holding a 
Bachelor’s degree account for the vast majority (8,629), 
followed heavily by Master's degree holders (5,000).

Geographically, the United States is the primary hub for this 
respondent pool, boasting a heavy concentration of 3,441 
users. This geographic trend matches job market demands 
where technological strongholds like Washington DC (over 
5,000 postings) and Detroit lead the charts, contrasting sharply 
with regions like San Francisco, Austin, or Philadelphia which 
show remarkably minimal posting counts under 500.

**Implications**

Organizations looking to optimize their tech infrastructure or attract top
tier talent should aggressively align their projects around 
JavaScript/TypeScript web frameworks (specifically React) and 
PostgreSQL database layers. Investing or building in outdated alternative 
frameworks risks alienation, whereas alignment with these technologies 
ensures a seamless recruitment pipeline and long-term project viability.

Since the core developer pool consists of highly educated 25-to-34-year
olds, companies must offer benefits that appeal to this exact 
demographic. This includes modern, progressive workplace flexibility, 
clear career progression tracks, and robust tuition reimbursement or 
continuous learning programs to satisfy an audience that deeply values 
formal education and personal growth.

Companies seeking traditional developer talent should focus their 
physical recruitment operations near east-coast/midwest hubs like 
Washington DC and Detroit rather than relying purely on legacy West 
Coast tech hubs. Conversely, the massive volume of job openings in these 
top cities implies stiff hiring competition; savvy businesses might find a 
competitive advantage by target-hiring remote talent in underserved 
markets (like Austin or San Francisco) where job postings are currently 
low but talent pools remain active.

**Conclusion**

- There is a clear alignment between what developers currently use and what they desire to work with in the future, highlighted by the absolute dominance of the 
JavaScript/TypeScript ecosystem, React, and PostgreSQL.
- The talent pipeline is heavily concentrated within a young, academically credentialed demographic, specifically professionals aged 25–34 who predominantly hold Bachelor's or Master's degrees.
- While the developer community spans globally, the United States remains the primary geographic epicenter for this respondent base.
- In Module 1 Job Postings, regional employment opportunities 
are highly centralized in specific cities like Washington DC and Detroit, contrasting sharply with much lower activity in traditional tech hubs like San Francisco and Austin.
