# Ex03 Time Table
# Date:28.11.2024

# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```<!DOCTYPE html>
<html>
<head>
    <title>Time Table</title>
    <link rel="stylesheet" href="styles.css">
<style>


body {
    font-family: cursive, Helvetica, sans-serif;
    background-color: #dadada;
    margin: 0;
    padding: 0;
}

h1 {
    text-align: center;
    color: #45271f;
    font-size: 20px; 
    font-weight: 200;
}

img {
    width: 100%;
    height: auto;
    object-fit: contain;
}

.table-container {
    width: 95%;
    margin: 40px auto;
}

.timetable, .subject-list {
    width: 100%;
    font-size: 20px; 
    border:1px solid black;
}

th, td {
    border: 1px solid #0a0a0a; 
    padding: 3px; 
    text-align: center;
}

th {
    background-color: #312237;
    color: #eff2f5;
}

.highlight {
    background-color: #bebdb8;
}

.special {
    background-color: #bdb7ab;
}

</style>
</head>
<body>
    <img src="/static/sec1.jpg" width="100%" height="20%">
    <h1>SLOT TIME TABLE- RESHMITHAA B (24900030)</h1>
    <div class="table-container">
        <table class="timetable">
            <tr>
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td class="highlight"><b>8:00-10:00</b></td>
                <td>DE</td>
                <td>ENG</td>
                <td colspan="2">FREE SLOT</td>
                <td>ENG</td>
                <td>FREE SLOT</td>
            </tr>
            <tr>
                <td class="highlight"><b>10:00-12:00</b></td>
                <td>FWAD</td>
                <td>MAT</td>
                <td>CHE</td>
                <td>FREE SLOT</td>
                <td>CHE</td>
                <td>FOC</td>
            </tr>
            <tr>
                <td class="highlight"><b>12:00-1:00</b></td>
                <td colspan="6" class="special">LUNCH</td>
            </tr>
            <tr>
                <td class="highlight"><b>1:00-3:00</b></td>
                <td>FOC</td>
                <td>DE</td>
                <td>MENTOR MEET</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>MAT</td>
            </tr>
            <tr>
                <td class="highlight"><b>3:00-5:00</b></td>
                <td colspan="5">FREE SLOT</td>
                <td>FWAD</td>
            </tr>
        </table>
    </div>
    <div class="table-container">
        <table class="subject-list">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EE404</td>
                <td>Digital Electronics (DE)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI404</td>
                <td>Fundamentals of Web Application (FWAD)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI304</td>
                <td>Fundamentals of C (FOC)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EN101</td>
                <td>Communicative English (ENG)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra (MAT)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19CY205</td>
                <td>Principles of Chemistry (CHE)</td>
            </tr>
        </table>
    </div>
</body>
</html>```




# OUTPUT
![output](https://github.com/user-attachments/assets/f18feaed-13cb-4e8a-91db-51ce83a414e8)




# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
