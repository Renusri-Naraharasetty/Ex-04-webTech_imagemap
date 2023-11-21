# Places Around Me
NAME : RENUSRI NARAHARASHETTY

REFERENCE NUMBER : 23009126

DEPARTMENT : ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING

# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1:
Take screenshots of places around your house using Google Maps.
## Step 2:
Identify a minimum of five different locations and mark them using image maps.
## Step 3:
Develop a webpage(minimum of 50 words) for each location and link it to the image region.
## step 4:
mention the co-ordinates and the link to be appeared when clicked.

# Code:
## map.html
```
<!DOCTYPE html>
<html>
    <body>
        <h2>IMAGE MAP</h2>
        <P>You can click on DG vaishnav college, panchali amman temple, good hope school, 
        kola perumal school and arihant panache
        to read more about the topic:</P>
        <img src="https://res.cloudinary.com/dlseemi4e/image/upload/v1700324082/image_map_zyiqed.png" 
        alt="Workplace" usemap="#workmap" width="1000" height="600">
        <map name="workmap">
            <area shape="poly" coords="1073,698,1241,841,1367,501,1107,394,980,490"  alt="college"
            href="DG.html">
            <area shape="rect" coords="980,26,797,104" alt="temple" href="temple.html">
            <area shape="rect" coords="586,363,403,486" alt="school" href="school.html">
            <area shape="circle" coords="961,138,87" alt="building" href="building.html">
            <area shape="rect" coords="1515,531,1695,723" alt="private school" href="privateschool.html">
          </map>
    </body>
</html>
```

## building.html
```
<!DOCTYPE html>
<head>
    <body>
        <h1>ARIHANT PANACHE</h1>
        <p>Arihant Panache offers a host of facilities for residents. This includes Gymnasium, Power Backup. 
            Sportsies can use Cycling & Jogging Track. There is 24x7 Security. These amenities in Arihant Panache are 
            those that every homebuyer aspires for!.
            For home loans, interested buyers can seek financing from major banks like HDFC, 
            LIC Housing Finance, Punjab National Bank .
            Arihant Foundations and Housing Ltd is a reputed building firm with 4 projects since its inception in 1995.
            Arumbakkam is well-connected to other parts of city by road, which passes through the heart of this suburb. 
            Prominent shopping malls, movie theatres, school, and hospitals are present in proximity of this residential project.</p>
    </body>
</head>
```

## dg.html
```
<!DOCTYPE html>
<head>
    <body>
        <h1>DG VAISHNAV COLLEGE</h1>
        <P>DG Vaishnav College, also known as DGVC, is a private institution situated in Chennai and was established in the year 1964. 
            DG Vaishnav College is one of the most popular colleges in Chennai that provides the best education in the state. 
            DGVC College is affiliated with the University of Madras and accredited with a grade "A++” by the NAAC (National Assessment and Accreditation Council).
            In the academic year 2009-2010, DG Vaishnav College has been conferred the status of “Autonomus” by the University Grant Commission (UGC) and endorsed by the University of Madras. 
            DG Vaishnav College was ranked 96 out of 120 in India Today Rankings 2020 and 107 out of 124 in Outlook Rankings 2020.</P>
    </body>
</head>
```

## private school.html
```
<!DOCTYPE html>
<head>
    <body>
        <h1>KOLA PERUMAL SCHOOL</h1>
        <p>The active involvement of the Sabha and the munificence of Chettigaru together triggered the starting of Kola Perumal 
            Chetty Vaishnav School on 3 July 1972 with the blessings of His Holiness 108 Goswami Shri Brijratnalalji Maharaj. 
            That day the school made a humble beginning by admitting students from LKG to V standard. Handsome donations 
            periodically by Shri Kola Perumal Chetty totalled to more than a million rupees. This and the untiring efforts of the 
            Managing body resulted in a three storey building within a year of its inception, paving the way for the steady growth of 
            the school over the years. In fact, the school came to be styled as Kola Perumal Chetty Vaishnav Senior Secondary School 
            in 1978 with the opening of Plus Two, affiliated to the Central Board of Secondary Education (CBSE), New Delhi. 
            Spacious class rooms, good furniture, well equipped laboratories, excellent playgrounds and other amenities have made 
            this Institution enviable and most sought after by the parents and students alike.</p>
    </body>
</head> 
```
## school.html
```
<!DOCTYPE html>
<head>
    <body>
        <h1>GOOD HOPE SCHOOL</h1>
        <p>Good Hope School, sponsored by the Missionary Sisters of the Immaculate Conception, 
            is a Catholic School for Girls. It provides an all-round, quality education for young ladies aged 3 to 18, 
            and aims to nurture graceful, capable and caring women leaders of the future through its teaching of Love, 
            Hope, Joy and Thanksgiving as core values.
            The School is staffed by a dedicated team of professionals, all of whom take great care to constantly 
            maintain a culture of academic excellence. They also attach great importance to enhancing all aspects of 
            the Good Hope Spirit, the outward demonstration of every student’s spiritual, moral, intellectual, physical, 
            social, emotional and aesthetic capability.
            </p>
    </body>
</head>
```

## Temple.html
```
<!DOCTYPE html>
<head>
    <body>
    <h1>PANCHALI AMMAN TEMPLE</h1>
        <p>About 120 years back, this temple was built and recently it is modified. 
            The outer premise of the temple is adorned with 14 statues of guardian angles, even the animals which had helped 
            Goddess Pachai Amman were revered in this temple. There are effigies of an elephant, five horses, and a dog. 
            It is a wide belief that even today, these animals are the watching guardians of Pachai Amman. The temples fame 
            reached all over Tamilnadu, after the visit of Sri Ramana Maharishi. He is a very prominent and peerless saint of 
            Tamilnadu, he and his followers, stayed many days at this temple and people say that he comes often to this place, 
            for taking an oil bath in the water tanks near the temple. As this temple is located amidst the dense forest, 
            many Rishis, saints, gurus, and religious persons come to this temple to do penance and gain enlightenment. 
            The water bodies near this temple are believed to have many medicinal powers and can relieve any kind of body pains.</p>
    </body>
</head>
```

# Output:
![Alt text](output.png)


# Result:
therefore, when we click a particular point on the image a webpage about the place will appear.

