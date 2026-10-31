# Lab 4 – Divs, Attributes and a Small Fix

## Aim
To group parts of a webpage using `div` elements, add a custom data attribute, and correct errors in a broken HTML page.

## Introduction
HTML provides different elements to structure a webpage. The `<div>` element is used to group related content. HTML attributes provide additional information about elements.

## 1. Div Element
The `<div>` tag is a block-level container used to group HTML elements.

**Syntax:**
html
<div>
    Content goes here
</div>

### Types of Div Sections
- **Header:** Contains the heading or introductory content.
- **Main:** Contains the main content of the webpage.
- **Footer:** Contains copyright or closing information.

### Example
html
<div class="header">Website Header</div>
<div class="main">Main Content</div>
<div class="footer">Website Footer</div>

## 2. HTML Attributes

Attributes provide additional information about HTML elements. They are written inside the opening tag.

### Class Attribute
The `class` attribute assigns a class name to an element. It is commonly used for CSS styling.

Example:
```html
<div class="header">Welcome</div>


### ID Attribute
The `id` attribute gives an element a unique identifier.

Example:
html
<div id="profile">
    My Profile
</div>


### Data Attribute
Custom data attributes store extra information in an HTML element. They begin with `data-`.

Example:
```html
<p data-topic="hobbies">My hobbies are reading and coding.</p>
```

The value of a data attribute is not directly displayed on the webpage.

## 3. Fixing HTML Errors

HTML tags should be properly opened and closed.

Common errors in the given broken page:
1. The `<h1>` heading was not closed.
2. The first paragraph used an opening `<p>` tag instead of a closing `</p>` tag.

Correct syntax:
html
<h1>Attendance Report</h1>
<p>Asha: 92%</p>
<p>Rohan: 85%</p>