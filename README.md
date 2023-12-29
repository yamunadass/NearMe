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
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>YAMUNA M (212223230248)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="1115,353,1289,457" href="home.html" title="My Home Town">  
<area shape="circle" coords="1041,565,54" href="hotel.html" title="Devi hotel">
<area shape="circle" coords="1373,519,66" href="beach.html" title="Silver beach">
<area shape="circle" coords="1231,606,68" href="college.html" title="Ck college">
<area shape="rect" coords="731,353,867,419" href="temple.html" title="Tirupathiripuliyur temple">
</map>
</center>
</body>
</html>

beach.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="voilet">
<h1 align="center"> 
<font color="brown"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Silver Beach</b></font>
</h3>
<hr size="3" color="orange">
<p align="justify">
</html>
<font face="Georgia" size="5">
Silver Beach is a beach on the southeast coast of India. It is located 2 km (1.2 mi) from 
downtown Cuddalore, the headquarters of Cuddalore district in the state of Tamil Nadu. Silver Beach, 
however, is untouched by the busy life of the city. It is the second longest beach on the Coromandel 
Coast and one of the longest beaches in Asia. The 57 km-long stretch of beach faces severe seafront erosion. 
There are town buses which ply frequently between Cuddalore town bus stand and Silver Beach. 
It is also accessible via Taxis and Autos from different parts of the town. To the south of the beach 
the South Cuddalore Bay area appears as if it is a separate island. The backwater separating the main beach 
from the island-like structure is a safe place for water sports. Boats are not available for rent 
currently as the boat house has been closed. </font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="white">
<h1 align="center"> 
<font color="red"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CK college</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
A CK college is an educational institution or a constituent part of one.
A CK college may be a degree-awarding tertiary educational institution, a part of a collegiate or
federal university, an institution offering vocational education, a further education institution,
or a secondary school.In most of the world, a college may be a high school or secondary school, a
college of further education, a training institution that awards trade qualifications, a higher-education
provider that does not have university status (often without its own degree-awarding powers), or
a constituent part of a university.</font>
</p>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center"> 
<font color="red"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="voilet"><b>Home Town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
Cuddalore, also spelt as Kadalur, is the city and headquarters of the Cuddalore District in 
the Indian state of Tamil Nadu. Situated south of Chennai, Cuddalore was an important city and port 
during the British Raj.While the early history of Cuddalore remains unclear, the city first 
rose to prominence during Pallavas and Medieval Cholas' reign. After the fall of Cholas, the town was 
ruled by various dynasties like Pandyas, Vijayanagar Empire, Madurai Nayaks, Thanjavur Nayaks, 
Thanjavur Marathas, Tipu Sultan, French and the British Empire. Cuddalore was the scene of the Seven Years' 
War and the Battle of Cuddalore in 1758 between the French and British. It has been a part of 
independent India since 1947. During the 2004 Indian Ocean earthquake, and the subsequent tsunamis generated, 
Cuddalore was one of the affected towns, with 572 casualties.</font>
</p>
</body>
</html>

hotel.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center"> 
<font color="red"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Devi hotel</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
A Devi hotel is an establishment that provides paid lodging on a short-term basis. 
Facilities provided inside a hotel room may range from a modest-quality mattress in a 
small room to large suites with bigger, higher-quality beds, a dresser, a refrigerator, and 
other kitchen facilities, upholstered chairs, a flat-screen television, and en-suite bathrooms. 
Small, lower-priced hotels may offer only the most basic guest services and facilities. Larger, 
higher-priced hotels may provide additional guest facilities such as a swimming pool,
a business center with computers, printers, and other office equipment, childcare, conference 
and event facilities, tennis or basketball courts, gymnasium, restaurants, day spa, and social function
services. Hotel rooms are usually numbered (or named in some smaller hotels and B&Bs) to allow 
guests to identify their room. Some boutique, high-end hotels have custom decorated rooms. Some hotels 
offer meals as part of a room and board arrangement. In Japan, capsule hotels provide a tiny room suitable 
only for sleeping and shared bathroom facilities.</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center"> 
<font color="yellow"><b>Cuddalore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Tirupathiripuliyur temple</b></font>
</h3>
<hr size="3" color="grenn">
<p align="justify">
</html>
<font face="Georgia" size="5">
Pataleeswarar Temple is a Hindu shrine dedicated to Shiva in the town of Thirupathiripuliyur, Cuddalore.
It was constructed during the Pallava and Medieval Chola periods.The Saivite saint Appar is believed to have 
adopted Saivism at this temple. It is one of the shrines of the 275 Paadal Petra Sthalams. 
There is a belief/myth that by worshiping this God a single time is equal to 16 times worshiping the Shiva in Kasi, 
eight times in Thiruvannamalai, and three times in Chidambaram.Thirupathiripuliyur in Cuddalore is one of the ancient
temples in Tamil Nadu. It is named after the Pathiri Tree and the Puliyur, a tiger-legged saint who obtained absolution in the area.
The temple has a large temple car called Theeruvadaichan, a silver chariot and a golden chariot.</font>
</p>
</body>
</html>


```
## OUTPUT

![Screenshot 2023-12-29 192035](https://github.com/yamunadass/NearMe/assets/138971172/498884f4-a413-4fd5-ae4b-328ae9cfa648)
![Screenshot 2023-12-29 192238](https://github.com/yamunadass/NearMe/assets/138971172/81799b22-4315-4a7d-8c09-dae11a055d3e)
![Screenshot 2023-12-29 192421](https://github.com/yamunadass/NearMe/assets/138971172/859ead68-d4d6-4208-9cf0-df2541e4e994)
![Screenshot 2023-12-29 192522](https://github.com/yamunadass/NearMe/assets/138971172/c2135127-b6d3-4295-8dec-169d6293d1df)
![Screenshot 2023-12-29 192635](https://github.com/yamunadass/NearMe/assets/138971172/9ac4fd38-d5ff-44ef-8248-8092967711da)
![Screenshot 2023-12-29 192734](https://github.com/yamunadass/NearMe/assets/138971172/cf6b0766-0e4d-4247-b1fc-7e91d08035fc)
## RESULT
The program for implementing image maps using HTML is executed successfully.
