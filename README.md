# Ex03 Time Table
## REGISTER NUMBER: 212221040044
## DATE: 07-10-2023
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
        <img src="web_logo.png " alt="Saveetha Engineering college" width="70%" style="margin-left: auto;margin-right: auto;display: block;">
        <table border="5 black" style="text-align: center;margin-left: auto;margin-right: auto;width: 70%;height:300px;">
            <tr style="background-color: orange;font-size: large;">
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
                <td>MAD</td>
                <td>CNS</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">10-12</td>
                <td>JAP</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MAD</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">12-1</td>
                <td colspan="5">LUNCH</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bold;">1-3</td>
                <td colspan="2">FREESLOT</td>
                <td>EVS</td>
                <td>MATH</td>
                <td>MATH</td>
            </tr>
            <tr>
                <td style="background-color: coral;font-weight: bolder;">3-5</td>
                <td colspan="2">FREESLOT</td>
                <td>OS</td>
                <td>CNS</td>
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
                <td>Japanese Basics (JAP)</td>
            </tr>
            <tr>
                <td style="text-align: center;">3</td>
                <td style="text-align: center;">19PH206</td>
                <td>Mobile App Development (MAD)</td>
            </tr>
            <tr>
                <td style="text-align: center;">4</td>
                <td style="text-align: center;">19CY205</td>
                <td>Algebra and number theory(MATH)</td>
            </tr>
            <tr>
                <td style="text-align: center;">5</td>
                <td style="text-align: center;">19MA201</td>
                <td>Cryptography and network security (CNS)</td>
            </tr>
            <tr>
                <td style="text-align: center;">6</td>
                <td style="text-align: center;">19EY701</td>
                <td>Environmental Science(EVS)</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
<img width="960" alt="Screenshot 2023-10-31 161828" src="https://github.com/divvisha/FWAD-EX-3/assets/127508123/a4d97fb2-2e7a-4fd1-aedf-9321c637ad69">


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
