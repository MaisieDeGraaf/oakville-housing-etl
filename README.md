# oakville-housing-etl

__________________________

## Description

The project talks about:

1. Comparative housing prices for Oakville to surrounding regions (Burlington, Milton, Vaughan, Oshawa)
2. Factors in the regions such as population, income, school districts, amenities.
3. Comparing sale changes and growth in all regions, and how they compare to Oakville.
4. Analysing in specifics the house prices and sales in Oakville by neighbourhood
5. Weather Data for Oakville that may affect market trends through the months.

The analysis we are going to do is:
1. Analyzing sale prices of housing within various regions comparable to Oakville.
2. Analyzing factors such as popularity of the city, income, schools, amenities, and other variables that may affect housing prices.
3. Create visualizations that help demonstrate factors that may be a stronger influence than others of housing prices in cities within the GTA.
4. Analyse specific areas of Oakville's housing trend by neighbourhood, house size, type, amenities and weather patterns that may affect this month by month.

The questions we are going to answer are:
1. What unique variables has set Oakville apart from the other cities nearby if at all?
2. What sort of factors increase or decrease the value of housing within the GTA?
3. What are the different economic states of each city based on household income, unemployment rate, and housing cost?
4. Which city displays the greatest growth (population, infrastructure, economic)?
5. Which cities offer the greatest housing opportunities?
6. Which city/cities is/are more appealing for families?
7. What areas of Oakville specifically are ideal for housing purchases?
8. What factors make specific neighbourhoods in Oakville ideal?
9. How does weather affect sale prices?

## Members of the group
1. Maisie DeGraaf ([@MaisieDeGraaf](https://github.com/MaisieDeGraaf))
2. Jaylene Hughes ([@jhyooz](https://github.com/jhyooz))
3. Pooja Niranjan ([@Pooja14n](https://github.com/Pooja14n))
4. Robert Skrepnek ([@RSkrep](https://github.com/RSkrep))
5. Peggy Tadi ([@peggz19](https://github.com/peggz19))


## Work breakdown structure
1. Maisie DeGraaf - Burlington Data Frame, HTML scraping, Oakville Weather, Database
2. Jaylene Hughes - Vaughan Data Frame
3. Pooja Niranjan - Oakville Data Frame
4. Robert Skrepnek - Milton Data Frame
5. Peggy Tadi - Oshawa Data Frame

## Datasets used:
1. Census Profile, 2016 Census
...
11. Oshawa, Whitby, Clarington, and GTA Property Tax Rates 2016
https://johnowen.realtor/blog.html/oshawa-whitby-clarington-and-gta-property-tax-rates-2016-4393669
John Owen, May 25, 2016
12. HouseSigma.com
13. [Historical Weather Data - Government of Canada Environment and Natural Resources](https://climate.weather.gc.ca/historical_data/search_historic_data_e.html)

## Code Snippets
![image](https://github.com/MaisieDeGraaf/oakville-housing-analysis/assets/144713762/bd556054-22a7-4172-8568-dff1b3b5c14c)
![image](https://github.com/MaisieDeGraaf/oakville-housing-analysis/assets/144713762/f7150cf1-1f5a-40f6-a7a3-4ab1525346c1)
![image](https://github.com/MaisieDeGraaf/oakville-housing-analysis/assets/144713762/661dc7dc-9769-45b3-9c45-78951eb05ae6)


## Limitations
1. Size of sample
2. Reliability of data
3. Available data
4. Data only since 2016
5. Incomplete 2023 data

## New Code - housesaledata Jupyter Notebook
The `housesaledata` Jupyter Notebook scrapes housing sale data from a specified website. To use this notebook, follow these steps:

1. Add your username and password to the `api_keys` file as `email` and `passw`, respectively. Make sure to add this file to your `.gitignore` to keep your credentials secure.

2. Set up an account on the website specified in the notebook.

3. Specify the watched areas on the website to scrape data from. These areas will be scraped into the database.

4. Run the notebook to execute the scraping process. The scraped data and the weather data will be saved into the database for further analysis.

