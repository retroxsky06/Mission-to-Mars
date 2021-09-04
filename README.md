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
By clicking the "Scrape New Data" button, the Mission to Mars HTML webpage will retrieve the latest facts, news, and images about Mars.  Information is gathered from the following websites: NASA Mars News, Jet Propulsion Laboratory's Space Images, Galaxy Facts, and Astropedia. The scraping code used for this project can be found in the python document, scraping.py.

To view an example of the Mission to Mars HTML webpage, [click here](https://github.com/retroxsky06/Mission-to-Mars/blob/main/Mars_site.png)

## Updating Mission to Mars Webpage
To further customize the webpage, Bootstrap 3 components were added, such as modifying the Mars hemisphere images to be displayed horizontally when on a desktop, and bolding the font on the "Scrape New Data" button.  The codes used for the modifications are displayed below: 
```
<b> </b>
<div class="col-md-3" </div>
```
#### Figure 1. Mars Hemispheres displayed horizontally
![fig2](https://github.com/retroxsky06/Mission-to-Mars/blob/main/Mars_hemispheres.png)

```
To verify that the mars_app database exists, run the following command in your terminal (mongo environment active):
> show dbs
```

### Mobile Responsive Web Application
As shown below, the Mission to Mars webpage is also optimized for mobile devices.



![fig2](https://github.com/retroxsky06/Mission-to-Mars/blob/main/Mars_hemispheres.png)





