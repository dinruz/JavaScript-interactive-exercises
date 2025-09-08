# JavaScript Exercises: Mastering interactive JS (Fundamentals)

## Table of Contents 📖

- [Overview](#overview)
- [Installation & Usage](#installation--usage)
- [List of Exercises](#list-of-exercises-)
  - [DOM Manipulation Exercises](#dom-manipulation-exercises)
  - [Event Listeners Exercises](#event-listeners-exercises)
- [Exercises Details and Instructions](#exercises-details-and-instructions)
- [Resources](#resources-)

---

## Overview 

This repository contains my solutions to various exercises for mastering interactive JavaScript. All solutions are the result of self-study and learning.

Exercises are focused on fundamental concepts such as:
*  **DOM Manipulations** 
*  **Event Listeners**

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

## List of Exercises 🧩

### DOM Manipulation exercises 


| No. | Exercise Name          | Status      | HTML Code      | JS Code |
| :-- | :--------------------- | :---------- | :------------------ |:------------|
| 1   | [Create and Append Elements](#ex-1)|   ✔️   | [01-HTML](/dom-manipulation/01-create-and-append-elements.html) | [01-JS](/dom-manipulation/01-create-and-append-elements.js) |  
| 2   | [Append and Style Elements](#ex-2)|   ✔️   |[02-HTML](/dom-manipulation/02-append-and-style.html) |[02-JS](/dom-manipulation/02-append-and-style.js) |  |
| 3   | [Insert and Style Elements](#ex-3)|   ✔️   | [03-HTML](/dom-manipulation/03-insert-and-style.html)|[03-JS](/dom-manipulation/03-insert-and-style.js) |  
| 4   | [List Manipulation & Styling](#ex-4)|   ✔️   | [04-HTML](/dom-manipulation/04-list-manipulation-style.html)|[04-JS](/dom-manipulation/04-list-manipulation-style.js) |  
| 5   | [Interactive FAQ Section](#ex-5)|   ✔️   | [05-HTML](/dom-manipulation/05-faq-section.html)|[05-JS](/dom-manipulation/05-faq-section.js) |  
| 6   | [Profile Card](#ex-6)|   ✔️   | [06-HTML](/dom-manipulation/06-profile-card.html)|[06-JS](/dom-manipulation/06-profile-card.js) |  


### Event Listeners exercises 


| No. | Exercise Name          | Status      | HTML Code      | JS Code |
| :-- | :--------------------- | :---------- | :------------------ |:------------|
| 7   | [Inline Event Handler](#ex-7)|   ✔️   | [07-HTML](/event-listeners/07-inline-handler.html) | - |  
| 8  | [Traditional Event Handler](#ex-8)|   ✔️   | [08-HTML](/event-listeners/08-traditional-handler.html) | [08-JS](/event-listeners/08-traditional-handler.js)|  


##  Exercises Details and Instructions 


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

<details id="ex-5">
  <summary><strong>Exercise 5: Interactive FAQ Section</strong></summary>

In this exercise, you will dynamically create and append new elements to build a simple Frequently Asked Questions (FAQ) section. 

You'll start with an empty HTML structure:

```html
<body>
  <div id="faq-container">
    </div>
</body>
```

**Tasks:**

**1.** Get the Container:

  * Get a reference to the `<div>` element with the ID 'faq-container'.

**2.** Create and Style the Main Heading:

  * Create an `<h2>` element.

  * Give it the text content "Frequently Asked Questions".

  * Add a class named 'faq-heading' to this element.

  * Append it to the 'faq-container'.

**3.** Create and Style the First Question:

  * Create an `<h3>` element with the text "What is DOM Manipulation?".

  * Add a class named 'question' to it.

  * Append this `<h3>` to the 'faq-container'.

**4.** Create and Style the First Answer:

  * Create a `<p>` element.

  * Give it the text content "DOM stands for Document Object Model. It is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content."

  * Add a class named 'answer' to this `<p>` element.

  * Append it to the 'faq-container'.

**5.** Create and Style the Second Question and Answer:

  * Using the same methods as above, create another `<h3>` and `<p>` for a second question and answer.

  * The question should be: "Why is it important?".

  * The answer should be: "DOM manipulation allows web developers to create dynamic and interactive web pages without needing to reload the page. This is the foundation of modern web applications."

  * Append both elements to the 'faq-container' in the correct order.


✔️ **Solution:** 
* [05 - HTML Code](./dom-manipulation/04-list-manipulation-style.html)
* [05 - JS Code](./dom-manipulation/04-list-manipulation-style.js)

</details>

---

<details id="ex-6">
  <summary><strong>Exercise 6: Profile Card </strong></summary>

The goal is to create and style a complete profile card using all DOM manipulation skills.The task simulates loading user data, but instead of running on a click, the JavaScript executes as soon as the page loads. You'll begin with an empty `<body>` tag. You'll add all content using JavaScript.

```html
<body>
</body>
```

**Tasks:**

1. Get the Body Element:

    * Get a reference to the `<body>` tag.

2. Create the Profile Card:

    * Create a div element. Give it the id "profile-card". Append it to the `<body>`.

3. Create the Profile Picture:

    * Create an img element. Set its src attribute to "06-profile-card-avatar.png". Set its alt attribute to "Profile Picture". Give it the id "profile-pic". Append it to the "profile-card" div.

4. Create the Name and Status:

    * Create an h2 element. Set its textContent to "John Doe". Give it the id "profile-name". Append it to the "profile-card" div.

    * Create a p element. Set its textContent to "Online". Give it the id "profile-status". Append it to the "profile-card" div.

5. Add Classes and Styles:

    * Add the class "online-status" to the `<p>` element.

    * Set the backgroundColor of the `<p>` element to 'lightgreen' using an inline style.

6. Create the Button:

    *  Create a button element. Set its textContent to "Send Message". Give it the id "message-button". Append it to the "profile-card" div.

✔️ **Solution:** 
* [06 - HTML Code](./dom-manipulation/06-profile-card.html)
* [06 - JS Code](./dom-manipulation/06-profile-card.js)

</details>

---

<details id="ex-7">
  <summary><strong>Exercise 7: Inline Event Handler</strong></summary>

Create a button that displays a message directly from its HTML code.
Begin with a basic HTML file. You'll add the button directly into the `<body>` tag.

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exercise 7: Method 1</title>
</head>
<body>

</body>
</html>
```

**Tasks**:

1. Add a `<button>` element inside the `<body>` tag. Add the text "Click Me!" inside the button tags.

2. Set its onclick attribute to alert ('Hello from Method 1!').

3. Save the file and open it in your browser to test it.

✔️ **Solution:** 
* [07 - HTML Code](./event-listeners/07-inline-handler.html)

</details>

---

<details id="ex-8">
<summary><strong>Exercise 8: Traditional Event Handler</strong></summary>

Connect your HTML and JavaScript files and use the onclick property to set the button's functionality. 

**Initial HTML code**:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exercise 8: Method II</title>
</head>
<body>
    <button id="btn">Click Me!</button>
</body>
</html>
```

**Tasks:**

1. In .js file, get a reference to the button element using `document.querySelector()`.

2. Set the onclick property of the button to a function that displays an alert with the message 'Hello from Method 2!'.

3. Save both files and test your button in the browser.

✔️ **Solution:** 
* [08 - HTML Code](./event-listeners/08-traditional-handler.html)
* [08 - JS Code](./event-listeners/08-traditional-handler.js)

</details>

---

## Resources 📚

This repository contains exercises & assignments with some content sourced from the following resource:

* [The Odin Project: DOM Manipulation and Events](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) | Foundations Course
