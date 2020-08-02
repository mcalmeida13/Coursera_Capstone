# Japanese Restaurant in São Paulo

This is the final project of a series courses by IBM called **Data science Professional Certificate**.

https://www.coursera.org/professional-certificates/ibm-data-science

## 1. Introduction

São Paulo is the biggest city in Brazil. As all metropolis around the world, it has a long history of international immigration and it is home to nearly 12.2 million people in 2018, accounting for over 27% of the population of São Paulo State.

The city continues to be the leading metropolitan gateway for legal immigrants admitted into Brazil.

São Paulo is known for its strong Asian culture, not only the one that came with Japanese immigrants but also Korean, Chinese, and many others.

In 1908, the Japanese began to immigrate to Brazil, becoming the place with the highest number of Japanese people outside Japan. The Brazilian census agency calculated in 2017 there were around 1.5 million Japanese descendants living in Brazil.

For many years, the Japanese culture was concentrated in São Paulo, in a neighborhood called 'Liberdade' ('Freedom' in Portuguese). There, the majority of the shops sell Asian related products. 

Nowadays, Japanese cooking is a Brazilian passion, and it gained lots of local adaptations.


## 2. Problem Statement

We want to explore the best locations for Japanese restaurants throughout the city of São Paulo.
However, as with any business, opening a new restaurant requires serious consideration and is more complicated than it seems. 
In particular, the restaurant's location is one of the most critical factors that will affect whether it will have success or failure. 
So our project will attempt to answer the questions "Where should the investor open a Japanese Restaurant?" and "Where should I go If I want great Japanese food?"

## 3. Data Collection

To answer the above questions, we will need data from São Paulo's neighborhoods, boroughs to include boundaries, latitude, longitude, restaurants, and restaurant ratings and tips.

São Paulo's information about neighborhoods and boroughs will be obtained from the data source: https://en.wikipedia.org/wiki/List_of_postal_codes_in_Brazil

All data related to locations and quality of Japanese restaurants will be obtained via the FourSquare API utilized via the Request library in Python.

## 4. Methodology

* Data fom São Paulo will be collected, cleaned and processed into a dataframe.
*  FourSquare be used to locate all venues and then filtered by Japanese restaurants. Ratings, tips, and likes by users will be counted and added to the dataframe.
* Data will be sorted based on rankings.
*  Finally, the data will be visually assessed using graphing from Python libraries.
