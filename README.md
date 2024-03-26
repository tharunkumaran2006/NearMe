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
### kos.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAP</title>
</head>
<center>
<body bgcolor="grey">
    <h1>ARANI-TOWNMAP</h1>
    <h2>THARUN V K(212223230231)</h2>
    <img src="Screenshot 2024-03-21 141659.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="Old Bus Stand" title="Old Bus Stand" href="bus.html" coords="740,274,591,226" shape="rect">
        <area target="" alt="Suriya Lake" title="Suriya Lake" href="lake.html" coords="637,379,686,413" shape="rect">
        <area target="" alt="Lakshmi Theatre" title="Lakshmi Theatre" href="theatre.html" coords="696,338,16" shape="circle">
        <area target="" alt="Home" title="Home" href="home.html" coords="462,377,4" shape="circle">
        <area target="" alt="GK Hospital" title="GK Hospital" href="clinic.html" coords="687,183,37" shape="circle">
    </map>
</body>
</center>
</html>
```
### bus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Old Bus Stand</title>
</head>
<body bgcolor="violet">
    <center>
    <h1>ARANI</h1>
    <h2>OLD BUS STAND</h2>
    <hr>
    </center>
    <h3>1.The old bus stand located in arani is heart of the town arani and the new bus stand also located near to it.</h3>
    <h3>2.Thera are two bus stands in Arani. So it is easier to the people of Arani to travel through the buses.The atmosphere at the old bus stand is often bustling with activity, especially during peak hours when buses arrive and depart frequently.<h3>
    <h3>3.It's a place where locals gather, vendors sell their goods, and travelers embark on their journeys.The old bus stand is nearly 1.5 km away from the new bus stand.</h3>
</body>

</html>
```
### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
</head>
<body bgcolor="yellow">
    <center>
        <h1>ARANI</h1>
        <h2> MY HOME</h2>
        <hr>
    </center>
    <h3>1.My home is located at the area called saidapet ,pichandi nagar, which is very peacefull area. My home is fully surrounded of shops, hotels, beach, malls and so on.</h3>
    <h3>2.Nestled within the vibrant community of Arani, my home stands as a beacon of comfort and familiarity. Situated on a peaceful street just a stone's throw away from the bustling town center, it enjoys the perfect balance between serenity and convenience.</h3>
</body>
</html>
```
### clinic.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>G K hospital</title>
</head>
<body bgcolor="chartreuse">
    <center>
        <h1>ARANI</h1>
        <h2>G K HOSPITAL</h2>
        <hr>
    </center>
    <h3>1.The G K Hospital is situated at the heart of the town, Town General Hospital stands as a beacon of healthcare accessibility for the local community and surrounding areas.</h3>
    <h3>2.The hospital boasts a modern yet welcoming architectural design, with clean lines and ample natural light streaming through large windows. Its exterior is adorned with well-maintained gardens and greenery, offering a serene ambiance amidst the urban bustle.</h3>
    <h3>3.Town General Hospital stands as a pillar of healthcare excellence, providing comprehensive medical services with a focus on compassion, innovation, and community partnership.</h3>
</body>
</html>
```
### theatre.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>theatre</title>
</head>
<body bgcolor="cyan">
    <center>
        <h1>ARANI</h1>
        <h2>LAKSHMI THEATRE</h2>
        <hr>
    </center>
    <h3>1.Nestled in the heart of Arani, amidst the vibrant pulse of the town, lies the beloved Arani Lakshmi Theatre, a cultural gem and hub of entertainment for the community.</h3>
    <h3>2.Lakshmi theatre is situated on a bustling street corner, its marquee adorned with neon lights announces the latest shows and screenings, beckoning passersby to indulge in the magic of cinema.</h3>
    <h3>3.As you approach, the grand façade of the theater captivates with its classic architecture and ornate details. Tall columns flank the entrance, evoking a sense of grandeur and sophistication, hinting at the rich history and cultural significance of the venue.</h3>
</body>
</html>
```
### lake.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lake</title>
</head>
<body bgcolor="coral">
    <center>
        <h1>ARANI</h1>
        <h2>SURIYA LAKE</h2>
        <hr>
    </center>
    <h3>1.Nestled within the heart of the town lies the serene and picturesque Suriya Lake, a shimmering jewel amidst the urban landscape. Surrounded by lush greenery and dotted with swaying trees, it serves as a tranquil retreat for both locals and visitors alike.</h3>
    <h3>2.Boating enthusiasts can indulge in leisurely rides across the lake's surface, while avid anglers find solace in casting their lines amidst the tranquil surroundings.</h3>
    <h3>3.Adjacent to the Suriya Lake stands the iconic MC Theatre, a beloved landmark that has been a cornerstone of entertainment in the town for generations</h3>

</body>
</html>
```
## OUTPUT
![Screenshot 2024-03-25 175432](https://github.com/tharunkumaran2006/NearMe/assets/151625188/4470c1d5-1077-449f-afab-a98800dd6252)

![Screenshot 2024-03-25 175812](https://github.com/tharunkumaran2006/NearMe/assets/151625188/2e7a70c8-5a0a-4e36-940a-6c19f36fcd33)

![Screenshot 2024-03-25 175940](https://github.com/tharunkumaran2006/NearMe/assets/151625188/9cba4d24-cb1e-4099-93bf-efac10b33fa7)

![Screenshot 2024-03-25 175915](https://github.com/tharunkumaran2006/NearMe/assets/151625188/983a6442-e92a-411f-a73f-9ea743422b5b)

![Screenshot 2024-03-25 175903](https://github.com/tharunkumaran2006/NearMe/assets/151625188/83aa2afa-fa69-4be6-8e38-1539fa5e5368)

![Screenshot 2024-03-25 175925](https://github.com/tharunkumaran2006/NearMe/assets/151625188/be81c074-4b54-44dc-a841-3054dc268893)



## RESULT
The program for implementing image maps using HTML is executed successfully.
