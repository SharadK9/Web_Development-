<!DOCTYPE html>
<html>
  <head>
    <style>
    label
    {
      font-weight:bold;
    }
    </style>
  </head>
  <body>
    <!-- The code starts here -->
    <!-- Welcome to Page 3 -->
    <!-- HTML Tables -->
    <table style="width:100%" border=1>
      <caption><b> Time Table</b></caption>
    <thead>
      <tr>
       <th></th>
       <th>08.30 - 09.30</th>
       <th>09.30 - 10.30</th>
       <th>10.30 - 11.30</th>
       <th>11.45 - 12.40</th>
       <th>12.40 - 01.20</th>
      </tr>
    </thead>
    <tbody>
      <tr align="center" bgcolor="pink">
       <th>MON</th>
       <td></td>
       <td>X</td>
       <td>VII</td>
       <td>VI</td>
       <td></td>
      </tr>
      <tr align="center">
       <th>TUE</th>
       <td></td>
       <td>VII</td>
       <td> </td>
       <td>IX</td>
       <td></td>
      </tr>
      <tr align="center">
       <th>WED</th>
       <td></td>
       <td></td>
       <td>VI</td>
       <td>IX</td>
       <td></td>
      </tr>
      <tr align="center">
       <th>THU</th>
       <td>X</td>
       <td></td>
       <td>IX</td>
       <td>VII</td>
       <td></td>
      </tr>
      <tr align="center">
       <th>FRI</th>
       <td></td>
       <td></td>
       <td>IX</td>
       <td></td>
       <td>VIII</td>
      </tr align="center">
      <tr align="center">
       <th>SAT</th>
       <td></td>
       <td>X</td>
       <td></td>
       <td></td>
       <td></td>
      </tr>
    </tbody>
  </table>
<br>
<hr>
<!-- HTML Forms -->  
  <form action="#">
  <fieldset>
  <legend align="center"><b>Student Information</b></legend>
  <label for="Fname">First Name:</label><br>
  <input type="text" value="" name="Fname" id="Fname" placeholder="Enter your first  name.">
  <br>
  <label for="Lname">Last Name:</label><br>
  <input type="text" value="" name="Lname" id="Lname" placeholder="Enter your last name.">
  <br>
  <label for="Email">Email ID:</label><br>
  <input type="email" value="" name="email" id="email" placeholder="Enter your Email ID.">
  <br>
  <label for="Roll">Roll Number:</label><br>
  <input type="Roll" value="" name="Roll" id="Roll" placeholder="Enter your roll number.">
  <br>
  <label for='gender'>Gender:</label>
  <select name="gender" id="gender">
      <option name='Male' selected>Male</option>
      <option name='female' >Female</option>
     <option name='others'>Others</option>
  </select>
  <br>
  <label for="Mob">Mobile:</label><br>
  <input type="number" name="Mob" id="Mob" range=10>
  <br>
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
  </fieldset>
  </body>
</html>
