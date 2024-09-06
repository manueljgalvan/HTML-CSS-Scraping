# HTML-CSS-Scraping

#### Requirements
Part 1: Scrape Titles and Preview Text from Mars News (40 points)
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)

The titles and preview text of the news articles were scraped and extracted. (20 points)

The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)

Part 2: Scrape and Analyze Mars Weather Data (60 points)
The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)

The data was analyzed to answer the following questions: (10 points)

How many months exist on Mars? (5 points)
How many Martian days' worth of data are there? (5 points)
The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)

Which month, on average, has the lowest temperature? The highest? (10 points)
Which month, on average, has the lowest atmospheric pressure? The highest? (10 points)
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)
The DataFrame was exported into a CSV file. (5 points)

### Analyze the Data

Analyze your dataset by using Pandas functions to answer the following questions:

1. How many months exist on Mars?
#### 12

2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
#### 1867

3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
#### Minimum Temperature
#### Month 8 (Aug) had the hottest average temperature of -68.38297872340425
#### Month 3 (March) had the coldest average temperature of -83.30729166666667

4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
#### Atmospheric Pressure
#### The month with the lowest average pressure is: 6 (June) with 745.05 mmHg
#### The month with the highest average pressure is: 9 (Sept) with 913.31 mmHg

5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
#### Year Length
#### Based on Approximate number of sols in a Martian year via Google = 687  
#### There are approximately 705.55 terrestrial days in a Martian year.
