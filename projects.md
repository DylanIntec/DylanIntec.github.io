---
youtubeId: cW0H2eTIYWA
layout: landing
---



# Coding Projects

## My Journey
An interactive scrollytelling experience that follows my journey from growing up in Tasmania to studying at the Australian Maritime College. Using modern web technologies to create an immersive story with maps and animations.

Without the help of Cusor this would have taken many more hours to create.

[View My Journey](my-story.html)

![alt text](images/mystory/cover.JPEG)

## Write OrcaFlex Code with Codex

### Overview

Codex is a language model created by Open AI that translates natural language into code. It was trained on over 175 billion words scraped from the internet and code from Github. The model does not have any pre existing knowledge of the OcraFlex API as it was not in the training data. I showed the model examples of how to write OrcaFlex code and then replicated some code which I had written for extracting wave elevation, velocity and acceleration. The results were very impressive.

<p align="center"><iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:6893885192474378241" height="698" width="504" frameborder="0" allowfullscreen="" title="Embedded post"></iframe></p>

## OrcaFlex in AR

### Overview
I created a simulation of a yacht on anchor while in shifty winds. I then used Python to extract the simulation data and animate the simulation in Blender. Exporting the simulation to a .usdz file to be viewed on a phone in AR.

<p align="center"><iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:6804001832822812672" height="622" width="504" frameborder="0" allowfullscreen="" title="Embedded post"></iframe></p>

## Adventure Dashboard Web App
![alt text](images/adventure.png)

#### Overview

Adventure Outside is a website that collates location of all the outdoor activities in Australia. This allows for easy adventure planning packing the most into a weekend ensuring you don't miss a spot. 

#### Backend

The website is a multipage Dash App. Dash was created by Plotly to easily create interactive graphing apps in Python without having to write any Java Script. Heroku makes it easy to deploy the app once the dependencies are specified.

#### Data 

The locations, brief details and url link to comprehensive information where web-scraped off the main activity websites. The web-scraping was done in Python using a combination of Requests, Beautiful Soup and Selenium. GPS coordinates were either web-scraped or using Googles Geolocation API.

The Website is now offline as Heroku is no longer free.

## Facebook Data Mining


Everybody is now well aware that Facebook collects your data for personalised ads but how much data do the really collect and store? Thanks to General Data Protection Regulation (GDPR) laws in Europe, it is now easy to download and sift through this data. 

[Facebook instructions here](https://www.facebook.com/help/1701730696756992)

[Google instructions here](https://support.google.com/accounts/answer/3024190?hl=en)

There is a lot of data here, 2.6gb from Facebook. I made a Dash app to visualise data I found interesting.

## Learning Python for Data Science

![logo](images/python.png)

Here is a collection of Jupyter Notebooks I have compiled/created for learning Python for Data Science. I taught this to the graduates at Worley in person. The notebooks are hosted on Binder making them fully interactive without the hassle of installing Python and setting up an environment.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DylanIntec/PyDataSci/HEAD){:target="_blank"}

## Optical Character Recognition
![alt text](images/age.png)

Optical Character Recognition (ORC) can be used when automating a process that requires reading text. This example uses Tesseract, an Open Sourced program by Google, to perform OCR. Image processing is done using OpenCV. Google provides APIs such as Google Image to perform OCR. This has the advantage of being scalable but has a cost per request.

[Show me the notebook...](2020-10-02-or.html)

[Download the notebook...](2020-10-02-or.ipynb)
## Web Scraping with Python

![alt](images/webscrap.png)

Web scraping is an essential tool for any data analysis project. The Crag is a platform for logging and detailing rock climbing areas and routes. The Crag's well structured data makes it a great candidate for web scraping.

[Show me the notebook...](2020-02-11-thecrag.html)

[Download the notebook...](notebooks/TheCragAPI.ipynb)

## AR Business Cards

![alt](images/arbc.gif)

Business cards spiced up with some AR. The AR model was built using Apple's Reality Creator and is hosted on this website (Github). The QR code links to this website for easy access. The AR animation has image recognition built into it so it tracks the business card.

[Link to the model...](2021-02-05-mm-bc.html)

