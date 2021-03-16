# Pymaceutical Study

## Background

The purpose of this project was to leverage my knowledge of the Python Matplotlib and apply it to a real-world situation and dataset:

![Laboratory](Images/Laboratory.jpg)

In this projected I acted as a senior data analyst for the fictitious company Pymaceuticals Inc. 

Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

I received a complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. 

The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

My responsibility was to generate all of the tables and figures needed for an executive committee technical report of the study. 


## Method

I first cleased the data to check for any mouse ID with duplicate time points and removed any data associated with that mouse ID.

Next I generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

I followed this by constructing a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that showed the total number of measurements taken for each treatment regimen throughout the course of the study.

Additionally, I generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that showed the distribution of female or male mice in the study.

I then performed statistical analysis by calculationg the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. I calculated the quartiles and IQR then quantitatively determined if there are any potential outliers across all four treatment regimens.

Using Matplotlib, I generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

I selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

I then generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

I calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. After that, I plotted the linear regression model on top of the previous scatter plot.

Once this analysis was completed I wrote up my observations.

### Contact
Lauren Parrish
ljeanparrish@gmail.com
