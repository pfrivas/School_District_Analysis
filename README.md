# School District Analysis

## Project Overview

The purpose of this project is to analyze the data for the math and reading standardized test results of an entire School District as well as analyzing the correlation to between sets of data, such as funding and student grades, in order to learn new insights and visually provide clear results on each school's performance. This analysis was conducted twice due to potential academic dishonesty among a group of students at one of the high schools in the school district. The group's test scores in question were omitted from the second school district analysis.

## Resources

**Resources:** All data used in this analysis is found inside of the [Resources](https://github.com/pfrivas/School_District_Analysis/tree/main/Resources) folder.

**Software:** Python 3.11, Anaconda, Jupyter Notebook

**Code:** [PyCitySchools Challenge](https://github.com/pfrivas/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Results

### Top 5 and bottom 5 performing schools, based on the overall passing rate

**Top 5 Performing Schools**
- Cabrera High School: Overall Passing Rate = 91.33%
- Thomas High School: Overall Passing Rate = 90.63%
- Griffin High School: Overall Passing Rate = 90.60%
- Wilson High School: Overall Passing Rate = 90.58%
- Pena High School: Overall Passing Rate = 90.54%

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Top%205%20Schools.png>

**Bottom 5 Performing Schools**
- Rodriguez High School: Overall Passing Rate = 52.99%
- Figueroa High School: Overall Passing Rate = 53.20%
- Huang High School: Overall Passing Rate = 53.51%
- Hernandez High School: Overall Passing Rate = 53.53%
- Johnson High School: Overall Passing Rate = 53.54%

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools.png>

### The average math score received by students in each grade level at each school

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Math%20Score%20in%20each%20grade%20level%20at%20each%20school.png>

### The average reading score received by students in each grade level at each school

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Reading%20Score%20in%20each%20grade%20level%20at%20each%20school.png>

### School performance based on the budget per student
- The average performance based on the overall passing rate does not increase as spending per student increases. 
- This is shown by the average math/reading scores not having a positive correlation as funding per student increasing
- This exemplifies that there are more different and more distinguishing factors than budget per student that decides average student scores.

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20Budget%20per%20Student.png>

### School performance based on the school size 
- The average performance based on the overall passing rate does not increase as school size increases, in fact, it decreases. 
- This is shown through the "Large" school in the dataset having the lowest average scores and passing percentages by over 30%. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%)
- This exemplifies that school size is a factor that plays a role in student performance, the data shows that the smaller the school size the better students perform. 

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20School%20Size.png>

### School performance based on the type of school
- Students that went to Charter schools performed better than District schools. 
- This is shown by the top five schools with the highest overall passing percentages all being Charter schools, whereas the bottom five were all District Schools. 
- It is also exemplified by Charter schools having a 36% higher overall passing percentage than District schools.

<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20School%20Type.png>


### How does replacing the ninth-grade scores affect the District Analysis:
Updating the total student counts to exclude Thomas High School ninth grades and omitting their scores from the dataset caused

**How is the district summary affected?**
- The school district had both its averages for the math and reading scores also decrease a near negligible amount
- The change of adding Nan to all grade 9 and Thomas High School math and reading scores did not have a large impact on the district analysis, with each metric decresing by less that 0.5 percentage point each (meaning scores changed by less than 0.5%).
- This is because there were only 461 students in grade 9 at Thomas High School, and given the total student count is 39,170, the grade 9 students only make up 1.2% of the total student count, so removing their math and reading scores should not impact the data set by a significant amount

*District Summary (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/District%20Summary%20Original.png>

*Districted Summary (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/District%20Summary%20Updated.png>

**How is the school summary affected?**
- The overall passing percentages for Thomas High School decreased a significantly

*School Summary (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Summary%20Original.png>

*School Summary (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Summary%20Updated.png>

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
- Thomas High School did not lose it's placement as a top 5 school
- The school rankings (both top and bottom 5) including Thomas High School was not affected by the update.
- This is because the changes of the averages were near negligible for the averages (change of less than 0.1%)

*Top 5 Schools (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Top%205%20Original.png>

*Top 5 Schools (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Top%205%20Schools.png>

*Bottom 5 Schools (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Bottom%205%20Original.png>

*Bottom 5 Schools (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools.png>

**Math and reading scores by grade?**
-  The only score that is impacted on this DataFrame is that the grade 9 students at Thomas High School have Nan instead of a grade for both math and reading.

*Math Scores (Original)*
- For the original math scores click here: [Original Math Scores](https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Math%20Scores%20Original.png)

*Math Scores (Updated)*
- For the updated math scores click here: [Updated Math Scores](https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Math%20Score%20in%20each%20grade%20level%20at%20each%20school.png)

*Reading Scores (Original)*
- For the original reading scores click here: [Original Reading Scores](https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Reading%20Scores%20Original.png)

*Reading Scores (Updated)*
- - For the updated reading scores click here:[Updated Reading Scores](https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Reading%20Score%20in%20each%20grade%20level%20at%20each%20school.png)

**Scores by school spending?**
-  There was a slight change in the scores by school spending groups scores for the $630-644 per student grouping as this is where Thomas High School is grouped, however the change is almost negligible because it's a change of less than 0.1%

*Scores by Spending (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Performance%20by%20Spending%20Original.png>

*Scores by Spending (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20Budget%20per%20Student.png>

**Scores by school size?**
- The scores for the Medium (1000-2000) size schools had an almost negligible change (less than 1 percentage point). 
- They were impacted as Thomas High School included in this group as it has 1,635 students who attend (including the grade 9 students).

*Scores by Size (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Performance%20by%20Size%20Original.png>

*Scores by Size (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20School%20Size.png>

**Scores by school type?**
- Thomas High School is a Charter type school
- This is why we see almost negligible changes to the scores for Charter (less than change of 0.1%)
- There were no changes to District type school scores as Thomas High School not part of that group
- No other school scores were affected.

*Scores by School Type (Original)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Performance%20by%20Type%20Original.png>

*Scores by School Type (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20School%20Type.png>

## Summary

### District Analysis 
- Changes to all scores across all metrics are has a change by less than 0.5%
- The omittion of the ninth graders from THS had no impact to school or student count.

### Math and Reading Scores
- The difference between math and reading passing rates is greater among lower performing schools, large schools, and higher spending per student which all seem to correlate.
- Average math and reading scores stay consistent across grade level when grouped by school

### School Ranking 
- However Thomas High School scores did change by less than 1% for each metric
- No change to ranking when data was omitted

### Scores by School Spending
- Student spending per student is higher in bottom performing schools than top performing
- No change to when data was omitted

### Scores by School Size 
- Smaller schools tend to perform better than Larger schools
- When scores were omitted there were changes to Medium (1000-2000) grouping for all scores by less than 0.1%

### Scores by School Type 
- Charter schools tend to perform better than District schools
- Changes to Charter type grouping for all scores changed by less than 0.1%
