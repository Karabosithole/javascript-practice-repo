# **JavaScript Practice Repository**

This is my personal JavaScript practice repo. I'm using it to sharpen my skills in both **Node.js** and **browser-based JavaScript**. The goal is to cover the basics, dive into advanced topics, and work on small projects that help me get more practice in JavaScript .

---

## **Setup Instructions**

1. Clone the repo:
   ```bash
   git clone https://github.com/Karabosithole/javascript-practice.git
   cd javascript-practice
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

---

## **How I’ll Use This Repo**

### **Node.js Practice**
I can run any JavaScript file directly in the terminal using Node.js. For example:
```bash
node src/basics/variables.js
```
This is great for learning core JavaScript concepts and working with server-side code.

### **Browser Practice**
For anything involving the DOM or browser-specific features:
1. Open the `index.html` file in a browser.
2. Check the **Console** tab in DevTools to see the output.

I’ll also use **Live Server** in VS Code to make this easier. 

---

## **Repo Structure**

Here’s how I’ve organized everything:

```
/javascript-practice
│
├── /src
│   ├── /basics          # Practice the JavaScript fundamentals
│   ├── /advanced        # Work on more advanced JavaScript concepts
│   ├── /projects        # Mini-projects for hands-on experience
│   └── index.js         # General practice entry point for Node.js
│
├── /tests               # Unit tests for practice files
├── index.html           # Entry point for browser-based practice
├── package.json         # Node.js package config
├── .gitignore           # Ignored files
└── README.md            # Notes about the repo
```

---

## **What I’m Practicing**

### **Basics**
- Variables (`src/basics/variables.js`)
- Functions (`src/basics/functions.js`)
- Arrays and Objects (`src/basics/arrays.js`, `src/basics/objects.js`)
- Loops and Control Flow (`src/basics/loops.js`)

### **Advanced Topics**
- Promises and Async/Await (`src/advanced/promises.js`, `src/advanced/async_await.js`)
- Modules (`src/advanced/modules.js`)
- Classes and Prototypes (`src/advanced/classes.js`, `src/advanced/prototypes.js`)

### **Projects**
- A calculator (`src/projects/calculator.js`)
- A to-do list app (`src/projects/todo_list.js`)
- Fetching data from an API (`src/projects/weather_api.js`)
- A stopwatch (`src/projects/stopwatch.js`)

---

## **How I Test My Code**
I’m using **Jest** for testing. To run all tests:
```bash
npm test
```
Each test file lives in `/tests` and matches a corresponding file in `/src`.

---

## **Reminders for Myself**
1. Use `console.log()` a lot to debug and understand what’s happening.
2. Commit changes regularly with meaningful messages.
3. Explore new tools and concepts along the way.
4. Keep things simple and focus on learning.

