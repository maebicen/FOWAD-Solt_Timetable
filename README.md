# Ex03 Time Table
# Date: 13 March 2025
# Name: Maebicen Kirubakar C
# Reg no: 24001839

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
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\admin\OneDrive\Pictures\Screenshots\logo.png"height="100" width="600">
</center>
<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="3" bgcolor="lightblue">
<caption><b>SLOT TIME TABLE - Maebicen Kirubakar c (24001839)</b></caption>
<tr align="center">
<th bgcolor="orange">Day/Time</th>
<th bgcolor="orange">Monday</th>
<th bgcolor="orange">Tuesday</th>
<th bgcolor="orange">Wednesday</th>
<th bgcolor="orange">Thursday</th>
<th bgcolor="orange">Friday</th>
<th bgcolor="orange">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="lightgreen">8-10</th>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
<td>Python progrmming</td>
<td>FREE SLOT</td>
<td>Computer Networks</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="lightgreen">10-12</th>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
<td>Computer Networks</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="Lightgreen">12-1</th>
<td colspan="7" align="center">L U N C H  B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="Lightgreen">1-3</th>
<td>Python programming</td>
<td>Physics for quantum computing</td>
<td>Physics for qauntum computing</td>
<td>Fundamentals of Web Application Development</td>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="Lightgreen">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="1" border="3">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center"><b><font color = blue>19AI414</font></b></td>
<td><b><font color = blue>Fundamentals of Web Application Development(FWAD)</font></b></td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center"><b><font color = blue>19AI301</font></b></td>
<td><b><font color = blue>Python Programming(Python)</font></b></td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center"><b><font color = blue>19CS406</font></b></td>
<td><b><font color = blue>Computer Networks(CN)</font></b></td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center"><b><font color = blue>19MA220</font></b></td>
<td><b><font color = blue>Mathematics for Artificial Intelligence(MATHS)</font></b></td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center"><b><font color = blue>19PH214</font></b></td>
<td><b><font color = blue>Physics for quantum computing(PQC)</font></b></td>
</tr>
</table>
</body>
</html>

```

## OUTPUT

![Screenshot (6)](https://github.com/user-attachments/assets/a9a7033b-014d-4595-8ad9-df7928c620a2)


## RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.
