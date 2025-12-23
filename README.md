# Ex03 Time Table
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center><img src="logo.png" height="150" width="800" alt=""> </center>
    <h3 align="center">  SLOT TIME TABLE - DEVADHAARINI.R (25010156) </h3>
    <table align="center" border="8" cellpadding="6" cellspacing="4" bgcolor="pastel green">
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>CE</td>
            <td>CE</td>
            <td>FP</td>
            <td>WEB</td>
            <td>FP</td>
            <td>FP</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>WEB</td>
            <td>FP</td>
            <td>PY</td>
            <td>FP</td>
            <td>FP</td>
            <td>CE</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>FP</td>
            <td>FP</td>
            <td>MM</td>
            <td>CE</td>
            <td>WEB</td>
            <td>PY</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FP</td>
            <td>PY</td>
            <td>WEB</td>
            <td>PY</td>
            <td>WEB</td>
            <td>PY</td>
        </tr>
        <br>
        <table border="5" cellpadding="7" cellspacing="2" align="center" bgcolor="lightblue">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>4S3-1</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>4V1-2</td>
             <td>COMMUNICATION ENGLISH  </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>4L1-1</td>
             <td>FUNDAMENDALS OF C PROGRAMMING  </td>
          </tr>
          <tr>
             <th>4.</th>
             <td>6J1-1</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr>

    </table>
</body>
</html>


## OUTPUT
<img width="1920" height="1080" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/c461b0f7-ac55-4ce0-999e-661baa5ba1e3" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
