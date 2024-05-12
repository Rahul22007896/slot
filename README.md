# Ex03 Time Table
## Date:14-03-2024

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
<body>
<center>
<img src="/static/logo.png"height="100"width="540">
</center>
<br>
<table align="center" width="1000" border="5" bgcolor="Lavender" cellspacing="12" cellpadding="12">
<caption><b>SLOT TIME TABLE - Rahul K (212221043006)</b></caption>

<tr bgcolor="CornflowerRed">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="CornflowerRed"> 8-10 </th>
   <td bgcolor="red"><b> Fundamentals Of Web Development Application</b></td>
   <td> Free Slot </td>
   <td bgcolor="lightgreen"><b>Problem sloving And Python Programming</b></td>
   <td> Free Slot </td>
   <td> Free Slot </td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="CornflowerRed"> 10-12 </th>
    <td> Free Slot</td>
    <td bgcolor="yellow"><b>Parallel Computing Architecture</b></td>
    <td bgcolor="yellow"><b>Parallel Computing Architecture</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td bgcolor="grey"><b>Programming in C</b></td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 12-1 </th>
    <th colspan="1">LUNCH</th>
    <th bgcolor="white" colspan="1">MENTOR MEET</th>
    <td colspan="6" align="center"><b>LUNCH</b></td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 1-3 </th>
    <td > Free SLOT </td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b> </td>
    <td bgcolor="grey"><b> Programming in C</b> </td>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="pink"><b>Advanced Quantitative and Logical Reasoning</b> </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 3-5 </th>
    <td> Free Slot </td>
    <td bgcolor="lightgreen"><b>Problem Solving and Python Programming</b></td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>
</tr>
</table>
<br>
<br>
<table align="center" border="8" cellspacing="12" cellpadding="12">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td bgcolor="lightgreen"> 1. </td>
<td bgcolor="lightgreen"> 19CS301 </td>
<td bgcolor="lightgreen"> Problem Solving and Python Programming </td>
</tr>
<tr align="center">
<td bgcolor="red"> 2. </td>
<td bgcolor="red"> 19AI414 </td>
<td bgcolor="red"> Fundamentals of Web Application Development </td>
</tr>
<tr align="center">
<td bgcolor="grey"> 3. </td>
<td bgcolor="grey"> 19CS302 </td>
<td bgcolor="grey"> Programming in C </td>
</tr>
<tr align="center">
<td bgcolor="yellow"> 4. </td>
<td bgcolor="yellow"> 19AI407 </td>
<td bgcolor="yellow"> Parallel Computing Arhitecture </td>
</tr>
<tr align="center">
<td bgcolor="purple"> 5. </td>
<td bgcolor="purple"> 19ME531 </td>
<td bgcolor="purple"> Intellectual Property Rights </td>
</tr>
<tr align="center">
<td bgcolor="pink"> 6. </td>
<td bgcolor="pink"> 19EY704 </td>
<td bgcolor="pink"> Advanced Quantitative and Logical Reasoning  </td>
</tr>
</html>
```

## OUTPUT
![alt text](<Screenshot (2).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
