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
| 7   | [I - Inline Event Handler](#ex-7)|   ✔️   | [07-HTML](/event-listeners/07-inline-handler.html) | - |  
| 8  | [II - Traditional Event Handler](#ex-8)|   ✔️   | [08-HTML](/event-listeners/08-traditional-handler.html) | [08-JS](/event-listeners/08-traditional-handler.js)|  
| 9 | [III - Modern Event Handler](#ex-9)|   ✔️   | [09-HTML](/event-listeners/09-modern-handler.html) | [09-JS](/event-listeners/09-modern-handler.js)|  
| 10 | [Three Buttons](#ex-10)|   ✔️   | [10-HTML](/event-listeners/10-3-buttons.html) | [10-JS](/event-listeners/10-3-buttons.js)|  
| 11 | [Styling with Buttons](#ex-11)|   ✔️   | [11-HTML](/event-listeners/11-style-buttons.html) | [11-JS](/event-listeners/11-style-buttons.js)| 
 | 12 | [Dynamic Text & Color](#ex-12)|   ✔️   | [12-HTML](/event-listeners/12-dynamic-txt-color.html) | [12-JS](/event-listeners/12-dynamic-txt-color.js)| 
 | 13 | [Simple Night Mode Toggle](#ex-13)|   ✔️   | [13-HTML](/event-listeners/13-simple-night-mode.html) | [13-JS](/event-listeners/13-simple-night-mode.js)| 
 | 14 | [3 Methods w/ Named Functions](#ex-14)|   ✔️   | [14-HTML](/event-listeners/14-named-func.html) | [14-JS](/event-listeners/14-named-func.js)| 
 | 15 | [Event Listener - Anon & Named Function](#ex-15)|   ✔️  | [15-HTML](/event-listeners/15-events-anon-named.html) | [15-JS](/event-listeners/15-events-anon-named.js)| 
 | 16 | [Interactive card - Hovering](#ex-16)|   ✔️  | [16-HTML](/event-listeners/16-interactive-card.html) | [16-JS](/event-listeners/16-interactive-card.js)| 
  | 17 | [Interactive Topic Gallery](#ex-17)|   ✔️  | [17-HTML](/event-listeners/17-interactive-gallery.html) | [17-JS](/event-listeners/17-interactive-gallery.js)| 
  | 18 | [Single-Select Topic Gallery](#ex-18)|   ✔️  | [18-HTML](/event-listeners/18-single-gallery.html) | [18-JS](/event-listeners/18-single-gallery.js)| 
 

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

<details id="ex-9">
<summary><strong>Exercise 9: Modern Event Listener</strong></summary>

Use the `addEventListener()` method, which is the most flexible and recommended approach.
Create .html and .js files, linked in the same way as in the previous exercise.

**Initial HTML code:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exercise 9: Method III - 'addEventListener'</title>
</head>
<body>
    <button id="btn">Click Me!</button>
</body>
</html>
```

**Tasks:**

1. In .js file, get a reference to the button and use the `addEventListener()` method on the button.

2. Pass 'click' as the first argument.

3. Pass a function that displays an alert with the message 'Hello from Method 3!' as the second argument.

4. Save both files and test your button.

✔️ **Solution:** 
* [09 - HTML Code](./event-listeners/09-modern-handler.html)
* [09 - JS Code](./event-listeners/09-modern-handler.js)

</details>

---

<details id="ex-10">
<summary><strong>Exercise 10: Three Buttons</strong></summary>

 Create a single web page with three different buttons, each using a distinct method to handle a "click" event.

**Initial HTML code:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise 10: Mixed Event Handlers</title>
</head>
<body>
    <h1>Event Handler Showcase</h1>
    <button id="btn1" >Button 1</button>
    <button id="btn2">Button 2</button>
    <button id="btn3">Button 3</button>

    <p id="message-display">Messages will appear here!</p>
</body>
</html>
```

**Tasks:**

**1. Button 1 (Inline Event Handler):**

* Modify the HTML file to add an onclick attribute directly to 'btn1'.

* The value of this attribute should be a JavaScript command that updates the text of the `<p>` element (with the ID 'message-display') to "You clicked Button 1 using an inline handler!"

**2. Button 2 (Traditional Event Handler):**

* In your .js file, get a reference to 'btn2' using document.getElementById().

* Set its onclick property to a function that changes the text of the `<p>` element to "You clicked Button 2 using a traditional handler!"

**3. Button 3 (Modern Event Listener):**

* In your .js file, get a reference to btn3.

* Use the `addEventListener()` method on this button. The event type should be 'click', and the function should update the text of the `<p>` element to "You clicked Button 3 using a modern event listener!"

**Testing:** Save both files and open the HTML file in your browser. Verify that clicking each button updates the text of the message display as specified.

✔️ **Solution:** 
* [10 - HTML Code](./event-listeners/10-3-buttons.html)
* [10 - JS Code](./event-listeners/10-3-buttons.js)

</details>

---

<details id="ex-11">
<summary><strong>Exercise 11: Style with Buttons</strong></summary>

Create a single web page with three buttons. 
Each button will use a different JavaScript event handler method to change the background color of the same `<div>` element.

**Initial HTML code:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Three-Button Stylist</title>
    <style>
        #color-box {
            width: 200px;
            height: 200px;
            border: 2px solid black;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Change the Color</h1>
    <button id="btn1">Change to Red</button>
    <button id="btn2">Change to Blue</button>
    <button id="btn3">Change to Green</button>

    <div id="color-box"></div>

</body>
</html>
```

**Tasks:**

**1. Button 1** (Inline Event Handler):

* Directly in the HTML file, add an onclick attribute to btn1.

* The value of this attribute should be a JavaScript command that finds the div element with id="color-box" and sets its background color style to 'red'.

**2. Button 2** (Traditional Event Handler):

* In your .js file, get a reference to btn2 using `getElementById()`.

* Set its onclick property to a function that finds the #color-box element and changes its background color to 'blue'.

**3. Button 3** (Modern Event Listener):

* In .js file, get a reference to btn3.

* Use the `addEventListener()` method to listen for a 'click' event and run a function that sets the background color of #color-box to 'green'.

✔️ **Solution:** 
* [11 - HTML Code](./event-listeners/11-style-buttons.html)
* [11 - JS Code](./event-listeners/11-style-buttons.js)

</details>

---

<details id="ex-12">
<summary><strong>Exercise 12: Dynamic Text and Color</strong></summary>

Create a web page with a single button and a `<p>` element. When the button is clicked, it should change the text content of the `<p>` element and also change the text color to red.

**Initial HTML Code:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Content</title>
</head>
<body>
    <h1>Change Text & Color</h1>
    <button id="changeBtn">Change It</button>
    <p id="displayText">The text will change here.</p>
</body>
</html>
```

**Tasks:**

1.  Get a reference to both the button and the paragraph using `document.getElementById()`.

2. Add an Event Listener. 

* Inside the function, update the textContent of the `<p>` element to "You clicked the button!".

* Change Color: Still inside the same function, change the color of the `<p>` element's text to 'red' by directly modifying its style.color property.

✔️ **Solution:** 
* [12 - HTML Code](./event-listeners/12-.html)
* [12 - JS Code](./event-listeners/12-.js)

</details>

---

<details id="ex-13">
<summary><strong>Exercise 13: Simple Night Mode Toggle</strong></summary>

Create a night mode option for website by switching it with night mode button.

**Initial Codes:**

* **HTML Code**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Night Mode Toggle</title>
</head>
<body>
    <button id="modeBtn">Night Mode: TURN ON 🌙</button>
    <h1>Welcome to my page</h1>
    <p>This is a paragraph of text that will change color.</p>
</body>
</html>
```

* **CSS Code**
```css
body {
    background-color: white;
    color: black;
    font-family: Arial, sans-serif;
    transition: all 0.5s ease;
}

.night-mode {
    background-color: #121212;
    color: #f1f1f1;
}

#modeBtn {
    padding: 10px 20px;
    font-size: 16px;
    border: 1px solid #333;
    background-color: #f1f1f1;
    color: #333;
    cursor: pointer;
    transition: all 0.5s ease;
}

.night-mode #modeBtn {
    background-color: #f1f1f1;
    color: #333;
    border-color: #f1f1f1;
}
```
**Tasks:**

1. Get elements reference in JavaScript. Add Event Listener, add a 'click' event listener to the button.

2. Inside the event listener function, use `classList.toggle()` on document.body to add or remove the night-mode class.

3. (*Optional, but useful step*) 

Inside the same function, add logic to check if the night-mode class is active. If it is, change the button's text to "Night Mode: TURN OFF 🌞". If it's not, change it back to "Night Mode: TURN ON🌙".

✔️ **Solution:** 
* [13 - HTML Code](./event-listeners/13-simple-night-mode.html)
* [13 - CSS Code](./event-listeners/13-simple-night-mode.css)
* [13 - JS Code](./event-listeners/13-simple-night-mode.js)

</details>

---

<details id="ex-14">
<summary><strong>Exercise 14: 3 Methods w/ Named Functions</strong></summary>

This task aims to show three different methods (as exercised above) to run a named function when a button is clicked.

**Initial Code:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Handlers</title>
</head>
<body>
    <h1>Three Methods with Named Functions</h1>

    <div>
        <button id="btn1">1. `onclick` attribute</button>
        <p id="message1">Method 1: The text will change.</p>
    </div>

    <hr>

    <div>
        <button id="btn2">2. `onclick` property</button>
        <p id="message2">Method 2: The text will change.</p>
    </div>

    <hr>

    <div>
        <button id="btn3">3. `addEventListener()`</button>
        <p id="message3">Method 3: The text will change.</p>
    </div>
</body>
</html>
```


**Tasks:**

In your .js file, create three named functions. Each function should change the text in its corresponding paragraph. Then, link each function to its button using one of the three methods.

**1. Method 1 (onclick attribute):** Write the function `handleMethod1()`. 

**2. Method 2 (onclick property):** Write the function `handleMethod2().` 

Get the btn2 button and assign the function to its onclick property.

**3. Method 3 (addEventListener):** Write the function `handleMethod3()`. 

Get the btn3 button and add a click event listener that runs this function.


✔️ **Solution:** 
* [14 - HTML Code](./event-listeners/14-named-func.html)
* [14 - JS Code](./event-listeners/14-named-func.js)

</details>

---

<details id="ex-15">
<summary><strong>Exercise 15: Event Listener with Anon and Named Function </strong></summary>

This exercise will let you practice two key methods for writing event functions: using a named function and an anonymous function. We'll use two different events: click and dblclick (double-click).

**Initial Code:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Listeners</title>
    <style>
        #infoBox {
            width: 300px;
            height: 150px;
            padding: 20px;
            margin: 50px auto;
            border: 2px solid #333;
            text-align: center;
            line-height: 1.5;
            cursor: pointer;
            background-color: #f1f1f1;
            transition: background-color 0.5s ease;
        }
    </style>
</head>
<body>
    <h1>Click or double-click!</h1>
    <div id="infoBox">
        <p>Click once to change the text.</p>
        <p>Click twice to change the background color.</p>
    </div>
</body>
</html>
```
**Tasks:**

In your .js file, create the functionality for the div element above.

**1. Named Function**

* Write a named function (e.g., changeText). Inside this function, change the text of the paragraph inside the infoBox to "The text has been changed!".

* Get a reference to the #infoBox.

* Add a click event listener that calls your named function.

**2. Anonymous Function** 

* On the #infoBox, add another event listener, but this time for the dblclick event.

* Instead of calling a named function, write an anonymous function directly inside the event listener.

* Inside this anonymous function, change the background-color of the infoBox element to "lightblue".

✔️ **Solution:** 
* [15 - HTML Code](./event-listeners/15-events-anon-named.html)
* [15 - JS Code](./event-listeners/15-events-anon-named.js)

</details>

---

<details id="ex-16">
<summary><strong>Exercise 16: Interactive Card - Hovering</strong></summary>

Create an interactive information "card" that reacts to two different events: 
* `mouseenter` (when the mouse enters the element's area) 
* `mouseleave` (when the mouse exits).

**Initial Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Info Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #e0e0e0;
            margin: 0;
        }
        #infoCard {
            width: 300px;
            height: 200px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            transition: all 0.3s ease-in-out;
            border: 2px solid transparent;
            padding: 20px;
        }
        #infoCard h2 {
            margin-top: 0;
            color: #333;
        }
        #infoCard p {
            color: #666;
            transition: opacity 0.3s ease-in-out;
            opacity: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div id="infoCard">
        <h2>Hover me!</h2>
        <p>Here are some extra details that will appear.</p>
    </div>
</body>
</html>
```

**Tasks**

 **Step 1: Setup**

* Create a new JavaScript file. Link it to your HTML file. 
* In your JS file, get a reference to the #infoCard element.

 **Step 2: `mouseenter` Functionality**

 * Write a named function called 'showInfo'. Inside this function, get the `<p>` tag within the card and set its opacity style to 1.

* Also, within the same function, change the border color of the #infoCard element to '2px solid #007bff'.

* Add a mouseenter event listener to the #infoCard element that calls your showInfo function.

**Step 3: `mouseleave` Functionality**

* On the #infoCard element, add a second event listener, this time for the mouseleave event.
For this event, use an anonymous function directly inside the event listener.

* Inside the anonymous function, set the opacity of the paragraph back to 0.

* Also, within the same function, change the border color back to '2px solid transparent'.

💡 **Hint:**

This is the equivalent of what you achieve with the CSS pseudo-class `:hover`. The advantage of the JavaScript approach is that it gives you much more flexibility and control over what happens (e.g., you can change text, color the background, start animations, or even send data to a server), whereas CSS is limited to style changes.

✔️ **Solution:** 
* [16 - HTML Code](./event-listeners/16-interactive-card.html)
* [16 - JS Code](./event-listeners/16-interactive-card.js)

</details>

---

<details id="ex-17">
<summary><strong>Exercise 17: Interactive Gallery</strong></summary>

Create three interactive "topic cards." Clicking on any card will change its appearance, and clicking it again will revert it to its original state.

**Initial Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Topics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #e9ecef;
            gap: 20px;
            padding: 20px;
        }
        .topic-card {
            width: 250px;
            padding: 25px;
            background-color: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            text-align: center;
            cursor: pointer;
            border: 2px solid transparent;
        }
        .topic-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
        }
        .topic-card h3 {
            margin-top: 0;
            color: #333;
        }
        .topic-card p {
            color: #666;
            font-size: 0.9em;
        }
        /* The class you will activate with JavaScript */
        .topic-card.active {
            background-color: #d4edda;
            border-color: #28a745;
            transform: translateY(-10px);
        }
    </style>
</head>
<body>
    <div class="topic-card">
        <h3>Web Development</h3>
        <p>Learn to build interactive pages with HTML, CSS, and JS.</p>
    </div>
    <div class="topic-card">
        <h3>UX/UI Design</h3>
        <p>Create user interfaces that are intuitive and visually appealing.</p>
    </div>
    <div class="topic-card">
        <h3>E-learning</h3>
        <p>Design and implement digital educational content.</p>
    </div>
</body>
</html>
```

**Tasks**

**1. Get the group of elements:**

 In your JavaScript file, get all elements with the class topic-card. The result will be a NodeList, similar to an array.

**2. Iterate through the group: **

Use a forEach loop to go through each element you've retrieved.

** 3. Add an event listener:**

 Inside the forEach loop, add a click event listener to each individual card.

** 4. Toggle the class:**
 Inside the click event listener function, use this (or the variable name that represents the individual card in the loop) and the classList.toggle('active') method. 


✔️ **Solution:** 
* [17 - HTML Code](./event-listeners/17-interactive-gallery.html)
* [17 - JS Code](./event-listeners/17-interactive-gallery.js)

</details>

---

---

<details id="ex-18">
<summary><strong>Exercise 18: Single-Select Topic Gallery</strong></summary>

Modify the JavaScript code from previous exercise. The goal is to make it so that **only one** topic card can be active at a time, similar to a radio button or a multiple-choice quiz. This is a very common and practical pattern for creating interactive web content.

**Initial Code:**

Use the exact same initial code you used for the previous exercise. 
Your changes will only be in the JavaScript file.

**Tasks**

**1. Get the NodeList: **

Start by getting a reference to all the topic cards using document.querySelectorAll(), just as you did before.

**2. Iterate and Listen:**

 Add a click event listener to each card using a forEach loop.

** 3. Implement the Single-Select Logic: **

This is the new part. Inside the click event handler for a card, you need to add a few lines of code to handle the selection logic.

* First, iterate through all of the cards in the NodeList again.

* Inside this loop, remove the .active class from every single card. This ensures all cards are "turned off" before you select a new one.

* Finally, add the .active class to the specific card that was just clicked. You can use the this keyword or the card variable from your forEach loop to refer to the clicked element.

✔️ **Solution:** 
* [18 - HTML Code](./event-listeners/18-single-gallery.html)
* [18 - JS Code](./event-listeners/18-single-gallery.js)

</details>

---

## Resources 📚

This repository contains exercises & assignments with some content sourced from the following resource:

* [The Odin Project: DOM Manipulation and Events](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) | Foundations Course
