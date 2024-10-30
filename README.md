# Glassmorphism Login Form

This project demonstrates how to create a login form with a modern glassmorphism effect using HTML and CSS. Glassmorphism is a UI design trend that makes elements look like translucent, frosted glass surfaces, giving a unique and modern aesthetic. This form also includes a floating-label animation for an engaging user experience.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Customization](#customization)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Features
- Glassmorphism design effect with semi-transparent and blurred background.
- Floating-label animation for input fields.
- Responsive and modern layout.
- 'Remember me' checkbox and 'Forgot password' link.

## Demo
You can view a live demo of the Glassmorphism Login Form on [CodingNepal's website](https://www.codingnepalweb.com/demos/create-glassmorphism-login-form-html-css/).

## Installation
1. Clone or download the repository to your local machine.
2. Open the project folder.
3. Ensure you have two files: `index.html` and `style.css`.

## Usage
1. Open the `index.html` file in your browser to view the login form.
2. Customize the form by editing the HTML and CSS files as needed.

## Project Structure
- **index.html**: Contains the structure of the login form.
- **style.css**: Contains the styles for the glassmorphism effect, layout, and animations.

## Code Snippets
### HTML Structure (index.html)
This file contains the main form elements, including input fields for email and password, a remember-me checkbox, and a login button.

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glassmorphism Login Form</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper">
    <form action="#">
      <h2>Login</h2>
      <div class="input-field">
        <input type="text" required>
        <label>Enter your email</label>
      </div>
      <div class="input-field">
        <input type="password" required>
        <label>Enter your password</label>
      </div>
      <div class="forget">
        <label for="remember">
          <input type="checkbox" id="remember">
          <p>Remember me</p>
        </label>
        <a href="#">Forgot password?</a>
      </div>
      <button type="submit">Log In</button>
      <div class="register">
        <p>Don't have an account? <a href="#">Register</a></p>
      </div>
    </form>
  </div>
</body>
</html>
