| Previous Chapter | Next Chapter |
| ------------- |:-------------|
| [Chapter 1 - Codecademy HTML Course](./HTML_CODECADEMY.md) | [Chapter 3 - Codecademy CSS Course](./CSS_CODECADEMY.md) |

<br/>

# HTML Dog - Beginner HTML Tutorial

Another free web site that contains a large set of tutorials is *HTML Dog*. That is where you are headed next to practice using the HTML elements you first learned at Codecademy.

The next step is to build your own web page on your computer instead of the integrated editor and browser that Codeacemy gives you. To set you up for success, follow these instructions before moving on to the assignment.

## Setup for Coding on Your Machine

### Visual Studio Code

You need to make sure that you can run Visual Studio Code from the command line. It will make your life tremendously easier once you get the hang of it.

1. Run the Visual Studio Code application.
1. Open the command list by typing in the keyboard shortcut that applies to you.
    1. On Windows, `control+shift+p`
    1. On Mac, `shift+command+p`
1. A list of commands will immediately appear with an input field.
1. Type in the following text, "shell command" and the list of command will filter down to 2 options.
1. Select the *_Install 'code' command in PATH_* option.
1. Close Visual Studio Code and move on to the next series of instructions.

### Directories and Files

1. If you did not install everything that was listed in the previous book, please go back and do that. You will need Visual Studio Code installed as your code editor.
1. Open your terminal and change your location to your home directory.
    ```sh
    cd ~
    ```

1. Make a new sub-directory named `workspace` and use `cd` to move to that directory. Try your tab completion skills with the `cd` command. Type just the first couple of letters and hit your tab key.
    ```sh
    mkdir workspace
    cd workspace
    ```

1. This is the directory which will contain all of the work that you do while you are at NSS. While you are working through the *Foundations Course*, make sure it is separated from the work you will do in class. Make a new sub-directory inside workspace named `foundations`.
    ```sh
    mkdir foundations
    cd foundations
    ```
1. You will be working on HTML, CSS and JavaScript during the *Foundations Course*, so to keep your work organized, make three new sub-directories to hold the work for each of these languages.
    ```sh
    mkdir html
    mkdir css
    mkdir javascript
    ```
1. Then move to your `html` directory.
    ```sh
    cd html
    ```
1. Now use your `pwd` command to see where you are currently located in your terminal. You should see the following path at the end of the output. There will be more information to the left, but that is different for everyone. As long as the last three directory look like the path below, you are fine.
    ```sh
    workspace/foundations/html
    ```
1. The next assignment asks you to create a file named `myfirstpage.html` so you can create it in this directory.
    ```sh
    touch myfirstpage.html
    ```
1. Now launch Visual Studio Code and it will start with the files in this directory automatically ready to be accessed and edited. Putting the dot after the `code` command is important - don't forget it.
    ```sh
    code .
    ```
1. Once Code finishes loading, on the left you will see the `myfirstpage.html` file. Double-click it to start editing.
1. Now you're ready to start on your next assignment. Read the notes below before you begin.

> **NOTE:** HTML Dog suggests you use Notepad, but you will use Visual Studio Code as your editor.

> **NOTE:** While you are working, if you close Chrome completely, or just the tab you are working on, you can always open a new tab and use `ctrl+O` on Windows or `command+O` on Mac to open your file again. That's an O, not a zero.

## Assignment

Visit and complete the [HTML Beginner Tutorial](https://www.htmldog.com/guides/html/beginner/) course on HTML Dog. They estimate that it will take four hours of your time to read the content, work on exercises, and complete the project(s) they assign you. We want you to start with this course because it has you coding immediately, not doing a lot of reading about theory.

<br/>
<br/>
<br/>

| Previous Chapter | Next Chapter |
| ------------- |:-------------|
| [Chapter 1 - Codecademy HTML Course](./HTML_CODECADEMY.md)      | [Chapter 3 - Codecademy CSS Course](./CSS_CODECADEMY.md) |
