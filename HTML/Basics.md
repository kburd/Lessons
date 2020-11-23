# HTML Basics

Author: Kaleb Burd

Length: 3 hours

---

## Hello World
```html
<!DOCTYPE html>
<html>
    <head></head>
    <body>
        Hola Mundo!
    </body>
</html>
```

## Title
```html
<head>
    <title>My Awesome Webpage</title>
</head>
```

## Meta Data
```html
<head>
    <meta charset="UTF-8">
    <meta name="description" content="A basic webpage to learn html">
    <meta name="author" content="Marshal Matthers">
</head>
```

## Favicon
```html
<head>
    <link rel="icon" href="demo_icon.gif" type="image/gif" sizes="16x16">
</head>
```

## Paragraph
```html
<p>Hello Kazakhstan</p>
<p>My name Borat</p>
<p>It very nice</p>
```

## Headings
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Block vs inline
```html
<div>Block</div>
<div>Make me on a new line!!!</div>
```

```html
<span>In-Line</span>
<span>In-Line Again</span>
<br>
<span>Make me on a new line!!!</span>
```

## Ordered List
```html
<ol>
    <li>Alpha</li>
    <li>Bravo</li>
    <li>Charlie</li>
</ol>
```

## Unordered List
```html
<ul>
    <li>Alpha</li>
    <li>Beta</li>
    <li>Gamma</li>
</ul>
```

## Anchor
```html
<!-- Web link -->
<a href="http://google.com">Click Me!!!!</a>

<!-- Link to another HTML Page -->
<a href="../bootstrap2/index.html">Open another file</a>
```

## Image
```html
<img src="img/The_Eminem_Show.jpg" width="250px" height="250px">
```

### Image Alt
```html
<!-- Image with missing pic -->
<img src="The_Eminem_Show.jpg" width="250px" height="250px" alt="Image not found">
```

### Accepted Image types
```html
<img src="img/The_Eminem_Show.jpg" width="250px" height="250px" alt="Image not found">
<img src="img/The_Eminem_Show.png" width="250px" height="250px" alt="Image not found">
<img src="img/The_Eminem_Show.ico" width="250px" height="250px" alt="Image not found">
```

## Path Types
```html
<!-- Image with relative path -->
<img src="img/The_Eminem_Show.jpg" width="250px" height="250px" alt="Image not found">
<br>
<!-- Image with Absolute path -->
<img src="/Users/kalebburd/Documents/Projects/Demos/The_Eminem_Show.jpg" width="250px" height="250px" alt="Image not found">
<br>
```

## Table
```html
<table>
    <thead>
        <tr>
            <th></th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>1</th>
            <td>1</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr>
            <th>2</td>
            <td>2</td>
            <td>4</td>
            <td>6</td>
        </tr>
    </tbody>
</table>
```
