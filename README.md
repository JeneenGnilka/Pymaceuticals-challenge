# Pymaceuticals-challenge

Prepare data
	- Ran provided package dependency and data imports
	- Merge the mouse_metadata and study_results DataFrames into a single DataFrame
	- Display number of unique Mouse IDs
	- Checked for duplicates and display related data
	- Created new DataFrame with duplicate data removed
Generate Summary Statistics
	- Include a row for each Drug Regimen - names should be contained in the index
	- Separate columns for each of the following: mean, median, variance, standard deviation, and SEM of the tumor volume
Create Bar and Pie Charts
	- Generate two bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen. First using DataFrame.plot() and second using pyplot.
	- Generate two pie charts showing the distribution of female vs male mice in the study. First using DataFrame.plot() and second using pyplot.
Calculate Quartiles, Find Outliers, and Create a box plot
	- Calculate the final tumor volume for the four most promising regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
	- Calculate the quartiles and IQR, and determine if there are any potential outliers.
	- Created a grouped ‘DataFrame that shows the last time post for each mouse. Merged this grouped DataFrame with original cleaned DataFrame.
	- Created list of 4 treatments and and empty list to hold the tumor volume data
	- loop through each drug in the treatment list to find them in the created merged DataFrame. Appended the resulting final tumor volumes for each drug to the empty list.
	- Determine outliers by using the upper and lower bounds. Printed results.
	- Created a box plot that shows distribution of the final tumor volume for all mice in each treatment group.
Created Line and Scatter Pit
	- Selected a single mouse that was treated with Capomulin and generated a line plot of tumor volume vs time point for that mouse.
	- Generated a scatter plot of mouse weight vs average observed tumor volume for the entire Capomulin treatment regimen.
Calculated Correlation and Regression
	- Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin regimen
	- Plotted the linear regression on top of previous scatter plot
