# Buttons

## Icebreaker: TODO

## Review: Data Types
Have the students raise their hands to answer the questions in [the Data Types and Values review presentation](Review.pptx). The main point of this exercise is to make sure they remember the difference between a string and a number.

There is also some math that looks a lot like algebra towards the end. Take those slides slow and walk through them step by step so that everyone understands that it is not algebra. We are not solving for `x` in the traditional way -- resist the urge to subtract from both sides!

## Lecture: Buttons
Use [this presentation](Buttons.pptx) to introduce:
- the `<button>` element
- the concept of functions
  - how to define them
  - how to call them

The last slide is a link to the [Button Example](https://replit.com/@HylandOutreach/ButtonExample) repl. Note the syntax of each piece of the code.

## Code-Along: Hello, Buttons!
Walk through adding a button to the [JavaScript Starter](https://replit.com/@HylandOutreach/JavaScriptStarter) repl. The button should call a function that should display an alert that says `Hello!`, similar to the example we just saw at the end of the lecture. Here's the gist:

```html
<html>
  <head>
    <script src="script.js"></script>
  </head>
  <body>
    <button onclick="sayHello()">Hi</button>
  </body>
</html>
```

```javascript
function sayHello() {
  alert("Hello!");
}
```

## Self-Paced Activity: Tickle Me Elmo
Have the students fork the [Tickle Me Elmo](https://replit.com/@MattLuceen/TickleMeElmo?v=1) repl and fix the issues with it.

## Agenda

| Activity | Time |
|-|-|
| Icebreaker | 5m |
| Review | 10m |
| Lecture | 15m |
| Code-Along | 10m |
| Self-Paced Activity | 15m | 
| Survey | 5m |
