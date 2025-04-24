# Code-Along: Chatbot
In this activity, create a simple [chatbot](https://en.wikipedia.org/wiki/Chatbot) that can respond to some basic messages.

## Part Zero: Background
Start by talking to [ELIZA](https://psych.fullerton.edu/mbirnbaum/psych101/eliza.htm), a "Rogerian Therapist" chatbot from the 1960s. This is a small example of what is possible with chatbots. For this activity, your job is to make a chatbot that will act as a friend to people who do not have many friends. This will help them feel less lonely.

[**Click here to view the project.**](https://vscodeedu.com/1QQtkOwtYr4UFYBk1Mus) Copy the project to begin.

### The Code
Make sure to note how the code is currently working. The "Chat" button displays a message when it is clicked.

In the **index.html**, the `<button></button>` element has an `onclick` attribute that calls the `talk` function.

In the **script.js** file, the `talk` function is defined - it runs an `alert` to display a pop-up message.

## Part One: Prompt For Message
The first thing to do is ask the user to input a message. This is possible by creating a new variable, and using `prompt`.

1. Open the **script.js** file for editing
1. Make a new line between the `{` and `}`, under the `alert` statement
1. Create a new variable named `message`
1. Set the `message` variable to a `prompt`
1. Make the text for the prompt say "Please enter a message..."

The added JavaScript should look something like this:

```js
let message = prompt("Please enter a message...");
```

Run the code. Click the button, and verify that a prompt appears asking for a message. Nothing should happen when entering a message yet though!

## Part Two: Responding to the Message
Next, the chatbot should respond to certain messages the user enters. This is where `if` statements come in: the response should be different depending on the message.

To start, have the chatbot respond to a message of "Hi" from the user.

1. Open the **script.js** file for editing
1. Make a new line between the `{` and `}`, under the `message` variable
1. There, create an `if` statement
    - Keyword: `if`
    - Parentheses: `()`
    - Curly brackets: `{}`
1. For the `if` condition, check if the user said "Hi"
    - Condition goes between the parentheses
    - Use `message` variable, `===`, and `"Hi"` to compare
1. In the _body_ of the `if`, display a message saying "Well hey there!"
    - Body is between the curly brackets
    - Use `alert("Well hey there!");`

The added JavaScript should look something like this:

```js
if (message === "Hi") {
    alert("Well hey there!");
}
```

Run the code. Click the button, enter "Hi" as the message, and verify that the proper response appears! If any other message is entered, no response should appear.

## Part Three: More Responses
The chatbot is functional, but it is not very powerful yet. It needs to be able to respond to some more messages! Add a couple more responses using `if` statements.

| Message | Response |
|-|-|
| I love you | That's nice |
| Are you my friend? | Yes, of course... |

These `if` statements will look very similar to the previous `if` statement. For each of the responses, follow these steps:

1. Have the **script.js** file open for editing
1. Make a new line at the bottom of the `chat` body (above `}`)
1. Add an `if` statement: `if () {}`
1. For the condition (between `(` and `)`), check if `message ===` the given message
1. In the body (between `{` and `}`), `alert` with the response

The added JavaScript should look something like this:

```js
if (message === "I love you") {
    alert("That's nice");
}

if (message === "Are you my friend?") {
    alert("Yes, of course...");
}
```

Run the code. Click the button, and try out each of the messages. Make sure to enter them exactly right, with proper punctuation/capitalization/etc. Each message should produce the correct response!

## Final Code
By the end of the activity, the code should look something like this:

**index.html**
```html
<html>
  <head>
    <link href="style.css" type="text/css" rel="stylesheet">
    <script src="script.js"></script>
  </head>
  <body>
    <h1>Friend Proxy Chatbot 🗣️🤖</h1>
    <p>Lonely? Press the "Chat" button to talk to the friend proxy chatbot.</h1>
    <button onclick="talk()">Chat</button>
  </body>
</html>
```

**script.js**
```js
function talk() {
  alert("Hi friend 🙂");

  let message = prompt("Please enter a message...");

  if (message === "Hi") {
    alert("Well hey there!");
  }

  if (message === "I love you") {
    alert("That's nice");
  }

  if (message === "Are you my friend?") {
    alert("Yes, of course...");
  }
}
```

## Next Steps
After the basic code-along activity has been completed, work on some of these additional features.

### Even More Responses
There is always room for more responses to be added to the chatbot! Come up with some original ones, or use this list as a basis. Each new response should use a similar `if` statement structure:

```js
if (message === "MESSAGE") {
    alert("RESPONSE");
}
```

Add several responses to make the chatbot more lifelike.

| Message | Response |
|-|-|
| What's up? | Not much |
| How are you | I am fine |
| Sing a song | Mary had a little lamb |
| What is 1+1 | 1+1 is 2 |
| Tell me a joke | I'm against picketing, but I don't know how to show it. |
| Give me a quote | You miss 100% of the shots you take |

### Advanced Challenges
[Click here and try to complete the advanced challenges.](Challenges.md)
