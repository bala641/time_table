# Ex03 Time Table
## Date:21.12.24

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
    <center>
    <body>
        <img src="logo.png">

        <table border="1">
            <caption>SLOT TIMETABLE-BALA B (24900698)</caption>
            <tr bgcolor ="yellow">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="cyan">
                <td>8-10 </td>
                <td colspan="3"> Free slot</td>
                <td>EDM</td>
                <td>FWAD</td>
                <td>EDM</td>
            </tr>
            <tr bgcolor="cyan">
                <td>10-12</td>
                <td>DE</td>
                <td>MAT</td>
                <td>FUN C</td>
                <td>Career</td>
                <td>FUN C</td>
                <td>EDM</td>
            </tr>
            <tr bgcolor="cyan">
                <td>12-1</td>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr bgcolor="cyan">
                <td>1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>Mentor</td>
                <td>DE</td>
                <td colspan="2">Free slot </td>
            </tr>
            <tr bgcolor="cyan">
                <td>3-5</td>
                <td colspan="2">Free slot</td>
                <td colspan="2">Chem</td>
                <td colspan="2">Free slot</td>
            </tr>
        </table>
        <br>
        <table border="1" cellspacing="15" cellpadding="2">
        <tr>
        <th>S.NO</th>
        <th>Course Code</th>
        <th>Course Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications and Designs</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI304</td>
            <td>Fundamentals of C programming</td>
            </tr>
        <tr>
            <td>3</td>
            <td>19AI302</td>
            <td>Engineering Design and Modelling</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EY708</td>
            <td>Career Devolopment and Skills</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra </td>
        </tr>
        <tr>
            <td>6</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>7</td>
            <td>ECAM-SCOFT</td>
            <td>Mentor meet</td>
        </tr>
        </table>
        
    </body>
    </center>
</html>
```

## OUTPUT

![exp 3 slot](https://github.com/user-attachments/assets/bee5cc8c-0601-4339-8f68-04a574252f90)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

