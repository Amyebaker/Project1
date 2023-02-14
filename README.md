# Drawing Conclusions: How Education Impacts Income Across the United States

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to explore the impact of higher education on income in the United States. We will be gathering data from 2019 to 2021 for those with a higher degree: Associates and Bachelor degrees, as well as those with no formal higher education.

### Methods Used
* Inferential Statistics
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

## Limitations
- After adjusting the per capita personal income, the outliers were eliminated which removed the state of Louisiana from our results. 
- We adjusted the income to match the cost of living per state, to provide better findings. We understand people can have multiple degrees. (Associates, Bachelors, and higher degrees).


## Instructions
### Setting Up DataFrames

1. Prepare the data using the provided package dependency and data imports. Remove unncecessary columns from the costindex dataframe (You will only be keeping the "State" and "costIndex" columns from the costindex dataframe)![$ Any College vs Adj Income](https://user-images.githubusercontent.com/119981413/218827348-ff0d310c-6d5b-4767-bd57-ec19fe46e5b7.png)

2. Invert the state dictionary and update the state column to show state abbreviations in place of the full state name
3. Merge the income and new_cost DataFrames into a single DataFrame. 
4. Using the merged dataframe calculate and display the "Adjusted Per Capita Personal Income 2021" by county and format properly. 
5. Remove unnecessary columns and rename reamining columns to display information: Per Capita Income 2021, Count of Associate Degrees, Count of Bachelor Degrees or Higher, Percent of Associate Degreesm Percent of Bachelor Degrees or Higher. Add a column to show: Percent of No College, Percent with Any College and Count of Any College Degree
6. Using the group by function, generate a summarary by state.

### Visualizing Data
1. Display a box and whisker plot using both Panda DataFrame.plot() and Matplotlib pyplot to show the Adjusted Per Capita Personal Income for 2021 (Adj Income) by State.
2. Calculate quartiles, find outliers in the dataset and remove.

![BoxPlot](https://user-images.githubusercontent.com/119981413/218827135-1495e781-4802-4272-9985-e4ef232ab1f5.png)


### College Vs. No College Analysis
1. Display a scatter plot using matplotlib to show % of Any College Degree vs Adjusted per Capita Personal Income 2021 (Adj Income.) 

![$ Any College vs Adj Income](https://user-images.githubusercontent.com/119981413/218827379-0ca5a80c-dc06-4306-b5d0-d5609678ad62.png)

2. Display a scatter plot using matplotlib to show % of no college degree vs Adjusted per Capita Personal Income 2021
![% No College vs Adj Income](https://user-images.githubusercontent.com/119981413/218827560-2a643f74-b0b2-4232-a361-b1f471e61912.png)

### College Degree Type Analysis
1. Display a scatter plot using matplotlib to show % Associate Degree vs Adj Income
![% Associates Degree vs Adj Income](https://user-images.githubusercontent.com/119981413/218827977-ee7a5ee4-2a7e-46b4-8b81-4c5758324b9b.png)

2. Display a scatter plot using matplotlib to show % Bachelors Degree or Higher vs Adj Income
![% Bachelor Degrees vs Adj Income](https://user-images.githubusercontent.com/119981413/218828195-0d1f814d-a589-46e0-a044-a4d3c720b336.png)

### Analysis by Region
1. Use the Pandas copy function to create a dataframe to store region data. Addiitonally create a column to store the region each state belongs to and add Regions to your dataframe.
2. Display a bar chart to show the Adjusted Per Capital Personal Income 2021 and Count of Any College Degree by Region

![Region Bar Chart](https://user-images.githubusercontent.com/119981413/218830422-db8a9f64-b7ed-4005-b06a-202f6f9fb9a1.png)


### Bonus - Creating a map of counties using API
1. Import requests, JSON and API Key.
2. Add additional empty columns for latitude and longitude & define the parameters for the search.
3. Call the API to find the latitude and longitude of each county 
4. Export API Results to CSV

### Analysis Location
Using all data gathered we were able to create an analysis located in the main branch under "Project 1 Analysis.docx" 
https://github.com/Amyebaker/Project1/blob/main/Project%201%20Analysis.docx

Additional Visuals can be found in https://github.com/Amyebaker/Project1/tree/main/Outputs


## Contributing Members

Kudirat Abdulsalam, Amy Baker, Lexie (Alexis) Fallow, Aminah Qandeel, Caleb Stevens 

## Data Sources
- Kaggle: Per Capita Income by County (2021) vs. Education (main data source)
  - U.S. Bureau of Economic Analysis
  - U.S. Department of Agriculture (USDA)

- World Population Review: Cost of Living Index by State

- Geoapify API Data

