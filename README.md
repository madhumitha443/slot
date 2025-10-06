# Ex03 Time Table
## Date:06.10.2025

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
~~~
slot.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BORDERED TABLE</title>
</head>
<body>
    <h3 align="center" ><IMG SRC="logo.png"HEIGHT="200"WIDTH="600"BORDER=6>
    <h4 align="center">SLOT TIME TABLE- MADHUMITHA R </h4>
    <table BORDER="1" CELLPADDING="10" CELLSPACING="0" Align="center">
    
    
        <tr style="background-color:BLUE;">
            
            
        
            <th>day/time</th>
            <th>monday</th>
            <th>tuesday</th>
            <th>wednesday</th>
            <th>thursday</th>
            <th>friday</th>
            <th>saturday</th>
        </tr>
        <tr >
            <td style="background-color:yellow;">8-10</td>
            
            <td style="background-color:red;">web</td>
            <td style="background-color:red;">CRYPTO</td>
            <td style="background-color:red;">WEB</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">CRYPTO</td>
        </tr>
        <tr>
            <td style="background-color:yellow;">10-12</td>
            <td style="background-color:red;">C PROGRAM</td>
            <td style="background-color:red;">CRYPTO</td>
            <td style="background-color:red;">WEB</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">WEB</td>
            <td style="background-color:red;">WEB</td>

            
        </tr>
        <tr>
            <td style="background-color:yellow;">12-1</td>
            <td style="background-color:red;">LUNCH</td>
            <td style="background-color:red;">LUNCH</td>
            <td style="background-color:red;">LUNCH</td>
            <td style="background-color:red;">LUNCH</td>
            <td style="background-color:red;">LUNCH</td>
            <td style="background-color:red;">LUNCH</td>

            
        </tr>

        
            
        </tr>
        <tr>
            <td style="background-color:yellow;">1-3</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">MENTOR MEET</td>
            <td style="background-color:red;">CRYPTO</td>
            <td style="background-color:red;">C PROGRAM</td>
            <td style="background-color:red;">C PROGRAM</td>

            
        </tr>
        
            
        </tr>
        <tr>
            <td style="background-color:yellow;">3-5</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">C PROGRAM</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">FREE SLOT</td>
            <td style="background-color:red;">C PROGRAM</td>

            
        </tr>
        
        
       
 <table BORDER="1" CELLPADDING="10" CELLSPACING="0" Align="center">
    <<tr>
        <td style="background-color:purple;">S.NO</td>
        <td style="background-color:purple;">SUBJECT CODE</td>
        <td style="background-color:purple;">SUBJECT</td>
    </tr>
    <tr>
        <td style="background-color:green;">1</td>
        <td style="background-color:yellow">19AI414</td>
        <td style="background-color:orange;">FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT(FWAD)</td> 
    </tr>
    <tr>
        <td style="background-color:green;">2</td>
        <td style="background-color:yellow;">19CS547</td>
        <td style="background-color:orange;">FUNDAMENTAKS OF CRYPTOCURRENCY</td>  
    </tr>  
    <tr>
        <td style="background-color:green;">3</td>
        <td style="background-color:yellow;">19AI304</td>
        <td style="background-color:orange;">FUNDAMENTALS OF C PROGRAMMING</td>
    </tr>
</table>
</body>
</html>
~~~


## OUTPUT

![alt text](<Screenshot 2025-10-06 111608.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
