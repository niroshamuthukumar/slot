# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>Slot Time Table-Nirosha M(212223110032)</title>
    </head>
    <body>
        <img src="logo.png" height="100" width="870">
        <br>
        <table border="2" cellspacing="5" cellpadding="5" width="40" height="50">
            <caption><b>Slot Time Table-Nirosha M(212223110032)</b></caption>
            <tr bgcolor="yellow">
                <th>Day/Time</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>Thursday</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">8-10</td>
                <td rowspan="2" bgcolor="skyblue">FREESLOT</td>
                <td bgcolor="skyblue">DIGITAL ELECTRONICS</td>
                <td rowspan="2" bgcolor="skyblue">FREESLOT</td>
                <td bgcolor="skyblue">DIGITAL ELECTRONICS</td>
                <td bgcolor="skyblue">WEB</td>
                <td bgcolor="skyblue">PROBABILITY</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">10-12</td>
                <td bgcolor="skyblue">FREE SLOT</td>
                <td bgcolor="skyblue">PROBABILITY</td>
                <td bgcolor="skyblue">C PROGRAMMING</td>
                <td bgcolor="skyblue">TRANSFORMS</td>
            
            </tr>
            <tr align="center">   
                <td bgcolor="yellow">12-1</td>
                <td colspan='6' bgcolor="yellow">LUNCH</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">1-3</td>
                <td bgcolor="skyblue">FREE SLOT</td>
                <td bgcolor="skyblue">WEB</td>
                <td bgcolor="skyblue">FREE SLOT</td>
                <td bgcolor="skyblue">WEB</td>
                <td bgcolor="skyblue">COMPUTER NETWORK</td>
                <td colspan="2" bgcolor="skyblue">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">3-5</td>
                <td bgcolor="skyblue">C PROGRAMMING</td>
                <td bgcolor="skyblue">TRANSFORMS</td>
                <td bgcolor="skyblue">COMPUTER NETWORK</td>
                <td bgcolor="skyblue">CREATIVE SKILL</td>
                <td colspan="2" bgcolor="skyblue">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow">5-7</td>
                <td bgcolor="skyblue">EMPD</td>
                <td colspan="2" bgcolor="skyblue">FREE SLOT</td>
                <td bgcolor="skyblue">EMPD</td>
                <td colspan="2" bgcolor="skyblue">FREE SLOT</td>
            </tr>
    </body>
    <br>
    <table border="2" cellspacing="7" cellpadding="7" width="500" height="30">
        <tr>
            <th align="center" >S.No</th>
            <th align="center" >Subject code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19CS406</td>
            <td>COMPUTER NETWORKS</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19MA222</td>
            <td>PROBABILITY AND QUEUEING MODELS</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19MA219</td>
            <td>TRANSFORMSAND ITS APPLICATIONS</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19AI303</td>
            <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
        </tr>
        <tr>
            <td align="center">7.</td>
            <td align="center">19EE404</td>
            <td>DIGITAL ELECTRONICS</td>
        </tr>

    </br>
    </table>
</html>
```
## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
