<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Employee Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    fieldset {
      border: 1px solid #ccc;
      padding: 15px;
      margin-bottom: 20px;
    }
    legend {
      font-weight: bold;
    }
    label {
      display: inline-block;
      width: 120px;
      margin-bottom: 8px;
    }
    input[type="text"], input[type="date"], input[type="email"], select, textarea {
      width: 300px;
      padding: 5px;
      margin-bottom: 8px;
    }
    input[type="radio"] {
      margin-left: 10px;
    }
    textarea {
      height: 80px;
    }
    .notes {
      width: 95%;
      height: 100px;
    }
  </style>
</head>
<body>

  <fieldset>
    <legend>Basic Info</legend>
    <label>Employee ID:</label>
    <input type="text" value="9"><br>

    <label>Last Name:</label>
    <input type="text" value="Dodsworth"><br>

    <label>First Name:</label>
    <input type="text" value="Anne"><br>

    <label>Gender:</label>
    <input type="radio" name="gender"> Male
    <input type="radio" name="gender"> Female
    <input type="radio" name="gender"> XXX
    <input type="radio" name="gender" checked> ZZZ
    <br>

    <label>Title:</label>
    <input type="text" value="Sales Representative"><br>

    <label>Suffix:</label>
    <input type="text" value="Ms."><br>

    <label>BirthDate:</label>
    <input type="text" value="1969-07-02 00:00:00"><br>

    <label>HireDate:</label>
    <input type="text" value="1994-11-15 00:00:00"><br>

    <label>SSN #:</label>
    <input type="text"><br>

    <label>Reports To:</label>
    <input type="text" value="Buchanan"><br>
  </fieldset>

  <fieldset>
    <legend>Contact Info</legend>
    <label>Email:</label>
    <input type="email" placeholder="name@example.com"><br>

    <label>Address:</label>
    <input type="text" value="7 Houndstooth Rd."><br>

    <label>City:</label>
    <input type="text" value="London"><br>

    <label>Region:</label>
    <input type="text"><br>

    <label>Postal Code:</label>
    <input type="text" value="WG2 7LT"><br>

    <label>Country:</label>
    <select>
      <option>Russian Federation</option>
      <option>United Kingdom</option>
      <option>USA</option>
    </select><br>

    <label>US Home Phone:</label>
    <input type="text" value="(234)234-2342"><br>

    <label>Photo:</label>
    <input type="text" value="EmpID9.bmp"><br>
  </fieldset>

  <fieldset>
    <legend>Optional Info</legend>
    <label>Notes:</label><br>
    <textarea class="notes">Anne has a BA degree in English from St. Lawrence College. She is fluent in French and German.ZZZ</textarea>
  </fieldset>

</body>
</html>
