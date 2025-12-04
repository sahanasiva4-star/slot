# Ex03 Time Table
## Date:26.11.2025
REFERENCE NO: 25013621

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
~~~
!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body bgcolor="white">

<center>
    <h2>Slot Timetable</h2>

    <!-- Logo image -->
    <img src="/static/logo.png" alt="College Logo" height="100" width="540">

    <br><br>

    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
        <caption>
            <b>SLOT TIME TABLE : DEEPTIKA S (22008367)</b>
        </caption>

        <!-- Row 1 – Days Header -->
        <tr align="center">
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>

        <!-- Row 2 – Slot 1 -->
        <tr align="center">
            <th bgcolor="yellow">8–10</th>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PHYSICS FOR QUANTUM COMPUTATION</td>
            <td>STATISTICS AND NUMERICAL METHODS</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>

        <!-- Row 3 – Slot 2 -->
        <tr align="center">
            <th bgcolor="yellow">10–12</th>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            <td>FREE SLOT</td>
            <td>STATISTICS AND NUMERICAL METHODS</td>
        </tr>

        <!-- Row 4 – Slot 3 -->
        <tr align="center">
            <th bgcolor="yellow">12–1</th>
            <td colspan="5" bgcolor="lightgreen"><b>LUNCH BREAK</b></td>
        </tr>

        <!-- Row 5 – Slot 4 -->
        <tr align="center">
            <th bgcolor="yellow">1–3</th>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>PHYSICS FOR QUANTUM COMPUTATION</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>

    </table>
</center>

</body>
</html>
~~~

## OUTPUT
<img width="1866" height="759" alt="image" src="https://github.com/user-attachments/assets/f8db708e-7f25-4d8c-b81c-e11c31acd422" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
