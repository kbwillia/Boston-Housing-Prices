# Boston-Housing-Prices

Project 3. Boston Housing Research methods
1.	Choose a variable other than CHAS and MEDV (the target, median home price).
a.	Compute the mean and standard deviation of the variable.
b.	Plot a histogram of the variable.
c.	What is the sample correlation between your chosen variable and median home price?
d.	Perform a regression, predicting MEDV from your chosen variable.
 
2.	You have a theory that tracts that border the Charles River (CHAS) will have higher median price (MEDV or target) than those that do not.
a.	What is the null hypothesis?
b.	Calculate the p-value. Use the sample mean of the target as an estimate of the population mean.
c.	What is the 90% confidence interval for the target (price) of tracts that border the Charles River?
d.	Assume an effect size (Cohen’s d) of 0.6. If you want 80% power, what group size is necessary?
 
3.	Imagine you are the city planner of Boston and can add various new features to each census tract, such as a park. Be creative with your new “features” – we use the term loosely. You can assume that none of the tracts contained your features previously. Design an experiment to explore the effects of these features on the media house price in census tracts. You should include an explanation of the experimental design as well as a plan of analysis, which should include a discussion of group size and power. Be sure to apply the knowledge you learned in the Data Science Research Methods courses.
The new feature I propose to add in the area would be 
1)	Scooter/Bike path and scooter/bike stations

Overall Experiment plan:
1)	The Research process
a)	Goals of research is to determine the following:
i)	If residents would like an added path and scooters and bikes
ii)	How much path to put?
iii)	How wide? Material?
iv)	Where to put path?
b)	Clarifying questions
i)	Quantify survey questions on Likert Scale
ii)	Ex: How often would you use path (1-5)? How far your commute is?
c)	Psychology of data
i)	Phrase and ask questions to reduce bias 
ii)	Ex: leading questions, double barrel, Jargon, double negatives, loaded questions
2)	Planning for analysis
a)	Sample vs population
i)	Determine sample size for 80% power
ii)	Code below
b)	Discrediting null hypothesis
i)	Null hypothesis would be that adding the path, scooters, and bikes will not raise median price
ii)	Will test by adding the feature “distance to path/scooter on next census or path use

3)	Correlation and experimental design
a)	Correlate with MEDV
