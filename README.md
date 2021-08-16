# Mission-to-Mars
## Summary

Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Deliverable 1

[notebook](https://github.com/jzebker/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.ipynb)

• finds the full resolution image url from [USGS search results](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)

• saves the image url address ('img_url') and image name ('title') to a list of dictionaries as pictured below:
<p align='center'>
  <img src='https://user-images.githubusercontent.com/84994321/129502701-bf5d114a-8dc3-40df-9bc5-d2838468502a.png'>
</p>

## Deliverable 2
• function ***mission_to_mars_imgs(browser)*** retrieves the full-resolution image URL and title for each hemisphere image; ***scrape_all()*** has been updated to include this in the output data dictionary

[scraping.py](https://github.com/jzebker/Mission-to-Mars/blob/main/scraping.py)
<p align='center'>
  <img src="https://user-images.githubusercontent.com/84994321/129503284-6836a33e-ed12-476f-9f85-4751b5992c62.png">
</p>

• the attached [HTML template](https://github.com/jzebker/Mission-to-Mars/blob/main/templates/index.html) has also been updated (see picture below)
<p align = 'center'>
  <img src="https://raw.githubusercontent.com/jzebker/Mission-to-Mars/main/Readme_pics/d2hemisection.png">
</p>

• the web app contains all data after the scrape has been completed
<p align = 'center'>
  <img src="https://raw.githubusercontent.com/jzebker/Mission-to-Mars/main/Readme_pics/d2completesite.png">
</p>

## Deliverable 3

• now featuring mobile responsive output (works on phones!)
