# Math! Code-Along
Start by forking the [JavaScript Starter Repl](https://replit.com/@HylandOutreach/JavaScriptStarter), then follow along as a group to perform a math experiment! You can name your fork something like `Math!` so it's easy for you to find later.

## Set Up the Experiment
Click **script.js** to open the file in the Replit editor pane.

Write the code that will `prompt` the user for their favorite number between 1 and 9 and store their answer in a new variable named `first`.

<input type="checkbox" id="reveal1" class="reveal-checkbox" />

<label for="reveal1" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
let first = prompt("Enter your favorite number between 1 and 9:");
```

On the next line, ask the user for *another number* and store that answer in a new variable named `second`.

<input type="checkbox" id="reveal2" class="reveal-checkbox" />

<label for="reveal2" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
let second = prompt("Enter another number between 1 and 9:");
```

## Perform the Experiment
Now that we have some input from the user, we can start to do some math!

First, simply concatenate (add) the `first` and `second` answers together and store that in a new variable named `result1`.

<input type="checkbox" id="reveal3" class="reveal-checkbox" />

<label for="reveal3" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
let result1 = first + second;
```

Next, use JavaScript's `Number()` function to convert the answers to numbers *before* adding them together. Store that value in a new variable: `result2`.

<input type="checkbox" id="reveal4" class="reveal-checkbox" />

<label for="reveal4" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
let result2 = Number(first) + Number(second);
```

## Show the Results
Now that the math has been done, display the results in `alert` messages to the user.

<input type="checkbox" id="reveal5" class="reveal-checkbox" />

<label for="reveal5" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
alert("The results are in!");
alert("When we add your answers together as STRINGS, we get: " + result1);
alert("When we add your answers together as NUMBERS, we get: " + result2);
```

Save and run the page to test it out!

## Expand the Experiment
Add a third result -- see what happens when you convert *only one* of the answers to a number.

<input type="checkbox" id="reveal6" class="reveal-checkbox" />

<label for="reveal6" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
let result3 = first + Number(second);

alert("When we convert only ONE of your answers to a number, we get: " + result3);
```

## Final Code
The experiment is over.

However... to make it easier for you to understand your code later... you can add **comments**!

Some developers like to start a task by writing *just* the comments (like an essay outline) and then they'll fill in the code beneath each one. 🧠

<input type="checkbox" id="reveal7" class="reveal-checkbox" />

<label for="reveal7" class="reveal-label">👀 Click to Reveal Code 👀</label>

```javascript
// Set up the experiment
let first = prompt("Enter your favorite number between 1 and 9:");
let second = prompt("Enter another number between 1 and 9:");

// Perform the experiment
let result1 = first + second;
let result2 = Number(first) + Number(second);

// Show the results
alert("The results are in!");
alert("When we add your answers together as STRINGS, we get: " + result1);
alert("When we add your answers together as NUMBERS, we get: " + result2);

// Expand the experiment
let result3 = first + Number(second);
alert("When we convert only ONE of your answers to a number, we get: " + result3);
```

## Bonus
Try switching to [template strings](TemplateStrings.md) if there is time. Did it make your code easier to read... or harder? 🤔