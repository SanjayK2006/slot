# Ex04 Time Table
## Date: 11-11-2024
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
<html>
<head>
    <title>SLOT TIME TABLE - 212223220094 SANJAY K</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="saveetha.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - SANJAY K 212223220094</strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="3" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">TOC</th>
            <th colspan="1" bgcolor="Cyan">CD</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">CN</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">TOC</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">QA</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">3-5</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">CN</th>
            <th colspan="1" bgcolor="Cyan">CD</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI41</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19CS406</th>
            <th colspan="2" bgcolor="White">Computer Network (CN)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19CS407</th>
            <th colspan="2" bgcolor="White">Theory of Computation (TOC)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19CS409</th>
            <th colspan="2" bgcolor="White">Compiler Design (CD)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19MA222</th>
            <th colspan="2" bgcolor="White">Probability And Queueing Models (MAT)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19EY710</th>
            <th colspan="2" bgcolor="White">Quantitative Ability (QA)</th> 
        </tr>
    </table>
</body>
</html>
```
## OUTPUT

![Screenshot (73)](https://github.com/user-attachments/assets/8f35921f-168b-4699-be80-411f07501410)

## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.
