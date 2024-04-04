# Fall 2024 Foundations of Web Design and Development — Final Project

* **Read these instructions repeatedly until you understand, then begin your project. If something is not clear, ask.**

## ❖・Before You Begin・❖

1. Log in to GitHub.
2. Fork this repo(sitory). See [this video](http://code-warrior.github.io/tutorials/git/github/forking-and-cloning-at-the-github-web-site/) on how to carry out this step and step `3`.
3. Clone your fork, using either the web site or the GitHub Desktop client.
4. Checkout your personalized branch, the one with your name and GitHub handle.

---

## ❖・Introduction・❖

For your final project, you’ll be building a portfolio-themed web site of your undergraduate work. If you don’t have a portfolio of work, you have three options:

1. Use a friend’s, colleague’s, or family member’s work as the basis for your project.
2. Create a portfolio of an artist’s or designer’s work whom you admire. (They can be alive or deceased.)
3. Produce a portfolio for a fictitious person or entity using open source images.

I encourage you to consider both traditional web design elements (navigations on top, 960 pixel widths, etc) and non-traditional elements (navigation elements perhaps on the bottom, non-linear display of content, etc). Experiment!

---

## ❖・Preflight・❖

1. As in previous assignments, ensure _editorconfig_, _Stylelint_, and _HTMLHint_ are installed as command line interface, or CLI, tools via Node and as plugins in VS code. You’ll also need to install `stylelint` and `stylelint-config-standard-scss` as Node development dependencies. Do so by running the following command from the root of this project:

```bash
npm i
```

If you encounter an `npm ERR!` error and you’re using macOS, precede the `npm` command with `sudo`:

```bash
sudo npm i
```

2. Recall that CSS is compiled via Sass from your CLI. If you don’t have an alias set up in your environment to work with Sass, then you’ll need to type the following — from the root of this project — each time you work with Sass:

```bash
sass --style=compressed --update --watch scss/style.scss:css/style.css
```

**Note¹**: A folder called `node_modules` will be added to this project’s root folder after you run the `npm i` command from step 1. You’ll need it as you develop this assignment. Thus **do not** delete it.

**Note²**: Ignore any warnings in the `link` elements within the `head` elements of any of your HTML files about `The value of the href attribute ... must be relative.` Do, however, adhere to those warnings within the `body` element.

---
---

## ❖ Due ❖

Monday, 29 April 2024, at 5:00 PM.

---

## ❖ Submission ❖

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may _only_ be submitted via GitHub. **No other form of submission will be accepted**.
