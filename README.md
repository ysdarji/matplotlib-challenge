# Pymaceuticals - The Power of Plots
![Drugs](https://geomarketing.com/wp-content/uploads/2016/12/How-Pharma-Brands-Are-Using-Location-To-Target-Consumers.jpg)
## Challenge Instructions
This project utilizes Python Matplotlib to generate tables and figures from an animal study carried by Pymaceuticals Inc., in order to screen for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. In addition, a top-level summary of the study results was generated.

## Tasks
- Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID. Use the cleaned data for the remaining steps
- Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen
<p align="center">
  <img src="https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Summary_Table.png">
</p>

- Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of total data points for each treatment regimen throughout the course of the study \
![Total_Data_Points](https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Total_Data_Points.png)
- Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study \
![Distribution](https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Distribution.png)
- Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens
- Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style \
![Final_Tumor_Volume](https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Final_Tumor_Volume.png)
- Select a mouse (g316) that was treated with Capomulin and generate a line plot of time point versus tumor volume for that mouse \
![Capomulin_g316](https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Capomulin_g316.png)
- Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen \
![Weight_Tumor](https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Weight_Tumor.png)
- Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot \
![Linear_Regression](https://github.com/Jiuhe2020/matplotlib-challenge/blob/master/images/Linear_Regression.png)
- Include three observations or inferences based on previously generated figures and tables at the top of notebook

## List of Content
1. Pymaceuticals.ipynb: a Jupyter Notebook containing the main script
2. Mouse_metadata.csv: the resource of mouse information
3. Study_results.csv: the resource of study results

---
### Copyright
Jiuhe Zhu © 2020. All Rights Reserved.
