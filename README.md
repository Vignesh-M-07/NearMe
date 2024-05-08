# Ex04 Places Around Me
## Date: 08.05.2024

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
map1.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Poonamallee</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>vignesh M (212223040235)</b></font>
        </h3>
        <center>
            <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-05 102557.png" usemap="#image-map">
           

<map name="image-map">
    <area target="" alt="Schneider Electric" title="Schneider Electric" href="se.html" coords="13.058871645829367, 80.10387165113505" shape="rect">
    <area target="" alt="Doosan" title="Doosan" href="d.html" coords="13.061868386231902, 80.10914537136644" shape="circle">
    <area target="" alt="HITSS group of companies" title="HITSS group of companies" href="hgc.html" coords="13.043503667652688, 80.12167457790896" shape="circle">
        </center>  
    </body>
</html>



se.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>Poonamallee</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"></b>Schneider Electric</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                We drive digital transformation by integrating world-leading process and energy technologies, end-point to cloud connecting products, controls, software and services, across the entire lifecycle, enabling integrated company management, for homes, buildings, data centres, infrastructure and industries.

                We are the most local of global companies. We are advocates of open standards and partnership ecosystems that are passionate about our shared Meaningful Purpose, Inclusive and Empowered values.
            </font>
        </p>
    </body>
</html>



<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b>Poonamallee</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"></b>Doosan</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Doosan competes and thrives in both domestic and global markets.
                From large-scale power plants that generate electricity in India to desalination plants that supply clean water
                to millions of people in the Middle East, construction machines with unrivaled leading position in the North American market,
                and energy storage systems and fuel cells that show exponential growth in demand,
                Doosan’s advanced technologies enhance the value of human life for everyone in the world.
            </font>
        </p>
    </body>
</html>

hgc.html

<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="cyan"><b>Poonamallee</b></font>
        </h1>
        <h3 align="center">
            <font color="red"><b></b>HITSS group of companies</font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                The HITSS GROUP of companies was established in 2014, in a span of almost 7 years, the company has grown and diversified and is today a name that commands recognitions and respect in the Domestic Market.
                HITSS Group of Companies is one among the promising industry in the Plastic Injection Moulding, Spray Painting, and Product Assembly Manufacturer. It caters with a strong presence in segments of Automobile, Electrical and Electronic, Engineering products and Home appliances.
            </font>
        </p>
    </body>
</html>

## OUTPUT

![Screenshot 2024-05-08 092201](https://github.com/Vignesh-M-07/NearMe/assets/151615193/aa59dd1d-be9a-4b1a-be3e-08438a0f6fbf)

![Screenshot 2024-05-08 092219](https://github.com/Vignesh-M-07/NearMe/assets/151615193/03b646cc-4540-44d7-9d95-a2762aa605b6)





## RESULT
The program for implementing image maps using HTML is executed successfully.
