# Week 1 - Day 2: HTML Basics

## Introduction

In today's session, we delved into the basics of HTML (Hypertext Markup Language). HTML forms the foundation of web development, defining the structure and content of web pages. Below, you'll find a summary of what we covered and some tasks to reinforce your understanding.

## HTML Basics Recap

### Document Structure

HTML documents have a basic structure that includes the `<!DOCTYPE html>` declaration, `<html>`, `<head>`, and `<body>` tags.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

### Heading Tags

Use heading tags `<h1>` to `<h6>` to define headings of different levels.

```html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<!-- ... -->
```

### Paragraphs, Line Breaks, and Formatting

```html
<p>This is a paragraph.</p>

<strong>This text is strong.</strong>
<em>This text is emphasized.</em>
<i>This text is italicized.</i>

<br> <!-- Line break -->
```

### Lists

### Ordered List (OL)

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <!-- ... -->
</ol>
```

### Unordered List (UL)

```html
<ul>
    <li>Item A</li>
    <li>Item B</li>
    <!-- ... -->
</ul>
```

### Division (DIV) Tag

```html
<div>
    <!-- Content goes here -->
</div>
```

### Anchor Link (A) and Image (IMG)

```html
<a href="<https://www.example.com>" target="_blank">Visit Example</a>

<img src="image.jpg" alt="Description">

```

### Tables

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
</table>
```

### Forms

```html
<form action="/submit" method="post">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username">

    <label for="password">Password:</label>
    <input type="password" id="password" name="password">

    <input type="submit" value="Submit">
</form>
```

## Tasks

1. Create an HTML document using the basic structure.
2. Experiment with heading tags, paragraphs, formatting, and line breaks.
3. Create ordered and unordered lists.
4. Use the `div` tag to structure your content.
5. Include anchor links to external websites and images.
6. Experiment with creating tables.
7. Build a simple form with text inputs and a submit button.

Feel free to explore and enhance your HTML skills. Happy coding! 🚀💻 #CodeWithPAAI