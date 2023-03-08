# Bike Sharing Customer Insight Analysis

This project focused on the application of Python Pandas and Tableau, and how we leveraged their useful functions and GUIs for performing in-depth data analytics and visualizations.
[link-to-dashboard](https://public.tableau.com/views/Chris-city-bike-analysis/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

## Table of Contents

- [Overview and Objective of Project](#overview-and-Objective-of-project)
  - [Resources](#resources)
  - [Data Overview](#Data-overview)
  - [Technology](#Technology)
- [Experimental and Analysis Results](#experimental-and-analysis-results)
  - [Discovery1](#Discovery1)
  - [Discovery2](#Discovery2)
  - [Discovery3](#Discovery3)
- [Summary](#summary)
- [References](#references)

## Overview and Objective of Project

This project focused on cultivating knowledge and skills of data analytics and visualizations that helped to further understand the concepts of crafting convincing analysis report and bike sharing business proposal. During the completion of this project we mainly leveraged the powerful features offered by Python Pandas and [Tableau Public](https://www.tableau.com/products/public), a free platform that lets us explore, create, and publicly share data visualizations online.

### Resources

- Source data: [201908-citibike-tripdata](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
- Image file: png files
- Software: [Tableau Public](https://www.tableau.com/products/public), [Pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide).

### Challenge Overview

Below is the outline and a written report for presenting the results and analysis summary. Upon completion of this project, I created visualizations that showed the length of time that bikes were checked out for all riders and genders, the number of bike trips for all riders and genders for each hour of each day of the week, and the number of bike trips for each type of user and gender for each day of the week. I then compiled a final presentation that summarizes our analysis results and data visualizations for our stakeholders and potential investors.

### Technology
- Tableau 
- Python
- Jupyter Notebook
- Pandas
- CSV

## Experimental and Analysis Results

I first reformatted the original csv data by using Python Pandas and then used Tableau to perform in-depth analysis and visualizations. Although I retained all the initial field data when saving the modified DataFrame to a csv file, there were several unique approaches that I used when accomplishing the required visualizations as discussed and highlighted below. Some of the improvement ideas for future analysis were also analyzed and embodied in the Tableau visualization dashboard

### Discovery 1
This is the starting location of the bike rental trips. The size represents the number of trips were started at that station location. The orange colors represent the trips happened during daytime likewise blue represents nigh time trips. Based on this distribution, most trips started from low-mid Mahattan area and slowly reduces further to north Mahattan and east of river. 
Next step: The company shall optimize the bike availability in mid Mahattan especially 20-40th stress with larger bubbles in oranage during daytime. The bike supply should be optimized in 10-20th and 40-50th streets during evening as there are more larger blue bubbles in the region.
<img src="https://github.com/chris820629/bikesharing/blob/main/Images/Image_10.png" width="500" height='300'>  

### Discovery 2
Most common hours are 7/8am and 5/6pm on weekdays. Weekend usage is more evenly distributed throughout 10am to 5pm. Thurs and Fri occasionally have customers between 1 and 5pm as well. It also shows that males are the majority of customer.\
Next step: since weekend all day and weekday day time are the least usage time, we could add promotion to incentivice customers or conduct a survery to understand customers' bike usage ghabit.                                                                                  
<img src="https://github.com/chris820629/bikesharing/blob/main/Images/Image_4.png" width="500" height='300'>   

### Discovery 3
Male subscriber is the dominent customer base.\
Next step: The business team can focus effort on acquring more subscriber customers like subscription discount coupons. A focus group study can also be conducted to further understand why customers without subscription tend to have less trips taken. Another study could be understanding the total trip duration per user between subscriber vs. non-subscribers since the ultimate metric is optizimie revenue per customer.                                      
<img src="https://github.com/chris820629/bikesharing/blob/main/Images/Image_5.png" width="200" height='200'> 

### Discovery 4
Most rides are around 10 minutes, showing users may be using them as secondary transportation from office to metro stations. Further investigation could focus on the customer id on their start and end destionations for customer behavior study.  
<img src="https://github.com/chris820629/bikesharing/blob/main/Images/Image_1.png" width="500" height='300'>  

### Discovery 5
Male are the most frequent users, being almost 4x of the female users.  
<img src="https://github.com/chris820629/bikesharing/blob/main/Images/Image_2.png" width="500" height='300'> 


## References

[Pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide)  
[Tableau Public](https://public.tableau.com/app/profile/chris.horng/viz/Chris-city-bike-analysis/Story1?publish=yes)   




 
