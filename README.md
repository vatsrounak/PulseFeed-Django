## Website Live Link
https://news-aggregator-ku26.onrender.com/

</p>
<h1 align = 'center'>PulseFeed</h1>
<br>

<br>

[![](https://img.shields.io/badge/Made_with-Python3-blue?style=for-the-badge&logo=python)](https://www.python.org "Python3")[![](https://img.shields.io/badge/Made_with-Django-blue?style=for-the-badge&logo=django)](https://www.djangoproject.com/ "Django")

</p>

## Description

PulseFeed is a Django project to scrape a news website using Beautiful soup and request module and hence combination of web crawlers and web applications.
Both of these technologies have their implementation in Python.

## Features

Our PulseFeed works in 3 steps:<br>
1.It scrapes the news website for the articles.In this Django project, we are scraping a website 'www.theonion.com'<br>
(We have scraped news articles from 'latest' section of 'www.theonion.com' for demonstration)<br>
2.Then it stores the article’s images, links, and title.<br>
3.The stored objects in the database are served to the client. The client gets information in a nice template by clicking the 'Load news' button and select the different options available to you.The options are: Latest,Entertainment,Sports,Politics,Opinion,Breaking-News<br>

        ----------------------------------------------------------------------------------------
### Screenshots ###
## Latest
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/latest_light_mode.PNG)
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/latest_night_mode.PNG)
## Entertainment
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/entertainment_light_mode.PNG)
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/entertainment_night_mode.PNG)
## Sports
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/sports_light_mode.PNG)
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/sports_night_mode.PNG)
## Politics
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/politics_light_mode.PNG)
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/politics_night_mode.PNG)
## Breaking News
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/breaking_light_mode.PNG)
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/breaking_night_mode.PNG)
## Opinion News
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/opinion_light_mode.PNG
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/opinion_night_mode.PNG)
## Facebook share
![](https://github.com/sam-boghara/News-Aggregator/blob/master/screenshots/facebook_share.PNG)
## Whatsapp share
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/whatsapp_share.PNG)
## Telegram share
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/telegram_share.PNG)
## Copy to clipboard
![](https://github.com/vatsrounak/PulseFeed-Django/blob/main/screenshots/copy_to_clipboard.PNG)
---------------------------------------------------------------------------------------

## How To Use

#### Software Requirements

Python3

#### Installation

Download and install any virtual environment of your choice. (pipenv and conda are my personal favourites, either one of them can be used)
Activate the virtual environment

Install the dependencies by running:
```html  
    pip install -r requirements.txt

```

#### Run using Command Prompt

Navigate to the News-Aggregator folder which has manage.py file then run the following command on cmd

```html
python manage.py runserver
```

### Tech stack

`Backend` : Python3,Beautiful soup <br>
`Framework` : Django <br>
`Database` : Sqlite3 <br>
`Frontend` : Html,CSS,Bootstrap <br>
