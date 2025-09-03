# JavaScript Exercises: Mastering interactive JS (Fundamentals)


## Table of Contents 

- [Overview](#overview)
- [Installation & Usage](#installation--usage)
- [DOM Manipulation exercises](#dom-manipulation-exercises-)
- [Resources](#resources-)

---

## Overview 

This repository contains my solutions to various exercises for mastering interactive JavaScript. All solutions are the result of self-study and learning.

Exercises are focused on fundamental concepts such as:

*  **DOM Manipulations** 
*  **Event listeners**.

This repository is a work in progress, with new exercises to be added frequently.


---

## Installation & Usage

**1.**  **Fork the repository**

Begin by forking this repository to your own GitHub account. 
Click the 'Fork' button on the top right of this page.

**2.**  **Clone it**

Open your terminal or command prompt and run the following command to clone the repository to your local machine:

```bash
     git clone https://github.com/dinruz/JavaScript-interactive-exercises.git
```

**3.** **Running an exercise** ⚙️

First, navigate to the root directory of the repository:

```bash
     cd JavaScript-interactive-exercises
```

Then, simply open the corresponding .html file in your web browser. 

---

## DOM Manipulation exercises 🧩


| No. | Exercise Name          | Status      | Solution - code      | View demo |
| :-- | :--------------------- | :---------- | :------------------ |:------------|
| 1   | [Create and Append Elements](#ex-1)|   ✔️   | [Solution](/dom-manipulation/01-create-and-append-elements.js) | [Demo](/dom-manipulation/01-create-and-append-elements.html) |


<details id="ex-1">
  <summary><strong>Exercise 1: Create and Append Elements</strong></summary>

Copy the example below:

```html
<!-- The DOM -->
<body>
  <h1>THE TITLE OF YOUR WEBPAGE</h1>
  <div id="container">
    <div class="content">This is the glorious text-content!</div>
  </div>
</body>
```

 To make it work, you’ll need to supply the rest of the HTML skeleton and either link your JavaScript file or put the JavaScript into a script tag on the page. Make sure everything is working before moving on!

Add the following elements to the container using ONLY JavaScript and the DOM methods shown above:

1. a `<p>` with red text that says “Hey I’m red!”
2. an `<h3>` with blue text that says “I’m a blue h3!”
3. a `<div>` with a black border and pink background color with the following elements inside of it:
 *  another `<h1>` that says “I’m in a div”
 *  a `<p>` that says “ME TOO!”



💡  **Hint:**  After creating the `<div>` with createElement, append the `<h1>` and `<p>` to it before adding it to the container.

🔗 **Source:** [The Odin Project: DOM Manipulation and Events](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) | Foundations Course

✔️ **Solution:** 
* [View Code](./dom-manipulation/01-create-and-append-elements.js)
* [Live Demo](./dom-manipulation/01-create-and-append-elements.html)
    


</details>

---

## Resources 📚

This repository contains exercises & assignments with some content sourced from the following resource:

* [The Odin Project: DOM Manipulation and Events](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) | Foundations Course
