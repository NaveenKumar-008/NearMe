# Ex04 Places Around Me
# DATE: 31.10.23

## AIM
To develop a website to display details about the places around my house.

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
## Map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WEB EXPERIMENT</title>
</head>
<body>
    <h1 align="center">
        <font color=""><b>Meenambakkam</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Naveen Kumar M 212221040113</b></font>
        </h3>
<center>        
<img src="Map.jpg" usemap="#image-map" height="650" width="1600">
</center>
<map name="image-map">
    <area shape="rectangle" coords="953,345,705,482" href="aerohub.html" title="Aerohub">
    <area shape="rectangle" coords="314,304,533,470" href="airport.html" title="Chennai Airport">
    <area shape="rectangle" coords="577,642,769,783" href="theatre.html" title="PVR theatre">
    <area shape="rectangle" coords="1167,408,1344,577" href="rs.html" title="Tirusulam">
    <area shape="rectangle" coords="791,627,1029,784" href="market.html" title="Friday Market">
</map>
</body>
</html>
```
## Market.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Market</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>Meenambakkam</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Pallavaram Friday Market</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Pallavaram Friday Market (Popularly Known as Pallavaram Sandhai) is a market in Pallavaram, Chennai, Tamil Nadu.
                It is an ancient marketplace for vendors where food items, plant saplings, animals and electronic goods are available.
                The market had its origin in 1800.[3] The market is open only on Fridays, and is known locally as the Friday Market.
                The Friday market is located closer to Pallavaram Railway Station, Pallavaram Bus Stand and Chennai International Airport.
                Pallavaram Sandhai was originally existed in Cattle Shandy Road (or) Sandhai Road (Currently Known as Acharya Tulsi Road) in Cantonment Pallavaram. 
                Later the market was moved to Old Trunk Road near Pallavaram Railway Station Flyover.
            </font>
        </p>
    </body>
</html>
```
## Railway Station.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Railway Station</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Meenambakkam</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tirusulam Railway Station</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                The Tirusulam Railway Station is one of the railway stations of the Chennai Beach–Chengalpattu section of the Chennai Suburban Railway Network. 
                It serves the neighbourhood of Tirusulam, a suburb of Chennai where the city's airport is located. 
                It is located at a distance of 21 km (13 mi) from Chennai Beach terminus and is situated on the GST Road across the airport, with an elevation of 20 m (66 ft) above sea level.
                The station has two suburban platforms and another island platform for long-distance mainline trains.
                Since mainline trains do not halt at the station, the island platform remains unused. 
                The platform is 280 m long and has been considered to be extended to 575 m as there are plans to halt long-distance trains at the station.
            </font>
        </p>
    </body>
</html>
```
## Theatre.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Cinema Multiplex</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Meenambakkam</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>PVR Grand Galada</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                PVR Grand Galada Mall is a 5-screen multiplex which provides immersive theathrical experience .
                The ticket fare is Rs.190 incl.of taxes.
                It is located at Kohinoor-2 Officers Line, Grand Southern Trunk Rd, Pallavaram, Chennai, Tamil Nadu 600043.
                There is Geetham Restaurant outside of the theatre premises.
        </p>
    </body>
</html>
```
## Airport.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Airport</title>
    </head>
    <body bgcolor="#FFF9E3">
        <h1 align="center">
            <font color="red"><b>Meenambakkam</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Chennai International Airport</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Chennai International Airport (IATA: MAA, ICAO: VOMM) is an international airport serving the city of Chennai, the capital of Tamil Nadu, India and its metropolitan area.
                 It is located in Tirusulam, around 20 km (12 mi) southwest of the city centre.
                 The Airport Consists of 4 Terminals T1,T2,T3 and T4 where T1 and T4 handling domestic arrivals and departures, T2 and T3(which is under construction) handling International arrivals and departures. 
                 The airport is the 5th busiest airport in India, and 3rd by international traffic. 
                 It was also 49th busiest airport in Asia in 2018 making it one of the four major airports in India under the top 50 list of 2018.
                 In financial year 2022-23, the airport handled over 18 million passengers.
        </p>
    </body>
</html>
```
## Aerohub.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Mall</title>
    </head>
    <body bgcolor="#F3E5AB">
        <h1 align="center">
            <font color="red"><b>Meenambakkam</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Aerohub</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Aerohub is a cutting-edge mall with tantalising dining options, a state-of-the-art 5-screen movie theatre, and an amazing 2.5 Lakh sq. ft. of premium space.
                It is situated at Chennai International Airport in Meenambakkam with a total of 2,200 equivalent parking spaces can be found in the nearby multi-level car parking facility.
                Aerohub Mall is the perfect destination for anyone seeking an all-in-one shopping and entertainment experience. 
                With premium facilities, an array of dining options, a state-of-the-art movie theatre, and a kids’ play area, it is redefining the concept of malls and ensuring a memorable experience for all visitors.
            </font>
        </p>
    </body>
</html>
```
## OUTPUT
## Map
![Alt text](<Screenshot (8).png>)

## Market
![Alt text](<Screenshot (12).png>)

## Railway Station
![Alt text](<Screenshot (13).png>)

## Theatre
![Alt text](<Screenshot (11).png>)

## Airport
![Alt text](<Screenshot (9).png>)

## Aerohub
![Alt text](<Screenshot (10).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
