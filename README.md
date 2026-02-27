# Ex03 Places Around Me
## Date: 15.02.2026

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

image_map.html

<html>
    <head>
        <title>Image map</title>
    </head>
    <body>
        <h1>CHENNAI</h1>
        <h3>SATHIYA PRIYAN(25018768)</h3>
        <img src="image 1.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="ST JOSEPH MAT HR SEC SCHOOL" title="ST JOSEPH MAT HR SEC SCHOOL" href="school.html" coords="1624,242,1406,337" shape="rect">
    <area target="_blank" alt="DOMINOS" title="DOMINOS" href="domino's.html" coords="453,396,484,520,648,497,648,430,616,405,567,385" shape="poly">
    <area target="_blank" alt="BAKERY" title="BAKERY" href="bakery.html" coords="1526,762,103" shape="circle">
    <area target="_blank" alt="INDIAN BANK" title="INDIAN BANK" href="bank.html" coords="1281,105,1108,176" shape="rect">
    <area target="_blank" alt="HOTEL" title="HOTEL" href="hotel.html" coords="900,209,81" shape="circle">
</map>
    </body>
</html>

bakery.html

<html>
    <head>
        <title>THEOBROMA BAKERY</title>
    </head>
    <body align="center" bgcolor="green">
        <h1>CHENNAI</h1>
        <h3>THEOBROMA BAKERY</h3>
        <p>Theobroma, a renowned patisserie known for premium,, high-quality, and authentic baked goods, has brought its popular offerings to Chennai and surrounding areas. Famous for its rich chocolate brownies, artisanal pastries, and decadent cakes, it serves as a go-to spot for desserts and gourmet snacks. </p>
    </body>
</html>

bank.html

<html>
    <head>
        <title>INDIAN BANK</title>
    </head>
    <body align="center" bgcolor="orange">
        <h1>CHENNAI</h1>
        <h3>INDIAN BANK</h3>
        <p>Indian Bank is a major Indian public sector bank, established on August 15, 1907, and headquartered in Chennai. Owned by the Government of India (approx. 73.84% shareholding) and under the Ministry of Finance, it operates over 5,900 branches and 5,400+ ATMs, serving over 100 million customers with a total business exceeding ₹10 lakh crore.</p>
    </body>
</html>

domino's.html

html>
    <head>
        <title>DOMINOS</title>
    </head>
    <body align="center" bgcolor="blue">
        <h1>CHENNAI</h1>
        <h3>DOMINOS</h3>
        <p>Domino's is one of the world's leading pizza restaurant chains, recognized for its delivery model and rapid growth since its inception. Founded in 1960 in Ypsilanti, Michigan, by Tom and James Monaghan, it was originally named "DomiNick's" before being rebranded to Domino's Pizza in 1965. </p>
    </body>
</html>

hotel.html

<html>
    <head>
        <title>Junior Kuppana</title>
    </head>
    <body align="center" bgcolor="violet">
        <h1>CHENNAI</h1>
        <h3>junior kuppana</h3>
        <p>juniour kupana is a nice restarurant in our town. the food in the hotel are good. </p>
    </body>
</html>

school.html

<html>
    <head>
        <title>ST JOSEPH MAT HR SEC SCHOOL</title>
    </head>
    <body align="center" bgcolor="red">
        <h1>CHENNAI</h1>
        <h3>ST JOSEPH MAT HR SEC SCHOOL</h3>
        <p>St. Joseph’s Matriculation Higher Secondary School in MaraiMalai Nagar, Chengalpattu, is a well-established co-educational institution (est. 1969/1982) managed by the Montfort Brothers of St. Gabriel. It focuses on holistic development, offering English-medium education from pre-primary to higher secondary (Grades 1-12) with a motto of "In God is our Trust". </p>
    </body>
</html>
~~~

## OUTPUT

![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (19).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
