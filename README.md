# Ex04 Places Around Me
## DATE: 18.11.2023
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
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Thiruttani</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>HARIHARAN J (23011967)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="600,250,700,650" href="home.html" title="MY HOME TOWN">
                <area shape="rect" coords="300,300,700,600" href="temple.html" title="The Arulmigu Subramaniya Swamy Temple">
                <area shape="rect" coords="808,398,905,434" href="hospital.html" title="Peacock Hospital">
                <area shape="rect" coords="550,100,800,800" href="railway.html" title="Thiruttani Railway Station">
                <area shape="rect" coords="290,290,700,600" href="saravana poigai.html" title="Saravana Poigai">
            </map>
        </center>
    </body>
</html>

home.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
            <font color="red"><b>Thiruttani</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Thiruttani - My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                Tiruttani is a town in the Tiruvallur district, a suburb of Chennai within the Chennai Metropolitan Area,
                located in the state of Tamil Nadu, India. The town is renowned for the Tiruttani Murugan Temple,
                which is one of the Arupadaiveedu and is dedicated to Kartikeya (Murugan). Tiruttani was added to the 
                Chennai Metropolitan Area in October 2022.It has an average elevation of 76 metres (249 ft).The name Tiruttani
                is of Tamil origin. During the formation of Andhra state on 1 November 1953, Tiruttani was part of Chittoor 
                district of Andhra Pradesh state and continued to be there until 1960. On 1 April 1960, with the Andhra Pradesh
                and Madras Alteration of Boundaries Act of 1959, Tiruttani, Pothatturpettai, Pallipattu and Ramakrishnarajapettai
                assembly areas of Andhra Pradesh are transferred to Madras state (now Tamil Nadu) in exchange for smaller area on 
                linguistic basis.


            </font>
        </p>
        </body>
        </html>

temple.html

</head>
<body bgcolor="pink">
    <h1 align="center">
        <font color="red"><b>Thiruttani</b></font>
    </h1>
    <h3 align="center">
        <font color="purple"><b>The Arulmigu Subramaniya Swamy Temple</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" sixe="5"></font>
        The Arulmigu Subramaniya Swamy Temple is a Hindu temple, on the hill of Tiruttani, Tiruvallur district, Tamil Nadu, India,
        dedicated to Murugan. The hill has 365 steps indicating 365 days of the year. It is fifth among the six abodes of Murugan 
        (Arupadai Vidu) The other five are Palani Murugan Temple, Swamimalai Murugan Temple, Thiruchendur Murugan Temple, 
        Thiruparankundram and Pazhamudircholai Murugan Temple. Tiruttani is 87 kilometres (54 mi) from Chennai. It is the only adobe 
        located within the Greater Chennai Metropolitan Area limit. During the Sangam era, Tiruttani was known as Kundruthoradal. After
        killing the asura Tarakasura in Tiruchendur, he came here to subside his anger, so Surasamharam is not conducted here.The origins 
        of this temple, are buried in antiquity. This temple has been mentioned in the Sangam period work Tirumurugatruppadai composed by 
        Nakkeerar. It has been patronized by the Vijayanagara rulers and local chieftains and zamindars. The original animal mount of Murugan
        is believed to have been an elephant, compared to the peacock which is considered to be the most common mount. The white elephant, is
        considered a powerful, terror striking animal. The iconography is maintained only in two places, namely, this temple and Tiruttani Murugan Temple.
    </font>
</p>
</body>
</html>

saravana poigai.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
            <font color="red"><b>Thiruttani</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Saravana Poigai (Tiruttani Lord Muruga Temple Theppakkulam)</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                The sacred tanks of the shrines of our Lord are all known as Saravanapoikai sacred pond of the reedy marsh where Lord Karttikeya was born. The tank at Tiruttani, which (unlike in other places) is at the very foot of the hill, is particularly renowned for its sacred water (teertham) having curative effect for ailments both bodily and mental, as it is rich in minerals such as sulfur, iron, etc. A bath in this holy tank refreshes the devotee and makes him hale and healthy to propitiate our Lord with faith and devotion.
            </font>
        </p>
    </body>
 </html>

 hospital.html

 </head>
<body bgcolor="cyeon">
    <h1 align="center">
        <font color="blue"><b>Thiruttani</b></font>
    </h1>
    <h3 align="center">
        <font color="red"><b>Peacock Hospital</b></font>
    </h3>
    <hr size="3" color="yellow">
    <p align="justify">
        <font face="Georgia" sixe="5"></font>
        It is the only big hospital in a small town, catering to not only to the resident people but also
        to the people from  the  surrounding villages and other nearby towns such as Tiruvallur, Arakkonam,
        Sholingur and Nagari. The townspeople know us for the quality of our services, for our sensitives,
        and for our ethical high standards.Before the hospital came up in 2017, its people had to travel to
        Chennai and other big cities for treatment. Now, however, the best of the benefits of city hospitals
        are available in the neighbourhood.It is a 100-bedded hospital on a 50,000 sq.ft campus. It has a 
        built up area of 40,000 sq.ft that houses high-end diagnostic and treatment facilities, including 
        hitech labs, MRI, CT scan and dialysis stations, CSSDs, high-tech OTs, ICUs and special labour rooms.
        The building also has an emergency hall; consulting rooms; waiting areas for patients and their caretakers;
        and patient wards, both general and private.The entire building is connected through ramps and bed lifts to
        aid fast and  smooth patient transfers. Also on the campus, there is a car park that can accommodate up to 30 cars
         and 150 two wheelers. Besides, the hospital has its own water and power management plants, fire fighting unit, and
          facelities for effluent and waste management.
        </font>
    </p>
</body>
</html>

railway.html

</head>
<body bgcolor="orange">
    <h1 align="center">
        <font color="yellow"><b>Thiruttani</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Thiruttani Railway Station</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="white" sixe="5"></font>
        Tiruttani Railway station is in Thiruvallur district making it an important 
        railway station in the Indian state of Tamil Nadu. The station code name of
        Tiruttani is TRT. As part of one of the busiest and populated Indian states,
        Tamil Nadu, the Tiruttani railway station is known amongst the top hundred train
        ticket booking and train traveling stations of the Indian Railway. The total number
        of trains that pass through Tiruttani (TRT) junction is 76.
    </font>
</p>
</body>
</html>

```

## OUTPUT
![1](https://github.com/HariharanJayavel/NearMe/assets/144870546/714f4464-aff4-4314-9755-9f459aa83b43)
![home](https://github.com/HariharanJayavel/NearMe/assets/144870546/effa7335-f662-4e8f-8cf7-cec3918f257e)
![templ](https://github.com/HariharanJayavel/NearMe/assets/144870546/4b81147b-6249-495e-b6e8-a24969aac95c)
![saravana poigai](https://github.com/HariharanJayavel/NearMe/assets/144870546/145e8ed2-e3a9-4511-99da-ea58902d1226)
![hospital](https://github.com/HariharanJayavel/NearMe/assets/144870546/f30bc053-b1f7-4b7c-8542-7d9e536b8cc9)
![rail](https://github.com/HariharanJayavel/NearMe/assets/144870546/507ebfe0-3689-4dac-8673-cfbaebb266e5)

## RESULT
The program for implementing image maps using HTML is executed successfully.
