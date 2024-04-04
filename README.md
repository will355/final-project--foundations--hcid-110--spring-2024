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
## ❖ The Rules ❖

* Use two typefaces from [`https://fonts.google.com/`](https://fonts.google.com/).
* Use at least two colors, neither of which may be a neutral. Look to [`https://color.adobe.com/`](https://color.adobe.com/) for ideas.
* No lorem ipsum content; that is, no filler content.
* Only submit files that are required by your project; do not submit working files, such as `.psd`, `.ai`, `.indd`, or `.sketch` files.
* Use lowercase, combined with kebab case, to name folders and files (`do-this` or `do-this.html`); no spaces in folder or file names (`not this`); no camel case (`notThis`); no snake case (`not_this`).
* You may _not_ author _any_ CSS, **only Sass**.
* The Sass files you author _must_ be placed in the included `scss` folder and included as a partial that’s loaded via `style.scss`.
* _Do not_ alter any of the `.gitignore` files.
* _All_ HTML files must go in the root of this folder, with the `index.html` file acting as the springboard for your site.
* All images must be placed in the `img` folder and _must_ be 1MB _or_ smaller.
* Your site must be a multi-page site consisting of at least three segments: _about_, _contact_, and _gallery_ or _portfolio_. These can be folders (`about/`, `contact/`, `gallery/`, or `portfolio/`) or files (`about.html`, `contact.html`, `gallery.html`, or `portfolio.html`).
* Your site must respond to _at least_ the following breakpoints: `400` for phone, `768` for tablet, and `1024` for desktop, all in pixels.
* Your site _cannot_ generate any horizontal scroll bars.
* Your site’s design and UI must be logical, clear, and easy to use.

---

## ❖ Questions to Consider ❖

* What is the trend in pages that display similar content? How far can my design stray from that trend without affecting user experience (UX) negatively?
* Is the contrast between type and (back) ground balanced sufficiently to make reading easy? If not, can I justify why?
* Which typeface will help me to get my meaning across? If using more than one typeface, does each complement each other, and do they work harmoniously with the overall design?
* Is the space I use around content helping the user consume my design, or is it making the user work hard at understanding my intentions?
* Which sections of the content are most important?
* What should be emphasized?
* Does the color scheme complement the message I’m trying to convey, or is it simply serving an aesthetic role in my design?
* Is my design communicating what I need it to?
* Is my site easy to navigate?

---

## ❖ Grading ❖

| Item                                                                           | Points |
|--------------------------------------------------------------------------------|:------:|
| All code is neat, professional, and well-organized                             | `20`   |
| HTML is W3C-compliant                                                          | `15`   |
| Sass is valid and compiles                                                     | `15`   |
| Site responds to phone, tablet, and desktop                                    | `15`   |
| Two external Google typefaces used                                             | `10`   |
| Rules outlined above followed correctly                                        | `05`   |
| Two or more colors used used                                                   | `05`   |
| Proper file naming conventions used                                            | `05`   |
| HTML scaffold is correct                                                       | `05`   |
| Images 1MB or smaller                                                          | `05`   |

---

## ❖ Due ❖

Monday, 29 April 2024, at 5:00 PM.

---

## ❖ Submission ❖

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may _only_ be submitted via GitHub. **No other form of submission will be accepted**.
