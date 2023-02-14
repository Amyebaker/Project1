# Drawing Conclusions: How Education Impacts Income Across the United States

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to explore the income impact on higher education in the United States. We will be gathering data from 2019 to 2021 for those with a higher degree: Associates and Bachelor degrees, as well as those with no formal higher education.


### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization

### Technologies
* Python
* Pandas
* jupyter
* matplotlib
* scipy
* plotly

## Project Questions Addressed
In this project we address these three main questions:
1. What is the correlation between education levels (higher education vs no higher education) and income?
2. What degree type (associates or bachelors) has the greatest impact on income?
3. Which US Region has the highest amount of people with higher education degrees and does this region also have the highest income?


## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

## Instructions
### Setting Up DataFrames

1. Prepare the data using the provided package dependency and data imports. Remove unncecessary columns from the costindex dataframe (You will only be keeping the "State" and "costIndex" columns from the costindex dataframe)
2. Invert the state dictionary and update the state column to show state abbreviations in place of the full state name
3. Merge the income and new_cost DataFrames into a single DataFrame. 
4. Using the merged dataframe calculate and display the "Adjusted Per Capita Personal Income 2021" by county and format properly. 
5. Remove unnecessary columns and rename reamining columns to display information: Per Capita Income 2021, Count of Associate Degrees, Count of Bachelor Degrees or Higher, Percent of Associate Degreesm Percent of Bachelor Degrees or Higher. Add a column to show: Percent of No College, Percent with Any College and Count of Any College Degree
6. Using the group by function, generate a summarary by state.

### Visualizing Data
1. Create a box and whisker plot using both Panda DataFrame.plot() and Matplotlib pyplot to show the Adjusted Per Capita Personal Income for 2021 by State.
2. Calculate quartiles, find outliers in the dataset and remove.

### College Vs. No College Analysis
1. Create scatter plot using matplotlib to show % of Any College Degree vs Adjusted per Capita Personal Income 2021. 






## Contributing Members

**Team Leads (Contacts) : Kudirat Abdulsalam, Amy Baker, Lexie (Alexis) Fallow, Aminah Qandeel, Caleb Stevens 
