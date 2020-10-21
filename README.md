# matplotlib-challenge
Homework

1.  Add dependencies neededfor the workbook
2.  Add the csv files (2) with data, and merge them into a single dataset
3.  Check for duplicates in the merged file (five records) and remove them (drop.duplicates).  (Mouse ID: g989 had duplicate records)
4.  Calculate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen
5.  Generate summary statistics table of the above calculations using pandas DataFrame and aggregate method (SUmmary1 and Summary2 created). 
6.  Generate a bar plot using both Pandas DataFrame and Matplotlib pyplot, which  shows the number of unique mice for each treatment regimen. 
7.  Generate a pie plot using both Pandas's Pandas DataFrame and Matplotlib pyplot, which shows the distribution of female or male mice in the study.
8.  Calculate the final tumor volume of each mouse across four regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles, IRQ, and upper/lower bounds for each regimen.  Identify the outlier for each regimen.  
9. Generate a box and whisker plot of the final tumor volume for all four treatment regimens
10. Select a mouse that was treated with Capomulin (s185) and generate a line plot of tumor volume vs. timepoint
11. Generate a scatter plot of mouseweight versus average tumor volume for the Capomulin
12. Calculate the correlation coefficient and linear regression model equation between mouse weight and average tumor volume for the Capomulin.  

Observations on data:
1.  As this is a controlled study, all drug regimen have similar number of mice receiving treatment.  ALso, equal number of male and female mice were used in the study.  This is probably to reduce bias.
2.  Based on the summary statistics of all drug regimen, Ketapril, Naftisol and Stelasyn had the greatest mean tumor volume and it was similar to that of the Placebo treatment.  This implies that the three drugs were statistically no better than placebo.
3.  Based on the summary statistics and the box plots, Ramican might actually be a better drug than Capomulin (lower mean/median).  

