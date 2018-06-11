# A Breakable Toy for JavaScript DOM interactions

This repository includes a simple HTML page with a variety of different elements, and a JavaScript script file.

Use this as a space to explore what you can do when using JS to interact with the DOM.

## How to use

1. Clone this repository
2. Open `index.html` file in Chrome or Firefox, and check that 'Hello, world :)' has logged to the console
3. Go play - use JavaScript to implement the features described on the page and add more!

## Example JavaScript Code

The following code adds an event listener to the colour change box:

```
document.getElementById('color-box').addEventListener('click', changeColor);

function changeColor() {
  document.getElementById('color-box').innerHTML =
    '<div style="background-color: red; width: 200px; height: 200px" />'
}
```

## Planned Features

- Getting data from a form and displaying it on the page
- Show/hide a div on a button click
- Show/hide a modal element
- Type text in an input, have it display in another div after a delay
- Make an API call and display what is returned in a div
- Change the colour of a div on a button click - cycle through colours
- Check for other event listeners and think of things you can do
- Update a counter every time there is a click anywhere on the page
- Form input types:
  - Text
  - Radio Buttons
  - Check boxes
  - Submit


Another possible tool:

- You don't need JS for that... cool page animations you can implement using CSS
