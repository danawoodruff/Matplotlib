# Matplotlib - The Power of Plots

Analysis of a drug study published by Pymaceuticals, a mythological company.

* Data cleaning: Any mouse ID with duplicate time points is identified and all data associated with that mouse ID is removed. The cleaned data is used for analysis.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![bar](/images/JN2_stats.PNG)

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

![bar](/images/JN_bar.PNG)

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![bar](/images/JNboxplot.PNG)

* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen. Plot the linear regression model on top of the scatter plot.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 
