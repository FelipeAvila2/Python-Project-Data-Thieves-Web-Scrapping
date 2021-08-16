# Project Data Thieves Web Scrapping

This is a collaborative project from students of the Ironhack Data Analytics Bootcamp:

Felipe: https://www.linkedin.com/in/felipedeavilagranja/

Guilherme: https://www.linkedin.com/in/guilherme-torres-pereira/

Joanita: https://www.linkedin.com/in/joanita-duarte-mateus/


## Brief Wiki Descrpition

Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. The web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser. While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler. It is a form of copying in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet, for later retrieval or analysis.

## Overview

The Data Thieves project consist in harvesting data from various websites to build a product. The product that was build in this project was a price comparing across supermarkets. The target for our project was baby products. We know that being a parent is hard. Between changing diapers and waking up at 4 AM somebody needs to go shopping for baby products. And preferably we want the best prices. So, for that, what you would usually do is look-up websites for the lowest prices. Our automatization does that for you, and also ranks the best prices that it found.

## DISCLAIMER!

This project was done for Lisbon/Portuguese users. The language in the app is portuguese.

## How to use the product

1. Either fork or clone the repository.
2. Download the requirements that are expressed at: Project-Data-Thieves-Web-Scrapping/requirements.txt.txt
3. Open the notebook: Project-Data-Thieves-Web-Scrapping/project final.ipynb
4. Run the code, including the final cell that has the engine: execute()
5. Insert name of the product that you look for
6. If you want to do a new search digit "Sim" and then you are able to insert a new product.


## Web-Scrapping

The web-scrapping was done with HTML scrapping of supermarkets, with the help of the BS4 package.

The supermarkets scrapped where: Lidl, Continente and Auchan

This is a example of a scrapping function used:
![image](https://user-images.githubusercontent.com/83870535/129603612-2ba69791-a4a0-4c42-8928-cdae44410f70.png)


## Product

The product searches the best prices for baby products. The user interface is really raw and needs much improvements. Ideally you would have a Flask app to do your searches.
But for now, the product consist on this table, for example when you search for "Banana":
![image](https://user-images.githubusercontent.com/83870535/129603833-fd898c12-fa03-428c-b3f5-6c1c8c750c81.png)

