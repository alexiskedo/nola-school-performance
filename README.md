# LEAP Longitudinal Achievement Analysis 
In Orleans Parish, is there a relationship between a school's percentage of economically disadvantaged students and its Louisiana Assessment of Educational Progress (LEAP) Mastery+ rate? For this project, I aggregated descriptive, longitudinal data from three different LEAP adminsistration years - 2019, 2021, and 2022. 

As LEAP is only administered to students in 3rd through 8th grade, the conclusions below are drawn from examining from this subset of students. 

# Deliverables 
I was tasked with: 

1. Developing a merged dataset suitable to be used as a basis for performing descriptive analysis. This can be found in the file "final_table.xlsx" and can also be accessed using the link [here](https://github.com/alexiskedo/nola-school-performance/blob/main/final_table.xlsx). My answers to the five analysis questions can be found in my jupyter notebook for this task, titled "deliverable-1-codebook" and also available [here](https://github.com/alexiskedo/nola-school-performance/blob/main/deliverable-1-codebook.ipynb). 

2. Creating a handful of visualizations that show a) the relationships between LEAP achievement and economic status for individual schools in Orleans Parish (again, from 2019, 2021, and 2022) and b) the distribution of average Mastery+ scores for the entire district, broken down by year. These visualizations are published on Tableau public and can be viewed [here](https://public.tableau.com/views/LEAPLongitudinalAnalysis/LEAPLongitudinalAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link). I have also added a screenshot below. 

The visualizations are also an interactive dashboard, which can be accessed with an active Tableau account. 


# Conclusions 
![dashboard](https://github.com/alexiskedo/nola-school-performance/blob/main/dashboard-screenshot.png)

**What, if any, trends or insights exist in the data related to the key question?**
Immediately evident is the strong inverse correlation between the level of economic disadvantage existent in a particular school and that school's LEAP achievement level. The p-value indicates a strong relationship between the two variables (0.0001).

Economic disadvantage was roughly able to account for between 60-70% of the variance of our data (r-squared), indicating that it may have some predictive power. 

There are also some interesting patterns in the boxplots. The variance between average LEAP scores has shrunk considerably from 2019 to 2022 (as shown in the length of the "whisker" elements of each boxplot). There was also a sharp dip downward in the median average score from 19% in 2019 to 10.5% in 2021, evidently due to the effects of COVID-19. However, the median average score has risen back to 13% in the 2022 school year. 

**Are there any schools that seem to be outliers in the data? Please explain.**
Lake Forest Elementary Charter School appears to be one consistent outlier from year to year. Between 78%-89% of students at this school can be classified as economically disadvantaged, yet this school achieves a Mastery+ rate between between 75% and 87% for each of the three years included in this analysis.  


