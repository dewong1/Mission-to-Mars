# Mission-to-Mars
Automate a web browser to visit different websites to extract data about the Mission to Mars 

## Overview of Project

*Web scraping* is a method used by organizations worldwide to extract online data. We stored Mars data in a NoSQL database, and then rendered the data (*Mars news, image, facts, hemisphere*) in a web application created with Flask. Using *Splinter* to automate a web browser and *BeautifulSoup* to parse/extract the data, we created a *MongoDB* database to store data from the web scrape. Then we created a web application with *Flask* to display the data from the web scrape. Next, we created *HTML/CSS* portfolio to showcase projects. Last, we used *Bootstrap* components to polish and customize the portfolio. 

### Purpose and Background

The purpose of the project was to add additional Mars data information. In addition to the original web-scraped data (*Mars news, image, facts*), we want to include Mar's hemispheres (*four hemisphere images*). Using *Beautiful Soup* and *Splinter* to scrape full-resolution images of Mar's hemispheres and the titles of those images, we stored the scraped data on a *Mongo* database, used a web application to display the data, and altered the web app (mobile-responsive webpage & Bootstrap 3 components) to accommodate these images.


![after scraping data (webpage pictures)](https://user-images.githubusercontent.com/107021231/185365980-b3468232-25a2-41f6-a7c3-94a2c55d40da.png)
