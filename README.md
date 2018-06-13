## Setup

We want to continue building our profile page. For that, let's copy our previous profile into this challenge's folder and add a CSS file to it:

```bash
cp -r ../01-Profile-content/profile .
cd profile
touch style.css
```

## Background & Objectives

Add simple CSS rules to design **fonts** and **colors** for your profile page.

## Specs

[This is an example](http://lewagon.github.io/html-css-challenges/02-fonts-colors/) of what you need to create. Here is a list of CSS rules to write:

### Body

Pick a nice `background-color`, `font-family`, `color`, `font-size` and `line-height` for the `<body>`. **Setting these font rules at the body-level will apply them on all basic text tags ** (`<p>`, `<li>`, etc.).

### Headers

- Choose a nice `color` and `font-family` for headers (`<h1>`, `<h2>`, `<h3>`)
- Choose harmonious `font-size` and `line-height` for headers
- Hint: **small headers** are more elegant. If you check out any website (Medium, Airbnb, etc.), you'll see that the `font-size` of their headers is quite small.

### Links

- Change the `color` & `text-decoration` of all the links
- Add hover effects to links using the pseudo-class `a:hover`.

## Further suggestions & resources

- Find inspiration on [Coolors](http://coolors.co/) or [Color hunt](http://colorhunt.co/) to choose an awesome color scheme.
- Pick your fonts on [Google fonts](https://www.google.com/fonts)
- On Google fonts, **Open Sans** is the standard choice for the `body`. **Raleway**, **Varela**, **Montserrat**, **Roboto** are a few good ones you could use for `h1`, `h2`, `h3`.

For instance, if you wanted to use Open-Sans and Montserrat (with different font-weights), you could add this in the `<head>` of your HTML:


```html
 <!-- Google fonts -->
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:400,300,700|Montserrat:400,700">
```

Then you can apply it in the CSS:

```css
body {
  font-family: 'Open Sans', sans-serif;
  font-weight: 300; /* if you want the light version */
}
```

**Feel free to choose other fonts on Google fonts and be creative 😎🌈!**
