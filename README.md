# Ex03 Time Table
## Date:20-04-2025

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
<!DOCTYPE html>

<head>
    <title>Slot Timetable</title>
</head>

<body>
    <!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>

<body>
    <!-- Logo or banner image -->
    <div align="center">
        <img src="/static/logo.png" width="543.49">
    </div>
    <br>

    <!-- Title -->
    <center><b>SLOT TIME TABLE - PANGA THANUJA(24900052)</b></center>

    <!-- Timetable -->
    <table border="4" bordercolor="gray" align="center" bgcolor="cyan" cellpadding="5" width="543.48">
        <tr bgcolor="yellow">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        
        <!-- 8:00 - 10:00 Slot -->
        <tr>
            <td bgcolor="yellow" align="center"><b>8-10</b></td>
            <td bgcolor="cyan" align="center">Operating System (OS)</td>
            <td bgcolor="cyan" align="center">Free Slot</td>
            <td bgcolor="cyan" align="center">Machine Learning (ML)</td>
            <td bgcolor="cyan" align="center">Operating System (OS)</td>
            <td bgcolor="cyan" align="center">Free Slot</td>
            <td bgcolor="cyan" align="center">Free Slot</td>
        </tr>

        <!-- 10:00 - 12:00 Slot -->
        <tr>
            <td bgcolor="yellow" align="center"><b>10-12</b></td>
            <td bgcolor="cyan" align="center">BEEE</td>
            <td bgcolor="cyan" align="center">MAT</td>
            <td bgcolor="cyan" align="center">Free Slot</td>
            <td bgcolor="cyan" align="center">FWAD</td>
            <td bgcolor="cyan" align="center">CHEM</td>
            <td bgcolor="cyan" align="center">C Program</td>
        </tr>

        <!-- 12:00 - 1:00 Slot (Lunch) -->
        <tr>
            <td bgcolor="yellow" align="center"><b>12-1</b></td>
            <td colspan="6" align="center" bgcolor="cyan"><b>LUNCH</b></td>
        </tr>

        <!-- 1:00 - 3:00 Slot -->
        <tr>
            <td bgcolor="yellow" align="center"><b>1-3</b></td>
            <td bgcolor="cyan" align="center">Free Slot</td>
            <td bgcolor="cyan" align="center">FWAD</td>
            <td bgcolor="cyan" align="center">Mentor Meet</td>
            <td bgcolor="cyan" align="center">C Program</td>
            <td bgcolor="cyan" align="center">MAT</td>
            <td bgcolor="cyan" align="center">Free Slot</td>
        </tr>

        <!-- 3:00 - 5:00 Slot -->
        <tr>
            <td bgcolor="yellow" align="center"><b>3-5</b></td>
            <td bgcolor="cyan" align="center">ML</td>
            <td bgcolor="cyan" align="center">Free Slot</td>
            <td bgcolor="cyan" align="center">CHEM</td>
            <td bgcolor="cyan" align="center">PROB</td>
            <td bgcolor="cyan" align="center">BEEE</td>
            <td bgcolor="cyan" align="center">PROB</td>
        </tr>

    </table>
    <br>
    </body>

   
 <!-- Subject Table -->





    <br>
    <table border="1" align="center" cellpadding="5">
        <tr bgcolor="yellow">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td bgcolor="#87CEFA"align="center">1.</td>
            <td bgcolor="#87CEFA" align="center">19AI414</td>
            <td bgcolor="#87CEFA">Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td bgcolor="#FFB6C1"align="center">2.</td>
            <td bgcolor="#FFB6C1" align="center">19CS405</td>
            <td bgcolor="#FFB6C1">Operating System (OS)</td>
        </tr>
        <tr>
            <td bgcolor="#E6E6FA"align="center">3.</td>
            <td bgcolor="#E6E6FA" align="center">19EE305</td>
            <td bgcolor="#E6E6FA">Basic Electrical, Electronics and Measurement Engineering (BEEE)</td>
        </tr>
        <tr>
            <td bgcolor="#B0E0E6"align="center">4.</td>
            <td bgcolor="#B0E0E6" align="center">19CY205</td>
            <td bgcolor="#B0E0E6">Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td bgcolor="#FFE4B5"align="center">5.</td>
            <td bgcolor="#FFE4B5" align="center">19MA201</td>
            <td bgcolor="#FFE4B5">Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td bgcolor="#ADD8E6"align="center">6.</td>
        <td bgcolor="#ADD8E6" align="center">19AI410</td>
        <td bgcolor="#ADD8E6">Introduction to Machine Learning (ML)</td>
    </tr>
    <tr>
        <td bgcolor="#98FB98"align="center">7.</td>
        <td bgcolor="#98FB98" align="center">19AI304</td>
        <td bgcolor="#98FB98">Fundamentals of C Programming</td>
    </tr>
    <tr>
        <td bgcolor="#F08080"align="center">8.</td>
        <td bgcolor="#F08080" align="center">19MA222</td>
        <td bgcolor="#F08080">Probability and Queueing Models (PROB)</td>
    </tr>
</table>
```



## OUTPUT:
![alt text](<Screenshot 2025-04-20 140115.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
