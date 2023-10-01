# Matplotlib
The power of plots


Background
What good is data without a good plot to tell the story?


![obraz](https://user-images.githubusercontent.com/87150331/153756507-2943e545-deb0-44ea-8334-89af707932b6.png)


While my data companions rushed off to jobs in finance and government, remained adamant that science was the way for me. Staying true to my mission, I've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Instructions
My tasks are to do the following:


Before beginning the analysis, I checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.


Used the cleaned data for the remaining steps.


Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of time points for all mice tested for each drug regimen throughout the course of the study.
NOTE: These plots should look identical.


Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.



Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Used this Matplotlib documentation page for help with changing the style of the outliers.


Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.


Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.


Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


Looked across all previously generated figures and tables and wrote three observations that can be made from the data.












