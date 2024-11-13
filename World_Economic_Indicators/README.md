# WORLD ECONOMIC INDICATOR ANALYSIS
## Background
The World Bank supports infrastructure projects in developing countries and publishes an annual report on economic indicators as part of its mission. They have shared a dataset covering key economic and development indicators from 1960 to 2018, including metrics like electricity consumption, GDP per capita, life expectancy, birth rate, and more.

To enhance this dataset, the United Nations (UN) has provided Human Development Index (HDI) data, which includes additional indicators to monitor development, environmental impact, and inequality for each country from 1990 to 2021.

With this comprehensive data, I conducted an in-depth analysis of various economic indicators across different countries and timeframes.

## Project Objective
The primary goal of this project was to carry out a comprehensive analysis of each country’s data, focusing on crucial economic indicators such as GDP growth, population, life expectancy, income, unemployment rates, and more.

I aimed to examine how these indicators have evolved over time and how they differ across countries. My objective was to analyze these economic metrics to identify key trends and patterns that could guide policy-making and investment decisions. Furthermore, I sought to uncover relationships between various indicators and explore the potential factors influencing these connections.

For this project, various insights would be generated to understand the world performance of various countries but the recommended analysis involved:
- Identifying which countries have experienced the highest growth in population and GDP? Is there overlap?
  
- Which regions saw the most growth in HDI in the 21st century?

- Which factors are highly correlated with life expectancy?

- Which factors differentiate “High Income” vs “Low Income” Countries?

- The Process

## Data Exploration with Excel
To begin, initial analysis and exploration of the dataset provided by World Bank was done using Excel. This main purpose of using Excel was to find early trends and patterns in the data, this phase entailed:

- Filtering and sorting all the columns in the World Bank dataset and HDI dataset,
- Data cleaning to eliminate duplicates, ensuring all columns are properly categorized and removing discrepancies such as spelling errors.
- Data Cleaning with Power Query
- After the data cleaning with Excel, an Extract, Transform and Load (ETL) Process was carried out on the datasets. The ETL process involves, extracting and importing the datasets (All in CSV format) into Power Query where each table will be cleaned and sorted.

## World Bank Dataset

In the World Bank dataset, I started by standardizing the headers and verifying the data types of each column. This involved promoting the first rows to headers for consistency and converting the year column to a date format. I then checked for any null values and examined all columns to gain a clear understanding of the data structure, values, and attributes assigned to each field.

## Replace Values

I updated the "High Income" category in the income group by renaming and dividing it into two distinct categories: "Upper High Income" and "Lower High Income." This allowed for a more nuanced classification within the high-income bracket.

## HDI Dataset

The HDI dataset was extensive, featuring 207 rows and 1,008 columns. It included detailed information such as the HDI Index and Rankings, male and female life expectancy, gender development and inequality, average and expected years of schooling, maternal mortality rate, and much more.

## Unpivot Columns

For this project, I identified the key columns necessary for the analysis and applied the unpivot columns function. This allowed me to extract each relevant column from the HDI dataset one by one, creating individual tables for deeper analysis.

After unpivoting, the year data was in a text format. The unpivot function was particularly effective for grouping the years, enabling me to convert the year column into a date format. To achieve this, I used the “Extract — Text After Delimiter” function to remove any text preceding the year, leaving only the numeric date values. This made it easy to convert the data type to a proper date format.
## Advanced Visualization with Power BI

After the cleaning was done on Power Query, I selected the “Close & Apply” function which then loads all the data tables into Power BI ready for visualization.

Microsoft Power BI was the primary visualization tool for this project. Its main purpose was to create interactive visuals that effectively communicated insights and provided a clear overview.

To ensure seamless integration of all datasets, I performed data modeling, linking the tables together using the correct relationship key—Country Code.

### With the aid of Power BI, the following were achieved:

- Advanced visualizations were created to highlight key trends and patterns in the economic indicators. These included growth trends in GDP and population, gender comparisons, time-series analysis showing changes in life expectancy, and correlations between income groups and factors such as region, power consumption, internet usage, and more.

- Interactive features like "Drill Through" and "Slicer" were incorporated to enable dynamic exploration of the data, such as filtering by region.

- To present the insights, multiple dashboards were designed, offering a comprehensive and user-friendly way to view and interact with the data.

## Analysis & Insight
After conducting an exploratory analysis of the World Bank dataset several key insights were uncovered:

### GDP & Population Evolution:
The general population density, measured as people per square kilometer of land area, showed a steady increase over the years, reaching its peak in 2017. In terms of GDP per capita, there was a significant surge between 2001 and 2007, with a growth rate of over 89.1%. The highest point for GDP per capita occurred in 2014, totaling $3,573,608.72.

Europe and Central Asia emerged as the most dominant region, with a GDP per capita of $42,015,530.39 and a population density of 1,175,142.90. On the other hand, South Asia recorded the lowest values in both population density and GDP.
### Life Expectancy Trends:
Over the years, the average life expectancy has steadily increased, with 2019 marking the highest noticeable average at 72.4 years. Female life expectancy was slightly higher than that of males, with the male average at 68.59 years and the female average at 71.09 years.
### Human Development Index: 
South Asia experienced the highest growth in HDI during the 21st century, with a remarkable 42.37% increase, followed by Sub-Saharan Africa, which had a growth rate of 34.36%. In terms of overall HDI values, North America had the highest rating at 0.90, while Sub-Saharan Africa recorded the lowest at 0.48. Switzerland was ranked as the top country in terms of HDI.
### Income Groups: 
Most countries were categorized in the middle-income region, with nearly half (101 countries) falling into this group. The unemployment rate impacted most regions, but it was most pronounced in Europe & Central Asia, where the rate reached 10%.

A large population of 2,865,306 people fell under the lower high-income group, which also generated the highest GDP per capita at $34,669,944.42.

The analysis also identified potential areas for improvement and growth, such as countries with significant growth in population and GDP, which could present opportunities for investment.

### Quantifiable results include:

- The average life expectancy increased by 12% from 1960 to 2018.
- GDP per capita globally grew by approximately 184% from 1960 to 2018.
- The Human Development Index (HDI) experienced an average increase of 22% from 1990 to 2021.

## Conclusion
In conclusion, the analysis of key economic indicators from the World Bank dataset provides valuable insights into global economic health and development. The correlation between GDP and life expectancy illustrates how economic prosperity influences quality of life. Population trends, combined with income data, highlight regional disparities and growth patterns.

Moreover, the Human Development Index (HDI) emphasizes the complex nature of progress by integrating economic performance with social well-being. This comprehensive visualization not only clarifies the current state of global economies but also supports the forecasting of future trends and the development of targeted policies for sustainable growth.
