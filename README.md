# Ex04 Places Around Me
## Date: 30-11-2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

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

map.html
```
<html>
    <head>
        <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Jawahar(24004142)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map" >

<map name="image-map">
    <area target="_blank" alt="Palamathi Hills" title="Palamathi Hills" href="hills.html" coords="1321,534,50" shape="circle">
    <area target="_blank" alt="Golden Temple" title="Golden Temple" href="temple.html" coords="927,596,50" shape="circle">
    <area target="_blank" alt="Poigai" title="Poigai" href="poigai.html" coords="655,398,786,493" shape="rect">
    <area target="_blank" alt="Pulimedu Waterfall" title="Pulimedu Waterfall" href="waterfall.html" coords="449,752,630,862" shape="rect">
    <area target="_blank" alt="Rangapuram" title="Rangapuram" href="rp.html" coords="1342,312,1320,280,1337,227,1381,251,1408,293" shape="poly">
</map>
        </center>
    </body>
</html>
```
hills.html
```
<html>
    <head>
        <title>
            Palamathi Hills
        </title>
    </head>
    <body bgcolor="blue">
        <h1>Palamathi Hills</h1>
        <p>The Palamathi Hills are an extension of the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu. The Palamathi Hill range, the nearby Palamathi Reserve Forest, and the Otteri lake are collectively referred to as Palamathi Hills.</p>
    </body>
</html>
```
poigai.html
```
<html>
    <head>
        <title>
            Poigai
        </title>
    </head>
    <body bgcolor="red">
        <h1>Poigai</h1>
        <p>Poigai is a Village in Anaicut Block in Vellore District of Tamil Nadu State, India. It is located 10 KM towards west from District head quarters Vellore.</p>
</html>
```
rp.html
```
<html>
    <head>
        <title>
            Rangapuram
        </title>
    </head>
    <body bgcolor="purple">
        <h1>Rangapuram</h1>
        <p>It's a calm residential area, with individual houses with terraces available. it's ideal for a family.</p>
</html>
```
temple.html
```
<html>
    <head>
        <title>
            Sri Lakshmi Narayani Golden Temple
        </title>
    </head>
    <body bgcolor="cyan">
        <h1>Sri Lakshmi Narayani Golden Temple</h1>
        <p>Sri Lakshmi Narayani Golden Temple complex inside the Thirupuram spiritual park is situated at the foot of a small range of green hills at Thirumalaikodi Vellore in Tamil Nadu, India. It is 120 km from Tirupati, 145 km from Chennai, 160 km from Pondicherry and 200 km from Bengaluru.</p>
</html>
```
waterfall.html
```
<html>
    <head>
        <title>
            Pulimedu Waterfall
        </title>
    </head>
    <body bgcolor="green">
        <h1>Pulimedu Waterfall</h1>
        <p>Diamond Waterfalls in Pulimedu,Vellore listed under Tourist Attraction in Vellore.</p>
</html>
```

## OUTPUT

![Screenshot (38)](https://github.com/user-attachments/assets/e700707f-6ff1-4ceb-8a85-4b80313137fa)


![Screenshot (33)](https://github.com/user-attachments/assets/75459765-4c8b-4830-b578-751721706c88)


![Screenshot (34)](https://github.com/user-attachments/assets/fd73b3ee-5736-4517-81f6-a76d9a7ceb58)


![Screenshot (35)](https://github.com/user-attachments/assets/726252c0-93d3-45ce-8ce6-74a92b28a8ea)


![Screenshot (36)](https://github.com/user-attachments/assets/bf57ca2a-2583-44d9-a056-cb02f3d51846)


![Screenshot (37)](https://github.com/user-attachments/assets/62f95d02-3073-440b-b30c-21b406b88619)


## RESULT
The program for implementing image maps using HTML is executed successfully.
