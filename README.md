# Ex03 Time Table
# Date:02/04/2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table> `tag in html.

## STEP 4
Add header row using `<th> `tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
 
 <html>
    <head>
        <title>Table</title>
        <style>
            .hor{writing-mode: horizontal-tb;text-align: center;}
        </style>
    </head>
    <body>
        <center><img src="https://saveetha.ac.in/wp-content/uploads/2024/03/sec-logo-01as.png"width="500px">  </img>
    
    <h1>TIME TABLE</h1>
    <h2>DINESH R(24900440</h2>
    <table border="10px" style="text-align: center;">
        <tr>
            <tr>
                <th style="color:black"; bgcolor="red"; >Day & Time</th>
                <th bgcolor="green"; style="color:black"; >8-10</th>
                <th bgcolor="orange"; style="color:black";>10-12</th>
                <th bgcolor="lightblue"; style="color:black";>12-1</th>
                <th bgcolor="yellow"; style="color:black";>1-3</th>
                <th bgcolor="pink"; style="color:black";>3-5</th>
            </tr>
            <tr>
                <th style="color:black"; bgcolor="wheat";>Monday</td>
                <td style="color:black"; bgcolor="purple";>-</td>
                <td style="color:black"; bgcolor="tomato"; >Evs sh4801</td>
                <td rowspan='6'; style="color:black"; bgcolor="lavender"; >Lunch</td>
                <td style="color:black"; bgcolor="red"; >Fwa 19al414</td>
                <td style="color:black"; bgcolor="purple"; >-</td>
            </tr>
            <tr>
                <th style="color:black"; bgcolor="skyblue";>Tuesday</td>
                <td style="color:black"; bgcolor="lightgreen"; >Eng 19en101</td>
                <td style="color:black"; bgcolor="purple";>-</td>
                <td style="color:black"; bgcolor="pink"; >C Prog 19al304</td>
                <td style="color:black"; bgcolor="purple"; >-</td>
            </tr>
            <tr>
            <th style="color:black"; bgcolor="lightgreen";>Wednesday</td>
                <td style="color:black"; bgcolor="purple"; >-</td>
                <td style="color:black"; bgcolor="wheat";>Empd 19al303</td>
                <td style="color:black"; bgcolor="darkblue"; >Mentor Meet</td>
                <td style="color:black"; bgcolor="gold"; >Chem 19cy205</td>
            </tr>
            <tr>
            <th style="color:black"; bgcolor="lavender"; >Thursday</td>
                <td style="color:black"; bgcolor="lightblue";>Edm 19al302</td>
                <td style="color:black"; bgcolor="pink"; >C Prog 19al304</td>
                <td style="color:black"; bgcolor="wheat";>Empd 19al303</td>
                <td style="color:black"; bgcolor="purple"; >-</td>
             </tr>
             <tr>
                <th style="color:black"; bgcolor="tomato"; >Friday</th>
                <td style="color:black"; bgcolor="lightgreen"; >Eng 19en101</td>
                <td rowspan='2'; style="color:black"; bgcolor="red";>Fwa 19al414</td>
                <td style="color:black"; bgcolor="salmon"; >Career Dev. 19ey708</td>
                <td style="color:black"; bgcolor="purple";>-</td>
            </tr>
            <tr>
                <td style="color:black"; bgcolor="ivory";>Saturday</td>
                <td style="color:black"; bgcolor="lightblue"; >Edm 19al302</td>
                <td style="color:black"; bgcolor="gold"; >Chem 19cy205</td>
                <td style="color:black"; bgcolor="purple";>-</td>
            </tr>
            <tr>
            <th bgcolor="red">Sunday</th>
            <th bgcolor="red" colspan="6">H  O  L  I  D  A  Y</th>
            </tr>
    </table>
    <br>
</br>
        <table border="10px" style="text-align: center;">
        <tr>
            <th style="color:black";>S.no</th>
            <th style="color:black";>Subject Code</th>
            <th style="color:black";>Subject Expansion</th>
        </tr>
        <tr>
            <td style="color:black";>1</td>
            <td style="color:black";>19EN101</td>
            <td style="color:black";>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr>
            <td style="color:black";>2</td>
            <td style="color:black";>19AL302</td>
            <td style="color:black";>ENGINEERING DESIGNING AND MODELLING</td>
        </tr
        <tr>
            <td style="color:black";>3</td>
            <td style="color:black";>19AL303</td>
            <td style="color:black";>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
        </tr>
        <tr>
            <td style="color:black";>4</td>
            <td style="color:black";>19AL304</td>
            <td style="color:black";>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr>
            <td style="color:black";>5</td>
            <td style="color:black";>19CY205</td>
            <td style="color:black";>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        <tr>
            <td style="color:black";>6</td>
            <td style="color:black";>19EY708</td>
            <td style="color:black";>CAREER DEVELOPMENT SKILLS</td>
        </tr>
        <tr>
            <td style="color:black";>7</td>
            <td style="color:black";>19AL414</td>
            <td style="color:black";>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
            <td style="color:black";>8</td>
            <td style="color:black";>SH4801</td>
            <td style="color:black";>ENVIRONMENTAL SCIENCES AND SUSTAINABILITY</td>
        </tr
    </table>
</body>


    </center>
</html>

```

# OUTPUT
![Screenshot (66)](https://github.com/user-attachments/assets/ceceae09-aed1-4600-ac82-dd8294cae098)
![Screenshot (67)](https://github.com/user-attachments/assets/82290055-ae8d-46c4-9ff1-3bd12c0b72a4)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
