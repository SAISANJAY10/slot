# Ex03 Time Table
## Date:18/03/2024

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
   <head>
       <title> TIME TABLE </title>
   </head>
 <body align="center">
 <table border="6" cellspacing="8" cellpadding="10" align="center" bgcolor="CYAN">
<img src="logo.png" align="center" height="70" width="800">
<caption><b>SLOT TIMETABLE- SAI SANJAY R(23013189)</b></caption>

   <tr>
        <th bgcolor="red">Day/Time</th>
        <th bgcolor="red">Monday</th>
        <th bgcolor="red">Tuesday</th>
        <th bgcolor="red">Wednesday</th>
        <th bgcolor="red">Thursday</th>
        <th bgcolor="red">Friday</th>
  </tr>
  <tr>
        <th bgcolor="red">8-10</th>
        <td>LC</td>
        <td>Advance C</td>
        <td>FWAD</t>
        <td>LC</td>
        <td>CN</td>
 </tr>
 <tr>
        <th bgcolor="red">10-12</th>
        <td>Free Slot</td>
        <td>FWAD</td>
        <td>CN</t>
        <td>Advance C</td>
        <td>DE</td>
 </tr>
 <tr> 
        <th bgcolor="red">12-1</th>
        <TD colspan="5" Align="center"><B>L U N C H </B></TD> </tr>
 <tr>
        <th bgcolor="red">1-3</th>
        <td>FWAD</td>
        <td>DE</td>
        <td>CSC</t>
        <td>EDM</td>
        <td>Free Slot</td>
 </tr>
 <tr>
        <th bgcolor="red">3-5</th>
        <td>Free Slot</td>
        <td>EDM</td>
        <td>Free Slot</t>
        <td>Free Slot</td>
        <td>Free Slot</td>
</tr>
</body>
</html>
<table cellspacing="8" cellpadding="0" align="center">
<html>
<head>
    <title> subject code </title>
</head>
 <body>
 <table border="6" cellspacing="8" cellpadding="10" align="center">

<tr> 
        <th>S.NO</th>
        <th>Subject Code</th>
        <th>Subject</th>
</tr>        
<tr>
     <td>1</td>
     <td>19AI414</td>
     <td>Fundamentals of Web Application Development(FWAD)</td>
</tr>    
<tr>
     <td>2</td>
     <td>19AI305</td>
     <td>Advanced C Programming(Advance C)</td>
</tr> 
<tr>
     <td>3</td>
     <td>19AI302</td>
     <td>Engineering Design and Modelling(EDM)</td>
</tr>     
<tr>
     <td>4</td>
     <td>19CS406</td>
     <td>Computer Networks(CN)</td>
</tr>   
<tr>
     <td>5</td>
     <td>19MA206</td>
     <td>Logic and combinatorics(LC)</td>
</tr>  
<tr>
     <td>6</td>
     <td>19EY702</td>
     <td>Creative Skills For Communication(CSC)</td>
</tr>  
<tr>
     <td>7</td>
     <td>19EE404</td>
     <td>Digital Electronics(DE)</td>
</tr>    
</body>
</html>
            

            
```


## OUTPUT
![alt text](<Screenshot 2024-03-20 090639.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
