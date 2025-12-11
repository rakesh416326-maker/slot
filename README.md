# Ex03 Time Table
## Date:
## ref no:25018957

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="logo.png " height="100" width="540">
    </center>
    <br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="3" bgcolor="cyan">
    <caption><b>SLOT TIME TABLE - RAKESH (25018957)</b></caption>
    <tr align="center">
    <th bgcolor="YELLOW">Day/Time</th>
    <th bgcolor="YELLOW">monday</th>
    <th bgcolor="YELLOW">tuesday</th>
    <th bgcolor="YELLOW">wednesday</th>
    <th bgcolor="YELLOW">thursday</th>
    <th bgcolor="YELLOW">friday</th>
    <th bgcolor="YELLOW">saturday</th>
    </tr>
    <tr align="center">
     <TH bgcolor="YELLOW">8-10</TH>
     <TD>PYTHON PROGRAMMING</TD>
     <TD>FREE SLOT</TD>
     <TD>FREE SOLT</TD>
     <TD>PYTHON PROGRAMMING</TD>
     <TD>PYTHON PROGRAMMING</TD>
     <TD>FREE SLOT</TD>
    </tr>
    <tr align="center">
     <TH bgcolor="YELLOW">10-12</TH>
     <TD>FUNDAMENTALS OF WEB 
        APPLICATION DEVELOPMENT</TD>
     <TD>COMMUNICATIVE ENGLISH</TD>
     <TD>FREE SLOT</TD>
     <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
     <TD>PYTHON PROGRAMMING</TD>
     <TD>FREE SLOT</TD>
    </tr>
    <tr>
        <th bgcolor="YELLOW">12-1</th>
        <td colspan="5" align="center">L U N C H</td>
    </tr>
    </tr>
    <tr align="center">
     <TH bgcolor="YELLOW">1-3</TH>
     <TD>FUNDAMENTALS OF 
        WEB APPLICATION DEVELOPMENT</TD>
     <TD>FREE SLOT</TD>
     <TD>MENTOR MEET</TD>
     <TD></TD>
     <TD>COMMUNICATIVE ENGLISH</TD>
     <TD>FREE SLOT</TD>
    </tr>
     <tr align="center">
     <TH bgcolor="YELLOW">3-5</TH>
     <TD>COMMUNICATIVE ENGLISH</TD>
     <TD>PYTHON PROGRAMMING</TD>
     <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
     <TD>COMMUNICATIVE ENGLISH</TD>
     <TD>NO CLASS</TD>
     <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    </tr>
</table><br><br>
<table align="center" width="600" border="2" cellspacing="2" cellpadding="4">
    <TR align="center"></TR>
    <th>S.No</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
    
    <tr align="center">
        <td>1.</td>
        <td>19AI301</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    </tr>
    <tr align="center">
        <td>2.</td>
        <td>19AI414</td>
        <td>PYTHON PROGRAMMING</td>
    </tr>
      <tr align="center">
        <td>3.</td>
        <td>19EN101</td>
        <td>COMMUNICATIVE ENGLISH</td>
    </tr>

</table>

</table>
</body>
</html>
```

## OUTPUT
<img width="1895" height="910" alt="image" src="https://github.com/user-attachments/assets/b94a199f-f0d0-48ab-ad64-ad2797402635" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
