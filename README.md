# Philips_Curve
In this project, I replicated the Philips Curve with the most up-to-date economic statistics from the Federal Reserve Economic Data(FRED), comparing the inflation index with the unemployment rate. 

For my measure of inflation, I used the Personal Consumption Expenditure Price Index and manipulated to obtain the year over year percentage change. I used the Unemployment Rate for my measure of unemployment, that is also on the year over year basis.

I cleaned the datasets containing the relevant data and, for visualization, concised the dataframe to be within the twenty-first century. I colored the scatter dots differently by year range that is determined or categorized by the corresponding significant economic events. I then performed polynomial regression of the inflation measure on the unemployment measure and plotted the best fitted curve on the scatterplot.

I have plotted two different graphs where one contains the data from 2024 and the other doesn't. The comparison between these two graphs showed no apparent shifts of the Philips Curve, potentially due to the size of the weight, but a vertial shift of the scatters. You can find the graphs in pdf files attached above.
