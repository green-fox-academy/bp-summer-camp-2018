# Updating your Blog

## Adding a new Post
- Create an EventListener for the New Post form's button
- Read the necessary values from the fields
- Create one post's HTML structure and place the texts (read out from the form) in it
- Append the whole thing after or before the existing posts

## Optional
- Placing the posts from JavaScript
  - Create an array that contains the data of the initial posts
  - Remove the initial posts from the HTML
  - Create an HTML element *for each* post object in the `initialData` array and append them into the containing element
```javascript
let initialData = [
  {
    title: "First Post",
    text: "Text of the first one"
  },
  ...
];
```
  
- Make the posts appear with a fancy animation