# webscraping-challenge

## Scape Titles and Preview Text from Mars News
1. Used automated browsing to visit the Mars news site; utilized the Chrome DevTools to identify which elements to scrape.

2. Extracted the text elements fromt the website using the Beautiful Soup object.

3. Stored the title-and-preview elements in a Python dictionary and subsequently into a Python list.

4. Exported the scraped data to a JSON file.

## Scrape and Analyze Mars Weather Data
1. Used automated browsing to visit the Mars Temperature Data site at https://static.bc-edx.com/data/web/mars_facts/temperature.html; utilized the Chrome DevTools to identify which elements to scrape.

2. Extracted the text elements fromt the website using the Beautiful Soup object.

3. Created a Pandas DataFrame using the scraped data to include the columns `id`, `terrestrial_ddate`, `sol` `ls`, `month`, `min_temp`, and `pressure`.

4. Examined the data types of the columns and converted them to the appropriate datetime, int, or float data types. 

5. Performed an analysis of the dataset using Pandas funtions including:
    * How many moths exist on Mars
    * How many Martian days worth of data exist in the dataset
    * The coldest and warmest months on Mars
    * The Mars months witht eh lowest and highest atmospheric pressure
    * How many terrestrial (Earth) days exist in a Martian year.

6. Exported the DataFrame to a CSV file.

