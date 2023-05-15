# DATA-ANALYTICS-EXCEL-TERRO-REAL-ESTATE-AGENCY

1.The first step to any project is understanding the data. So, for this step, generate the summary statistics for each of the variables. What do you observe? • From the given data, the mean=68.575 shows the average age value in the town. • From the median=77.5, it clearly shows that most of them are aged persons in the town. • All the given variables except the PT-ratio have a Positive skewness. • There is minimum outlier data in Crime rate, NOX and Avg. Room.

2.Plot the histogram of the Avg_Price Variable. What do you infer? • AVERAGE PRICE is a dependent variable, which has a very few outlier data and it is Rightly skewed with a leptokurtic kurtosis. • There are 133 Houses with the price range of 21000 dollars to 25000 dollars.

3.Compute the covariance matrix. Share your observations. There are both Positive covariance and Negative covariance in the above matrix. The most positive covariance value is 2397.942 (Tax and Age) The most Negative covariance value is -724.82 (Tax and Avg_price)

4.Create a correlation matrix of all the variables as shown in the Videos and various case studies. State top 3 positively correlated pairs and top 3 negatively correlated pairs. Top 3 Positive correlated values • Tax and Distance • Indus and Nox • Age and Nox Top 3 Negative Correlated values • Avg_price and Lstat • Avg_room and Lstat • Avg_price and PT ratio

5.Build an initial regression model with AVG_PRICE as the y or the Dependent variable and LSTAT variable as the Independent Variable. Generate the residual plot too. a. What do you infer from the Regression Summary Output in terms of variance explained, coefficient value, Intercept and the Residual plot? • The value of the variance is less than 0.05, so the model is highly significant. • From the residual plot, we can see that there is some outlier in a data.

b. Is LSTAT variable significant for the analysis based on your model? Yes, LSTAT variable is significant for the analysed model.

6.Build another instance of the Regression model but this time including LSTAT and AVG_ROOM together as independent variables and AVG_PRICE as the dependentvariable? a. Write the Regression equation. If a new house in this locality has 7 rooms (on an average) and has a value of 20 for L-STAT, then what will be the value of AVG_PRICE? How does it compare to the company quoting a value of 30000 USD for this locality? Is the company Overcharging/ Undercharging? BY using a regression equation, the AVG_PRICE value is 21.4581. Comparing to the quoting value, the company is overcharging for the property.
b. Is the performance of this model better than the previous model you built in Question 5? Compare in terms of adjusted R-square. Explain. • Previous model Adj. R-square= 0.543241825954707 • New model Adj. R-square= 0.637124475470123 • Yes, the performance of this new model is better than the previous model by comparing to the value of adjusted R-square.

7.Now, build a Regression model with all variables. AVG_PRICE shall be the Dependent Variable. Interpret the output in terms of adjusted R-square, coefficient and Intercept values, Significance of variables with respect to AVG_price. Explain? By seeing the coefficient from the regression data, we can say that • Avg. price and Avg. room variables are directly proportional. • NOX and Avg. Price are inversely proportional to each other. The significance variables in this model are: • AGE • INDUS • NOX • DISTANCE • TAX • PTRATIO • AVG_ROOM • LSTAT

8.Pick out only the significant variables from the previous question. Make another instance of the Regression model using only the significant variables you just picked. a. Interpret the output of this model. This model has a Better Adjusted R-square value of 68.86%.

b. Compare the adjusted R-square value of this model with the model in the previous question, which model performs better according to the value of adjusted R-square? The New model performs well than the previous model by comparing the value of an Adjusted R-square value.

c. Sort the values of the Coefficients in ascending order. What will happen to the average price if the value of NOX is more in a locality in this town? The AVERAGE_PRICE is HIGH, if the NOX is LOW

d. Write the regression equation from this model. Multi-Linear regression equation: Y=m1x1+ m2x2+ m3x3+ m4x4+ m5x5+ m6x6+ m7x7+ m8x8 + c Multi-linear regression equation of this model: Y= -10.2727050815094x1 -1.07170247269449x2 -0.605159282035406x3 -0.0144523450364819x4+ 0.0329349604286303x5+ 0.130710006682182x6+ 0.261506423001819x7+ 4.12546895908474x8 + 29.4284734939458

Y= Predicted Variable m= weight of the variable Xn= Independent variable C= Intercept
