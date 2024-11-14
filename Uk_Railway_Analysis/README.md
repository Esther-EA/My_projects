# UK Rail System Analysis
## Background
The UK rail service providers are Network Rail and the Rail Delivery Group (RDG), which operates under the trading name National Rail. My role as a BI Developer involved analyzing this data, which included details on ticket types, travel dates and times, departure and arrival stations, ticket prices, and more.

The primary objective of the project was to develop an exploratory dashboard to evaluate passenger behavior and operational efficiency. This analysis aimed to uncover key insights and trends that could help National Rail Transport optimize their operations and improve overall performance.

## Project Objective
The primary goal was to identify trends, patterns, and insights within the UK National Rail transport system from January to April 2024 using comprehensive ticket sales data. By analyzing passenger behavior and operational performance, the study sought to provide actionable insights to support strategic decision-making, optimize pricing strategies, enhance operational efficiency, and improve customer satisfaction. The key business questions addressed were:

- Identifying the most popular routes to ensure adequate resource allocation.
- Determining peak travel times to manage capacity and reduce congestion.
- Analyzing revenue from different ticket types and classes to optimize pricing strategies.
- Assessing on-time performance and identifying contributing factors to minimize delays and cancellations.
  
## Exploratory Process
### Initial Analysis & Data Exploration with Excel

The dataset, covering ticket sales from January to April 2024, included various data points like ticket prices, departure and arrival stations, travel times, preferred ticket classes, ticket types, railcards, and purchasing methods.

- Excel was used for preliminary Exploratory Data Analysis (EDA). This phase involved sorting and filtering columns, removing duplicates, and correcting discrepancies such as spelling errors. It also included a detailed examination of train route frequencies and travel times.

### Data Cleaning with Power Query

The dataset was relatively clean, consisting of a single-table structure. An ETL process was conducted, importing the dataset in CSV format into Power Query. Headers were established, and column data types were properly defined. Null values were checked, and columns were inspected to understand the data attributes.

### Data Visualization with Power BI

Power BI was utilized to create an interactive and clear representation of the UK rail transport system's dynamics. A calendar table was created to extract years, months, and days from the dataset, linking it with the railway data in the data modeling tab.

Key achievements using Power BI included:

- Creating advanced visualizations such as bar and column charts, pie charts, area charts, and a flow map to showcase operational performance and passenger behavior. These visualizations helped identify high-demand routes, peak travel times, revenue by ticket type and class, and on-time performance with contributing factors.
- Adding interactive elements to enable dynamic data exploration, including month-based filtering.

With the aid of Power BI, the following were achieved:

- Advanced visualizations were made using column and bar charts, pie graphs, area charts, and a flow map to show the operating performance and passenger insights. This aided in the identification of high-demand routes and peak travel times, insights into revenue generation by ticket type and class, and an assessment of on-time performance along with its influencing factors.
- Interactive elements were incorporated to allow dynamic exploration of the data, such as filtering by month.
  
To present the insights, the following dashboards were created:

### Overview Dashboard: 
Provides a summary of National Rail Transport operations in the UK, including a flow map, key departure stations, and passenger behavior analysis.

### Trips Analysis Dashboard: 
Focuses on top rail routes, most active departure and arrival stations, peak travel times, and the status of trips (on-time, delayed, or canceled).

### Revenue Dashboard: 
Highlights revenue by route, highest-grossing routes, and insights into preferred ticket classes and types.

## Results & Insights
The analysis of the National Rail dataset revealed several key findings:

### Customer Preference:
Online ticket purchases were preferred, with 18,521 tickets bought online compared to 13,132 at station counters. Regarding payment methods, 60.46% of commuters used debit cards.

### Routes Analysis: 
The Manchester Piccadilly to Liverpool Lime Street route emerged as the most popular, with 4,338 trips. Manchester Piccadilly was the most frequented departure station, with 5,335 trips, a 332.43% increase compared to Bristol Temple Meads, which had only 16 trips.
### Peak Travel Times: 
There are two peak travel periods.

### Morning Peak (6 AM — 8 AM): 
A total of 7,497 trips, reflecting the time when most commuters travel to work.
### Evening Peak (4 PM — 6 PM): 
A total of 7,708 trips, aligning with commuters returning from work.
Peak travel periods generated significant revenue, with the morning peak contributing £275,397 and the evening peak contributing £155,733. The highest daily revenue occurred at 8 AM, amounting to £132,566.

### Revenue based on Routes, Ticket Class & Ticket Type: 
There were 29,773 successful trips during the period, generating a total revenue of £703,219.

- The London Kings Cross to York route was the highest revenue generator at £179,498, with other London routes following.
- Standard tickets produced £560,184 in revenue, 25.5% more than first-class tickets, which earned £143,035. Most commuters preferred Advance tickets across all classes.

### On-Time Performance & Factors: 
Out of 31,653 trips booked, 27,481 (92% of successful journeys) were on time. The remaining 4,172 trips experienced delays or cancellations—2,292 were delayed, and 1,880 were canceled.

### Delays & Cancellations: Contributing Factors: 
- The primary cause of delays was “Weather Conditions,” affecting 927 out of 2,292 delayed trips.
- “Signal Failure” was the leading cause of cancellations, accounting for 519 out of 1,880 cancellations.
  
Due to delays and cancellations, 1,118 refunds were requested (3.53% of total commuters), totaling £38,702. Refunds were requested for 546 delayed trips (23.8% of delayed trips) and 572 canceled trips (30.4% of canceled trips).

## Recommendations
- Resource Allocation for Popular Routes: Increase train frequency and capacity on high-demand routes like Manchester Piccadilly to Liverpool Lime Street.
- Optimize Peak Travel Schedules: Adjust schedules and allocate more staff during peak morning and evening travel periods to enhance passenger experience.
- Revise Pricing Strategies: Adjust ticket prices, particularly for the London Kings Cross to York route, to balance demand and maximize revenue.
- Minimize Delays & Cancellations: Invest in infrastructure and technology to reduce signal failures and enhance communication systems, particularly for managing weather-related disruptions.

## Conclusion
This comprehensive analysis, visualized through Power BI, provided crucial insights into the UK's rail transport system. Weekday rush hours and weekend afternoons emerged as peak travel times, guiding resource allocation. Revenue analysis highlighted the importance of premium services, particularly first-class and advance tickets. High-demand routes, such as those connecting major cities, require focused attention to ensure operational efficiency.

While the on-time performance was strong at 85%, there remains room for improvement, especially on long-distance routes and during adverse weather conditions. Passenger preferences favor advance tickets and convenient travel times, guiding marketing and service adjustments. These insights enable the UK National Rail to refine strategies, boost customer satisfaction, and foster future growth.





