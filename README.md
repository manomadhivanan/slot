# Ex03 Time Table
## Date:15/03/2024

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
    <title>SEC SLOT TIMETABLE</title>
</head>
<center>
<img src="/static/logo.png" width='600'align="center">
</center>
<body>
    <table BORDER='3' width='600'bgcolor='white' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE- MANO M (212221040100)</CAPTION>
        <tr>
            <th align="center" bgcolor="red">Day/Time</th>
            <th align="center" bgcolor="red">Monday</th>
            <th align="center" bgcolor="red">Tuesday</th>
            <th align="center" bgcolor="red">Wednesday</th>
            <th align="center" bgcolor="red">Thursday</th>
            <th align="center" bgcolor="red">Friday</th>
            <th align="center" bgcolor="red">Saturday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">8-10</th>
            <td align="center" bgcolor="lightgreen" colspan="2">Calculus and matrix algebra</td>
            <td align="center" bgcolor="lightgreen">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightgreen">Free slot</td>
            <td align="center" bgcolor="lightgreen">Algebra and number theory</td>
            <td align="center" bgcolor="lightgreen">Compiler design</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">10-12</th>
            <td align="center" bgcolor="lightgreen">Creative Skills</td>
            <td align="center" bgcolor="lightgreen">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightgreen">Free slot</td>
            <td align="center" bgcolor="lightgreen">Free slot</td>
            <td align="center" bgcolor="lightgreen">Java programming</td>
            <td align="center" bgcolor="lightgreen">Free slot</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">12-1</th>
            <td align="center" bgcolor="lightgreen" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">1-3</th>
            <td align="center" bgcolor="lightgreen">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightgreen">Physics</td>
            <td align="center" bgcolor="lightgreen">Java programming</td>
            <td align="center" bgcolor="lightgreen">Algebra and number theory</td>
            <td align="center" bgcolor="lightgreen">Compiler design</td>
            <td align="center" bgcolor="lightgreen">Free slot</td>
        </tr>


        <tr>
            <th align="center" bgcolor="yellow">3-5</th>
            <td align="center" bgcolor="lightgreen">Microprocessor and microcontroller</td>
            <td align="center" bgcolor="lightgreen">Free Slot</td>
            <td align="center" bgcolor="lightgreen">Compiler design</td>
            <td align="center" bgcolor="lightgreen">Java Programming</td>
            <td align="center" bgcolor="lightgreen" >Free slot</td>
            <td align="center" bgcolor="lightgreen" >physics</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3" align="center">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19MA201</td>
            <td align="center">Calculus and matrix algebra</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19MA203</td>
            <td align="center">Algebra and number theory</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19CS412</td>
            <td align="center">Compiler design</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19PY205</td>
            <td align="center">Physics</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19EC308</td>
            <td align="center">Microprocessor and microcontroller</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19CS403</td>
            <td align="center">Java programming</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19</td>
            <td align="center">Creative Skills</td>
        </tr>
    </body>
    </html>
```

## OUTPUT
![alt text](<ex 3 web.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
