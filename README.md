# Ex04 Places Around Me
## Date: 24.12.2025
# Ref No : 25018768

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
~~~

MAP.html
--------
<html>
<head>
<title>CITY</title>    
</head>
<body>
    <h1 align="center">
    <font color="red"><b>CHENNAI</b></font>    
    </h1>
    <h3 align="center">
        <font color="black"><b> SATHYA PRIYAN (25018768)</b></font>
    </h3>
    <CENTER>
        <img src="map1.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Saveetha Engineering College" title="Saveetha Engineering College" href="Saveetha.html" coords="572,565,67" shape="circle">
    <area target="" alt="Chennai Airport" title="Chennai Airport" href="Airport.html" coords="1213,700,63" shape="circle">
    <area target="" alt="Chennai Institute of Technology" title="Chennai Institute of Technology" href="Cit.html" coords="676,809,68" shape="circle">
    <area target="" alt="Marina Beach" title="Marina Beach" href="Marina.html" coords="1663,387,1794,249,1645,734,1623,676" shape="poly">
</map>

<map name="CITY">
</map>
</CENTER>
</body>    
</html>

saveetha.html
-------------
<html>
    <head>
        <title>
            Saveetha Engineering College
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>Saveetha Engineering college</b></h1>
            <br>
            <img src="saveetha.webp" width="500">
            <p style="font-size: 30;">
              Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, a committed and dedicated Medical Professional.
SEC has a total strength of 6427 students in 15 UG courses, 8 PG Courses including MBA, MS by Research and Doctoral programs (PhD)  in five Departments.
National Board of Accreditation NBA has Accredited 5 UG courses.
Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, Central, State and Private Institutions in India. 
Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation Council (NAAC) for 5 Years.
SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020.
SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of Scientific and Industrial Research (DSIR), Government of India.
Five Research Centres recognised by Anna University
MoU's with Reputed Academic Institutions in India and Abroad 
             

            </p>
        </center>
        
    </body>
</html>


cit.html
--------
<html>
    <head>
        <title>
            Chennai Institute of Technology
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>Chennai Institute of Technology</b></h1>
            <br>
            <img src="CIT.png" width="800">
            <p style="font-size: 30;">
              <b>
                Chennai Institute of technology, the best engineering college in Chennai was established with the objective of providing quality technical education with adequate industrial exposure than any other engineering colleges in Chennai, caters the needs of the youth with its innovative teaching methods.

Apart from interactive classroom scenario, periodic guest lectures by experts from industries and academic background provides thirst to the students to learn and to prepare for the ready-to-serve industrial requirements with uncompromised professional ethics.

              </b>
            </p>
        </center>
        
    </body>
</html>

airport.html
-------------
<html>
    <head>
        <title>
            Chennai Institute of Technology
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>Chennai Institute of Technology</b></h1>
            <br>
            <img src="CIT.png" width="800">
            <p style="font-size: 30;">
              <b>
                Chennai Institute of technology, the best engineering college in Chennai was established with the objective of providing quality technical education with adequate industrial exposure than any other engineering colleges in Chennai, caters the needs of the youth with its innovative teaching methods.

Apart from interactive classroom scenario, periodic guest lectures by experts from industries and academic background provides thirst to the students to learn and to prepare for the ready-to-serve industrial requirements with uncompromised professional ethics.

              </b>
            </p>
        </center>
        
    </body>
</html>


marina.html
------------
<html>
    <head>
        <title>
            Marina Beach
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>Marina Beach</b></h1>
            <br>
            <img src="marina.avif" width="800">
            <p style="font-size: 30;">
            
                Marina Beach, or simply the Marina, is a natural urban beach in Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from near Fort St. George in the north to Foreshore Estate in the south, a distance of 6.0 km (3.7 mi), making it the second longest urban beach in the world, after Cox's Bazar Beach. It is a prominent landmark in Chennai.
                <br>
                <br>
                The Marina is a primarily sandy beach, with an average width of 300 m (980 ft) and the width at the widest stretch is 437 m (1,434 ft). Bathing and swimming at the Marina are legally prohibited because of the dangers, as the undercurrent is very turbulent. It is one of the most crowded beaches in the country and attracts about 30,000 visitors a day during weekdays and 50,000 visitors a day during the weekends and on holidays.During summer months, about 15,000 to 20,000 people visit the beach daily.

               
            </p>
        </center>
        
    </body>
</html>


~~~

## OUTPUT



<img width="1916" height="928" alt="Screenshot 2025-12-24 105210" src="https://github.com/user-attachments/assets/298a484c-a0b8-4b79-83a9-b8ab8b77237b" />

<img width="1916" height="918" alt="Screenshot 2025-12-24 105351" src="https://github.com/user-attachments/assets/b7b74f54-a283-4850-9e6e-1302615ae17f" />

<img width="1919" height="916" alt="Screenshot 2025-12-24 105409" src="https://github.com/user-attachments/assets/75abc8ec-2ee9-426b-bc9b-adf67431d5de" />

<img width="1919" height="916" alt="Screenshot 2025-12-24 105425" src="https://github.com/user-attachments/assets/f14bf812-30a5-46dc-b6de-7dce85c252cf" />

<img width="1912" height="918" alt="Screenshot 2025-12-24 105444" src="https://github.com/user-attachments/assets/9ea187e8-93f1-4787-8b3d-24f360eb52ee" />


## RESULT
The program for implementing image maps using HTML is executed successfully.
