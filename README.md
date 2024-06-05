# Connect to Coding | Exploring the Box Model and Generating Base Styles

## Description 📄
In this activity, you will learn how to use Chrome DevTools to examine the box model and CSS code of an element on a live app. You will also learn how to use AI to generate base styles for your HTML document and understand the use and reasoning behind the generated code.

---

## ToDo list ✅
**Attention**: When you complete a task, put an `x` in the middle of the brackets to mark it off your ToDo list.

### Explore the Box Model with Chrome DevTools
1. [ ] Go to [this live app](https://congenial-couscous-n8675z5.pages.github.io/). **Note:** the `?` can be clicked to learn about the app.
2. [ ] Right-click on a box element on the page and select "Inspect" to open Chrome DevTools.
3. [ ] In the Elements panel, select the box element to examine its box model.
4. [ ] Adjust the box model settings through the tool to see how margin, padding, and border affect the element.

### Create and Connect styles.css
5. [ ] Open a new file in your code editor named `styles.css`.
6. [ ] `<link>` it to your index.html `<head>` element.

### Generate Base Box Styles Using AI
7. [ ] Use the following AI prompt to generate base styles for your HTML code. 
    - **Example Prompt:** "Generate base CSS styles for this HTML document which will beused for a food truck website. Follow web development best practices and provide styles for the body, headers, paragraphs, links, and basic layout elements. Also include starter styles for cards and buttons." 
    * **Before you send your main request, copy your HTML code from index.html, paste it after the request, and then send it**
    * You can also try asking it to create or update your HTML for you, for instance by adding a button to your code. The more clear and specific you are, the better your results will typically be.

### Example Response: AI Generated Code
The AI not only can generate CSS, but it can generate updated HTML if asked. Below we'll see a possible CSS response, which may include some things you haven't yet been introduced to.

```css
/* Basic reset styles */
*,
*::before,
*::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

/* Global styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

h1, h2, h3, h4, h5, h6 {
    margin-bottom: 1rem;
}

p {
    margin-bottom: 1rem;
}

a {
    color: #007BFF;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Container class */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header styles */
header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    text-align: center;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

header nav ul li {
    margin: 0 1rem;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Card component styles */
.card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 20px;
    margin: 20px 0;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    text-align: center;
}

.card:hover {
    transform: translateY(-5px);
}

.card img {
    max-width: 100%;
    border-radius: 5px 5px 0 0;
}

.card .card-title {
    color: #e43;
}

.card .card-number {
    font-weight: bold;
}

.card .price {
    color: #e21;
    font-weight: bold;
}

/* Button styles */
.btn-primary {
    background: #007BFF;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s ease;
}

.btn-primary:hover {
    background: #0056b3;
}

.btn-secondary {
    background: #6c757d;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s ease;
}

.btn-secondary:hover {
    background: #5a6268;
}

/* Footer styles */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

```

## Understanding the Code
8. [ ] Ask the AI to explain the use, reasoning, and best practices around some of the code, especially any that you do not fully understand. Try to vary your prompts to get more precise and helpful answers, and if you run into trouble, ask it to help you solve the challenge.
    - **Example prompt:** "Explain the use, reasoning, and best practices for the code you just generated for base styles in a way that’s easy for brand new aspiring developers to understand."
9. [ ] Add the code to your project and view the results in the browser.
10. [ ] Have the AI help you troubleshoot any issues.
11. [ ] Ask the AI to generate an HTML element you'd like to add to your page.
12. [ ] Add, test, and troubleshoot the code as needed with the AI as your coding buddy.
13. [ ] **Review.** Discuss the explanations with your AI, your classmates, and/or your instructor and ask questions if needed. 
    * How helpful were the responses? 
    * Did your AI do what you asked of it? 
    * How might you improve your prompts in the future?

---

🎊 **AWESOME WORK! You just learned how to examine the box model with Chrome DevTools and use AI to generate base styles for your HTML document! 💃🏻🕺🏾** 🎊

---

### Solution codebase 👀
🛑 **Only use this as a reference** 🛑

💾 **Not something to copy and paste** 💾

**Note:** This lab references a solution file located [here](https://github.com/HackerUSA-CE/sdai-ic-d4-css-box-model/tree/solution)