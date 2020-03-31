# vgchartzfull - A crawler to download data from Global Videogame Sales

vgchartzfull.py is a python@3 script based on BeautifulSoup.

It creates a dataset with data from more than 57,000 games. based on data from  http://www.vgchartz.com/gamedb/ 

## Output

The dataset is saved as vgsales.csv.

## Install & execution

You will need to have some depencies compiled at **requirements.txt**.

It can be installed by pip.

```bash

  # Install dependencies
  $> pip install -r requirements.txt
  
  # Run
  $> python vgchartzfull.py
  

```

## Dictionary

| Field | Description              |
|-------|--------------------------|
| Rank  | Ranking of overall sales |
| Name | The games name |
| Platform | Platform of the games release (i.e. PC,PS4, etc.) |
| Year | Year of the game's release |
| Genre | Genre of the game |
| Publisher | Publisher of the game |
| NA_Sales | Sales in North America (in millions) |
| EU_Sales | Sales in Europe (in millions) |
| JP_Sales | Sales in Japan (in millions) |
| Other_Sales | Sales in the rest of the world (in millions) |
| Global_Sales | Total worldwide sales. |


## Links

* [vgchartz.com](https://www.vgchartz.com)
* [Original Crawler](https://github.com/GregorUT/vgchartzScrape)
* [Kaggle Dataset](https://www.kaggle.com/gregorut/videogamesales)

## Greetings

Thanks to [Chris Albon](http://chrisalbon.com/python/beautiful_soup_scrape_table.html) 
