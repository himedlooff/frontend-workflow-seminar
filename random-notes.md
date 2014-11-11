Random notes
============

## List of terms

- CLI
- Terminal
- Node.js
- NPM
- Bower
- bower.json
- package.json
- Grunt
- Gruntfile.js

## NPM

**What is it?**
A package manager for Node.js scripts.

**How does it compare with Bower?**
- NPM is for Node.js scripts meant for use in a Node.js environment like the server or your computer. Not used in the browser frequently. Bower is for frontend packaegs that you will be using in the browser.
- NPM uses nested dependencies. Bower uses flat dependencies. Show example.

## Bower

- How do dependencies work? Potential conflicts can arise.
- bower.json answers "what libraries and versions are in use?"
- https://github.com/mdo/preboot

## Grunt

- package.json identifies the tasks needed to automate a project
- Gruntfile.js intro
- tasks to demo:
  - concat
  - minify
  - compile less
  - copy files
  - banner?
  - watch
  - string replace?

> In one word: automation. The less work you have to do when performing repetitive tasks like minification, compilation, unit testing, linting, etc, the easier your job becomes. After you've configured it through a Gruntfile, a task runner can do most of that mundane work for you—and your team—with basically zero effort.

**Other task runners:** gulp, broccoli, ...