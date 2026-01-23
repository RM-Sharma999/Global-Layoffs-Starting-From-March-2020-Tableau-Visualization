<img width="1657" height="798" alt="image" src="https://github.com/user-attachments/assets/b98a7b26-10cb-4834-942d-f126d93a4e2c" />

# GLOBAL LAYOFFS (Starting From March 2020) Tableau Visualization
This project analyzes **global layoffs starting from March 2020** using a dataset sourced from **Kaggle**. The goal of this project is to clean **raw real-world data**, perform **SQL-based exploratory data analysis**, and build **interactive dashboard in Tableau** to uncover trends and patterns in workforce reductions across industries and countries.

This project showcases **end-to-end data cleaning, SQL-based analysis, and actionable insights for a Data Analyst portfolio**.

### [GLOBAL LAYOFFS Interactive Dashboard](https://public.tableau.com/views/GlobalLayoffsStartingfromMarch2020/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

# Background
With recent layoffs across major tech companies and other industries, I became curious about the underlying causes and their broader impact. To better understand this trend, I performed exploratory data analysis on the **Global Layoffs** dataset from Kaggle. The analysis reveals that **tens of thousands of employees** have been laid off across **57 countries, 2,586 companies, and 31 industries from 2020 to 2024**, highlighting the global scale and severity of this issue.

# About the Dataset
As stated above, the dataset was obtained from **Kaggle** https://www.kaggle.com/datasets/theakhilb/layoffs-data-2022 and contains company-level layoff records across **57 countries** and **31 industries** from **2020 to 2024**. It consists of **12 columns** out of which only nine were useful for EDA. These columns are: **company**(name of the layoff company), **location**(location of the company headquarters), **industry**(industry of the company), **total laid_off**(number of employees laid off), **percentage laid_off**(percentage of employees laid off), **date**(date of layoff), **stage**(stage of company funding), **country**(the country where company resides), and **fund_raised**(fund raised by the company in Million $). 


![](https://i.imgur.com/OEYzKPw.png)

# Data Cleaning Process
The dataset was loaded into **MySQL** and converted into a database table. A duplicate working table was created to ensure the raw data remained unchanged. The data was then cleaned using the following steps:

- Identified and removed duplicate records using temporary tables.
- Standardized data formats, corrected spelling inconsistencies, and converted the date column to a standard format.
- Updated incorrect data types and replaced blank values with NULL.
- Handled missing, null, and misleading values.
- Removed irrelevant rows and columns.

# Data Analysis AND Visualization
I Utilized SQL to perform Exploratory Data Analysis on the Layoffs Data and used the insights gathered to create some visualizations using Tableau. There were many possible visualizations using the insights gathered, but i created the following Visualizations:

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

# Recommendations
Companies should look for alternative means of adjusting or responding to economic recession rather than laying off tons of their employees. companies should also enhance financial forecasting, explore alternative cost-saving measures such as temporary pay adjustments, and invest in employee development. Adopting flexible staffing strategies, fostering a culture of innovation, and operational efficiency can also help.\
For employees, staying adaptable and continuously upgrading skills can make them more versatile and valuable, reducing the likelihood of being affected by layoffs.

Open communication between employers and employees and involvement in problem-solving activities and various social outings can also support efforts to navigate financial challenges and mitigate the need for workforce reductions.

# Conclusion
It can be seen that there was a significant impact of global layoffs since March 2020, highlighting a total of 599,442 layoffs. Major companies like Netflix, Meta, and Uber have raised substantial funds that doesn't correlate well with number of staff laid off. The data shows that the Retail industry has been affected the most, with 70,157 layoffs, followed by Consumer and Transportation sectors. The Global Layoff Map reveals notable layoffs in countries such as Canada and the United Kingdom.\
Additionally, there has been a significant increase in layoffs in 2023, accounting for 43.90% of the total, indicating a peak during this year and followed by a sharp decrease in layoffs in 2024 as compared to the previous year, 2023, that counts up to 12.53% of the total.
