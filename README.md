# Learning JavaScript with HTML/CSS

## Lesson 1: Hello World

Our first website.

## Lesson 1 to-do list

### Install software
* [x] Install Atom. https://atom.io/
* [x] Install GitKraken. https://www.gitkraken.com/
* [x] Optional: install Mac OS X command line tools. `xcode-select --install`

### Set up GitHub
* [x] Create GitHub account. https://github.com/join
* [x] Join **NeihuCode** organization on GitHub.
* [x] Fork/clone hello-world repository. https://github.com/neihucode/hello-world
* [ ] Copy the contents of `README.md` to a new issue in your repo.
* [ ] Change Settings -> GitHub Pages -> Source: `master branch /docs folder`

### Learn some Git, some HTML, some CSS
* [ ] View your new website. `*[your github account name]*.github.io/hello-world/`
* [ ] On GitHub, edit docs/index.html; add `<head><title>`. Save your change as a **commit**.
* [ ] Clone your GitHub repo with **GitKraken** app.
* [ ] Open your project files with **Atom**. ~/Sites/hello-world
* [ ] Edit docs/index.html; change `<p>` to `<h1>` and add paragraph of text.
* [ ] **Commit** your changes.
* [ ] **Push** your changes to GitHub and reload your website.
* [ ] Edit docs/index.html; add a `<link rel="stylesheet" href="css/styles.css">`. Create css folder and a css/styles.css file.
* [ ] Edit css/styles.css; add h1 hover styling.

### Learn Git branching and JavaScript.
* [ ] **Merge** the **branch** from your new pull request; it adds HTML and images.
* [ ] **Pull** the new changes from GitHub to your computer (using **GitKraken**).
* [ ] Learn about the new `<figure>`, `<figcaption>` and `<img>` HTML elements.
* [ ] Learn about the jQuery library that the pull request added. In your browser's console, run: `$('.carousel').slideToggle(5000)` which is documented at: http://api.jquery.com/slideToggle/
* [ ] Add Slick carousel to your project. Follow instructions under  "Example using jsDelivr" of https://github.com/kenwheeler/slick/ to add `link` and `script` tags to CSS and JS files.

## What we learned

* **Git** is a version control system
  * GitHub has a *copy* of your Git **repository**.
  * Making a **clone** of a repository, copies it.
  * To make a change to your code, you **stage** the changes, write a commit message, and then **commit** that single change to your code.
  * After you make changes to your code, you can share the new changes when you **push** commits to GitHub.
  * If you want to change someone else's code, you create a **branch** with your new commits; then you can create a **pull request** on GitHub and the repository owner can choose to **merge** your branch into their master branch.
  * The name of the default branch is *master*.
  * To get new changes of your code, you **pull** them from GitHub.
* **HTML** is HyperText Markup Language
  * An HTML document contains regular text content wrapped with HTML tags.
  * The special `<!DOCTYPE html>` tag tells browsers we are using HTML 5, the fifth major version of HTML.
  * The `<body>` tag contains the body of our content.
  * The `<head>` tag contains the `<title>` and links to CSS files.
  * The `<script>` tag loads a JavaScript file.
