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
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="magenda"><b>Nellore</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Narendra</b> (212221040117)</b></font>
        </h3>
        <center>
            
<map name="MyCity">
    <area shape="rect" coords="100,100,900,900" href="expmap.html" title="My Home Town"</map>
    

    <img src="Screenshot (25).png" usemap="#image-map">

<map name="image-map">
    <map name="image-map">    
    
            <area target="_blank" alt="Kovur" title="Kovur" href="kovur.html" coords="622,18,707,52" shape="rect">
            <area target="_blank" alt="Narasimhakonda" title="Narasimhakonda" href="Narasimhakonda.html" coords="107,206,252,246" shape="rect">
            <area target="_blank" alt="Mulumudi" title="Mulumudi" href=".html" coords="Mulumudi.html" coords="43,264,138,297" shape="rect">
            <area target="_blank" alt="Allipuram" title="Allipuram" href="Allipuram.html" coords="868,243,954,274" shape="rect">     
    </map>
</map>
        </center>
    </body>

</html>
```
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>Nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Mulumudi</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            According to Census 2011 information the location code or village code of Mulumudi village is 592089. Mulumudi village is located in Nellore mandal of Sri Potti Sriramulu Nellore district in Andhra Pradesh, India. 
        </font>
        </p>
    </body>
</html>
```

## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
