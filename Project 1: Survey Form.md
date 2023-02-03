# --Description-- 
**User Stories:**

1. You should have a page title in an `h1` element with an `id` of `title`
1. You should have a short explanation in a `p` element with an `id` of `description`
1. You should have a `form` element with an `id` of `survey-form`
1. Inside the form element, you are **required** to enter your name in an `input` field that has an `id` of `name` and a `type` of `text`
1. Inside the form element, you are **required** to enter your email in an `input` field that has an `id` of `email`
1. If you enter an email that is not formatted correctly, you will see an HTML5 validation error
1. Inside the form, you can enter a number in an `input` field that has an `id` of `number`
1. The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
1. If you enter numbers outside the range of the number input, which are defined by the `min` and `max` attributes, you will see an HTML5 validation error
1. For the name, email, and number input fields, you can see corresponding `label` elements in the form, that describe the purpose of each field with the following ids: `id="name-label"`, `id="email-label"`, and `id="number-label"`
1. For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
1. Inside the form element, you should have a `select` dropdown element with an `id` of `dropdown` and at least two options to choose from
1. Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the `name` attribute
1. Inside the form element, you can select several fields from a series of checkboxes, each of which must have a `value` attribute
1. Inside the form element, you are presented with a `textarea` for additional comments
1. Inside the form element, you are presented with a button with `id` of `submit` to submit all the inputs

## --solutions--

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
