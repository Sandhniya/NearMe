# Ex04 Places Around Me
## Date:14.04.24

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
    <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VELLORE</b></font>
         </h1>
         <h3 align="center">sandhiya sree.b(212223220093)</b></font>
         </h3>
         <center>
            <img src="map.png" usemap="#MYCITY" height="650" width="1500">
            <map name="MYCITY">
                <area shape="rect" coords="740,350,780,380" href="fort.html" title="VELLORE FORT">
                <area shape="rect" coords="910,70,956,120" href="college.html" title="VELLORE INSTITUTE OF TECHNOLOGY">
                <area shape="rect" coords="480,600,530,640" href="temple.html" title="SRI LAKSHMI NARAYANI GOLDEN TEMPLE">
                <area shape="rect" coords="790,300,820,350" href="hospital.html" title="CMC HOSPITAL">
                <area shape="rect" coords="700,590,750,620" href="home.html" title="MY HOME">
            </map>
         </center>
    </body>
</html>


fort.html

<html>
<head>
<title>My Home Town</title>

</head>

<body bgcolor ="cyan">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>VELLORE FORT</b></font>
</h2>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>Vellore Fort :</i></u></h>
<u1>
<li>The Fort was constructed by then the ruler Bommu Nayakar and his brother during 1526-1595 AD</li>

<li>The First Mutiny against the British in India broke out in Vellore Fort (1806 Sippoy Kalagam)Tippu Mahal, Hyder Mahal, Condy Mahal, Badhusha Mahal and the Begam Mahal in side the Fort.</li>

<li>The fort at Vellore is one of the great attractions in the District.</li>

<li> It is Said to have been built by Chinna Boomi Nayaka a subordinate under Sadasivaraya of the Vijayanagara Kindom in mid of 16th Century A.D.</li>

<li> The fort was occupied by the British in 1760 and used as a military garrison.</li>

 <li>The rectangular fort with a circumference of 3km is built entirely with massive granite cut stones.</li>


<li>The fort contains both secular and religious structures including tippu Mahal, Begum Mahal, Kandi Mahal, Jalakanteswara Temple, A mosque and a Church.</li>

<li>Museums also established by 01, April 1999 in this fort by the Archaeological Survey of India and State Department.</li>
</font>

<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>



<img src= "fort.jpg" width="450" height="420"  class="centerimage">



</p>
</body>
</head>
</html>


temple.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="orange">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="green"><b>TEMPLE</b></font>
</h2>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>GOLDEN TEMPLE-SRIPURAM:</i></u></h>
<u1>

<li>The temple is located on 100 acres of land and has been constructed by the Vellore-based charitable trust, Sri Narayani Peedam, headed by its spiritual leader Sri Sakthi Amma also known as 'Narayani Amma'.</li>
<li> The temple with its gold (1500 kg) covering, has intricate work done by artisans specialising in temple art using gold.</li>
<li>Every single detail was manually created, including converting the gold bars into gold foils and then mounting the foils on copper.
<li> Gold foil from 9 layers to 10 layers has been mounted on the etched copper plates.</li>
<li> Every single detail in the temple art has significance from the vedas.</li>
</u1>


<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>
<img src= "temple.png"  width="450" height="420" alt ="fort" class="centerimage"  >

</font>
</p>
</body>
</head>
</html>


home.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="lavender">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="purple"><b>HOME</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>MY HOME :</i></u></h>
<u1>

<li>Home is a safe haven and a comfort zone.</li> 
<li>A place to live with our families and pets and enjoy with friends.</li>
<li> A place to build memories as well as a way to build future wealth.</li>
<li> A place where we can truly just be ourselves.</li>
<li>My house is my most favourite place in the world.</li>
<li> I live with my mother and father in my house. </li>
<li>My house has three floors and lots of stairs.</li>
<li> We have a garden outside our house with beautiful flowers.</li>
<li>Maybe the reason you can never go home again is that, once you're back, you can never leave.</li>

<u1>

<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>
<img src= "house.jpeg"  width="450" height="420" alt ="fort" class="centerimage"  >

</font>
</p>
</body>
</head>
</html>


hospital.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="yellow">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>HOSPITAL</b></font>
</h2>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>CMC HOSPITAL :</i></u></h>
<u1>
<li>An Unending Dedication to Excellence in Research, Education, and Service.</li>

<li>The Christian Medical College (CMC) in Vellore was founded in 1900 as a one-room clinic by Dr. Ida S. Scudder, the only daughter of second-generation American missionaries.</li>

<li>People from around the world visit CMC to get world-class care, delivered with honesty, fairness, compassion, and integrity.</li>

<li>CMC's excellence continues with advances in research and an evolving curriculum aimed at transforming India's promising medical students into creative and compassionate healthcare providers.</li>

<li>CMC has come a long way from its humble start as a one-room clinic, growing into one of India's most prestigious private hospitals and medical schools.</li>

<li> Today, CMC cares for over two million patients and trains one thousand doctors, nurses and other medical professionals each year.</li> 

</u1>


<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>

<img src= "cmc hospital.jpg"  width="450" height="420" alt ="fort" class="centerimage"  >

</font>
</p>
</body>
</head>
</html>


college.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="pink">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="green"><b>TEMPLE</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>VELLORE INSTITUTE OF TECHNOLOGY:</i></u></h>
<u1>

<li>It was established under Section 3 of the University Grants Commission (UGC) Act, 1956, and was founded in 1984 as a
     self-financing institution called the Vellore Engineering College.</li>
<li>The Union Ministry of Human Resources Development conferred University status on Vellore Engineering College in 2001.</li>
<li>The University is headed by its founder and Chancellor, Dr. G. Viswanathan, a former Parliamentarian and Minister in the Tamil 
    Nadu Government.</li>
<li> In recognition of his service to India in offering world class education, he was conferred an honorary doctorate by the
     West Virginia University, USA. Mr.Sankar Viswanathan, Dr.Sekar Viswanathan and Dr.G.V. Selvam are the Vice-Presidents;
      Dr. Rambabu Kodali is the Vice-Chancellor and Dr. Partha Sharathi Mallick is the Pro-Vice Chancellor I/C.</li>


<u1>

<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>
<img src= "vit.jpg"  width="450" height="420" alt ="fort" class="centerimage"  >

</font>
</p>
</body>
</head>
</html>

```



## OUTPUT
![Screenshot 2024-04-14 145509](https://github.com/Sandhniya/NearMe/assets/151395890/74b2f55e-8a9b-44d2-8eb3-dcb79c0ed993)

![Screenshot 2024-04-14 145535](https://github.com/Sandhniya/NearMe/assets/151395890/f5da6763-c4b1-403c-8793-c83869180a34)

![Screenshot 2024-04-14 145640](https://github.com/Sandhniya/NearMe/assets/151395890/7c19304f-2af0-4c91-b942-5dfb5e95accb)

![Screenshot 2024-04-14 145615](https://github.com/Sandhniya/NearMe/assets/151395890/9959611c-65bf-4072-b04f-3c5919033eb2)

![Screenshot 2024-04-14 145704](https://github.com/Sandhniya/NearMe/assets/151395890/52fc4491-b03d-4666-8864-e832f4773b5e)





## RESULT
The program for implementing image maps using HTML is executed successfully.
