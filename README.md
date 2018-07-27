# Model the Rate of Uninsured Individuals in the United States as a function of:
Poverty & Poverty and Unemployment

# Data Sources included:
-APIs from the US Census Bureau
-US Bureau of Labor Statistics
-Inkplant.com



In this project, we wanted to look at something that a lot of people care about on a daily basis. We were passionate about modeling the rate of uninsured individuals in the United States as a function of poverty and then include both poverty and unemployment at the same time.

Our objects are as follows: Find our R2 and MSE scores to see whether or not our model works and experiment with the data set with our regression model. 

Technologies Used:
Python
Pandas
Matplotlib
Scikit Learn
Numpy
Jupyter Notebook
Sqlite
MS-Excel
Tableau
Agile Scrum

We’ll start out with univariate regression, just a basic linear model. We created a Univariate Linear Regression and calculated the correlation, R2 score and Mean Square Error. 
The correlation between Poverty and people without Insurance is 47%. 
The R2 score is around 0.17. 

We created as scatter plot and notice that the prediction of the model (shown in red), lies in between the actual data set, showing a positive correlation between the two parameters.
The counties on the line of best fit have the greatest correlation between poverty and uninsured.

Our next step was to draw a histogram of Uninsured and poverty. The data is skewed as we can see from the long tail of the histogram.

To smoothen the data we took the LOGARITHMIC values ot the two parameters(Poverty and Uninsured). The scatter plot pretty much tells the same story.

We generated a Random Forest Regression and noticed a small reduction in the overall R2 score form 0.22 to 0.19. The scatter plot is very similar to the Linear Regression.
