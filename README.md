# Final-Project-Restaurant Scope Analysis

## Project/Goals
Analyze data about restaurants in major cities of Canada providing insights to an investor in food industry before opening a new restaurant.
## Process
As per the project objectives I have accessed data from multiple API's, Cleaned and Transformed it using Pandas Python Library, Loaded database using python to SQLite3-VSCode, performed EDA using matplotlib and seaborn, including using both statistics and visualizations,identified trends and patterns in data using statistical models and interpreted the results using Tableau. Please find the documents and more details below:

### 1.Data Collection 
- Collect data from multiple API's to have a comprehensive dataset to observe a trend. Here data was fetched from ‘Yelp’ using python  
  /notebooks directory contains all the Jupyter notebooks with code for data collection in each city.
### 2.Data Cleaning
<a href="./notebooks/Data_cleaning.ipynb" > Data Cleaning Notebook </a>
- Identify and handle missing values in columns. You can fill missing values using the mean, median, or mode of the column or drop rows/columns with missing values based on the context.
- Check for and remove duplicate rows from the dataset. Duplicates can skew analysis results.
- Ensure that columns have the correct data types.
- Convert categorical variables into numerical values using techniques like one-hot encoding or label encoding.
- Store relevant information in Dataframes and convert into csv's for further analysis.

### 3.Data visualization for EDA using matplotlib and seaborn
<a href="./notebooks/EDA.ipynb" > EDA Notebook </a>
- Combine data from datasets created previously and observe trends.

### 4.Data visualization and Dashboard using Tableau
<a href="./Tableau Workbook/Final_Project_LHL1109.twbx" > Tableau Dashboard </a>
- Create plots to understand the data, discovering patterns and spotting anomalies.
- I used Seaborn Python data visualization library based on Matplotlib as it provides a high-level interface for creating attractive and informative statistical graphics.

### 5. Create database in SQLite3 using VSCode 


## Results
<a href="./Presentation/Restaurant Scope Analysis.pdf" > Final Presentation </a>
- Toronto and Vancouver has the most popular restaurants based on reviews and rating.
- Alexander’s Steakhouse is the most Popular restaurant in Canada with more than 4000 reviews and top rating.
- In total ‘Pizza outlet’ count is highest in Canada following Sushi bars.
- Top categories in Toronto are Italian, Japanese and Chinese
- Majority of restaurants are in ‘Affordable Category’

## Conclusion:
If you want to open a restaurant in Canada, Toronto and Vancouver will be favorable cities. Pizza outlet with American cuisine type is safe venture to start with. One can start with a food truck or setting up stalls at public events can also help to understand customer response.


## Challenges 
- Tableau automatically does certain aggregations which are not required
- It is a bit difficult to connect each viz and create meaningful interpretation
- Data needs to be formatted for each column
- Tooltip needs to be updated carefully so that it shows correct data with understandable names

## Future Goals
It was high level analysis about all major cities in Canada, to completely understand the dynamics to establish a successful restaurant one would need deep analysis about each city, its population, economy, diversity , etc. This would be my future goal to dive deep about one city and further analyze other aspects of a city.
