# Ex03 Time Table

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

## CODE
```
<html>
<head>
<title>Project Exhibition Schedule</title>
</head>
<body bgcolor="skyblue">

<h3>Project Exhibition Schedule</h3>
<TABLE BORDER="5" width="550" cellspacing="5" cellpadding="5" Align="center" bgcolor="white"> 
<TR bgcolor="lightgreen" > 
	<TH colspan="2" width="40%" ><h3><b>Reg. No.: 212221040044 </b></h3></TH> 
	<TH colspan="3" width="60%" ><h3><b>Name: DIVYASHREE B S </b></h3></TH>
</TR>   

<TR Align="center" bgcolor="violet"> 
	<TD width="10%" ><b>S.No.</b></TD>
	<TD width="20%"><b>Date</b></TD> 
	<TD ><b>Session</b></TD>
	<TD ><b>Topics</b></TD>
	<TD ><b>Language Used</b></TD>
</TR>
<TR>
	<TD >1</TD> 
	<TD rowspan="3">23.June.23</TD>
	<TD >8-11am</TD>
	<TD >Project-1</TD>
	<TD rowspan="2" >Python</TD>
</TR>
<TR>
	<TD >2</TD> 
	<TD >11-2pm</TD>
	<TD >Project-2</TD>
</TR>
<TR>
	<TD >3</TD> 
	<TD >2-5pm</TD>
	<TD >Project-3</TD>
	<TD> C</TD>
</TR>
<TR>
	<TD >4</TD> 
	<TD rowspan="2">24.June.23</TD>
	<TD >10-1pm</TD>
	<TD >Project-4</TD>
	<TD> C++</TD>
</TR>
<TR>
	<TD >5</TD> 
	<TD >1-4pm</TD>
	<TD >Project-5</TD>
	<TD rowspan="4"> Java</TD>
</TR>
<TR>
	<TD >6</TD> 
	<TD rowspan="3">25.June.23</TD>
	<TD >8-11am</TD>
	<TD >Project-6</TD>
</TR>
<TR>
	<TD >7</TD> 
	<TD >11-2pm</TD>
	<TD >Project-7</TD>
</TR>
<TR>
	<TD >8</TD> 
	<TD >2-5pm</TD>
	<TD >Project-8</TD>
</TR>

</TABLE>
</body>
<style>
h3 {text-align: center;}

</style>
</html>
```
## OUTPUT
![Alt text](<fwad ex3 op.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
