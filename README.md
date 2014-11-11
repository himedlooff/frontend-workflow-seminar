Why?
====

Common frontend scenario...

_You're working on a project with other developers and you need to add some functionality. You download the script, place it somewhere in the project folder, embed it on the page along with all the other existing scripts and move on. Later, another developer comes along needing similar functionality for a different page. They download the most up to date version of the same script, place it in a different folder, embed it on their page and move on._

There's a problem here, aside from the lack of communication. There's no clear or established workflow. In response to this a number of frontend tools have emerged. They help us to answer the following questions:

- What libraries and scripts are being used in this project, and what versions are we using?
- What is the process from obtaining these to placing them in our pages?

We will cover a few of these tools and set up a consistent workflow for dealing with these common issues. Future developers will thank you. Heck even your future self will thank you, because sometimes coming back to a project after a few months isn't as easy as it seems.

---

Next: [The universal tool that makes this all happen](cli.md)

---

**Random notes**

1. Command line, the universal tool
- Managing packages with [Bower](http://bower.io/)
- Running tasks with [Grunt](http://gruntjs.com/)

> In one word: automation. The less work you have to do when performing repetitive tasks like minification, compilation, unit testing, linting, etc, the easier your job becomes. After you've configured it through a Gruntfile, a task runner can do most of that mundane work for you—and your team—with basically zero effort.

- https://github.com/mdo/preboot