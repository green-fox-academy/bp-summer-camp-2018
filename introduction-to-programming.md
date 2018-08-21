# Introduction to programming

## Material Review

- What is JavaScript?
- `<script>` tag
- Declaring variables
- Assigning values
  ```javascript
  let myVariable;
  myVariable = 42;
  let myAnotherVariable = 42
  ```
- `console.log`
- Data types
  - String
    ```javascript
    let companyName = 'Green Fox Academy';
    let eventName = `Summer Coding Camp`;
    console.log(`${companyName} is hosting a ${eventName}!`);
    ```
  - Number
    ```javascript
    let days = 3;
    let PI = 3.14;
    ```
  - Boolean
    ```javascript
    let learning = true;
    let hunger = false;
    ```
  - Array
    ```javascript
    let mentors = ['Aze', 'Peti', 'Levi'];
    console.log(mentors[0]);
    mentors.forEach((mentor, index) => { ... });
    ```
  - Object
    ```javascript
    let company = { name: 'Green Fox Academy', address: 'Andrassy street 66' };
    console.log(company['name']);
    ```
- Comments
  ```javascript
  // I will never run
  ```
- Operators
  - Addition, `+`
  - Substraction, `-`
  - Multiplication, `*`
  - Division, `/`
  - Assignment, `=`
  - Equality, `===`
  - Not, `!`
  - Does-not-equal, `!==`
- Conditionals
  - `if`
  - `if ... else`
  ```javascript
  let coffee = true;
  if (coffee) {
    console.log('I am coding!');
  } else {
    console.log('I am waiting for caffein! ');
  }
  ```
- How to separate your script from the HTML document?
- Functions
  ```javascript
  let add = (a, b) => {
    return a + b;
  }
  ```
- What is jQuery?
  - `<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>`
- DOM manipulations with jQuery
  - `$(selector).action();`
  - `.val()`
  - `.val(content)`
    ```javascript
    $('h1').val('Hello World!');
    ```
  - `.append(HTML)`
    ```javascript
    $('div').append(
      `
      <h1>Hello World!</h1>
      `
    );
    ```
- Events
  - `$(selector).on(eventType, function);`
  - Click event
  - Submit event
  - Prevent default
  ```javascript
  $('form').on('submit', (event) => {
    event.preventDefault();
    console.log('The form was submitted.');
  });
  ```
- Developer tools
