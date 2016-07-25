# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

<!DOCTYPE html>
<html>
<head>
<h1></h1>
  <title></title>
</head>
<body>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
</body>
</html>
</DOCTYPE>

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
<img src=""> is where the actual image is referenced from or creating a path to pull image to page.

<div></div> sections whatever is in the div to do separate styles,fonts,color makes it so you can specifie changes to something with altering other things you don't want to.
```

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
inline must be put on every line that you want that style to be applied much more time cosuming in long files.

internal style sheet less time to do styling but also makes html file cluttered with more text.

external style separate file but connected so you have all your styling in one page and no where else.
```

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* comment like this */
/* gives div tag name border-radius of 50%*/
div {
  border-radius: 50%;
}
*/gives header p class font-size of 18px*/
.header p {
  font-size: 18px;
}
*/ gives footer class a position of absolute and at the very bottom of page/*
.footer {
  position: absolute;
  bottom: 0;
}
*/give class splash-image the actual background image of an ocean.jpg,with background-size cover and a width of 100% so the entire width of page./*
.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}

.ninja:hover {
  display: none;
  color: black;
}
```


---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
