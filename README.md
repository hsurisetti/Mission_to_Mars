# MISSION TO MARS

## Overview :

 In this project, we are organizing , analyisng and visulaizing the information about the climate of Mars by performing web-scraping and data analysis.

 Resources :
  - Data Source : Mars News ,  Mars Temperature Data
  - Software : Python, JupyterNotebook
  - Libraries: BeautifulSoup, Splinter

## Analysis :

### Scrape Titles and Preview Text from Mars News 
   - Using Splinter, automated browsing has been established. Then the page has been inspected using ChromeDevTools and identified all the major elements present in Mars News.
   - Using BeautifulSoup all the News page has been parsed and all text elements have been extracted
   - The title and preview of each article are stored in as dictionary and collectively all these dictionaries have been added and stored as python list
   - Finally the mars data has been exported into json 

Json Output File : [mars_data.json](https://github.com/hsurisetti/Mission_to_Mars/blob/main/mars_data.json)

### Scrape and Analyze Mars Weather Data

   - First automated browsing has been established using splinter for the mars temperature data which is in form of html table
   - Next, BeautifulSoup has been used to scrape the data in the HTML table.
   - The scraped data has been assembled into Pandas DataFrame.

Mars DataFrame csv File : [mars_table.csv](https://github.com/hsurisetti/Mission_to_Mars/blob/main/mars_table.csv)
 
 Upon extracting Mars temperature table, the table has been used to analyse and visulaize the data by finding answers to the below questions.

* How many months exist on Mars? 

        12 months exist in Mars
        
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        
        1867 martian days exist in the scraped data
* What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
    
        The anlysis show that Mars is the coldest month and August being the warmest

* Find the average the minimum daily temperature for all of the months.
Plot the results as a bar chart.
      <img src="https://github.com/hsurisetti/Mission_to_Mars/blob/main/images/Avg_min_Temp_plot.png" width=400/>


* Average daily atmospheric pressure of all the months on Mars
Plot the results as a bar chart.

<img src="https://github.com/hsurisetti/Mission_to_Mars/blob/main/images/Avg_pressure_month.png" width=400/>


<img src="https://github.com/hsurisetti/Mission_to_Mars/blob/main/images/Avg_pressure_month_plot.png" width=400/>

* About how many terrestrial (Earth) days exist in a Martian year?

  <img src="https://github.com/hsurisetti/Mission_to_Mars/blob/main/images/EarthDays_in_Martian_year.png" width=400/>
  
  


