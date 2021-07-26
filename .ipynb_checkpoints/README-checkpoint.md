# matplotlib-challenge
#### *Perform analyses of fictional pharmaceutical test data.*

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

Two data files are used:
1. **Mouse metadata**: For each of the 249 mice, a unique ID ('Mouse ID'), drug regimen tested, mouse sex, mouse age (months), and mouse weight (g).
2. **Study results**: Time series data by 'Mouse ID' representing number of metastatic sites and tumor volume (mm<sup>3</sup>) between 0 and 45 days, measured in 5 day intervals.

During initial data review, one 'Mouse ID' (g989) was identified with duplicate time entries (but differing tumor measurements). Lacking guidance on the source of the error, all data related to *g989* were removed from the study.

The following analyses were performed:
* Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* Bar chart of number of mice on each drug regimen.
* Pie chart of number of mice by sex.
* Exploratory analysis of Capomulin performance
    * Boxplots of final tumor volume by drug regimen for Capomulin and three other drug regimens.
    * Time series line plot of tumor volume for one mouse treated with Capomulin.
    * Scatter plot of mean tumor volume versus mouse weight for mice treated with Capomulin.
    * Correlation between mean tumor volume and mouse weight for mice treated with Capomulin
    * Regression model for mean tumor volume on mouse weight for mice treated with Capomulin
    
Supplemental analyses were performed, and the following observations and inferences are provided:
1. The number of mice tested with each drug regimen is essentially equivalent (n = 24 or 25), so variation in the initial population of drug regimen replicates is not a source of bias. However, a supplemental analysis demonstrates that the number of mice in each drug regimen with reported results at day 45 is considerably less, ranging from 7 to 21. As a result, variations in drug regimen replicates across the study duration may introduce bias and complicate comparison of results.
2. The distribution of sex is essential equivalent (male = 125, female = 123). However, a supplemental analysis shows that sex is not distributed equally for many drug regimens. Statistical analyses should be conducted to determine whether results are influenced by mouse sex.
3. The range and distribution of final tumor volume for Capomulin is comparable to Ramicane, while the range of the final tumor volume for other eight drug regimens is much higher, as shown in the supplemental analysis. Further analysis could be conducted to determine whether Capomulin and Ramicane differ in other meaningful ways.
    





