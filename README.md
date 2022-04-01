# COVID-19-interactive-map
An interactive map showing the evolution of number of COVID-19 cases in Africa

Realization : Noble Adounkpe - Peniel Adounkpe - Abed Adounkpe

This work was done the 10/24/2020 and translated from French to English for publication on GitHub the 07/25/2021.

# PRESENTATION OF THE CIVOCA PROJECT
Note: This document is the framework document for the realization of the innovative technological project CIVOCA submitted to the competition ''Riposte Covid-19'' of the Water, Hygiene and Sanitation Program (ProSEHA/GIZ) launched in partnership with EAU AFRIQUE. 
This project was submitted in the technology category concerning the invention of an innovative product, process or service in the fight against the spread of the Covid-19 epidemic. 

## CIVOCA: What is it about?
CIVOCA stands for "Carte Interactive de l’éVOlution du Covid-19 en Afrique" translated as Interactive Map of Covid-19 Evolution in Africa. It is an interactive map that allows you to plot the progress of Covid-19 in Africa.

## Why an interactive map?
The idea of an interactive map was born from the problem of access to detailed and geolocalized information on the spread of Covid-19 in Benin. The main objective is to combine cartography and computer science, and to make this information accessible to the public through the map.

If Covid-19 is called a pandemic, it is because it has transcended the borders of China to gradually spread to all countries of the world. Benin has not been spared. A first case was declared on March 16, 2020, and more than a hundred cases will follow, proof that the disease is gaining ground. As of this writing, Benin has 2,478 confirmed cases, compared to South Africa, the African country most affected by Covid-19, which recently reached the 500,000 confirmed case mark. 

In essence, CIVOCA is attempting to establish a visual timeline of the pandemic in Africa.

## CIVOCA Design Process
The development of CIVOCA involved accessing, analyzing, processing, and exploiting country boundary data and Covid-19 case count statistics at the continental scale. Once processed, these data were then integrated into the map design, all using Python programming software.

Google Colaboratory and Jupyter Notebook were used as the programming interface for the Python 3 language for this project. We also used Covid-19 count data and territorial boundary data from Johns Hopkins University and ArcGIS countries respectively. The libraries used in Python are as follows:
- numpy, to compute the logarithm of the Covid-19 infected population;
- pandas, to manipulate the file of Covid-19 cases in the world;
- geopandas, to manipulate the shapefile of countries in the world;
- folium, to visualize the data through an interactive map and
- branca.colormap, to set the colors on the map.

To do this, we first extracted the Africa data from the rest of the world data. Next, we combined the geography data with the Covid-19 case data using the country names as a common column. Finally, we set up the interactive map and saved it in HTML format to make our map accessible on phones, computers, and other electronic devices.

## Description of CIVOCA 
Our interactive map is, by definition, accessible and easy to use. It is presented in HTML format, a file type that can be opened in your browser. When you open it, a map of the world appears. Above the map is a scroll bar with the date on it. As you scroll from left to right, you will see the map gradually change color from a whitish yellow in some areas to a scarlet red in others. In the upper left corner of the map are two buttons, one to zoom in and one to zoom out. Conversely, a barometer indicates the number of confirmed cases in relation to the defined colors.

![carte_explication_en](https://user-images.githubusercontent.com/69150501/126908710-8617ce96-f241-4b36-a96d-02d52875cf97.png)
Figure: Description of CIVOCA graphical interface

## Who is CIVOCA for?
CIVOCA is intended for all users who want to learn more about the progress of Covid-19 in Africa.

## Difficulties encountered 
We have encountered considerable difficulties in designing CIVOCA. These are mainly related to: the inaccessibility of statistical data on the number of cases identified at the communal level in Benin and the time limit for submitting projects. 

Whether on the WHO website or on that of the Ministry of Health in Benin, very little data is made available online. Worse, we feared that the response time to a physical request for access to statistical data on the number of Covid-19 cases in Benin, addressed to the Ministry of Health, would exceed the time allowed for this competition. Finally, this competition was an opportunity for us to identify and correct shortcomings related to web development. We never stop learning, they say!

## Perspectives 
In order to make this project more useful and to increase its prospects of use, it would be crucial to provide data on the number of cases of Covid-19 in the different municipalities of Benin.

This will allow for a realistic projection of the evolution of Covid-19 in Benin and the identification of future hotspots of the virus at the communal level. After integrating the suggestions, this project will allow the government to better implement measures to fight this pandemic that is causing so much devastation.



