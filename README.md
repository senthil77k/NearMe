# Ex04 Places Around Me
## Date: 
25/03/2024

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
0.MAP
```
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Thiruvarur</b></font>
</h1>
<h3 align="center">
<font color ="blue"><b>Senthil kumaran.c (212223220103)</b></font>
</h3>
<center>
<img src="map.png" usemap="#Mycity" height="640" width="1500">
<map name="Mycity">
<area shape="rect" coords="120,200,210,240" href="Busstand.html" title="New Bus stand">
<area shape="rect" coords="250,450,400,550" href="Park.html" title="Park">
<area shape="rect" coords="800,500,900,600" href="Railway.html" title="Railway station">
<area shape="rect" coords="1050,200,1200,300" href="Theatre.html" title="Theatre">
<area shape="circle" coords="670,70,60" href="Lake.html" title="Temple Lake">
</map>
</center>
</body>
</html>
```
1.BUSSTAND
```
<html>
    <head>
        <title>Busstand</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
        <font color="red"><b>Thiruvarur</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>New Bus stand</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5" color="white">
    Thiruvarur New Bus Stand is a modern and spacious bus terminal that was inaugurated by the
     chief minister of Tamil Nadu in February 2019. It is located about 2 km away from the old bus stand 
     and the railway junction. It has 35 bus bays divided into three platforms, each serving different
    destinations. The bus stand is well connected by TNSTC and SETC buses, as well as cabs and autos. 
    It also has various facilities for the convenience of the passengers, such as booking counters,
    information centre, police cabin, pharmacy, feeding room, restrooms, and parking. The bus stand also
    has many stalls and hotels that offer food, snacks, water, and other essentials at reasonable prices.
     The bus stand is a major hub for the Cauvery Delta region, as it connects Thiruvarur with many 
     important cities and towns, such as Chennai, Trichy, Thanjavur, Kumbakonam, Nagapattinam, Velankanni,
      Salem, Coimbatore, Madurai, and Kanyakumari. Thiruvarur New Bus Stand is a symbol of the development
       and progress of the district, and a boon for the travellers and commuters

        </font>
    </p>
</html>
```
2.LAKE
```
<html>
    <head>
        <title>Temple Lake</title>
    </head>
    <body bgcolor="light blue">
    <h1 align="center">
        <font color="red"><b>Thiruvarur</b></font>
    </h1>
    <h3 align="center">
        <font color="black"><b>Temple Lake</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5" color="white">
            The Thiruvarur Thiyaagaraja Swayam Temple Lake, nestled near the sacred Thiyaagaraja Swayam Temple in Thiruvarur, Tamil Nadu, is a sublime reservoir steeped in spiritual and aesthetic significance. This picturesque lake, also known as Kamalalayam, reflects the cultural richness of the region and adds to the spiritual ambiance of the temple complex. The shimmering waters of the lake serve as a serene backdrop to the grandeur of the Thiyaagaraja Swayam Temple, creating a scene of tranquility and divine beauty. Pilgrims and visitors often find solace along the lake's shores, offering prayers and contemplating amidst the peaceful surroundings.

Kamalalayam is intricately linked to the temple's rituals and festivities, enhancing the religious experience for devotees. The lake's significance also extends beyond its spiritual role, as it plays a vital part in the conservation of water resources in the area. The well-maintained pathways around the lake invite devotees and tourists to take leisurely strolls, fostering a sense of connection with nature and divinity. The Thiruvarur Thiyaagaraja Swayam Temple Lake, with its blend of cultural, spiritual, and environmental importance, stands as a symbol of the town's rich heritage and its commitment to preserving both natural and sacred elements.




        </font>
    </p>
</html>
```
3.PARK
```
<html>
    <head>
        <title>Busstand</title>
    </head>
    <body bgcolor="purple">
    <h1 align="center">
        <font color="cyan"><b>Thiruvarur</b></font>
    </h1>
    <h3 align="center">
        <font color="lime"><b>Park</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5" color="white">
            Thiruvarur Park, nestled in the heart of the historic town of Thiruvarur in Tamil Nadu, is a serene oasis that seamlessly blends natural beauty with cultural richness. Spread across lush green acres, the park serves as a picturesque retreat for locals and tourists alike. Towering trees provide ample shade, creating a perfect setting for leisurely strolls and relaxation. The park's focal point is a tranquil pond adorned with blooming lotus flowers, adding a touch of elegance to the landscape. Visitors can enjoy the harmonious melodies of chirping birds, making it an ideal spot for nature enthusiasts.

Beyond its natural charm, Thiruvarur Park holds cultural significance with its sculptures and installations that narrate the region's rich history. Artistic depictions of classical dance forms, inspired by the famous Thyagaraja Aradhana festival held in Thiruvarur, add a cultural dimension to the park. Well-maintained walking paths lead to intricately designed gazebos, inviting visitors to pause and absorb the cultural ambiance. Families often gather for picnics, and the park becomes a hub of community activities during festive seasons. Thiruvarur Park stands as a testament to the seamless integration of nature and culture, making it a cherished destination for those seeking both tranquility and a glimpse into the vibrant heritage of the region.

    

        </font>
    </p>
</html>
```
4.RAILWAY
```
<html>
    <head>
        <title>Railway Station</title>
    </head>
    <body bgcolor="black">
    <h1 align="center">
        <font color="red"><b>Thiruvarur</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Railway station</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5" color="white">
            Thiruvarur Railway Station, a vital transport hub in the town of Thiruvarur, Tamil Nadu, serves as a gateway connecting the region to broader rail networks. This bustling station, characterized by its architectural charm, efficiently caters to the transportation needs of both locals and travelers passing through. The station's strategic location makes it a pivotal point for accessing cultural and historical sites in and around Thiruvarur. The facility is equipped with modern amenities, including waiting areas, ticketing services, and well-maintained platforms, ensuring a comfortable travel experience.

The railway station's importance extends beyond mere functionality, as it stands as a testament to the historical and economic significance of Thiruvarur. The comings and goings at the station reflect the dynamic nature of the town, with passengers representing a diverse tapestry of cultures and backgrounds. From the platforms, one can observe the ebb and flow of daily life, adding a vibrant touch to the overall atmosphere. Thiruvarur Railway Station not only facilitates seamless travel but also serves as a dynamic microcosm, capturing the essence of the town's spirit and its connections to the broader Indian rail network.


            
        </font>
    </p>
</html>
```
5.THEATRE
```
<html>
    <head>
        <title>Threatre</title>
    </head>
    <body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>Thiruvarur</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Theatre</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5" color="white">
            Thiruvarur Theatre, located in the culturally rich town of Thiruvarur in Tamil Nadu, is a vibrant hub for performing arts that resonates with the spirit of the community. This venue holds a special place in the hearts of locals, offering a platform for various forms of artistic expression, including traditional dance, music, and theatrical performances. The architecture of Thiruvarur Theatre reflects a blend of modern design and cultural aesthetics, creating an inviting space for both performers and audiences. From classical dance recitals to contemporary plays, the theater hosts a diverse range of events that cater to the eclectic tastes of its patrons. With a seating arrangement that fosters an intimate connection between performers and spectators, Thiruvarur Theatre fosters a sense of community engagement and appreciation for the arts, contributing significantly to the cultural tapestry of the region.


            
        </font>
    </p>
</html>
```

## OUTPUT

MAP
![alt text](<senthil/senthil/Screenshot 2024-03-27 150307.png>)
![alt text](<senthil/senthil/Screenshot 1.png>)
![alt text](<senthil/senthil/Screenshot 5.png>)

![alt text](<senthil/senthil/Screenshot 2.png>)
![alt text](<senthil/senthil/Screenshot 3.png>)
![alt text](<senthil/senthil/Screenshot 4.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
