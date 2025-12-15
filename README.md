# Ex04 Places Around Me
## Date: 15-12-2025

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

## CODE:
~~~
map.html

<html>
    <head>
        <title>My city</title>
    </head>
    <body align="center">
        <h1 align="center"><b>Thiruvalur</b></h1>
        <h2 align="center"><b>Bhargavi S()</b></h2>
       <img src="map2.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="Thiruvallur" title="Thiruvallur" href="town.html" coords="407,419,76" shape="circle">
            <area target="" alt="Amma Park Puthur Park" title="Amma Park Puthur Park" href="park.html" coords="876,465,1102,542" shape="rect">
            <area target="" alt="SS Sports Turf Ground" title="SS Sports Turf Ground" href="ground.html" coords="1546,682,76" shape="circle">
            <area target="" alt="Arjun Powerful Gym" title="Arjun Powerful Gym" href="gym.html" coords="1437,42,1522,73,1517,127,1333,143,1305,75" shape="poly">
        </map>
    </body>
</html>

town.html

<html>
    <head>
        <title>My Town</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="magenta"><b>Thiruvallur</b></font>
        </h1>
        <h3 align="center">
            <font color="Black" size="5" face="Cooper Black"><b>My Town</b></font>
        </h3>
        <hr color="black" size="5">
        <p align="justify">
            <font face="Lucida Handwriting" size="8" color="magenta">
              Thiruvallur is a rapidly developing district and town in Tamil Nadu, near Chennai, known for its rich history, religious significance, and growing industrial importance, home to the ancient Veeraraghava Temple dedicated to Vishnu, attracting pilgrims and visitors to its cultural sites like Poondi Reservoir and Pulicat Lake. 
              The name itself stems from the Tamil phrase "Tiru evvul," referencing Lord Vishnu's sleeping posture, and the town serves as a key administrative hub with a mix of urban and rural characteristics. 
            </font>
        </p>
        <img src="mapapp/static/thiruvallur.png ">
    </body>
</html>

gym.html

<html>
    <head>
        <title>Arjun Powerful Gym</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="magenta"><b>Thiruvallur</b></font>
        </h1>
        <h3 align="center">
            <font color="Black" size="5" face="Cooper Black"><b>Arjun Powerful Gym</b></font>
        </h3>
        <hr color="black" size="5">
        <p align="justify">
            <font face="Lucida Handwriting" size="8" color="magenta">
               Arjun Powerful Gym is a well-known fitness center located in the Ramapuram area of Tiruvallur, known for offering comprehensive fitness services to both men and women.
               It provides various fitness regimens, including strengthening exercises and cardio workouts, and offers personal trainers to help members with their fitness goals and diet plans
               The gym is situated on Pannerkulam Main Road in the Kakkalur Industrial Estate, easily identifiable near Indian Furniture.
            </font>
        </p>
        <img src="mapapp/static/gym.png">
    </body>
</html>

ground.html

<html>
    <head>
        <title>SS Sports Turf</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="magenta"><b>Thiruvallur</b></font>
        </h1>
        <h3 align="center">
            <font color="Black" size="5" face="Cooper Black"><b>SS Sports Turf</b></font>
        </h3>
        <hr color="black" size="5">
        <p align="justify">
            <font face="Lucida Handwriting" size="8" color="magenta">
               SS Sports Academy in Putlur offers a dedicated space for sports, particularly cricket, with an artificial turf pitch and nets, aiming to develop skills in a structured environment, focusing on physical fitness, skill enhancement, and mental strength for athletes in the Chennai region. 
               While specific academy details are limited, it serves as a local hub for sports training with amenities like toilets, parking, and UPI payments, potentially part of a larger network of sports facilities in Tamil Nadu. 
               Facilities: Artificial turf cricket pitch, nets, toilets, free parking, UPI payments.
            </font>
        </p>
        <img src="mapapp/static/ground.png">
    </body>
</html>


park.html

<html>
    <head>
        <title>Amma Park</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="magenta"><b>Thiruvallur</b></font>
        </h1>
        <h3 align="center">
            <font color="Black" size="5" face="Cooper Black"><b>Amma Park</b></font>
        </h3>
        <hr color="black" size="5">
        <p align="justify">
            <font face="Lucida Handwriting" size="8" color="magenta">
                Amma Park in Putlur (near Tiruvallur) is a local green space offering a peaceful escape with playgrounds for kids and open areas for recreation, serving as a community hub for walks, sports (like football & badminton), and fitness, providing residents a convenient spot for relaxation and outdoor activities amidst the bustles of daily life, though some reports mention maintenance needs for lights or bins.             
Location: Found in Gomathi Nagar, Putlur, Tiruvallur district.
Features: Includes children's play areas, skating rink, and large grounds for sports like football, making it popular for families and fitness enthusiasts.
Activities: Morning walks, evening sports, kids' play, and community gatherings.
Benefit: Offers a much-needed local sanctuary for fresh air, exercise, and stress relief for people of all ages. 
Amma Park in Gomathi Nagar,Tiruvallur 
            </font>
        </p>
        <img src="mapapp/static/park2.png ">
    </body>
</html>

~~~
## OUTPUT:
![alt text](<bhargavi/mapapp/static/Screenshot (28).png>)
![alt text](<bhargavi/mapapp/static/Screenshot (30).png>)
![alt text](<bhargavi/mapapp/static/Screenshot (26).png>)
![alt text](<bhargavi/mapapp/static/Screenshot (25).png>)
![alt text](<bhargavi/mapapp/static/Screenshot (29).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
