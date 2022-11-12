# Kickstarter Analysis
________________________________________

# Overview of the Project
### What Was Our Goal With This Dataset?
________________________________________

Louise initially came to us looking for help in gleaning insight from a Kickstarter dataset she had. We looked closely at outcomes of parent categories, outcomes based on goals, and provided some descriptive statistics of campaign funding goals.  

We were then asked to create a report to find out how different campaigns fared in relation to their launch dates and funding goals. Louise recently had a play of hers fall short of its funding goal, and she likely wants to know what she could be doing better for her next project.


# Analysis and Challenges
### How Did We Perform Our Analysis?
________________________________________

#### Outcomes By Month
Our first goal was to go about find information about outcomes based on their launch date. We achieved this using pivot tables and graphing to create visuals that were easy to follow.

We created a pivot table that would be the basis for our outcomes by launch date chart. We first made rows equal to the month of the year. Then we created a few columns filled with relevant data. We counted successful, failed, and canceled campaigns in separate columns. To tie it all together, we created a filter to change the year of the data and a filter to parent category of the campaign.

The two filters were arguably the most important part of our chart. The year gives us insight into yearly trends per category. The parent category lets us gauge performance broken down by month, and potentially allows us more avenues of analysis in the future.

**The result of this table is shown below:**

![](https://github.com/JosefMoore/kickstarter-analysis/blob/9fd92caf5e47cf7719cf188791daa05c75b237eb/Resources/Outcomes_vs_Goals.png)

#### Outcomes By Funding Goal Amount
Our second goal was to find out outcomes based on funding goal amounts. We created another pivot table with all rows being a range of funding amounts from 0 to greater than 50,000. In our columns we, again, counted the number of successful, failed, and canceled projects in relation to their funding goal. We achieved this using a COUNTIFS function to find data across worksheets. Lastly, we performed some simple math to find the percentage of successful and failed projects per funding range in the last two columns.

**The result of this table is shown below:**

![](https://github.com/JosefMoore/kickstarter-analysis/blob/9fd92caf5e47cf7719cf188791daa05c75b237eb/Resources/Theatre%20Outcomes%20Based%20On%20Launch%20Date.png)


## Results
________________________________________

#### What conclusions could we draw from outcomes by launch date for the theatre category?
We learned that the best month to launch a kickstarter for a theatre play was between April and mid-June with May being the best month by far to launch a project. Conversely, both the beginning and end of the year proved to be the worst times to launch campaigns with December being the worst by time of the year.

#### What conclusions could we draw from outcomes based on funding goals?
From our chart we learned that campaigns with a goal of $1000 or less had the highest success rate. We also learned that campaigns with a goal between $35,000 and $45,000 were moderately successful at 67%. Lastly, campaigns above a goal of $45,000 nearly had a 100% failure rate.

#### Limitations?
This dataset, while having a good volume of yearly data, is slightly outdated by nearly 6 years. Taste in theatre may change over time and having newer data would be crucial.

This analysis could've been improved with more visualizations based on category of play to analyze trends per category over time.
