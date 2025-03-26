# Ex03 Time Table
## Date:19.03.2025.

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <title>Time Table</title>

    <center>
        <img src=".ve">
        <table border="2" cellspace="3" cellpadding="4">
        <tr>
            <th bgcolor="cyan"><b>day/time</th>
            <th bgcolor="blue">Monday</th>
            <th bgcolor="blue">Tuesday</th>
            <th bgcolor="blue">Wenesday</th>
            <th bgcolor="blue">Thrusday</th>
            <th bgcolor="blue">Friday</th>
            <th bgcolor="blue">Saturday</th>

        </tr>
        <tr>
            <td bgcolor="yellow">8-10</td>
            <td  colspan="3"  bgcolor="pink"><center>Free</center></td>
            <td bgcolor="pink">Phy</td>
            <td bgcolor="pink">Che</td>
            <td bgcolor="pink">Mat</td>

        </tr>
        <tr>
            <td bgcolor="yellow">10-12</td>
            <td bgcolor="pink">Ger</td>
            <td bgcolor="pink">Free</td>
            <td bgcolor="pink">FWAD</td>
            <td bgcolor="pink">FWAD</td>
            <td bgcolor="pink">phy</td>
            <td bgcolor="pink">DE</td>
         </tr>
         <tr>
            <td bgcolor="yellow">12-1</td>
            <th colspan="7" bgcolor="pink"><center>Lunch</center></th>
         </tr>
         <tr>
            <td bgcolor="yellow">1-3</td>
            <td  colspan="2" bgcolor="pink"><center>Free</center></td>
            <td bgcolor="pink">EDM</td>
            <td bgcolor="pink">Che</td>
            <td bgcolor="pink">C PORG</td>
            <td bgcolor="pink">Python</td>

         </tr>
         <tr>
            <td bgcolor="yellow">3-5</td>
            <td  colspan="2" bgcolor="pink"><center>Free</center></td>
            <td bgcolor="pink">EDM</td>
            <td bgcolor="pink">Mat</td>
            <td bgcolor="pink">DE</td>
            <td bgcolor="pink">709</td>

         </tr>
        </table>
    </center>
    <br>
</br>
    <center>
    <table>
        <center>
            <table border="2" cellsapace="10" cellpatten="5"> 
            <tr>
                <th>s.no</th>
                <th>Subject code</th>
                <th cellspan="7">Subject Name</th>
            </tr>
            <tr>
                <td><center>1</center></td>
                <td><center>19AI304</center></td>
                <td><center>Fundamental of c programming</center></td>
            </tr>
            <tr>
                <td><center>2</center></td>
                <td><center>19AI414</center></td>
                <td><center>Fundamental of Web Application Development (FWAD)</center></td>

            </tr>
            <tr>
            <td><center>3</center></td>
            <td><center>19PY206</center></td>
            <td><center>Principal of Physics in Quantum Computing</center></td>
            </tr>
            <tr>
                <td><center>4</center></td>
                <td><center>19CY165</center></td>
                <td><center>Chemistry in Engineering</center></td>
                
            </tr>
            <tr>
                <td><center>5</center></td>
                <td><center>19AI301</center></td>
                <td><center>Python Programming</center></td>

            </tr>
            <tr>
                <td><center>6</center></td>
                <td><center>19EN106</center></td>
                <td><center>Germen Basic</center></td>
                
            </tr>
            <tr>
                <td><center>7</center></td>
                <td><center>19MA201</center></td>
                <td><center>Calculus And Matrix</center></td>

            </tr>
            <tr>
                <td><center>8</center></td>
                <td><center>19AI241</center></td>
                <td><center>Digital Electronics</center></td>

            </tr>
            </center>
            </table>
        </center>
    </table>
</body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/25b85e50-3e72-41e7-8cab-02b5c4b6eb2c)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
