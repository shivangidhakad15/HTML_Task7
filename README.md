# HTML_Task7
# Simple HTML Login Form

This README file provides instructions on how to create a simple HTML login form.

## Form Structure

The login form will have the following structure:

```html
<form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <input type="submit" value="Login">
</form>
```

In the above structure, we use the `<form>` element to create the login form. It contains `<label>` elements paired with `<input>` elements for capturing the user's username and password. The `id` attribute of each `<input>` element should match the `for` attribute of the corresponding `<label>` element for accessibility purposes.

## Form Validation

To ensure that the required fields are filled out before submitting the form, we include the `required` attribute on the input fields. This will prompt the user to complete those fields if they are left empty.

## Usage

To use the HTML login form, follow these steps:

1. Create a new HTML file or open an existing one in a text editor.
2. Copy the form structure provided above.
3. Paste the code into the `<body>` section of your HTML file.
4. Customize the form labels and input fields according to your needs.
5. Save the HTML file.
6. Open the HTML file in a web browser to view and interact with the login form.

That's it! You have now created a simple HTML login form. Feel free to add additional form elements or apply CSS styles to customize the form's appearance and behavior.
