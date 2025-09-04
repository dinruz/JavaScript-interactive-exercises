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


| No. | Exercise Name          | Status      | View code      | View demo |
| :-- | :--------------------- | :---------- | :------------------ |:------------|
| 1   | [Create and Append Elements](#ex-1)|   ✔️   | [Code](/dom-manipulation/01-create-and-append-elements.js) | [Demo](/dom-manipulation/01-create-and-append-elements.html) |
| 2   | [Append and Style Elements](#ex-2)|   ✔️   | [Code](/dom-manipulation/02-append-and-style.js) | [Demo](/dom-manipulation/02-append-and-style.html) |
| 3   | [ Insert and Style Elements](#ex-3)|   ✔️   | [Code](/dom-manipulation/03-insert-and-style.js) | [Demo](/dom-manipulation/03-insert-and-style.html) |


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
* [View Demo](./dom-manipulation/01-create-and-append-elements.html)
    


</details>

---

<details id="ex-2">
  <summary><strong>Exercise 2: Append and Style Elements </strong></summary>

Copy the example below, supply the rest of the HTML skeleton and link your JavaScript file.

```html
<body>
  <h1>DOM Manipulation</h1>
  <div id="container">
    <div class="initial-content">This is the starting point.</div>
  </div>
</body>
```
**Tasks:**
  
  1. Get the `<div>` with the id "container".  

  2. Create a new `<p>` element with the text "This text is light green." and set its color to 'lightgreen'.

  3. Create a new `<h2>` element with the text "This is an orange heading." and set its color to 'orange'.

  4. Create a new `<div>` element. Give it a '2px solid black' border and a 'lightblue' background color.
  
  5. Inside this new `<div>` create:

  - a new `<h4>` element with the text "I'm the first element in the new div."

  - a new `<p>` element with the text "And I'm the second!"
  
  6. Append all the newly created elements to the "container" div in the correct order.

✔️ **Solution:** 
* [View Code](./dom-manipulation/02-append-and-style.js)
* [View Demo](./dom-manipulation/02-append-and-style.html)
    
</details>

---

<details id="ex-3">
  <summary><strong>Exercise 3: Insert and Style Elements </strong></summary>

Start with a basic HTML structure:

```html
<body>
  <h1>Insert & Style</h1>
  <div id="container">
    <p class="intro">This is a starting paragraph. Add new content before and after me!</p>
  </div>
</body>
```
**Tasks:**
  
  1. Get the '#container div'.

  2. Create a new `<span>` element. Give it a class of highlight and the text "IMPORTANT: ". Add this `<span>` at the very beginning of the #container div, before the existing `<p class="intro">` element.

  3. Create a new `<div>` element. Give it an ID of 'info-box' and a red border.

  4. Inside the new info-box div, create a new `<h2>` element with the text "New Section" and a class of 'section-title'.

  5. Inside the new 'info-box div', create a new `<ul>` element with two list items (`<li>`):

  * The first `<li>` should say "First item".

  * The second `<li>` should say "Second item".

  6. Append 'the info-box div' to the '#container div' after the existing `<p class="intro">` element.

  7. Create another new `<p>` element. Give it the text "This is the final paragraph." and an ID of 'final-paragraph'.

  8. Append the #final-paragraph to the `<body>` element.

💡 **Hint:** For inserting the `<span>` element before the `<p class="intro">`, you'll want to use the `insertBefore()` method. 

✔️ **Solution:** 
* [View Code](./dom-manipulation/03-insert-and-style.js)
* [View Demo](./dom-manipulation/03-insert-and-style.html)

---

## Resources 📚

This repository contains exercises & assignments with some content sourced from the following resource:

* [The Odin Project: DOM Manipulation and Events](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) | Foundations Course
