<img width="1657" height="798" alt="image" src="https://github.com/user-attachments/assets/b98a7b26-10cb-4834-942d-f126d93a4e2c" />

# Global Layoffs (Starting From March 2020) Tableau Visualization
This project analyzes **global layoffs starting from March 2020** using a dataset sourced from **Kaggle**. The goal of this project is to clean **raw real-world data**, perform **SQL-based exploratory data analysis**, and build **interactive dashboard in Tableau** to uncover trends and patterns in workforce reductions across industries and countries.

This project showcases **end-to-end data cleaning, SQL-based analysis, and actionable insights for a Data Analyst portfolio**.

### [GLOBAL LAYOFFS Interactive Dashboard](https://public.tableau.com/views/GlobalLayoffsStartingfromMarch2020/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

--

# Background
With recent layoffs across major tech companies and other industries, I became curious about the underlying causes and their broader impact. To better understand this trend, I performed exploratory data analysis on the **Global Layoffs** dataset from Kaggle. The analysis reveals that **tens of thousands of employees** have been laid off across **57 countries, 2,586 companies, and 31 industries from 2020 to 2024**, highlighting the global scale and severity of this issue.

--

# About the Dataset
As stated above, the dataset was obtained from **Kaggle** https://www.kaggle.com/datasets/theakhilb/layoffs-data-2022 and contains company-level layoff records across **57 countries** and **31 industries** from **2020 to 2024**. It consists of **12 columns** out of which only nine were useful for EDA. These columns are: **company**(name of the layoff company), **location**(location of the company headquarters), **industry**(industry of the company), **total laid_off**(number of employees laid off), **percentage laid_off**(percentage of employees laid off), **date**(date of layoff), **stage**(stage of company funding), **country**(the country where company resides), and **fund_raised**(fund raised by the company in Million $). 


![](https://i.imgur.com/OEYzKPw.png)

--

# Data Cleaning Process
The dataset was loaded into **MySQL** and converted into a database table. A duplicate working table was created to ensure the raw data remained unchanged. The data was then cleaned using the following steps:

- Identified and removed duplicate records using temporary tables.
- Standardized data formats, corrected spelling inconsistencies, and converted the date column to a standard format.
- Updated incorrect data types and replaced blank values with NULL.
- Handled missing, null, and misleading values.
- Removed irrelevant rows and columns.

--

# Data Analysis AND Visualization
I utilized **SQL** to perform **exploratory data analysis (EDA)** on the layoffs dataset and leveraged the insights to create visualizations in **Tableau**. While there were many possible ways to visualize the data, the following key visualizations were created:

# Funds Raised By Top 20 Companies
This bubble chart Visualization displays the funds raised by the top 20 companies, with each bubble representing a company. The size of the bubbles indicates the amount of funds raised, with larger bubbles representing higher amounts. For instance, Netflix has raised the most funds, as shown by the largest bubble, followed by other companies like Meta, Uber, and WeWork. The chart effectively highlights the comparative fundraising levels among these companies.

![](https://i.imgur.com/id4VV2U.png)

# Layoffs Per Industry
This horizontal bar chart displays the number of layoffs across various industries. The industries are listed on the left, with the corresponding number of layoffs represented by the length of the bars plus the extra layoffs label at the end of the bar. The Retail industry has experienced the highest number of layoffs, followed closely by the Consumer and Other sectors. The chart provides a clear comparison of layoffs across different industries, highlighting the sectors most affected.

![](https://i.imgur.com/W5d9ZV9.png)

# Global Layoff Map
This World Map Visualization illustrates the distribution of layoffs across various countries worldwide. Each country is shaded differently, with labels indicating the number of layoffs recorded in that location. The United States shows the highest number of layoffs at 406,643, followed by other countries such as Canada, Brazil, the United Kingdom, and others. The map provides a geographical overview of the impact of layoffs, highlighting the countries most affected.

![](https://i.imgur.com/HdGjst3.png)

# Annual Layoffs Comparison(From the Years 2020 to 2024)
This pie chart Visualization shows the distribution of layoffs over five years. The sectors of the pie represent different years, with percentages indicating the proportion of total layoffs that occurred each year. The chart highlights that the highest percentage of layoffs occurred in 2023 (43.90%), followed by 2022 (27.41%). The smallest portion is from 2021 (2.64%). This visualization provides a clear comparison of layoffs by year, emphasizing the most and least affected time periods.

![](https://i.imgur.com/yMVKgWR.png)

--

# Recommendations
Companies facing economic challenges should explore alternatives to large-scale layoffs. This includes improving **financial forecasting**, implementing **cost-saving measures** such as temporary pay adjustments, investing in **employee development**, and adopting **flexible staffing strategies**. Fostering a culture of **innovation** and **operational efficiency** can help organizations navigate downturns while retaining talent.

For employees, staying **adaptable** and continuously **upskilling** increases versatility and reduces the risk of being affected by layoffs. Maintaining **open communication** with employers, participating in **collaborative problem-solving**, and engaging in team-building or social initiatives can further support workforce stability and mitigate the need for reductions.

--

# Conclusion
Since March 2020, global layoffs have had a significant impact, totaling **599,442 employees**. Major companies such as **Netflix, Meta, and Uber** raised substantial funding, which does not appear to correlate with the number of staff laid off. The **Retail industry** was the most affected, with **70,157 layoffs**, followed by the **Consumer** and **Transportation** sectors. The **Global Layoff Map** highlights notable layoffs in countries including **Canada** and the **United Kingdom**.  

Layoffs peaked in **2023**, accounting for **43.9% of the total**, followed by a sharp decline in **2024**, which represented **12.53% of the total layoffs**, indicating a significant recovery compared to the previous year.
