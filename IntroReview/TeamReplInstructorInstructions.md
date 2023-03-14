# Team Repl: Instructor Instructions
Follow these instructions to facilitate the **Team Repl** activity.

## Rundown
For this activity, students will all join [_one_ Repl project](https://replit.com/@HylandOutreach/UcsJsIntroReview) in Multiplayer mode, and build a project together.

- The [Multiplayer Invite Link](https://replit.com/join/qlopumkkfx-hylandoutreach) is available on the [lesson homepage](StudentDesc.md)
    - Each student should join the Multiplayer Repl from there
- Instructors should follow the [instructor instructions](TeamRepl.md)
    - These instructions should not be shared with students
    - There will be some opportunities for everyone to code at the same time
    - There will be structured sections where one individual will be responsible for adding code
- Each student should have the chance to write at least one part of the website code
- Instructors should **not** add any code
- One instructor should monitor the project and remove any code added out of turn

There is a high potential for chaos with this activity, but hopefully it will help everybody stay together and work as a team.

## Setup
Before starting anything, emphasize that **no students start editing right away**. Set expectations up front that students should only edit when given permission. Once that is clear, instruct students to join the Team Repl in Multiplayer mode from the lesson homepage.

## HTML Edits
Each student should add some HTML to the page. This can happen simultaneously. Students should:

1. Open the **index.html** file for editing
1. Add a `<p>` element with their name under the `<h2>Team Members</h2>` header
    - They can also modify existing `<p></p>` elements if they have not been claimed
1. Add an `<img>` element with any image under the `<h2>Images</h2>` header
1. Open the **page2.html** or **page3.html** files, and add whatever they would like (chaos)

## JavaScript Setup
For this next part, go around the room and call one student at a time. Each student should complete one step of the process. If any student completes the step when it is not their turn, they should be kicked out of the project (close their chromebook).

1. Create a new JavaScript file
    - It can be named anything, but will be referred to as **script.js**
    - It must end with **.js**
1. Open the **index.html** file, and add a `<script>` element
1. In the `<script>` element, add the `src` attribute
1. Set the `src` attribute value to **script.js**

Nothing should happen at the end of this section, but there should be aa new **script.js** file, and in the `<head></head>` of the **index.html** file, there should be this element:

```html
<script src="script.js"></script>
```

## A Pop-Up
Go around the room and call on one student at a time. The goal will be to display a welcome message to the user. Ask the students if they know what comes next before letting them attempt to add the code.

1. Open the **script.js** file and make a new line
1. Enter the pop-up function keyword: `alert`
1. Add the next thing: Parentheses (`()`)
1. Add the next thing, within the parentheses: Quotation marks (`""`)
1. Add the next thing, within the quotes: A welcome message
    - It can be whatever the student would like, or "Hi"
1. Add the next thing: A semi-colon (`;`)

Run the project, and make sure the pop-up message appears! The code in the **script.js** file should look like this:

```js
alert("Hi");
```

## A Variable Message
Go around the room and call on one student at a time. The goal is to create a variable for a name, and display a message that uses the variable value. Ask the students if they know what comes next before letting them attempt to add the code.

1. Open the **script.js** file and make a new line
1. There, add the first word to create a variable: `let`
1. Add the next thing: A variable name
    - This can be anything, but will be referred to as `name`
1. Add the next thing: An equals sign (`=`)
1. Add the next thing: Quotation marks (`""`)
1. Add the next thing, within the quotes: A name
    - It can be whatever the student would like, or "Finn Wolfhard"
1. Add the next thing: A semi-colon (`;`)
1. Under that, add a way to display a pop-up saying Hi: `alert("Hi ");`
1. In the parentheses, add the variable value: `"Hi " + name`

Run the project, and make sure the variable pop-up message appears! The new code in the **script.js** file should look like this:

```js
let name = "Finn Wolfhard";
alert("Hi " + name);
```

## A Question
Go around the room and call on one student at a time. The goal is to ask a question that yields a value stored in a variable. Ask the students if they know what comes next before letting them attempt to add the code.

1. Open the **script.js** file and make a new line
1. There, add the first word to create a variable: `let`
1. Add the next thing: A variable name
    - This can be anything, but will be referred to as `movie`
1. Add the next thing: An equals sign (`=`)
1. There, add the question keyword function: `prompt`
1. Next, add what comes after that: Parentheses (`()`)
1. Add the next thing, within the parentheses: Quotation marks (`""`)
1. Add the next thing, within the quotes: A question
    - This can be anything, but will be "What is your favorite movie?"
1. Add the next thing: A semi-colon (`;`)

Run the project, and make sure the prompt pop-up appears! The new code in the **script.js** file should look like this:

```js
let movie = prompt("What is your favorite movie?");
```

## A Response
Go around the room and call on one student at a time. The goal is to respond to the user input from the `prompt` question. Ask the students if they know what comes next before letting them attempt to add the code.

1. Open the **script.js** file and make a new line
1. There, add a way to display a pop-up: `alert("");`
1. Within the quotation marks, add a message about the user's input
    - This can be anything, but will be `"I like "`
1. Within the parentheses, after the text, add code to append the user input

Run the project, and make sure the dynamic pop-up appears! The new code in the **script.js** file should look like this:

```js
alert("I like " + movie);
```

## More Alerts
The main part of the activity is now complete! Each student should have been able to contribute at least one portion of the project.

From here, students are welcome to continue adding their own `alert` or `prompt` statements or variable creations to the **script.js** file. This may become fairly chaotic, but it should give them a chance to practice the full breadth of the skills from the prior lesson.
