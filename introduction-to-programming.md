
## Workshop

### Exercise 01
- Get your solution of the first exercise from yesterday
- Create an `scripts.js` file in the same folder as the `index.html`
- Include `jQuery` and your script file at the end of the html file, before the closing `<body>` tag
```html
...
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="scripts.js"></script>
  </body>
</html>
```
- Add `id`-s to the 3 blue html element in the html file
  - eg. `id="fox-1"`, `id="fox-2"` ...
- Using javascript (written in the `scripts.js` file)
  - Change the text of the first blue box from `Velox` to `Macrotis`
  - Change the border color of the second from `blue` to `purple`
  - Change the background color of all 3 blue boxes to `yellow`

### Exercise 02
- Get your solution of the second exercise from yesterday
- Create and include a `scripts.js` file just like before
- Add different classnames to the 4 elements in the html file
- Let's create some variables with the following names and values:
  - color: purple
  - number: 10
  - word: cool
- Change the background color of the first box to purple, if the `color` is purple
- Change the text of the second
  - if the `number` is bigger than 100 to `whoah, that's a big number.`
  - otherwise `just a regular number, please.`
- Change the text to `Power of DOM` of the third if the `word` is cool, otherwise change the fourth one

### Exercise 03
- Get your solution of the fourth exercise from yesterday
- Create and include a `scripts.js` file just like before
- Create an array with your neighbours' (at your table) names and yours
- Using `forEach` add each name to the `<ul>` list
- (Optional) Your name should be bold

### Exercise 04
- Work with the same files as in the previous excerise
- Create this object:
```javascript
let additionalBlock = {
  title: "Added with javascript",
  text: "This block was added using javascript's jQuery framework. How awesome!"
};
```
- Add a new block at the end of the page, the `title` should be in a heading, the `text` should be in a paragraph block

### Exercise 05
- Create this basic html (2 different headings and a button)
![Counter](assets/js-ex5.png)
- Create an `EventListener` for clicking on the button, increase the value of the second heading (currently `0`)
- (Optional) Create a working decreasing button as well

### Exercise 06
- Create this basic html
![Todo list](assets/js-ex6.png)
- When clicking on the `Add todo` button add the content of the input field to the list
- (Optional) Clicking on a list item should make the text line-through
