Matplotlib Pymaceuticals Project

Background:

* Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

* The most recent animal study included 249 mice identified with SCC tumor growth. They were treated with a variety of drug regimens and tumor development was observed over the course of 45 days. The purpose of this study is to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

The following tasks were completed as part of this analysis:

* Checked the data for any mouse ID with duplicate time points and removed data associated with that mouse ID.

* The cleaned data was utilized for the remaining steps.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

* Calculated the quartiles and IQR and quantitatively determined if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, I generated a box and whisker plot of the final tumor volume for all four treatment regimens. 

* Generated a line plot of tumor volume vs. time point for a mouse treated with Capomulin. 

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.

Observations from this Analysis:

* There is a positive and stastically significant correlation between weight and tumor volume. Increased weight indicates the mouse in quetion will in most cases have a greater tumor volume. This can be seen in the Correlation and Regression section with a correlation coefficent of 0.84. 

* Capomulin and Ramicane had the best performance amongst the different regimens included in this study with an average final tumor volume of less than 40 mm3. 

* The Ketapril drug regimen had the highest average tumor volume (55.24 mm3) across the treatment cycle, as well as the greatest varianace (68.55) across the treatment cycle. Capomulin and Ramicane had the lowest average tumor volumes and least variance across the cycle. This indicates both to be the most effective and consistent across those included in the study. 

