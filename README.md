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
~~~
<!DOCTYPE html>
<html>
    <body>
        <div style="text-align: center;">
        <h1> Explore My Neighbourhood</h1>
        <h2> Please click any of the pictures in the middle to know more about it</h2>
        
            <div style="text-align: center;">
            <img src="C:\Users\admin\Downloads\landmarks.jpg" alt="Not found" class="center" usemap="#Landmark" style="width:600px;height:500px;">
            </div>
        <map name="Landmark">
            <area shape="rect" coords="16,17,394,230" title="Prestige Bella Vista" href="https://www.prestigeconstructions.com/residential-projects/chennai/prestige-bella-vista">
            <area shape="rect" coords="19,17,1125,242" title="Ramachandra Medical College" href="https://www.sriramachandra.edu.in/">
            <area shape="rect" coords="17,18,748,457" title="Iyyapathangal Bus Depot" href="https://moovitapp.com/index/en/public_transit-Iyyappanthangal_Depot-Chennai-stop_33674765-4612">
            <area shape="rect" coords="18,20,394,693" title="Reliance Smart" href="https://www.joonsquare.com/supermarket/reliance-smart-iyyappanthangal-chennai">
            <area shape="rect" coords="19,22,1125,688" title="MMS Hospital" href="https://mmshospitals.com/">

        </map>
    </div>
    </body>
</html>        
~~~
## OUTPUT


![Screenshot 2024-10-14 140037](https://github.com/user-attachments/assets/02b79245-252a-49ae-896b-aacee75b4e07)





## RESULT
The program for implementing image maps using HTML is executed successfully.
