# Machine Learning Algorithms From Scratch

This repository consists of all the machine learning algorithms written from scratch using only pandas, numpy and matplotlib libraries

## Simple Linear Regression

Linear regression is a basic statistical algorithm used to find relationships between two things, like how one changes when the other changes. Imagine you’re studying how the number of hours someone studies affects their exam scores. You collect data from several students, plot it on a graph, and notice that as study hours increase, exam scores also tend to go up. Linear regression helps you draw the best-fitting straight line through those points, called the "line of best fit." This line summarizes the relationship, making it easier to predict an exam score based on the number of hours studied.

Another example could be predicting the cost of a house based on its size. If you gather data on house sizes and their prices, you can plot the data points and use linear regression to find a line that shows how price changes with size. Once you have this line, you can estimate the price of a house of a specific size.

The method works by minimizing the differences between the actual data points and the values predicted by the line. These differences are called "errors" or "residuals." Linear regression is widely used because it’s simple yet effective in many real-world scenarios, such as forecasting sales based on advertising spend, estimating fuel consumption based on speed, or predicting crop yield based on rainfall. It’s like a tool for finding patterns and making educated guesses based on past data.

In Univariate Linear Regression, we use only one independent variable, like years of experience, to predict the dependent variable, salary. The relationship can be represented as:

$$\hat y = wX + b$$

Here:

- $\hat y$ is the predicted salary.
- $X$ is the input (years of experience).
- $w$ is the weight (slope of the line).
- $b$ is the bias (y-intercept).

For example, if we gather data showing how salaries vary with experience and plot it, linear regression finds the straight line that best fits the points. This allows us to predict the salary for someone with, say, 5 years of experience.

