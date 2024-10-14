# Ex04 Places Around Me
## Date: 14-10-24

## AIM:
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

<!DOCTYPE html>
<html>
<head>
<title>NELLORE</title>
</head>
<body>
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b> MANI SRI LATHA (212223110025)</b></h3>
<center>
    <img src="nellore.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="Acer Mall" title="Acer Mall" href="acer.html" coords="810,216,964,286" shape="rect">
        <area target="" alt="Benelli Keeway" title="Benelli Keeway" href="benelli.html" coords="1087,357,1339,422" shape="rect">
        <area target="" alt="Priyadarshini College" title="Priyadarshini College" href="priyadarshini.html" coords="965,701,1178,709,971,809" shape="poly">
        <area target="" alt="Barashahid Dargha" title="Barashahid Dargha" href="dargha.html" coords="702,372,100" shape="circle">
        <area target="" alt="VPR Convention Center" title="VPR Convention Center" href="vpr.html" coords="662,754,878,820" shape="rect">
    </map>
</center>
</body>
</html>

```
```
acer.html

<!DOCTYPE html>
<html>
<head>
<title>Acer Mall</title>
</head>
<body bgcolor="cyan">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Acer Mall Exclusive Store</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Acer Mall Exclusive Store, located in Ground Floor, Opp.Madras Bus Stand, Main Road, Nellore, Andhra Pradesh, 524001<br>
2)Acer exclusive stores are the perfect place to find the latest and greatest in Acer technology. With knowledgeable staff on hand to help you find the perfect product.<br>

</p>
</body>
</html>
```
```
benelli.html

<!DOCTYPE html>
<html>
<head>
<title>Benelli Keeway</title>
</head>
<body bgcolor="lavender">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Benelli Keeway</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Benelli Keeway , located in Opp: Medicover Hospital, Sy no-932/A,Ayodhya Nagar Extension, NH16, Pinakini Avenue, Nellore, Andhra Pradesh 524003<br>
2)Benelli is a company which develops and produces motorbikes, with registered office at Strada della Fornace Vecchia, sn, 61122 Pesaro (PU), Italy, belonging to the Qianjiang group headquartered in Wenling, Zhejiang province, China.<br>

</p>
</body>
</html>
```
```
dargha.html

<!DOCTYPE html>
<html>
<head>
<title>Barashahid Dargha</title>
</head>
<body bgcolor="violet">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Barashahid Dargha</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Bara Shaheed Darga , located in Bara Shaheed Darga, Ambedkar Nagar, Nellore, Andhra Pradesh 524003<br>
 2)As per local tradition and according to stone slate in the campus of dargah that reads in Persian, they were twelve tombs of warriors part of first Muslim army to enter into the region and were martyred in the battle Of Karabala.<br>
 3)"Bara Shaheed Dargah" literally reads "Shrine of twelve martyrs" in Urdu. Dargah is on the bank of the Nellore water tank/lake, and has eid-gah, a tourist resort, and park next to it.<br>

</p>
</body>
</html>
```
```
priyadarshini.html

<!DOCTYPE html>
<html>
<head>
<title>Priyadarshini College</title>
</head>
<body bgcolor="purple">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Priyadarshini College</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Bara Shaheed Darga , located in Bara Shaheed Darga, Ambedkar Nagar, Nellore, Andhra Pradesh 524003<br>
 2)As per local tradition and according to stone slate in the campus of dargah that reads in Persian, they were twelve tombs of warriors part of first Muslim army to enter into the region and were martyred in the battle Of Karabala.<br>
 3)"Bara Shaheed Dargah" literally reads "Shrine of twelve martyrs" in Urdu. Dargah is on the bank of the Nellore water tank/lake, and has eid-gah, a tourist resort, and park next to it.<br>
 
</p>
</body>
</html>
```
```
VPR.html

<!DOCTYPE html>
<html>
<head>
<title>vpr convention center</title>
</head>
<body bgcolor="lavender">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>VPR convention center</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)VPR convention center is located in Nellore-Golagamudi Road, Kanuparthipadu, Village, Nellore, Andhra Pradesh 524004<br>
 2)The prophet dream of Sri Vemireddy Prabhakar Reddy garu, in giving a monumental place of gathering to celebrate for the people of his home town Nellore is the origin of the very existence of the most exclusive and astounding celebration destination – THE VPR CONENTION CENTER.<br>

</p>
</body>
</html>
```


## OUTPUT
![Screenshot 2024-10-13 160244](https://github.com/user-attachments/assets/ce0edd6f-53fb-42b6-84da-eef5bc723ad4)
![Screenshot 2024-10-13 155638](https://github.com/user-attachments/assets/b0739009-8c78-4c0e-bee6-8f50aacce04b)
![Screenshot 2024-10-13 155659](https://github.com/user-attachments/assets/625ee3b7-7a7e-40db-87e7-2fc70b045de9)
![Screenshot 2024-10-13 155722](https://github.com/user-attachments/assets/01a53f56-1e08-4959-82ea-35772955caa8)
![Screenshot 2024-10-13 155742](https://github.com/user-attachments/assets/e645138d-80cf-4b0d-8473-789dfd6b2e27)

## RESULT
The program for implementing image maps using HTML is executed successfully.
