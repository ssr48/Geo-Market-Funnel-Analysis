# Geo-Market-Analysis
## Read Me 
This repository provides the code and an an analytical tool in the form of a Tableau dashboard to analyze the enrollment funnel at geographic, First Source Code, high schools, and academic level. It captures data for enrollments in Fall 2017, Fall 2018, and Fall 2019 Freshmen from the US(1).

## Code
The code in python (Jupyter Notebooks) is used to clean the data, output descriptive statistics, and set up the data for Tableau Dashboard

## The Dashboard 
This dashboard is comprised of four sections - Targetting, First Source Code, High Schools, and Distributions.   

### Targetting 
The Targetting tab displays specific measures pertaining to the enrollment funnel at the state and city level to help the user track geographically the origins of inquiries and their further development through the enrollment funnel. The 'Select Measure' parameter allows the user to select the specific measures to display while the filters on the left side of the dashboard allows for drilling into specific candidate populations. The state map also acts as a filter. Clicking on a particular state displays data pertaining only to that state. User can select multiple states through the map or by using the State filter on the left.  

### First Source Code 
The First Source Code tab displays three key visualizations. The map captures geographically the first source codes using student ZIP codes. The list of first source codes sorts the data in descending order of magnitude for all first source codes. Both the map and the list displays measures as selected in the parameter "Select Display". Separately, the scatter plot displays counts of inquiries, applications, admissions, and enrollments againsts rates of conversion across the enrollment funnel for each first scource code. The user can slect the X-Axis and the Y-Axis displays using the parameter just above the scatter plot. The filters for the entire dashboard are located on the left. The list of first source codes also acts as a filter for both the map and the scatter plot. The user can select multiple first source codes from the list while holding ctrl/command button or using the first source code filter on the left.  

### High Schools 
The High Schools tab, like the First Source Code tab, displays three key visualizations. The map captures geographically the high schools using student ZIP codes(2). The list of high schools sorts the data in descending order of magnitude for all high schools. Both the map and the list displays measures as selected in the parameter "Select Display". Separately, the scatter plot displays counts of inquiries, applications, admissions, and enrollments againsts rates of conversion across the enrollment funnel for each high school. The user can slect the X-Axis and the Y-Axis displays using the parameter just above the scatter plot. The filters for the entire dashboard are located on the left. The list of high schools also acts as a filter for both the map and the scatter plot. The user can select multiple high schools from the list while holding ctrl/command button.  

### Distributions 
The Distributions tab displays the distribution of all inquiries by the ACT Scores(3), age at which loyola contacted them, age at which they entered college(4), and the number of months between initial contact and entry to college. The "Range" legend displays the range of values while the "Select Range Measure" parameter allows the user to select the measure to be displayed. Note that depending upon the availability of data, the number of inquiries displayed on each chart will vary. This tab should be used as a supplement to the overall analysis from the first three dashboards.  

### Notes 
    1. Candidates from outside of the US are not part of the analysis. Furthermore, the analysis also excludes the states of Alaska and Hawaii.  
    2. Note that students from different zip codes could attend the same high school. As such, selecting a high school can display multiple points on the map. 
    3. The dashboard displays the ACT scores for students reporting SAT scores by using the SAT to ACT concordance for their respective years of application. Owing
    to a lack of trackability, it is assumed that candidates who were part of Fall 2019 took their SAT in 2018 and as such the 2018 concordance is used for Fall
    2019 candidates.  
    4. Date of entry to college is assumed be August 1st of the application year. Age of entry and time between contact and entry is calculated based on the date of
    entry. 
