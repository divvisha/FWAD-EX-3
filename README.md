# Ex03 Time Table
## DATE: 05/10/2023
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
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>SLOT TIME TABLE</title>
    </head>
    <body>
        <img src="web_logo.png" alt="Saveetha Engineering college" width="70%" style="margin-left: auto;margin-right: auto;display: block;">
        <h3 style="text-align: center;">SLOT TIME TABLE - DIVYASHREE B S (212221040044)</h3>
        <table border="5 black" style="text-align: center;margin-left: auto;margin-right: auto;width: 70%;height:300px;">
            <tr style="background-color: crimson;font-size: large;">
                <td style="font-weight: bold;">Day/Time</td>
                <td style="font-weight: bold;">Monday</td>
		        <td style="font-weight: bold;">Tuesday</td>
                <td style="font-weight: bold;">Wednesday</td>
                <td style="font-weight: bold;">Thursday</td>
                <td style="font-weight: bold;">Friday</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">8-10</td>
                <td colspan="3";>FREESLOT</td>
                <td>PHY</td>
                <td>CHE</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">10-12</td>
                <td>GER</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>PHY</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">12-1</td>
                <td colspan="5">LUNCH</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">1-3</td>
                <td colspan="2">FREESLOT</td>
                <td>MAT</td>
                <td>MAT</td>
                <td>SS</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bolder;">3-5</td>
                <td colspan="2">FREESLOT</td>
                <td>GER</td>
                <td>CHE</td>
                <td>FWAD</td>
            </tr>
        </table>
        <table border="5" style="margin-left: auto;margin-right: auto;margin-top: 50px;width:43%;padding: 3px;">
            <tr style="font-weight: bolder;text-align: center;">
                <td style="font-size: 20px;">S.No.</td>
                <td style="font-size: 20px;">Subject Code</td>
                <td style="font-size: 20px;">Subject Name</td>
            </tr>
            <tr>
                <td style="text-align: center;">1</td>
                <td style="text-align: center;">19AI414</td>
                <td>Fundamentalsnof Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td style="text-align: center;">2</td>
                <td style="text-align: center;">19EN612</td>
                <td>German Basics (GER)</td>
            </tr>
            <tr>
                <td style="text-align: center;">3</td>
                <td style="text-align: center;">19PH206</td>
                <td>Physics for Information Technology (PHY)</td>
            </tr>
            <tr>
                <td style="text-align: center;">4</td>
                <td style="text-align: center;">19CY205</td>
                <td>Principles of Chemistry in Engineering (CHE)</td>
            </tr>
            <tr>
                <td style="text-align: center;">5</td>
                <td style="text-align: center;">19MA201</td>
                <td>Calculus and Matrix Algebra (MAT)</td>
            </tr>
            <tr>
                <td style="text-align: center;">6</td>
                <td style="text-align: center;">19EY701</td>
                <td>Soft Skills (SS)</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
<img width="959" alt="fwad ex3 op2" src="https://github.com/divvisha/FWAD-EX-3/assets/127508123/9cf468f9-4cb1-4807-ba28-67eecaad2607">


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
