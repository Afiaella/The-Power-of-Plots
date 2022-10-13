# The Power of Plots

## Background

Pymaceuticals Inc. has began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
In this study, 249 mice identified with SCC tumor growth were treated with a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 


## Project Contents


* Prepare the data.

* Generate summary statistics.

* Create bar charts and pie charts.

* Calculate quartiles, find outliers, and create a box plot.

* Create a line plot and a scatter plot.

* Calculate correlation and regression. 

* Submit your final analysis. 

### Prepare the Data

1. I run the provided package dependency and data imports, and then merged the `mouse_metadata` and `study_results` DataFrames into a single DataFrame.

2.I displayed the number of unique mice IDs in the data, and then checked for any mouse ID with duplicate time points. Displayed the data associated with that mouse ID, and then created a new DataFrame where this data is removed. 

3. I displayed the updated number of unique mice IDs.

### Generate Summary Statistics

I create two summary statistics DataFrames:

    * For the first table, I used the `groupby` method to generate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. This resulted in five unique series objects. I combine these objects into a single summary statistics DataFrames.

    * For the second table, I used the `agg` method to produce the same summary statistics table by using a single line of code.
    
    <img width="865" alt="image" src="https://user-images.githubusercontent.com/85926823/195664154-8d6aef85-f3ff-4044-a416-a937dd3ab14e.png">
<img width="864" alt="image" src="https://user-images.githubusercontent.com/85926823/195664281-f702e16f-d074-4b15-a8c2-222cb93d4bfe.png">


### Create Bar Charts and a Pie Charts

1. I created two bar plots. Both plots show the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

    * I created the first bar plot by using Pandas's `DataFrame.plot()` method.

    * I created the second bar plot by using Matplotlib's `pyplot` methods.

2. I created two pie plots. Both plots show the distribution of female or male mice in the study.

    * I created the first pie plot by using both Pandas's `DataFrame.plot()`.

    * I created the second pie plot by using Matplotlib's `pyplot` methods.
    
    <img width="781" alt="image" src="https://user-images.githubusercontent.com/85926823/195664420-01113191-d4b9-49d1-951a-747be6f8f74c.png">
<img width="556" alt="image" src="https://user-images.githubusercontent.com/85926823/195664532-3d8ef0b0-abba-4957-9095-592a3a48d87c.png">


### Calculate Quartiles, Find Outliers, and Create a Box Plot 

1. I calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, I calculated the quartiles and IQR and determine if there are any potential outliers across all four treatment regimens. 

# To be completed...




