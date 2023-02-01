# HTML & CSS Review Code-Along
Start by forking [this empty Repl](https://replit.com/@HylandOutreach/EmptyWeb), then follow the instructions below to build a simple webpage!

To fork the Repl, click the "Fork Repl" button on the page:

![](../Assets/ForkRepl.png)

## Add the Basic HTML Elements
Add the foundational elements to the **index.html** file. Start with `<html></html>`, then add `<head></head>` and `<body></body>` between the `html` tags.

```html
<html>
	<head>
	</head>
	<body>
	</body>
</html>
```

## Add a Header
Between the opening and closing `body` tags, add an `h3` element. Within the `h3` element, add the proper text.

```html
<h3>Fortnite Fan Site</h3>
```

## Add an Image
Add an image to the page.

1. Go to [Google Images](https://google.com/images/)
1. Find an image, and copy the image address/URL/location
1. Create an `img` element, and set its `src` attribute to be the URL for the image

```html
<img src="https://assets.reedpopcdn.com/Fortnite-Battle-Pass-creen-1.jpeg" />
```

## Add a Paragraph
Under the `img` element, add a `p` element that contains the text for the paragraph.

```html
<p>Fortnite is a great video game filled with several memorable characters and lots of action.</p>
```

## Add Another Header
Under the `p`, add an `h3` header that will serve as the title for a list.

```html
<h3>My Top Three Zones</h3>
```

## Add a List
Under the `h3`, create an `ol` element. Between the opening and closing tags, create three `li` elements with the proper text.

```html
<ol>
    <li>Greasy Grove</li>
    <li>Shattered Slabs</li>
    <li>Rickety Rig</li>
</ol>
```

## Add a Background Style
Now it's time to add some style. Between the opening and closing `head` tags, add a `style` element.

Add a ruleset to the `style` element that will select the `body` (all the content on the page). Within the ruleset, set the `background` property to `black`, and the `color` property to `white`.

```html
<style>
    body {
        background: black;
        color: white;
    }
</style>
```

## Add an Image Style
Currently, the image might be a little big. Use CSS to update its size. Add another ruleset to the `style` element that will select the `img`. Within the ruleset, set the `height` property to `200px`.

```css
img {
	height: 200px;
}
```

## Add a Main Header Style
Next, it would be nice for the main header to stand out a little more. To style _only_ the main header, add a `class` attribute to it in the HTML, and then select it by its class in the CSS.

In the **index.html** file, find the top `h3` header. Add a `class` attribute with a value of `shiny` to the element.

```html
<h3 class="shiny">Fortnite Fan Site</h3>
```

In the `style` element, add a ruleset that will select elements with a class of `shiny` using `.shiny`. Within the ruleset, set the `color` property to `gold` so that everyone knows you are legendary.

```css
.shiny {
	color: gold;
}
```

## Final Code
That's it! The Fortnite Fan Site looks pretty good.

### index.html
```html
<html>
	<head>
		<style>
            body {
                background: black;
                color: white;
            }
            img {
                height: 200px;
            }
            .shiny {
                color: gold;
            }
        </style>
	</head>
	<body>
		<h3 class="shiny">Fortnite Fan Site</h3>
		<img src="https://assets.reedpopcdn.com/Fortnite-Battle-Pass-creen-1.jpeg" />
		<p>Fortnite is a great video game filled with several memorable characters and lots of action.</p>

		<h3>My Top Three Zones</h3>
		<ol>
            <li>Greasy Grove</li>
            <li>Shattered Slabs</li>
            <li>Rickety Rig</li>
        </ol>
	</body>
</html>
```
