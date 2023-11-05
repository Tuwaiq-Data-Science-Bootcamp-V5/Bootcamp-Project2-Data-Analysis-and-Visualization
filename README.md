# **Public Transportation in KSA**

## Group 2 Members 

- Ali Al Mutairi 
- Nour Al dahan
- Nada Al Mutairi 

## Introduction 

Getting to\from work in rush hours in saudi arabia can be the most intolerable task anybody can face, especially in riyadh. The huge amount of cars does not only cause traffic to be at it worse, but also air,sound and even mood pollution for all of us. 
However, our dear government have started a steady bus trips that moves in soooo many stops to easy down the traffic. Unfortunately, they are sill cooking their popularity.

Therefore, in this study our objectives: 
- Find the Population of Saudi Arabia 
- Find the use of public transportation in KSA
- Find the Cars used in Saudi Arabia by Volume and other prameters 
- Do a comparison between KSA and NY

## Dataset Overview 
1. [Population Dataset](https://www.kaggle.com/code/faisalalshahrani/ksa-population-analysis/input)

* Descripe the Population estimation by nationality and gender for every region between the years 2010 to 2022
* Columns Description:

	- Region = region of saudi arabia (Riyadh, Makkah, Eastern Region, Madinah, Aseer, Jazan, Qaseem, Tabouk Hail, Al-Jouf, Najra, Northern Region, Al-Baha)
	- Year = the years that the data collection was condected in (2010 - 2022)
	- Gender = Female, Male
	- Nationality = Saudi, Non-Saudi
	- Population estimates


2. [Public Transportation in KSA Dataset](https://od.data.gov.sa/Data/ar/dataset/the-number-of-public-transport-passengers-by-year-and-city/resource/a81f6de0-799a-4ca0-93fb-5b1ee92c09a6?inner_span=True)

* Descripe the Volume estimation by region between the years 2016 to 2022
* Columns Description:
	- Cities = 4 cental region of saudi arabia (Riyadh, Jeddah, alMadinah, Dammam)
	- Year = the years that the data collection was condected in (2016 - 2022)
	- Ridership Volume

3. [Used Cars in KSA Dataset](https://www.kaggle.com/datasets/reemalruqi/used-cars-in-saudi-arabia)

* Descripe the the used cars soled in saudi arabia
* Columns Description:
	- car_brand = the car manufacturer
	- car_model = the name used by a manufacturer to market a range of similar cars
	- car_driven = the distance traveled by the car in kilometers
	- car_transmission = machine power transmission system
	- car_model_year = Year of the model
	- car_price

4. [Car Plates Issued by Type and Region Dataset](https://datasource.kapsarc.org/explore/dataset/car-plates-issued-by-type-of-vehicle-and-region-14-8_0/information/?disjunctive.type&disjunctive.region&sort=year&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoicmFuZ2UtQWNjZW50IiwieUF4aXMiOiJ2YWx1ZSJ9XSwieEF4aXMiOiJ5ZWFyIiwibWF4cG9pbnRzIjpudWxsLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwic29ydCI6IiIsInNlcmllc0JyZWFrZG93biI6InR5cGUiLCJjb25maWciOnsiZGF0YXNldCI6ImNhci1wbGF0ZXMtaXNzdWVkLWJ5LXR5cGUtb2YtdmVoaWNsZS1hbmQtcmVnaW9uLTE0LThfMCIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUudHlwZSI6dHJ1ZSwiZGlzanVuY3RpdmUucmVnaW9uIjp0cnVlLCJzb3J0IjoieWVhciJ9fX1dLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlLCJ0aW1lc2NhbGUiOiIifQ%3D%3D)

* Descripe the volume of Car Plates Issued in saudi arabia between the year 2017 - 2019
* Columns Description:
	- Year
	- Type = type of car plates (private, taxi, etc.)
	- Region = cities of saudi arabia
	- value = the amount of car plates Issued
	- Total = sum of car plates Issued by type and year

5. [New York City bus ridership Dataset](https://new.mta.info/agency/new-york-city-transit/subway-bus-ridership-2021)

* Descripe the volume of rideship for New York city between the year 2016 - 2021
* Volume By:
	- Weekdays
	- WeekEnds
	- Saturday's
	- Sunday's
	- Annualy

## Insights 

When we look at the ratio between population and public transportation we find that Dammam has the highest rate of public transportation use, indicating a densely populated area with a strong reliance on public transportation.
Medina also has high usage of public transportation, indicating a significant demand for these means of transport.

However, ignoring the ratios shows that Riyadh was the city with the highest public transportation use and we point out that Riyadh is also one of the highest cities with non-Saudi residents as we assume that the majority of public transportation users are non-Saudi at the moment. 

We can also see how the pandemic has affected the number of rideships to fall to more than half. 

As we investigated the data more we saw that the central cities (Riyadh, Makkah, Eastern Region) where non-Saudis were almost equal to the Saudis pointing that this piece of information is relevant to the tendency to use public transportation. 

Going further in our study, we have analyzed 2 more datasets to see other transportation methods used in KSA focusing on cars. 

Honda took first as the widely used car in Saudi, followed by Suzuki, Kia, and finally Toyota. 
Also, studying the top 5 expensive cars we came to realize that only Toyota made it from the previous group with being the 1.86% most expensive, while Audi took the first place with a huge difference of 92.8% most expensive. 

As for the volume of cars in Saudi Arabia, we decided not to include the years before 2019 for the reasons of lack of data and for it making a huge gap after announcing that women can drive -Thankfully-. 
We focused on 3 cities only (Riyadh, Almadina, Eastern Region). the only city that had a raise on new plates issued was Riyadh starting from 46k in 2017 and reaching 65k in 2019. 
both Almadina and Eastern Region volumes have fallen to a decrease. 

Finally, as a small comparison, we have studied the use in NY City to see that even the huge numbers pre-2019 also faced a fall due to the pandemic in 2019-2021. 
When put together -KSA and NY- there is hardly any comparison. 




