# Ex04 Places Around Me
## Date: 

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
```
map.html
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="coralblue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="lightpink"><b>Aishwarya V(212223220003)</b></font>
</h3>
<centre>
<h4 align="center">
<img src="map.png.png" usemap="MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html title="MyHomeTown">
<area shape="circle" coords="570,230,45" herf="temple.html" title="Arulmigu Manakula Vinayagar"
<area shape="circle" coords="1120,360,25" herf="fort.html" title="Puducherry Rock Beach">
<area shape="rect" coords="950,120,1100,140" herf="thetre.html" title="PVR cinemas">

</h4>
</map>
</centre>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="lightgreen"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Puducherry - My home town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Puducherry, formerly known as Pondicherry, gained its significance
 as "The French Riviera of the East" after the advent of French colonialisation in India. 
Puducherry is the Tamil interpretation of "new town" and mainly derives from "Poduke",
the name of the marketplace or "port town" for Roman trade in the 1st century, as mentioned 
in the Periplus of the Erythraean Sea.
</font>
</p>
</body>
</html>

thetre.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="blue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>PVR The Cinema Providence - Entertainment Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Movie theater in Puducherry
Address: No-7, Providence Mall, 4th and 5th Floor, Venkatasubba Reddiyar Salai, 
Via Cuddalore Road, Near Malai Malar, Pondicherry, Tamil Nadu 605001, India.
</font>
</p>
</body>
</html>

fort.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="blue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Puducherry Rock Beach - Tourist Spot</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Pondicherry no longer has the sandy beaches that once graced its coastline.
The breakwater to the harbour and other hard structures constructed on the shore
caused extreme coastal erosion, and the sand from Pondicherry's Promenade Beach has
disappeared entirely.
</font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
<h1 align="center">
<font color="black"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="black"><b>PEC - Educational University</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Pondicherry University, also known as PU, (French: Université de Pondichéry) is a 
central research university located in Kalapet, Pondicherry in Union Territory of
Puducherry, India. It was established by an Act of Parliament in 1985 by the Department 
of Higher Education, Ministry of Education, Government of India. 
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="blue"><b>Puducherry</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Arulmigu Manakula Vinayagar - Devotional Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Arulmigu Manakula Vinayagar Devasthanam on Manakula Vinayagar Street 
is a Hindu temple to Ganesha. Sri Manakula Vinayagar Temple was in existence 
before the French came and settled in Pondicherry in 1666.
</font>
</p>
</body>
</html>
```

## OUTPUT

![map png](https://github.com/aishaishwaryav/NearMe/assets/151565589/8e05b8f7-eb2d-4521-9470-04c299e6dea4)

![home html](https://github.com/aishaishwaryav/NearMe/assets/151565589/9b6f0fe0-c262-4185-897b-4bc6a93e43aa)

![fort](https://github.com/aishaishwaryav/NearMe/assets/151565589/e3575f68-bf06-4cfb-9d4a-28cb5b8c4e50)

![college](https://github.com/aishaishwaryav/NearMe/assets/151565589/f2c2cd5f-90d3-4445-9f05-36475169fde5)

![temple](https://github.com/aishaishwaryav/NearMe/assets/151565589/7bf249d6-65e0-4148-8827-d6a33d0c3826)

![thetre](https://github.com/aishaishwaryav/NearMe/assets/151565589/e41f7356-0510-4bea-a5ae-959fc5f41ac8)


## RESULT
The program for implementing image maps using HTML is executed successfully.
