# matplotlib_challenge
Challenge 5 - Matplotlib_Challenge

Analysis Report: 

Summary Statistics: After cleaning up the data and removing any duplicates we look at how the different regimens affected the tumor sizes.  We can see in the dataframe created that the drug Ramicane had the lowest average in tumor size and Ketapril had the highest average in tumor size.  In comparsion to the perferred drug Capomulin, the drug Ramicane had a slightly greater affect in decreasing the tumor size (the results were very close).

Bar and Pie Charts: The bar charts show us how many time a drug regimen was adminstered to the mice. Since Capomulin was the drug of intrest it was administered the most. The pie charts showed the total number to male mice to female mice used during the the 45 days. 

Lines and Scatter Plots: The line graph shows what size the tumor was at each timepoint. I observed mouse l509 who was given Capomulin and we can see from the graph that mouse l509's tumor grew from the first day to until day 20.  At day 20 the tumor size dropped and from here until day 45 the tumor continued to decrease in size with a few times where it did grow slightly but then dropped again. The scatter plot shows how the tumor size and weight may be related to each other when the mice is administered Capomulin.  I observed the affect that the mice weight may decrease when the tumor size decrease.    

Correlation and Regression: This graphs show the correclation and regression how th weight of the mice and tumor size. As stated above the weight decreased when the tumor size decreased. This is greater supported when I applied the regression line and found the correclation to be 0.84. This lets us know that there is great correlation. 


Sources:

1. https://github.com/BindiChen/machine-learning/tree/main/data-analysis - I used this to help with finding the duplicate 

2. https://pandas.pydata.org/docs/reference/api/pandas.core.groupby.DataFrameGroupBy.mean.html - I used to help with me with the grouby for mean, median, and so on. 

3. https://pandas.pydata.org/docs/reference/api/pandas.core.groupby.DataFrameGroupBy.aggregate.html - I used this to help me with aggregation method.

4. https://sparkbyexamples.com/pandas/pandas-filter-rows-by-conditions/ - I used this to help me filer the four drug regimens