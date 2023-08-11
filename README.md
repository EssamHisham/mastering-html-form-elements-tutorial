# mastering-html-form-elements-tutorial
<!DOCTYPE html>
<html>
<head>
  <title>Interactive HTML Form Elements: A Hands-On Tutorial</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
    }
    th, td {
      padding: 8px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }
  </style>
</head>
<body>
  <h1>HTML Form Tutorial</h1>
  <form>
    <table>
      <tr>
        <td><label for="name">Name:</label></td>
        <td><input type="text" id="name" name="name" placeholder="John Doe"></td>
        <td>
          <p><strong>Input Type:</strong> text</p>
          <p><strong>Description:</strong> Used for entering single-line text.</p>
        </td>
      </tr>
      <tr>
        <td><label for="email">Email:</label></td>
        <td><input type="email" id="email" name="email" placeholder="johndoe@example.com"></td>
        <td>
          <p><strong>Input Type:</strong> email</p>
          <p><strong>Description:</strong> Used for entering email addresses.</p>
        </td>
      </tr>
      <tr>
        <td><label for="phone">Phone:</label></td>
        <td><input type="tel" id="phone" name="phone" placeholder="123-456-7890"></td>
        <td>
          <p><strong>Input Type:</strong> tel</p>
          <p><strong>Description:</strong> Used for entering phone numbers.</p>
        </td>
      </tr>
      <tr>
        <td><label for="age">Age:</label></td>
        <td><input type="number" id="age" name="age" min="18" max="100"></td>
        <td>
          <p><strong>Input Type:</strong> number</p>
          <p><strong>Description:</strong> Used for entering numeric values.</p>
        </td>
      </tr>
      <tr>
        <td><label for="gender">Gender:</label></td>
        <td>
          <select id="gender" name="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
          </select>
        </td>
        <td>
          <p><strong>Input Type:</strong> select</p>
          <p><strong>Description:</strong> Used for selecting one option from a list.</p>
        </td>
      </tr>
      <tr>
        <td><label>Interests:</label></td>
        <td>
          <input type="checkbox" id="interest1" name="interest" value="reading">
          <label for="interest1">Reading</label><br>
          <input type="checkbox" id="interest2" name="interest" value="traveling">
          <label for="interest2">Traveling</label><br>
          <input type="checkbox" id="interest3" name="interest" value="sports">
          <label for="interest3">Sports</label>
        </td>
        <td>
          <p><strong>Input Type:</strong> checkbox</p>
          <p><strong>Description:</strong> Used for selecting multiple options from a list.</p>
        </td>
      </tr>
      <tr>
        <td><label for="message">Message:</label></td>
        <td><textarea id="message" name="message" rows="4" cols="50" placeholder="Your message here"></textarea></td>
        <td>
          <p><strong>Input Type:</strong> textarea</p>
          <p><strong>Description:</strong> Used for entering multi-line text.</p>
        </td>
      </tr>
      <tr>
        <td colspan="3"><button type="submit">Submit</button></td>
      </tr>
    </table>
  </form>
</body>
</html>
