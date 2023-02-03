
## html

```html
<html>
  <head>
    <title>Survey Form</title>
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out the following survey form to provide your feedback.</p>
    <form id="survey-form">
      <label id="name-label" for="name">Name:</label>
      <input id="name" type="text" name="name" placeholder="Enter your name here" required>
      <br><br>
      <label id="email-label" for="email">Email:</label>
      <input id="email" type="email" name="email" placeholder="Enter your email here" required>
      <br><br>
      <label id="number-label" for="number">Number:</label>
      <input id="number" type="number" name="number" min="1" max="100" placeholder="Enter a number between 1 and 100">
      <br><br>
      <label for="dropdown">Select an option:</label>
      <select id="dropdown" name="dropdown">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
      </select>
      <br><br>
      <label for="radio-group">Select one option:</label><br>
      <input type="radio" id="radio1" name="radio-group" value="radio1">
      <label for="radio1">Option 1</label><br>
      <input type="radio" id="radio2" name="radio-group" value="radio2">
      <label for="radio2">Option 2</label><br>
      <br>
      <label for="checkbox-group">Select multiple options:</label><br>
      <input type="checkbox" id="checkbox1" name="checkbox-group" value="checkbox1">
      <label for="checkbox1">Option 1</label><br>
      <input type="checkbox" id="checkbox2" name="checkbox-group" value="checkbox2">
      <label for="checkbox2">Option 2</label><br>
      <br>
      <label for="comments">Additional comments:</label><br>
      <textarea id="comments" name="comments" rows="5" cols="30"></textarea>
      <br><br>
      <button id="submit" type="submit">Submit</button>
    </form>
  </body>
</html>
```
