# School District Analysis

## Project Overview

The purpose of this project is to analyze the data for the math and reading standardized test results of an entire School District as well as analyzing the correlation to between sets of data such as funding and student grades, in order to learn new insights and visually provide clear results on each school's performance. This analysis was conducted twice due to potential academic dishonesty among a group of students at one of the high schools in the school district. The group's test scores in question were omitted from the shool district analysis.

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
- The school district had both its averages for the math and reading scores also decrease

*District Summary (Original)*

*Districted Summary (Updated)*

**How is the school summary affected?**
- The overall passing percentages for Thomas High School decreased significantly

*School Summary (Original)*

*School Summary (Updated)*

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
- Thomas High School lost it's placement as a top five school in the school district 

*Top 5 Schools (Original)*

*Top 5 Schools (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Top%205%20Schools.png>

*Bottom 5 Schools (Original)*

*Bottom 5 Schools (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools.png>

**Math and reading scores by grade?**
-  To increase back to high average scores and it's position as a top 5 school

*Math Scores (Original)*
- For the original math scores click here: [Original Math Scores]()

*Math Scores (Updated)*
- For the updated math scores click here: [Updated Math Scores](https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Math%20Score%20in%20each%20grade%20level%20at%20each%20school.png)

*Reading Scores (Original)*
- For the original reading scores click here: [Original Reading Scores]()

*Reading Scores (Updated)*
- - For the updated reading scores click here:[Updated Reading Scores](https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/Average%20Reading%20Score%20in%20each%20grade%20level%20at%20each%20school.png)

**Scores by school spending?**
-  is not affected

*Scores by Spending (Original)*

*Scores by Spending (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20Budget%20per%20Student.png>

**Scores by school size?**
- is not affected

*Scores by Size (Original)*

*Scores by Size (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20School%20Size.png>

**Scores by school type?**
- is not affected

*Scores by School Type (Original)*

*Scores by School Type (Updated)*
<img src = https://github.com/pfrivas/School_District_Analysis/blob/main/Resources/School%20Performance%20based%20on%20School%20Type.png>

## Summary
