# DEMO_MISSION_TO_MARS



## Overview of the project

The purpose of this project is to create a Web Application that scrapes a various websites and display the data in an HTML page to show the results.
We will be adjusting the Web Application to include all four of the hemisphere images, using BeautifulSoup and Splinter to scrape the full-resolution images of Mars's Hemispheres and the titles of those images and then we will store the scraped data on a Mongo Database.

### Resources

#### Software

• Python 

• Jupyter Lab

• Pandas

• MongoDB

• HTML

• Flask-PyMongo, BeautifulSoup, Splinter

#### Data Source

• https://galaxyfacts-mars.com

• [movies_metadata](https://data-class-mars.s3.amazonaws.com/Mars/index.html)

• https://marshemispheres.com/

• https://spaceimages-mars.com

## Results

##### Mars_Facts

<img width="376" alt="Mars_Facts" src="https://user-images.githubusercontent.com/107282754/187098310-fc6f8bfc-d724-4968-bebd-da249a8ffaca.png">

##### Web Scraping Urls 

<img width="693" alt="hemispheres_urls" src="https://user-images.githubusercontent.com/107282754/187096877-15fd89fc-cd95-40de-bf42-3563d06896f9.png">

##### Web App before scraping

<img width="1135" alt="Screen Shot 2022-08-28 at 6 07 51 PM" src="https://user-images.githubusercontent.com/107282754/187098411-ea5cfe02-1676-4da2-b836-7d41355e9288.png">

##### Web App after scraping
After we have scraped the data, the webpage has the images in full resolution and the titles of the four hemispheres (see below).

<img width="589" alt="Screen Shot 2022-08-29 at 9 53 10 PM" src="https://user-images.githubusercontent.com/107282754/187338136-8f856163-4732-44a1-b2ee-a7bc07620ca2.png">
<img width="601" alt="Screen Shot 2022-08-29 at 9 53 23 PM" src="https://user-images.githubusercontent.com/107282754/187338182-a0482aea-3476-4c23-b1d6-b4cc954c8e4d.png">

<img width="1287" alt="Screen Shot 2022-08-29 at 9 43 09 PM" src="https://user-images.githubusercontent.com/107282754/187562324-9b59f37b-bb3d-4f92-8635-5bb59486821a.png">
<img width="835" alt="Screen Shot 2022-08-30 at 6 40 29 PM" src="https://user-images.githubusercontent.com/107282754/187562341-a27eabca-cb2e-4a49-aa09-59e8ceef4efc.png">

## Summary

A successful page that displays the data collected with high resolution images and titles of Mars Hemispheres was created. It is is mobile-responsive and we add Bootstraps 3 components to style the webpage creating a user-friendly scraping tool.
