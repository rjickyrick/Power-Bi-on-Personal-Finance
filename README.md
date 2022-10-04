# PERSONAL-FINANCE-DASHBOARD-FOR-EASY-LIFESTYLE

## Problem Description

In This Project, Main Problem Was That How To Save Money From Your Own Costly Expanses For Future Financial Goal ( For Easy Lifestyles ) ? answer : I have Tried To Solve Solution Of Financial Related Problem For Easy Lifestyles Through Power BI Tools.

## Overview of Microsoft Power BI

Microsoft Power BI is a data analytics tool used to provide business intelligence capabilities, including loading, modelling, and visualizing data sets. Its initial release was over 10 years ago in July 2011, and since then the Microsoft team has continued to add greater functionality and improve ease-of-use on a monthly basis. 

The program itself can be used both on a local machine (via Power BI "Desktop") and also on the cloud (via Power BI "Services"). It can be used in a similar fashion as how one may use Excel, but also provides the greater ability to more easily create interactive visualizations called 'dashboards'.

## Data Collection Methodology
![image](https://user-images.githubusercontent.com/86226834/152378800-ef565a2d-f735-4c26-a826-5e3a834b2655.png)

I collected this data by keeping all purchase receipts and inputting the data manually into Excel. The information I kept track of was: Date, Item Category, Price, Location, Comment.

In order to import this data into PowerBI, it was quite the process. Since the data was contained in *multiple Excel sheets in the same Excel workbook*, I first had to separate the sheets into their own Excel workbook - this turned out to be the easiest avenue to importing the data.

## Data Cleaning
![image](https://user-images.githubusercontent.com/86226834/152377748-13e6f986-8c1b-47d6-aa6f-dca41e0ddb5a.png)

There was quite a bit of data cleaning to do. I had to do some basic editing of the 'Item' category column, in order to have consistent categories. For example, I had 'hair cut', 'Hair cut', 'Hair-Cut' as separate categores, and so had to standardize this into simply a 'Hair Cut' category.

There was a lot of work needed to be done with dates. Some dates were of a 'Text' type, some were a 'General' type, and still others were the 'Date' type. These had to be standardized.

Finally, only a few rows contained null entries, so I simply chose to remove these rows from the overall dataset; This would not drastically affect the variance of the overall data.

## Measure Creation & Visualizations
![image](https://user-images.githubusercontent.com/86226834/152377856-eae9c962-840a-49ea-8f24-d55c862699b4.png)

  
The item lookup table contained a single column of each distinct Item category. While working through the project, I realized that every month had a rental payment listed. It didn't make sense to me to have this consistently in each month, so I created a filter that can be used to manually include or exclude rental payments. To accomplish this I needed a second column in the Item Lookup table to represent the 'Rent' item as a Boolean.
  
The location table contains a single column of each distinct location of purchase.

## Conclusion

Using PowerBI I was able to visualize my purchases data in an interactive way. This allowed me to drill deeper into my spending behaviour and with this information I can now be more conscientious of what I choose to spend my money on.
