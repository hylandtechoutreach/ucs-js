# Buttons

## Warm-Up: Spring Break Chat
Talk about anything fun that happened over Spring Break.

## Review: Data Types
Have the students raise their hands to answer the questions in [the Data Types and Values review presentation](Review.pptx). The main point of this exercise is to make sure they remember the difference between a string and a number.

There is also some math that looks a lot like algebra towards the end. Take those slides slow and walk through them step by step so that everyone understands that it is not algebra. We are not solving for `x` in the traditional way -- resist the urge to subtract from both sides!

## Lecture: Buttons
Use [this presentation](Buttons.pptx) to introduce:
- the `<button>` element
- the concept of functions
  - how to define them
  - how to call them

The last slide is a link to the [Button Example](https://vscodeedu.com/WY9oFCLBca3Zs5dY7E6u) project. Note the syntax of each piece of the code.

## Code-Along: Hello, Buttons!
Walk through adding a button to the [JavaScript Starter](https://vscodeedu.com/JMoFoFMdRpj0fjJ0akvZ) project. The button should call a function that should display an alert that says `Hello!`, similar to the example we just saw at the end of the lecture.

Here's the gist:

```html
<html>
  <head>
    <script src="script.js"></script>
  </head>
  <body>
    <button onclick="sayHello()">Say Hi</button>
  </body>
</html>
```

```javascript
function sayHello() {
  alert("Hello!");
}
```

## Self-Paced Exercise: Tickle Me Elmo
Have the students copy the [Tickle Me Elmo](https://vscodeedu.com/FCDuELAuHHdXt0HZkAq6) project and fix the issues with it. The students should reference the [help page](SelfPacedExercise.md) when they get stuck (they will).

Once everyone has had a chance to read some of the help page, explain what SCP is:
> The [SCP website](https://scp-wiki.wikidot.com/) is a creative writing project where people share fictional stories about mysterious objects, creatures, or phenomena, known as SCPs, which are contained by a secret organization called the SCP Foundation. These stories often mix elements of science fiction, horror, and fantasy, creating a fascinating world where readers can explore the unusual and supernatural.
>
> SCP stands for **Secure, Contain, Protect**.

With any remaining time, you could have the students:
- change what Elmo says when he is tickled
- change the background color to something other than black
- add a title to the web page

## Agenda

| Activity | Time |
|-|-|
| Warm-up | 5m |
| Review | 10m |
| Lecture | 15m |
| Code-Along | 10m |
| Self-Paced Exercise | 15m |
