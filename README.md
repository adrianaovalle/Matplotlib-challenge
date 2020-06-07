# Matplotlib-challenge

## Background

The following report presents the results of the analysis of 249 mice identified with SCC tumor growth. The animals were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

## Study Results


## Detailed Analysis

### Data Quality
The 1893 test data points received were checked for quality. Mice with ID g989 was found to have duplicate measurements at the same time points. The 5 data points presented in the table below were discarded. 1888 test data points represent the clean dataset.
![Table1](Images/table1.jpg)

### Summary Statistics
The following table presents the statistics of the tumor volume in mm3 for each regimen.
![Table2](Images/table2.jpg)

### Bar Plots
The following bar plot presents the number of mice per time point for each treatment.
It is noted that the number of mice reduces as the days pass. One assumption is that mice do not survive the tumor. The treatment of study Capomulin maintains the number of mice high accross the study, followed by Ramicane. The other treatments have count mice redutcion along the study.
![Figure1](Images/Fig1.png)

### Pie Plots
The distribution by gender of the mice in the study is equivalent. Half of the mice are female and the other half are males.
![Figure2](Images/Fig2.png)

### Quartiles, Outliers and Boxplots
Four regimens of interest were reviewed with more detail: Capomulin, Ramicane, Infubinol and Ceftamin.
The box plots below show the Tumor Volume in mm3 for the 4 regimens, for the last reading of the treatment of each mice. All the mice started with a Tumor Volume of 45mm3. Both Capomulin and Ramicane have reduced the tumor volume of the mice. Ramicane has a lower median of 36mm3 compared to 38mm3 from Capomulin. Both Infubinol and Ceftamin have mice tumor volume increase in their results.

![Figure3](Images/Fig3.png)

### Line and Scatter Plots
Line plots are generated for any mice under Capomulin regimen. All plots show how reduction of Tumor Volume over time, as shown in the figure below for mouse y793.

![Figure4](Images/Fig4.png)

A positive correlation was developed for mice weight against Tumor volume. The r^2 is 0.71 indicating a fair correlation: tumor volume increases as the weight of the mice increase.
