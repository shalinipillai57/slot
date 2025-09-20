# Ex03 Time Table
## Date:20.09.25

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Slot Time Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      text-align: center;
    }
    h2 {
      margin-bottom: 10px;
      color: darkblue;
    }
    table {
      border-collapse: collapse;
      margin: 15px auto;
      width: 80%;
    }
    table, th, td {
      border: 2px solid black;
    }
    th, td {
      padding: 10px;
      text-align: center;
    }
    th {
      background: gold;
    }
    .slot {
      background: #66e0ff;
    }
    .subject-table th {
      background: #ddd;
    }
  </style>
</head>
<body>

  <h2>SLOT TIME TABLE - Shalini (25015951)</h2>

  <!-- Timetable -->
  <table>
    <tr>
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
    </tr>
    <tr>
      <td>8-10</td>
      <td class="slot">FUNDAMENTALS OF C PROGRAMMING</td>
      <td class="slot">COMMUNICTIVE ENGLISH</td>
      <td class="slot">PHYSICS FOR QUANTUM COMPUTATION</td>
      <td class="slot">STATISTICS AND NUMERICALMETHODS</td>
      <td class="slot">FUNDAMENTALS OF C PROGRAMMING</td>
    </tr>
    <tr>
      <td>10-12</td>
      <td class="slot">FREE SLOT</td>
      <td class="slot">FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT</td>
      <td class="slot">FWAD</td>
      <td class="slot">FWAD</td>
      <td class="slot">PHY</td>
    </tr>
    <tr>
      <td>12-1</td>
      <td colspan="5"><b>L U N C H</b></td>
    </tr>
    <tr>
      <td>1-3</td>
      <td class="slot">FREE SLOT</td>
      <td class="slot">MAT</td>
      <td class="slot">MAT</td>
      <td class="slot">MAT</td>
      <td class="slot">SS</td>
    </tr>
    <tr>
      <td>3-5</td>
      <td class="slot">FREE SLOT</td>
      <td class="slot">GER</td>
      <td class="slot">CHE</td>
      <td class="slot">CHE</td>
      <td class="slot">FWAD</td>
    </tr>
  </table>

  <!-- Subject Codes Table -->
  <h3>Subject Details</h3>
  <table class="subject-table">
    <tr>
      <th>S. No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr><td>1</td><td>19AI414</td><td>Fundamentals of Web Application Development (FWAD)</td></tr>
    <tr><td>2</td><td>19EN612</td><td>German Basic (GER)</td></tr>
    <tr><td>3</td><td>19PH206</td><td>Physics for Information Technology (PHY)</td></tr>
    <tr><td>4</td><td>19CY205</td><td>Principles of Chemistry in Engineering (CHE)</td></tr>
    <tr><td>5</td><td>19MA201</td><td>Calculus and Matrix Algebra (MAT)</td></tr>
    <tr><td>6</td><td>19EY701</td><td>Soft Skills (SS)</td></tr>
  </table>

</body>
</html>
```

## OUTPUT
  ![alt text](<Screenshot 2025-09-20 161636.png>)
![alt text](<Screenshot 2025-09-20 161651.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
