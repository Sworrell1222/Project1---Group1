# Project1
Sonya Worrell, Albert Ofori, Dameon Turner, Bright Tsevi

This project utilizes a data from the U.S. Beraeu of labor from the year 2019. The data inlcudes states, job and job descriptions, and many other attributes related to job and employment status. 

Questions to answer from datatset: 
1. How many High Tech and Non Tech Jobs are currently in the US both Nationally and by State?
2. What are the Annual Salaries of High Tech versus Non - Tech positions both nationwide and by State?
3. Which State has the highest salaries for high tech jobs?
4. Which State has the lowest salaries for high tech jobs?

Steps:

1. IMPORT DATA AND REPLACE * AND ** WITH NaN
2. FILTER ONLY US STATES
3. DEFINE FUNCTION TO REPLACE ALL '#' VALUES 100 FOR ALL HOURLY RATE COLUMNS AND 208000 FOR ANNUAL SALARY COLUMNS
4. REPLACE '#' VALUES WITH AFOREMENTIONED VALUES
5. DEFINE FUNCTION TO LOOP THROUGH COLUMNS OF INTEREST 
6. Find indices with null values 
7. Remove rows and null value indices
8. Remove unwanted characters
9. Cast cleaned columns as float
10. CLEAN ALL COLUMNS OF INTEREST
11. ENSURE ALL COLUMNS OF INTEREST HAVE NON-NULL VALUES
12. CALCULATE NUMBER OF HOURS WORKED PER WEEK FROM ANNUAL MEAN AND HOURLY MEAN
13. PRINT OUT MAXIMUM AND MINIMUM HOURS WORKED PER WEEK
14. DEFINE KEYWORDS THAT CAN BE FOUND IN TYPICAL TECH JOBS
15. CONVERT JOB TITLE COLUMN CHARACTERS TO LOWER CASE
16. FILTER CLEANED DATAFRAME TO GET TECH JOBS ONLY
17. DROP ALL TECH JOBS FROM CLEANED DATAFRAME TO GET NON-TECH JOBS
18. DEFINE NEW COLUMN TO INDICATE WHETHER OR NOT A JOB IS A TECH JOB
19. PLOT HISTOGRAM SHOWING PROBABILITY DISTRIBUTION OF TECH AND NON-TECH SALARIES
20. VISUALIZE TECH AND NON-TECH SALARIES USING A BOXPLOT TO IDENTIFY OUTLIERS
21. PERFORM AN ONE-WAY ANOVA TEST
22. GROUP DATAFRAME ACCORDING TO STATE
23. FIND THE MEAN ANNUAL AND HOURLY RATES PER STATE
24. FIND TOP 10 AND LOWEST 10 STATES BY MEAN ANNUAL SALARY
25. GROUP DATAFRAME BY STATE AND JOB CATEGORY
26. FIND AND PLOT TOP 10 STATES BY ANNUAL MEAN SALARY 
27. FIND AND PLOT LEAST 10 STATES BY ANNUAL MEAN SALARY 
28. INVESTIGATE OUTLIERS IN BOXPLOT
29. FIND HIGHEST SALARIES IN THE LOWEST PAYING STATES
30. FIND HIGHEST PAYING JOBS IN THE HIGHEST PAYING STATES
31. FIND HIGHEST PAYING JOBS IN THE LOWEST PAYING STATES
32. VISUALIZE DISTRIBUTION OF WORKING HOURS PER WEEK
33. FIND THE HIGHEST PAYING TECH JOBS
34. FIND ALL JOBS THAT LIE ABOVE THE UPPER FENCE IN TECH JOBS
35. FIND THE TOTAL EMPLOYMENT SPLIT BETWEEN TECH AND NON-TECH JOBS
36. FIND THE TOP AND BOTTOM 10 STATES BY EMPLOYMENT NUMBERS
37. FIND TOTAL EMPLOYMENT OF THE TOP 10 AND LOWEST 10 STATES BY EMPLOYMENT
38. MAKE A PIVOT TABLE OF THE VALUES AND PLOT THE TOP 10 STATES BY EMPLOYMENT NUMBERS
39. MAKE A PIVOT TABLE OF THE VALUES AND PLOT THE LOWEST 10 STATES BY EMPLOYMENT NUMBERS
40. IMPORT DATA ON STATE LONGITUDES AND LATITUDES
41. MERGE LOCATION DATA WITH EMPLOYMENT DATA BY STATE
42. VISUALIZE MAP DATA