
# Date:21-11-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Time Table</title>
    <style>
        body {
            font-family: Georgia, serif;
            background-color: #faf3e8;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #7a0000;
            font-size: 28px;
            margin-bottom: 20px;
            text-decoration: underline;
        }
        table {
            width: 90%;
            margin: auto;
            border-collapse: collapse;
            background-color: #f6e1cd;
        }
        th, td {
            border: 2px solid #7a0000;
            padding: 12px;
            text-align: center;
            font-size: 17px;
        }
        th {
            background-color: #e4b48b;
        }
        .vertical-text {
            writing-mode: vertical-rl;
            transform: rotate(180deg);
            font-weight: bold;
            text-align: center;
        }
    </style>
</head>
<body>
<div style="zoom:0.75;">

<center>
<img src="/static/SEClogo.png" width="540">
</center>


    <h2>TimeTable [LEKHA SHREE R D-25012947]</h2>

    <table>
        <tr>
            <th>DAY/TIME</th>
            <th>8am - 10am</th>
            <th>10am - 12pm</th>
            <th class="vertical-text" rowspan="7">LUNCH</th>
            <th>1pm - 3pm</th>
            <th>3pm - 5pm</th>
        </tr>

        <tr>
            <td>Monday</td>
            <td colspan="2">FREE SLOT</td>
            <td colspan="2">Python</td>
        </tr>

        <tr>
            <td>Tuesday</td>
            <td>FREE SLOT</td>
            <td>Communicative English</td>
            <td>Fundamentals of Web Application Development</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <td>Wednesday</td>
            <td>FREE SLOT</td>
            <td>Fundamentals of Web Application Development</td>
            <td>Mentor Meeting</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <td>Thursday</td>
            <td>Python Programming</td>
            <td>Communicative English</td>
            <td>Communicative English</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <td>Friday</td>
            <td>FREE SLOT</td>
            <td>Fundamentals of Web Application Development</td>
            <td>FREE SLOT</td>
            <td>Python Programming</td>
        </tr>

        <tr>
            <td>Saturday</td>
            <td colspan="2">Fundamentals of Web Application Development</td>
            <td>Python Programming</td>
            <td>Communicative English</td>
        </tr>

    </table>

    <br><br>

    <table style="width:50%; background-color:#f6e1cd;">
        <tr>
            <th>S.NO</th>
            <th>Course Code</th>
            <th>Course Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI301</td>
            <td>Python Programming</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
    </table>
</div>
</body>
</html>
```
# OUTPUT
<img width="1920" height="1080" alt="EX 03 WEB" src="https://github.com/user-attachments/assets/ed3b5ac8-93d8-4c83-8fe9-0603f7aa856c" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
