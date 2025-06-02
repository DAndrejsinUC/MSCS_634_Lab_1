# MSCS_634_Lab_1

The purpose of this lab was to gain practical experience with basic Data Visualization, Data Processing, and Statistical Analysis techniques. 

I found the lab relatively easy, mainly due to the fact that there are existing libraries and function to perform most if not all of the required steps. For example, instead of calculating Min Max Scaling from scratch, I was able to import relevant library and call the existing functions in one line of code. 

For my data set I followed the lab's suggestion and chose a Sales related dataset from Koggle. It was a huge dataset with almost 10,000 rows. The distribution of the data set had a strong positive skewness for sales data, which means there were several very very high outliers. The data had no missing values, so I was not able to implement any of the techniques for handling missing data. However, if the data set had missing data, I would most likely just delete those rows, given that the dataset was already quite large. 

After calculating IQR and upper bound, I could see that there was over 10% of high outliers, which supports what I observed from the initial histogram. 

Regarding correlation analysis, it is not surprising, that Sales have the highest correlation with profit. 
