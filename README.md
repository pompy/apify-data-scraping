# apify-data-scraping
Apify Scraping for new york state gov. This extracts real estate broker data (broker details like name, company, license no, address etc)
This crawls through all the detail pages and handles paging 

* Json you can import to apify it will set all the parameters. 
* Please install EditThisCookie plugin for google chrome 
* Please copy web cookie after opening the url https://appext20.dos.ny.gov/nydos/selSearchType.do#nbb & using the chrome plugin editthiscookie
* Specify initial cookie in advanced settings - (taken from editthiscookie)
* Do specify max pages per scroll depending on how many pages you want to crawl
* Start url can be something like this : https://appext20.dos.ny.gov/nydos/list.do?anchor=5d10ee.0#nbb (read from browser - everytime you crawl and change the cookies everytime)
* Psedo url can be https://appext20.dos.ny.gov/nydos/details.do?anchor=[.*]  with the name DETAIL
* Optional url is set as https://appext20.dos.ny.gov/nydos/list.do?anchor=[.*]
* After setting it appropriately run the crawl.
* If the structure of the source website changes this code wont work hence you are required to modify.


