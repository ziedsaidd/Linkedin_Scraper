# LinkedIn Scraper

This code permits the scraping of public linkedin profile informations for a given members names Entry and writes the found results in a given excel sheet.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Things you need to install to make the scraper working 

```
pip install selenium # it serves for the browser automation
pip install bs4 # it parses the html/lxml code of the wanted web page
pip install xlrd # to read from an excel workbook
pip install xlsxwriter # to write the output on an excel sheet 
pip install pandas # it makes the data manipulation easier and faster

```

### What about IP block ? 
LinkedIn scraping is a hot topic those days as Linkedin wants to own its users public data and prohebits external data-gathering prcecees. That's why they'reapplying IP tracking algorithms to catch scrapers. My advice to avoid any sort of IP block is to use selenium wisely with sleep time and ping variation. Also I would recommand the use of the 4G mobile data Hotspot as it attributes a new IP address to your PC everytime you connect to the network. 



