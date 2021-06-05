# ScrapeTheGum
- Gumtree will ban you if you send alot of requests (while using the script). Make sure you use the proxies or use sleeper method in python to delay the request durations.
## Scraping used 5 seaters
Website : https://www.gumtree.com/cars/uk?vehicle_seats=5

### Scrape your own data
If you want to scrape your own data from gumtree,paste your baselink and sublink in these variables that are located inside the script

pages_base_link = 'baselink'

hyperlink ='extendedlink'

There are two json files in this case. However, when you run the script,it will save in one json file. The reason I have two json file is that, my runtime was interrupted so I had to rerun again from where it was interrupted and save the remaining data into another json file. But you don't have to worry about that
