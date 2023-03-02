# Basic Chatbot Code-Along
For this exercise, start by forking [this empty Repl](https://replit.com/@HylandOutreach/EmptyWeb).

![](../Assets/ForkRepl.png)

Then, follow along with the instructor to build a little text-based JavaScript program. The program will `prompt` the user with a question and will then reply back with an `alert` message containing the user's answer.

## Create the JavaScript File
In the **Files** section on the left, click the **New file** button. Give the new file a name of `script.js`.

Within the **script.js** file, add a statement that will show a welcome message to the user.

<input type="checkbox" id="reveal1" class="reveal-checkbox" />

<label for="reveal1" class="reveal-label">👀 Click to Reveal Code 👀</label>

```js
alert("Welcome to the chatbot!");
```

## Link the JavaScript File
1. In the **index.html**, add a `<head></head>` element
1. Within the `<head></head>` element, add a `<script></script>` element
1. Add a `src` attribute to the `<script>` opening tag to point to the `script.js` file

<input type="checkbox" id="reveal2" class="reveal-checkbox" />

<label for="reveal2" class="reveal-label">👀 Click to Reveal Code 👀</label>

```html
<html>
    <head>
        <script src="script.js"></script>
    </head>
</html>
```

Run the webpage, and make sure the `alert()` pop-up with the message appears!

>_Note: a `<body></body>` is not required for this HTML page._

## Ask a Question
Ask the user for their name and show a text box to the user allowing them to type their answer. Be sure to choose a descriptive variable name to store this value!

<input type="checkbox" id="reveal3" class="reveal-checkbox" />

<label for="reveal3" class="reveal-label">👀 Click to Reveal Code 👀</label>

```js
let username = prompt("What's your name?");
```

## Display a Reply
Show the user a formatted message containing their name.

<input type="checkbox" id="reveal4" class="reveal-checkbox" />

<label for="reveal4" class="reveal-label">👀 Click to Reveal Code 👀</label>

```js
alert("Cool! I love the name '" + username + "'. I think it means 'smart.'");
```