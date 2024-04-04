# Ex04 Places Around Me
## Date: 04.04.2024

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
chris.html

<html>
  <head>
    <title>My HomeTown</title>
  </head>
  <body>
    <h1 align="center">
      <font color="pink"><b>Karaikudi</b></font>
    </h1>
    <h3 align="center">
      <font color="grey"><b>Jayavarsha T (212223040075)</b></font>
    </h3>
    <center>
      <img src="kkdi map.png" usemap="#My HomeTown" height="610" width="1450" />
      <map name="My HomeTown">
        <area shape="rect" coords="700,250,310,420" href="Home.html" title="My HomeTown"/>
        <area target="" alt="atchaya residency" title="atchaya residency" href="hotel.html" coords="915,83,1055,86,1072,100,1052,123,964,138,901,132,879,106" shape="poly">
        <area target="" alt="Pandian Cinemas" title="Pandian Cinemas" href="theatre.html" coords="828,302,67" shape="circle">
        <area target="" alt="Karaikudi Railway Station" title="Karaikudi Railway Station" href="train.html" coords="1109,495,1292,426" shape="rect">
        <area target="" alt="Karai Visual Photography" title="Karai Visual Photography" href="photo.html" coords="1426,445,103" shape="circle">
      </map> 
      </map>
    </center>
  </body>
</html>    

home.html
<html>
<head>
<title>My HomeTown</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="white"><b>Karaikudi</b></font>
</h1>
<h3 align="center"
<font color="line"><b>My HomeTown</b></font>
</h3>
<hr size="3" color="purple">
<p align="justify">
<font face="Georgia" size="5">
    Karaikudi is the largest city in Sivaganga district in the Indian state of Tamil Nadu. 
Karaikudi Municipal Corporation is the 21st largest urban agglomeration of Tamil Nadu based on 2011 census data. 
It is part of the area commonly referred to as "Chettinad" and has been declared a City Municipal Corporation by the 
Government of Tamil Nadu,[1] on account of the palatial houses built with limestone called Kaarai veedu. For this reason, 
the place is sometimes called Kaarai Nagar locally. The main municipality is spread across 33.75 km2 and the extended 
urban limit spreads about 115 km2 (44 sq mi) which undergoes major developments as part of Government Schemes.
</font>
</p>
</body>
</html>

hotel.html
<html>
<head>
<title>My HomeTown</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Karaikudi</b></font>
</h1>
<h3 align="center"
<font color="line"><b>atchaya residency</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="5">
    The Atchaiya Residency Tower is one of the finest luxury residency in the Karaikudi city.The Atchaiya Residency is best Rooms 
and Facilities offers the perfect gateway to Karaikudi city.Hotel Atchaiya Residency Tower is conveniently and strategically 
located in the heart and soul of Karaikudi which is full of bustling businesses, entertainment areas and a shopping paradise. 
Getting around the city won’t be a problem as our hotel is only a few walks away from new bus stand. Several of Karaikudi 
attractions and popular landmarks are also proximate to the hotel like World famous Kalanivasal road, Karaikudi.
</font>
</p>
</body>
</html>

theatre.html
<html>
<head>
<title>My HomeTown</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="black"><b>Karaikudi</b></font>
</h1>
<h3 align="center"
<font color="line"><b>Pandian Cinemas</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
    Pandian Cinemas - Sekkalai is a popular theatre located at No.263, Karaikudi Road, Near Hotel Subhalakshmi,
Sekkalai, Central, Karaikudi. Pandian Cinemas - Sekkalai has 1 screens. Movies now showing at Pandian Cinemas - Sekkalai are NONE.
</font>
</p>
</body>
</html>

train.html
<html>
<head>
<title>My HomeTown</title>
</head>
<body bgcolor="lightpink">
<h1 align="center">
<font color="white"><b>Karaikudi</b></font>
</h1>
<h3 align="center"
<font color="line"><b>Karaikudi Railway Station</b></font>
</h3>
<hr size="3" color="white" />
<p align="justify">
<font face="Georgia" size="5"> </font>
Karaikudi station was constructed as a part of Pudukkottai–Sivaganga railway line during the 1930s.
Initially during its older days this station acted as an ordinary railway station when the Tiruturaipundi 
Aranthangi line was extended to Karaikudi, it became a junction railway station. It became as a junction by 
connecting all the three terminal lines they are Manamadurai Sivagangai Railway line, Trichinopoly Pudukkottai 
Railway line and Tiruturaipundi Aranthangi Railway line. Being a junction station, three rail lines emerge from 
the station, one towards Tiruchirappalli Junction, another to Thiruthuraipoondi junction and the third and final 
one Manamadurai Junction.  
</font>
</p>
</body>
</html>

photo.html
<html>
<head>
<title>My HomeTown</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="dark blue"><b>Karaikudi</b></font>
</h1>
<h3 align="center"
<font color="line"><b>Karai Visual Photography</b></font>
</h3>
<hr size="3" color="dark blue">
<p align="justify">
<font face="Georgia" size="5">
    Karai Visual Photography is an photo studio team with lots of middle class members.Their photo shots and
snaps are unbeleivable and its showing their excellence of art in this stage of competeting world   
</font>
</p>
</body>
</html>

```

## OUTPUT

![alt text](<kkdi img1.png>)
![alt text](<kkdi img2.png>)
![alt text](<kkdi img3.png>)
![alt text](<kkdi img4.png>)
![alt text](<kkdi img5.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
