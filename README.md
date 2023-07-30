# js-login

A login validation form for one of my favourite cycling companies (Commencal) using JavaScript regular expressions.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learnt](#what-i-learnt)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

The challenge was to create a custom login form using regular expressions to validate the email address and password. I learnt about password validation as part of a module in my training at IT Career Swap. The form has two input fields: username and password. When the form is submitted the checkForm script parses the input values and returns either true or false. If a false value is returned then the form submission is cancelled.

### Links

- GitHub URL: [Code](https://github.com/Max88-git/js_login)
- Live Site URL: [Live Site](https://max88-git.github.io/js_login/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JavaScript
- Regular Expressions

# What I Learnt

- How to use HTML and CSS to create a basic login form.
- How to validate user information.
- How to label and style input fields.
- Create a function with multiple if statements using regex to verify user inputs.
- Add alert messages to test against various email and password requirements.
- Add a submit button to validate the information. On submit, returning the function checkForm.
- On submit, sending form-data to a relative URL called message.html.
- Use links to reference an external style sheet.
- introduce the script tag in the body.

Here is a code snippet I am proud of:

```javascript
re = /^[^ ]+@[^ ]+\.[a-z]{2,3}$/;
if (!re.test(form.email.value)) {
  alert("Error: This is not a valid email address");
  form.username.focus();
  return false;
}
```

### Useful resources

- [Password Validation using regular expressions](https://www.the-art-of-web.com/javascript/validate-password/) - This article helped me solidify my understanding of email and password validation and the importance of having strong passwords.

## Author

- Website - [Max Lockwood](https://www.maxlockwood.uk/)
