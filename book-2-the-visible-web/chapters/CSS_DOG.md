| Previous Chapter | Next Chapter |
| :------------- |:-------------|
| [Codecademy CSS Course](./CSS_CODECADEMY.md) | [Book 3 - The Invisible Web](../../book-3-the-invisible-web/README.md) |

<br/>
<br/>

# Adding CSS to your Web Page

> **IMPORTANT:** For the Foundations Course, when you see the words "terminal" or "command line", it means Git Bash for Windows users. For Mac users, it is the Terminal application.

Back to working locally, on your machine, to apply CSS styles to the file you created in the HTML chapter. You are going to practice some more bash commands so you can copy a file from one directory to another. You are going to leave the `myfirstpage.html` that you created previously untouched. You are going to create a copy of it and work on that copy.

Open your terminal, change your location to the `css` directory you created previously, and copy the file. Remember the pattern for copying a file.

`cp [what to move] [where to move it]`

Copy your file to the `css` directory. The dot in bash means "current directory".

```sh
cd ~/workspace/foundations/css
cp ../html/myfirstpage.html .
```

Now that you have copied the file into this directory, you are going to rename the file to `index.html`. This is the default document that gets shown to users who visit any web site.

```sh
mv myfirstpage.html index.html
```

Now launch Visual Studio Code in this directory with **`code .`**

## Assignment

Visit the HTML Dog [CSS Beginner Tutorial](https://www.htmldog.com/guides/css/beginner/), and learn how to add styles and layout to your `index.html` web page that you created a couple chapters ago. Your knowledge of selectors, colors, spacing, borders, and text that you learned in the Codecademy course will be reinforced in this assignment.

<br/>
<br/>
<br/>
<br/>
<br/>

| Previous Chapter | Next Chapter |
| :------------- |:-------------|
| [Codecademy CSS Course](./CSS_CODECADEMY.md) | [Book 3 - The Invisible Web](../../book-3-the-invisible-web/README.md) |
