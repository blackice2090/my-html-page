# 📌 Introduction

This repository contains a detailed explanation of the essential **HTML5** elements, along with practical examples for each element. This file serves as a comprehensive reference for learning **HTML5** and building complete web pages.

## 🌐 Live Demo
You can view the full HTML page here: [HTML5 Elements Showcase](https://blackice2090.github.io/my-html-page/)

## 🔗 Table of Contents
- [Adding Images](#adding-images)
- [Special Characters and Horizontal Rules](#special-characters-and-horizontal-rules)
- [Lists](#lists)
- [Tables](#tables)
- [Forms](#forms)
- [Internal Linking](#internal-linking)
- [Page Structure](#page-structure)

---

## 🖼️ Adding Images
```html
<img src="image.jpg" alt="Image description" width="300" height="200">
```
📌 **Attributes:**
- `src` specifies the image source.
- `alt` provides alternative text if the image cannot be displayed.
- `width` and `height` set the dimensions in pixels.

### 🔗 Using Images as Links
```html
<a href="https://example.com">
    <img src="logo.png" alt="Logo">
</a>
```

---

## 🔣 Special Characters and Horizontal Rules
- `&copy;` → ©
- `&lt;` → <
- `&gt;` → >

### 📏 Creating a Horizontal Rule
```html
<hr>
```

---

## 📜 Lists

### ✅ Unordered List
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

### 🔢 Ordered List
```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
</ol>
```

### 🔄 Description List
```html
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
</dl>
```

---

## 📊 Tables
### Simple Table
```html
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

### Using rowspan and colspan
```html
<table border="1">
    <tr>
        <th colspan="2">Merged Header</th>
    </tr>
    <tr>
        <td rowspan="2">Rowspan Cell</td>
        <td>Data A</td>
    </tr>
    <tr>
        <td>Data B</td>
    </tr>
</table>
```

---

## 📝 Forms
### Data Input Form
```html
<form action="submit.php" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <input type="submit" value="Submit">
</form>
```

---

## 🔗 Internal Linking
```html
<a href="#section1">Go to Section 1</a>

<h2 id="section1">Section 1</h2>
```

---

## 🏗️ Page Structure
### Header and Footer
```html
<header>
    <h1>Website Title</h1>
</header>
<footer>
    <p>&copy; 2024 All Rights Reserved</p>
</footer>
```

### Navigation
```html
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
    </ul>
</nav>
```

### Sidebar Content
```html
<aside>
    <p>Additional information...</p>
</aside>
```

---

## 📌 Additional Notes
- ==>
