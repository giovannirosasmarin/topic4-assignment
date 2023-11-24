# topic4-assignment

  
DATA VISUALIZATION AND CHARTS REPORT
Giovanni Rosas-Marin
 
 
After the Topic 4 DQ1 and Topic 4 DQ2 about data visualization ethical and variable relationship I had to learn to get the correct data to plot for the data visualization to be able to present better plots that can be represented and understand by the audience in a simpler manner. In this Topic 4 assignment Data Visualization and Charts selected a data set data set found in Kaggle. This data set can be found from the reference list “Income and Happiness Correlation” (1). Selected this data set with the assignment parameters with 8 variables.
 
It has some other variables that I left out that are columns ‘region’, and ‘country.1’ did not use it in getting the relationship between variables used the column ‘country’ to compare the happiness in this countries with the other variables provided ‘avg_statisfaction’, ‘adjusted_satisfaction’, ‘std_statisfaction’, ‘avg_income’, ‘median_income’, ‘income_inequality’, ‘happyScore’, ‘GDP’.
I got the correlation first of the data set that we can see in the next two images.
  
Select the first format of heatmap for the correlation to be displayed as percentage because it was simpler to understand the correlation between the variables, but the second image is the correct format for the correlation. The correlation with itself will be 1 and if its below one it has some relation but if it goes 0 it has no correlation and the range from "0.6 or -0.6 it can be called good correlation"(2). Also to better understand correlation and the relationship between the variable we need to understand the difference between correlation and causation it will help interpret the data because after getting the correlation in python “data.corr()” it will display the values but that values that the function provide but it does not know if the variables do cause the value of the other variables to change and “causation indicates that one  event is the result of the occurrence of the other event; i.e the is a causal relationship between the two events.”(3). This data set depends on and different factors to achieve happiness and it is true if we see the data and the countries income and satisfaction is does gives a correlation that makes the happiness value increase or decrease.
 
Looking at the sns.pairplot (data, diag_kind='kde', kind='scatter', hue='country') there is some linear in the points and some non-linear. This data can have correlation but can not be sure that it has a relationship if this variables make happiness in this countries but by logic it does makes sense at some level that income and satisfaction can help improve your life happiness but this topics to know if this variables have causation can be seen in the next topic 5 with regression to know if this variables make happiness dependent of this changes. 
Also did some linear and bar plots of the data and it goes between the columns and creates the plots to get a visualization of each variable with comparison with other variables.
The linear graph would be harder to comprehend than the bar plot or histogram provided, and it is also displayed per column information. The bar graph is simpler to interpret the data it was used country as the x axis and y-axis = columns to get the differences between countries and get and idea that each variable creates a relationship to happiness in each of this countries.
 
Reference: 
1.	Levy, E(2020) Income and Happiness Correlation. Happiness and Growth, Kaggle
https://www.kaggle.com/datasets/levyedgar44/income-and-happiness-correction/data 
2.	https://www.geeksforgeeks.org/python-pandas-dataframe-corr/
3.	Australian Bureau of Statistics, Correlation and Causation (Website) Accessed on November 15, 2023https://www.abs.gov.au/statistics/understanding-statistics/statistical-terms-and-concepts/correlation-and-causation#:~:text=A%20correlation%20between%20variables%2C%20however,relationship%20between%20the%20two%20events.


