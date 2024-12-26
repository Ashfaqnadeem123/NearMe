# Ex04 Places Around Me
## Date: 25-12-2024

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
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="magenda"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b> MOHAMMED ASHFAQ NADEEM A(24000199) </b></font>
        </h3>
        <center>
            
<map name="MyCity">
    <area shape="rect" coords="100,100,900,900" href="expmap.html" title="My Home Town"</map>
    

    <img src="kadapa_map.png" usemap="#image-map">

<map name="image-map">
    <map name="image-map">    
    
            <area target="_blank" alt="Kadapa Airport" title="Kadapa Airport" href="airport.html" coords="921,303,1163,384" shape="rect">
            <area target="_blank" alt="Ameen Peer Darga" title="Ameen Peer Draga" href="darga.html" coords="720,174,71" shape="circle">
            <area target="_blank" alt="Machupalle" title="machupalle" href="machupalle.html" coords="1095,202,1021,189,1027,87,1090,69,1147,96,1161,157,1138,194" shape="poly">
            <area target="_blank" alt="Viswanathapuram" title="Viswanathapuram" href="viswanathapuram.html" coords="930,762,1035,840" shape="rect">    
    </map>
</map>
        </center>
    </body>

</html>
```

airport.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Kadapa Airport</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Kadapa Airport (IATA: CDP, ICAO: VOCP) is a domestic airport serving Kadapa (formerly Cuddapah) in Andhra Pradesh, India.
        </font>
        </p>
    </body>
</html>
```

darga.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Ameen Peer Darga</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Ameen Peer Dargah in Cuddapah also known as Badi Peer Dargah is a century old mausoleum believed to fulfill wish of every pilgrim who visits the site.
        </font>
        </p>
    </body>
</html>
```
machupalle.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Machupalle</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Machupalli is a Village in Sidhout Mandal in Cuddapah District of Andhra Pradesh State, India. It belongs to Rayalaseema region.
        </font>
        </p>
    </body>
</html>
```

viswanathapuram.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>KADAPA</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Viswanathapuram</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            It is a very good place for greenery and devotional. Which is very near to the Sri Madvirat Veera Bramendra Swamy temple
        </font>
        </p>
    </body>
</html>
```


## OUTPUT

![map](https://github.com/user-attachments/assets/aeab6dd0-2a73-4242-be3d-f88212f24db8)
![1](https://github.com/user-attachments/assets/1962ba99-29b5-4f1c-b47a-be03e8c47173)
![2](https://github.com/user-attachments/assets/d009638f-989f-4e93-8dc1-532122da3fba)
![3](https://github.com/user-attachments/assets/f7479a93-2e82-48d5-9dd5-aaef76a9507f)
![4](https://github.com/user-attachments/assets/b33d8635-043a-4080-8b32-b5c3a8b16604)



## RESULT
The program for implementing image maps using HTML is executed successfully.
