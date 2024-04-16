# Ex04 Places Around Me
## Date: 30/03/2024

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
### map.html
```
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Ranipet</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vinnush kumar L S (212223230244)</b></font></h3>
<center>
<img src="Screenshot 2024-03-26 111923.png" usemap="#image-map"  height="610" width="1450">
<map name="image-map">
<area target="" alt="kaveripakkam" title="kaveripakkam" href="kaveri.html" coords="794,234,975,296" shape="rect">
<area target="" alt="sri prasanna venkatesa perumal temple" title="sri prasanna venkatesa perumal temple" href="temple.html" coords="603,616,26" shape="circle">
<area target="" alt="Sumbeam international" title="Sumbeam international" href="school.html" coords="332,320,16" shape="circle">
<area target="" alt="murugan idli shop" title="murugan idli shop" href="hotel.html" coords="679,342,30" shape="circle">
<area target="" alt="home" title="home" href="home.html" coords="804,378,797,362,826,362,828,378,816,389" shape="poly">
</map>
</center>
</body>
</html>
```
### kaveri.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Ranipet</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kaveripakkam</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Kaveripakkam is about 100 km west of Chennai, 40 km east of Vellore and 28 km west of Kanchipuram. Kaveripakkam has more than 50 small villages around the town. Kaveripakkam is the entry town of Vellore Dist
</p>
</body>
</html>
```

### temple.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>Ranipet</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri prasanna venkateswara</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
    The temple was once renovated by the Vijayanagara emperor Krishnadevarayar. It also houses shrines for Alamelumangai Thayar, Anjaneyar, Garudalvar, Desikar, Rukmini, Satyabhama, and Thirukkachi Nambi. Since this temple was patronised by Krishnadevarayar, there is an idol of his likeness within the sanctum
</p>
</body>
</html>
```

### school.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lavender">
<h1 align="center">
<font color="red"><b>Ranipet</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>sunbeam schools</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
The Sunbeam group has been a long-standing beacon of premium education. Established in 1989, our Group has institutions in Chennai, Vellore and Walaja. Over the years, we have grown into one of the leading school groups in Tamilnadu.
</p>
</body>
</html>
```
### hotel.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="light blue">
<h1 align="center">
<font color="red"><b>Ranipet</b></font>
</h1>
<h3 align="center">
<font color="white"><b>murugan idli shop</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5">
    This is a branch of the famous Murugan Idli shop of Chennai located on the Chennai - Bangalore highway near Kaveripakkam. Though the hotel lay out is good and spacious, the fare is not as tasty as that of the original located in Chennai. But for the brand name, this is not a place I would recommend. Further up after Kancheepuram one can take a halt of Saravana bhavan or a couple of kilometers down there are hotels just before and after the Kaveripakkam toll booth for better food.
</p>
</body>
</html>
```
### home.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
<h1 align="center">
<font color="red"><b>Ranipet</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>home</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    A home, or domicile, is a space used as a permanent or semi-permanent residence for one or more human occupants, and sometimes various companion animals. It is a fully- or semi-sheltered space and can have both interior and exterior aspects to it.[vague] Homes provide sheltered spaces, for instance rooms, where domestic activity can be performed such as sleeping, preparing food, eating and hygiene as well as providing spaces for work and leisure such as remote working, studying and playing.
</p>
</body>
</html>
```
## OUTPUT
 ![alt text](<Screenshot 2024-04-04 133200.png>) 
 ![alt text](<Screenshot 2024-04-04 133330.png>) 
 ![alt text](<Screenshot 2024-04-04 133511.png>) 
 ![alt text](<Screenshot 2024-04-04 133605.png>) 
 ![alt text](<Screenshot 2024-04-04 133814.png>)
 ![alt text](<Screenshot 2024-04-04 133900.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
