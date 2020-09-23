# Events

## Task 1 - the event object

In `main.js` you will find some code that looks like this...

```js
const button = document.querySelector("#click-me");

function handleClick(event) {
  // code goes here!
}

button.addEventListener("click", handleClick);
```

We have stored a reference to the button with id `#click-me` in the `button` variable, and have added an event listener to listen for when the button is pressed. When the button is pressed, the function `handleClick` will be called.

👉 If the `shiftKey` property of the event is `true`, then change the inner text of the button to be `"NAILED IT!!"`

## Task 2 - adding an event listener

There is a button with a class of `.task-2`

👉 Select the button with `querySelector` and store in a variable called `flowerButton`

👉 Write a function that changes the title of the document to be these flower emojis `💐🌷🌼`

👉 Add an event listener to the `flowerButton` which listens to the `click` event and calls your function from the previous step

## Task 3 - different events

There are [many different kinds of events](https://developer.mozilla.org/en-US/docs/Web/Events) other than click.

👉 Select the input with id `#title-changer`

👉 Write a function that takes in an event object as a parameter

👉 When that function is called, read the value from the `value` property, which is nested in an object on the `target` property of the event. Set the text in the `h1` tag to be that value

👉 add an event listener to the input which listens to the `keyup` event and calls your function

## Task 4 - more different events

👉 Listen to the `mouseenter` event on the `img` element and change the color of the `h1` to `hotpink`

👉 Listen to the `mouseleave` event on the `img` element and change the color of the `h1` back to `initial`

## Task 5 - go crazy!

👉 research some new events and make some different stuff happen
