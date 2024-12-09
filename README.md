![Screenshot 2024-12-09 065034](https://github.com/user-attachments/assets/9ce94761-f9f8-4ab7-9e2c-c317647f6a94)# Ex03 Time Table
# Date:08-12-2024
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
<html>
    <head>
        <title> TABLE </title>
        <stylE>
            .hor{writing-mode: horizontal-tb; text-align: center;}
        </stylE>
    </head>
    <body>
    <center><img src="/static/saveetha.png" width="750px"> </img></center>
    <CENTER>
        <h1> Schedule </h1>
    <table border="5pm" >
        <tr>
            <th>TIME</th>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THR</th>
            <th>FRI</th>
            <th>SAT</th>
        </tr>
        <tr>
            <th>8am to 10am</th>
            <td></td>
            <td></td>
            <td>fundamental of c</td>
            <td>physics</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <th>10am to 12am</th>
            <td>fundamental of web</td>
            <td>digital electronics</td> 
            <td>career development skills</td>
            <td>communicative english</td>
            <td></td>
            <td>physics</td>
         </tr>
         <tr>
            <th>12am to 1pm</th>
            <td class="hor" colspan="6">L   U    N    C   H</td>
        </tr>
         <tr>
            <th>1pm to 3pm</th>
            <TD>fundamental of c</TD>
            <td>communicative english</td>
            <td></td>
            <td>fundamental of web</td>
            <td>digital electronics</td>
            <td>chemistry</td>
        </tr>
        <tr>
            <th>3pm to 5pm</th>
            <td></td>
            <td></td>
            <td>chemistry</td>
            <td></td>
            <td></td>
            <td>fundamental of web</td>
        </tr>
    </table><br>
        <table border="5" >
            <tr>
                <th>sub-code</th>
                <th>sub-name</th>
    
            </tr>
            <tr>
                <th>SH3214</th>
                <td>physics for quantum computing</td>
            </tr>
            <tr>
                <th>19EE404</th>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <th>19AI414</th>
                <td>Fundamendals of Web Application Development </td>
            </tr>
            <tr>
                <th>19CY205</th>
                <td>Principles of Chemistry in Engineering</td>
            </tr>
            <tr>
                <th>19EN101</th>
                <td>Communicative English</td>
            </tr>
            <tr>
                <th>19EY708</th>
                <td>Career development skills</td>
            </tr>
            <tr>
                <th>19AI304</th>
                <td>Fundamendals of c programming</td>
            </tr>
            <tr>
                <td colspan="2">ECA-M -SCOFT - Mentor Meet</td>
            </tr>
            
        </table>
    
    </CENTER>
    </body>
    
</html>


       

```
# OUTPUT
![Uploading Screenshot 2024-12-09 065034.png…]()

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
