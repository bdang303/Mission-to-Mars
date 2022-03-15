# Mission-to-Mars
Web Scraping methods with data extraction tools

## Overview of Project
This project utilizes various web scraping methods to extract data from sources. In addition to identifying the appropriate HTML components of the data/images that we intented to be scraped, we were able to use BeautifulSoup & Splinter to automatically scrape the necessary components. Once the data was scraped, the components were then stored in a MongoDB database. Flask was then used to create & update the web page to display the data elements, tables, as well as images that have been scraped and extracted. 

## Deliverables
- 1) Scraping full resolution jpeg images & titles from a source
- 2) Updating a Web App to scrape new data as display new images along with their titles
- 3) Utilize Bootstrap 3 components to customize and add textures, features to clean up the Web App

### Code Sample

- Below captures a sample of the code utilized to execute this task. After all dependencies were imported, the scraping python script consisted of functions & for loops that extracted various data elements and stored them in a dictionary

![Sample Scraping Script](https://github.com/bdang303/Mission-to-Mars/blob/main/Resources/MissionMarsCode.png)

### Web App Sample

![Mission to Mars Web App](https://github.com/bdang303/Mission-to-Mars/blob/main/Resources/WebAppSample.png)


