scrapers
========

A collection of scraper scripts and their outputs.

Description of their i/o below. 

## Airbnb Scraper

Returns a csv file with:

- listing name (str)
- price (int)
- room type (str)
- reviews (int)
- location (str)

when given the 'clean' url of the result of an airbnb search by city.

i.e. remove from the '?' onwards in the url; e.g: 

-Good: "https://www.airbnb.com/s/C%C3%B3rdoba--Spain" 
-Bad: "https://www.airbnb.com/s/C%C3%B3rdoba--Spain?guests=2&source=bb"