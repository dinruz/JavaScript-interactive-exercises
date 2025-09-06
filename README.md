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


| No. | Exercise Name          | Status      | HTML Code      | JS Code |
| :-- | :--------------------- | :---------- | :------------------ |:------------|
| 1   | [Create and Append Elements](#ex-1)|   ✔️   | [01-HTML](/dom-manipulation/01-create-and-append-elements.html) | [01-JS](/dom-manipulation/01-create-and-append-elements.js) |  
| 2   | [Append and Style Elements](#ex-2)|   ✔️   |[02-HTML](/dom-manipulation/02-append-and-style.html) |[02-JS](/dom-manipulation/02-append-and-style.js) |  |
| 3   | [Insert and Style Elements](#ex-3)|   ✔️   | [03-HTML](/dom-manipulation/03-insert-and-style.html)|[03-JS](/dom-manipulation/03-insert-and-style.js) |  
| 4   | [List Manipulation & Styling](#ex-4)|   ✔️   | [04-HTML](/dom-manipulation/04-list-manipulation-style.html)|[04-JS](/dom-manipulation/04-list-manipulation-style.js) |  


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
* [01 - HTML Code](./dom-manipulation/01-create-and-append-elements.html)
* [01 - JS Code](./dom-manipulation/01-create-and-append-elements.js)

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
* [02 - HTML Code](./dom-manipulation/02-append-and-style.html)
* [02 - JS Code](./dom-manipulation/02-append-and-style.js)

    
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
* [03 - HTML Code](./dom-manipulation/03-insert-and-style.html)
* [03 - JS Code](./dom-manipulation/03-insert-and-style.js)
</details>

---

<details id="ex-4">
  <summary><strong>Exercise 4: List Manipulation & Styling </strong></summary>

You will build on an existing HTML structure to dynamically add new list items, style them based on their position and insert new content before and after a specific element. 

```html
<body>
  <h1>Interactive Shopping List</h1>
  <div id="shopping-list-container">
    <h2>Items to Buy</h2>
    <ul id="item-list">
      <li class="item">Milk</li>
      <li class="item highlight">Bread</li>
      <li class="item">Eggs</li>
    </ul>
  </div>
</body>
```

**Tasks:**

1. Get the Elements:

    * Select the `<ul>` element with the ID item-list.

    * Select the `<li>` element that has the class highlight.

2. Add and Style a New Item:

    * Create a new `<li>` element with the text "Cheese".

    * Add a class named new-item to this new element.

    * Append this new list item to the end of the item-list.

3. Insert an Item at the Beginning:

    * Create another new `<li>` element with the text "Apples".

    * Insert this new `<li>` element at the beginning of the item-list.

4. Add a Section Header:

    * Create a new `<h3>` element with the text "Don't Forget!"

    * Insert this new `<h3>` element directly before the item-list `<ul>` element.

5. Remove a Class and Add a New Style:

    * Remove the highlight class from the `<li>` element that currently has it.

    * Instead of a class, use inline styling to set the background color of this element to 'pink'.

✔️ **Solution:** 
* [04 - HTML Code](./dom-manipulation/04-list-manipulation-style.html)
* [04 - JS Code](./dom-manipulation/04-list-manipulation-style.js)

</details>

---

## Resources 📚

This repository contains exercises & assignments with some content sourced from the following resource:

* [The Odin Project: DOM Manipulation and Events](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) | Foundations Course
