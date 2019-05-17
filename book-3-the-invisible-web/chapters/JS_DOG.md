[Welcome](../../) > [Book 3 - The Invisible Web](../README.md) > HTML Dog - JavaScript

# HTML Dog - JavaScript Beginner Tutorial

## Setup

> **IMPORTANT:** For the Foundations Course, when you see the words "terminal" or "command line", it means Git Bash for Windows users. For Mac users, it is the Terminal application.

Time to copy files again. You're going to leave the code your wrote in `index.html` for the CSS course alone, and work on a copy of it for the JavaScript course.

1. In your terminal, move to your `javascript` directory, and copy the `index.html` file into it. Again, make sure you put that dot at the end so that it is copied into the current directory.
    ```sh
    cd ~/workspace/foundations/javascript
    cp ../css/index.html .
    ```
1. Your next step is to create another file that will contain all of the JavaScript you will write for this tutorial. In the terminal, you use the `touch` command to create files. Then open this directory in Visual Studio Code. Make sure you put the dot at the end.
    ```sh
    touch main.js
    code .
    ```
1. Now that your HTML and JavaScript files are created, you need to link them together using a `<script>` tag in your `index.html`. Open `index.html` and find the closing body tag near the bottom. It will look like this: `</body>`
    ```html
    <script src="./main.js"></script>
    ```


Now visit the HTML Dog [JavaScript Beginner Tutorial](https://www.htmldog.com/guides/javascript/beginner/) and use your `main.js` file to write all of your JavaScript as you go through the course.
