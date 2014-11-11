Why?
====

Common frontend scenario...

_You're working on a project with other developers and you need to add some functionality. You download the script, place it somewhere in the project folder, embed it on the page along with all the other existing scripts and move on. Later, another developer comes along needing similar functionality for a different page. They download the most up to date version of the same script, place it in a different folder, embed it on their page and move on._

There's a problem here, aside from the lack of communication. There's no clear or established workflow. In response to this a number of frontend tools have emerged. They help us to answer the following questions:

- What libraries and scripts are being used in this project, and what versions are we using?
- What is the process from obtaining these to placing them in our pages?

We will cover a few of these tools and set up a consistent workflow for dealing with these common issues. Future developers will thank you. Heck even your future self will thank you, because sometimes coming back to a project after a few months isn't as easy as it seems.

The tools
=========

## The command line

It all starts with the command line interface or CLI, the universal tool. It allows you to interact directly with your operating system by typing commands. Issuing commands are done by first typing the command and then pressing the `enter` key. For example try the following command to open a folder on your computer:

**Input**
```bash
open .
```

**Output**
![placeholder: screenshot of the folder it opened]()

`.` means the current folder that the CLI is in. If you're ever interested in knowing what folder you're currently in you can ask it:

**Input**
```bash
pwd
```

**Output**
```bash
/Users/himedlooff
```

This stands for "print working directory".

Interested in what files or folders are in the working directory?

**Input**
```
ls
```

**Output**
```bash
Applications		Movies			    VirtualBox VMs
Desktop			    Music			    lib
Documents		    PdaNetUninstall.sh	npm-debug.log
Downloads		    Pictures		    tmp
Dropbox			    Public
Library			    Sites
```

This command stands for "list", and gives you a list of all of the files and folders in the current folder. Compare what your CLI is showing to the folder that the CLI opened when you typed `open .`. They should show the same files and folders.

---

Notes
=====

1. Command line, the universal tool
- Managing packages with [Bower](http://bower.io/)
- Running tasks with [Grunt](http://gruntjs.com/)

> In one word: automation. The less work you have to do when performing repetitive tasks like minification, compilation, unit testing, linting, etc, the easier your job becomes. After you've configured it through a Gruntfile, a task runner can do most of that mundane work for you—and your team—with basically zero effort.

- https://github.com/mdo/preboot