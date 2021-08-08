# web-scraping-challenge
Written by Trent McNabb for Carleton University Data Analytics and Visualization Bootcamp
The code in this repository scrapes data from the Mars News Site https://redplanetscience.com/ to get the latest News Title and Paragraph text, as well as the feautured image and url to the image from https://spaceimages-mars.com and some facts about mars from https://galaxyfacts-mars.com and high resolution images of the Martian Hemispheres from https://marshemispheres.com. There is a flask app that has two routes (/scrape) runs the code, stores the results in MongoDB,  and (/) which displays the results that it pulls from MongoDB.
The repository contains:
README.md					a file that contains information about the repository
mission_to_mars.ipynb		a jupiter notebook that contains the code that scrapes the data