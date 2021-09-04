# Mission to Mars
Module 10 Challenge

## Project Overview
The purpose of this project is to build a web application that will scrape the latest Mars news, images, and updates from several websites with the click of a button.  The retrieved data will be stored in a NoSQL database, and will then be presented in a HTML webpage.

The project has three deliverables:
- Scrape High-Resolution Mars Hemisphere Images and Titles
- Update the Web App with Mars Hemisphere Images and Titles
- Add Bootstrap 3 Components

## Software
- Python 3.8.8
- BeautifulSoup
- Splinter
- Flask-PyMongo
- html5lib
- lxml
- Webdriver-Manager

## Scraping Mars Data
By clicking the "Scrape New Data" button, the Mission to Mars HTML webpage will retrieve the latest facts, news, and images about Mars.  Information is gathered from the following websites: [NASA Mars News](https://redplanetscience.com/), [Jet Propulsion Laboratory's Space Images](https://spaceimages-mars.com/), [Galaxy Facts](https://galaxyfacts-mars.com/), and [Astropedia](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars). The scraping code used for this project can be found in the python document, [scraping.py](https://github.com/retroxsky06/Mission-to-Mars/blob/main/scraping.py).

Once the scraping code is developed, the app.py is run, which enables the extracted data to be stored in MongoDB.  In order for the codes to run properly, a mars_app database must exist to store the information.  
```
To verify that the mars_app database exists, run the following command in your terminal (make sure mongo environment is active):
> show dbs
```
#### Fig 1. mars_app database
![fig1](https://github.com/retroxsky06/Mission-to-Mars/blob/main/mongo_mars_app.png)

To view an example of the Mission to Mars HTML webpage, [click here](https://github.com/retroxsky06/Mission-to-Mars/blob/main/Mars_site.png)

## Updating Mission to Mars Webpage
To further customize the webpage, Bootstrap 3 components were added, such as modifying the Mars hemisphere images to be displayed horizontally when on a desktop, and bolding the font on the "Scrape New Data" button.  The codes used for the modifications are displayed below: 
```
<b> </b>
<div class="col-md-3" </div>
```
#### Fig 2. Mars Hemispheres displayed horizontally
![fig2](https://github.com/retroxsky06/Mission-to-Mars/blob/main/Mars_hemispheres.png)

### Mobile Responsive Webpage
As shown below, the Mission to Mars webpage is also optimized for mobile devices.

#### Fig 3. Webpage as displayed on an iPhone X
![fig3](https://github.com/retroxsky06/Mission-to-Mars/blob/main/Mobile_responsive.png)






