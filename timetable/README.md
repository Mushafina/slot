# Ex03 Time Table
## Date:18-11-2024
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
<center>
    <img src="logo.png" height="200" width="1000">
</center>
<center>
<html>
    <body>
     <table border="5" bgcolor="cyan" cellpadding="10"> 
    <caption align="center"> R MUSHAFINA(24008061) </caption>
    <th colspan="7" align="center" bgcolor="red">SAVEETHA ENGINEERING COLLEGE </th>
     <tr>
        <th>S.NO</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
     </tr>
     <tr> 
        <td> 1</td>
        <td> -</td>
        <td> EDM</td>
        <td> EDM</td>
        <td>Calculus and matrix algebra</td>
        <td> Chemistry</td>
        <td> -</td>
     </tr>
     <tr>
        <td> 2</td> 
        <td> Web application</td>
        <td>-</td>
        <td>Web application</td>
        <td> Career development</td>
        <td>Python</td>
        <td>Public speaking</td>
     </tr>
     <tr>
        <td> 3 </td>
        <td> Calculus</td>
        <td> Chemistry</td>
        <td> mentor meeting</td>
        <td> Python</td>
        <td> Public speaking </td>
        <td> Web application</td>
     </tr>
     </table>
    </body>
</html>
<table border="2">
   <tr bgcolor="red">
       <th>S.no</th>
       <th>Couse code</th>
       <th>Course name</th>
   </tr>
   <tr bgcolor="yellow">
       <td>1</td>
       <td>19AI414</td>
       <td>FUNDAMENTALS OF WEB APPLICATION</td>
   </tr>
   <tr bgcolor="yellow">
       <td>2</td>
       <td>19MA201</td>
       <td>CALCULUS AND MATRIX ALGEBRA </td>
   </tr>
   <tr bgcolor="yellow">
       <td>3</td>
       <td>19EN105</td>
       <td>PUBLIC SPEAKING</td>
   </tr>
   <tr bgcolor="yellow">
       <td>4</td>
       <td>19AI301</td>
       <td>PYTHON PROGRAMMING</td>
   </tr>
   <tr bgcolor="yellow">
       <td>5</td>
       <td>19EY708</td>
       <td>CAREER DEVELOPMENT SKILLS</td>
   </tr>
   <tr bgcolor="yellow">
       <td>6</td>
       <td>19CY205</td>
       <td>PRINCIPLE OF CHEMISTRY IN ENGINEERING </td>
   </tr>
   <tr bgcolor="yellow">
       <td>7</td>
       <td>19AI302</td>
       <td>ENGINEERING DESIGN AND MODELLING(EDM)  </td>
   </tr>
</table>
</center>

```

## OUTPUT
[text](README.md)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
