# Birth-Statistics-and-School-Funding
An exploration of possible relationships between birth weights and public school funding received by the mother.

To view results and a summarized analysis, please follow this link to the Tableau storyboard for this project:  
https://public.tableau.com/app/profile/sebastian5242/viz/FromPublicSchooltoChildbirthAnExplorationofBirthStatisticsandSchoolFunding/Story1

DATA SOURCES

Source: US Births by Year, State, and Education Level (2016 – 2021)  
Source Description: This data was sourced from the CDC Natality page  
Data Description: This data provides educational level and average age for mothers who gave birth from 2016 to 2021, as well as additional data about the state, year, and baby birth weight.  
Limitations: All values fewer than 10 births in a category have been suppressed.  
Link to Dataset: https://www.kaggle.com/datasets/danbraswell/temporary-us-births  
Dimensions: 5496 rows, 9 columns  
Scope: The data encompasses the whole population of mothers and children  
Missing Values: There are rows missing for Maine, Montana, and Nebraska due to CDC-suppressed data. No cells included in the dataset contain missing values.  
Duplicates: None  


Source: US Educational Finances (1992 – 2016)  
Source Description: This data was sourced from the US Census Bureau  
Data Description: This data provides summaries of revenues and expenditures for each state from 1992 – 2016 as they pertain to education.  
Limitations: There is no accounting for inflation over time, only raw values.  
Link to Dataset: https://www.kaggle.com/datasets/noriuk/us-educational-finances  
Dimensions: 1275 rows, 12 columns  
Scope: The data encompasses the whole population of finance data by state and year  
Missing Values: ‘Enrolled’ and ‘Other Expenditures’ are missing for the year of 1992, leaving 51 blanks for each.  
Duplicates: None
