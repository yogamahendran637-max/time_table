# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Slot Timetable</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: white;
      text-align: center;
    }
    .header {
      background: white;
      color: red(203, 60, 203);
      padding: 15px;
    }
    .header h2 {
      margin: 5px 0;
    }
    table {
      border-collapse: collapse;
      width: 90%;
      margin: 20px auto;
    }
    th, td {
      border: 1px solid black(40, 7, 7);
       padding: 10px;
      text-align: center;
    }
    th {
      background-color: rgb(84, 74, 93);
    }
    td {
      background-color: rgb(220, 166, 210);
    }
.sub-table th {
      background-color: rgb(207, 211, 221);
    }
    td {
        background-color: rgb(130, 176, 186);
    }
  </style>
</head>
<body>
  <center> 
    <img src="/static/tt.png.png" height="100px" width="540">
  </center>
  <h3>SLOT TIME TABLE-PRIYA RITHANYA (25007623)</h3>

  <table>
    <tr>
      <th>Day/Time</th>
      <th>8-10</th>
      <th>10-12</th>
      <th>12-1</th>
      <th>1-3</th>
      <th>3-5</th>
    </tr>
    <tr>
      <td>MONDAY</td>
      <td>FWAD</td>
      <td>FREE SLOT</td>
      <td rowspan="6" class="vertical text">LUNCH</td>
      <td>FOCP</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td>TUESDAY</td>
      <td>ENG</td>
      <td>ENG</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td>WEDNESDAY</td>
      <td>FWAD</td>
      <td>FWAD</td>
      <td>MM</td>
      <td>FOC</td>
    </tr>
    <tr>
      <td>THURSDAY</td>
       <td>ENG</td>
      <td>FOC</td>
      <td>ENG</td>
      <td>FOC</td>
    </tr>
    <tr>
      <td>FRIDAY</td>
      <td>FOC</td>
      <td>FWAD</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
        <td>SATURDAY</td>
        <td>ENG</td>
        <td>FWAD</td>
        <td>ENG</td>
        <td>FREE SLOT</td>
    </tr>
  </table>
 <h3>Subjects</h3>
  <table class="sub-table">
    <tr>
      <th>S.No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>1</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19EN101</td>
      <td>Communicative English (ENG)</td>
    </tr>
    <tr>
      <td>3</td>
      <td>19AI304</td>
      <td>Fundamentals Of C Programming (FOC)</td>
    </tr>
    <tr>

  </table>
</body>
</html>
```
# OUTPUT
<img width="1920" height="1080" alt="Screenshot (23) (1)" src="https://github.com/user-attachments/assets/f1aceffc-d646-4a9f-987d-7175c64933b9" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
