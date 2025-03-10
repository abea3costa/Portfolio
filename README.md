Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)My name is Beatriz Costa
=====================================================================================================================================

Data Analyst
------------

### About
I hold a Bachelor of Science degree with a strong foundation in mathematics and statistics, and I’m about to graduate from the Just IT Data Technician Bootcamp. I transitioned from clinical work into data analysis to explore my enthusiasm for identifying patterns and trends. During my journey, I’ve honed my technical skills using tools like MySQL, Excel, Power BI, Tableau, Python, and R. My goal is to leverage my skills to help organizations make data-driven decisions and promote business growth. Looking for new opportunities to grow professionally and make meaningful contributions as a Data Analyst. I’m excited to apply my experience with BI tools and my problem-solving mindset to real-world data challenges. I’m always seeking new opportunities for personal and professional development, and I'm eager to collaborate on exciting projects!

*   🌍  I'm based in Newcastle Upon Tyne
*   ✉️  You can contact me at [abcostaa@gmail.com](mailto:abcostaa@gmail.com)
*   🧠  I'm learning the best ways to showcase my skills
*   🤝  I'm open to collaborating on exciting data-driven projects

### Skills
<p align="left">
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a><a href="https://www.r-project.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/rlang-colored.svg" width="36" height="36" alt="rlang" /></a><a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="36" height="36" alt="Git" /></a><a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" /></a><a href="https://www.adobe.com/uk/products/photoshop.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/photoshop-colored.svg" width="36" height="36" alt="Photoshop" /></a><a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/googlecloud-colored.svg" width="36" height="36" alt="Google Cloud" /></a>
                    </p>

### Socials

<p align="left"> <a href="https://www.github.com/abea3costa" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> </picture> </a></p>
                    
### CV [pdf](https://github.com/abea3costa/Portfolio/blob/main/CVBC.pdf)


## Table of Contents
- [About](https://github.com/abea3costa/Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/abea3costa/Portfolio/blob/main/README.md#portfolio-projects)
  - Python
    - [GDP (nominal) per Capita](link)
    - [Title](link)
  - MySQL
    - [Title](link)
    - [Title](link)
  - Azure
    - [Title](link)
  - Excel
    - [Title](link)
    - [Title](link)
  - Tableau
    - [Title](link)
    - [Title](link)
  - Power BI
    - [Title](link)
    - [Title](link)

## Portfolio Projects

This repository contains a collection of projects which showcase my work and skills as a Data Analyst. 

## Python

# GDP (nominal) per Capita

## Overview
This project aims to analyse how different estimates relate to each other. The dataset contains information on UN, World Bank and IMF GDP estimates across different countries/territories in the world.

## Technologies Used
- Python (pandas, matplotlib, seaborn)

## Dataset Description
- The dataset consists of 224 records featuring the different GDP estimates and the year these were recorded.
- Source: Kaggle's dataset: [GDP (in USD) Per Capita Income by Country](https://www.kaggle.com/datasets/rajkumarpandey02/gdp-in-usd-per-capita-income-by-country/data) 

## Methodology
- Data Cleaning: Handled missing values using averages and removed outliers.
- Exploratory Data Analysis: Calculated average estimates and visualised if there was a positive or negative correlation between them.
- Analysis: Verified how well each continent was represented by counting the number of records (Countries) per continent. Calculated the average IMF Estimate per continent. Calculated the World Bank Estimate by Year and Continent.
- Visualisation: Built correlation matrix between estimates. Created visualisations for the analysis above.

## Key Findings
- The GDP estimates from the World Bank and the UN showed a strong positive correlation.
- The World Bank and the IMF GDP estimates, as well as the UN and IMF GDP estimates, also show a positive correlation, although not as strong as the one observed between the World Bank and UN estimates.
- Each continent was represented by a comparable sample of approximately 50 country records, with the exception of Oceania’s sample, which only included 20 country records.
- Europe holds the highest GDP estimates and represents the highest rates of record keeping over the years when compared to other continents which present gaps in GDP estimate data.

## Results & Conclusions
- The analysis recommends that the records be dated and organized by year to prevent the risk of comparing the three distinct GDP estimates from different years.
- To ensure a more accurate and streamlined analysis, certain issues related to data collection need to be addressed. These issues include the substantial amount of missing data and the inadequate recording of the years in which each estimate had been recorded, within the same row.

## Challenges & Limitations
- 11% of the cells in this dataset contained missing values, which is fairly substantial. Although these values were replaced with average estimates, this likely impacted the accuracy of the analysis.

