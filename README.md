# MATPLOTLIB-Challenge


## Background

A study was conducted in which 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


### Initial Preparation

* Package dependency and data imports are run and `mouse_metadata` and `study_results` DataFrames are merged into a single DataFrame.

* The number of unique mice IDs in the data are displayed, duplicate data is identified, displayed and removed.



### Summary Statistics

* Two summary statistics tables are displayed:

    * The `groupby` method was used to generate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. The data is presented in a single summary statistics table.
    * For the second table, `agg` method is used to produce the same summary statistics table using a single line of code.

### Bar and Pie Charts

* Two bar plots are displayed:

    * Both of these plots are identical and show the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.
    * The first bar plot is created using Pandas's `DataFrame.plot()` method.
    * The second bar plot is crated using Matplotlib's `pyplot` methods.

* Two pie plots are generated:

    * Both of these plots are identical and show the distribution of female or male mice in the study.
    * The first pie plot is created using both Pandas's `DataFrame.plot()`.
    * The second pie plot is creted using Matplotlib's `pyplot` methods.

### Quartiles, Outliers and Boxplots

* The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin is calculated. The quartiles and IQR and quantitatively determine the outliers, if any
    
* A box and whisker plot of the final tumor volume for all four treatment regimens is created. Potention outliers in the plot are identified with a red x. 


### Line and Scatter Plots

* A line plot of tumor volume vs. time point for a selected mouse treated with Capomulin is displayed

* Ascatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen is displayed

### Correlation and Regression

* The correlation coefficient and linear regression model abetween mouse weight and average tumor volume for the Capomulin treatment is determine. The inear regression model on top of the previous scatter plot is plotted.

### Final Analysis

* Three observations are identified at the beginning of the notebook. 