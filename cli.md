The command line
================

It all starts with the command line interface or CLI, the universal tool. It allows you to interact directly with your operating system by typing commands. On Mac you can interact with the CLI using the Terminal app. Issuing commands are done by first typing the command into Terminal and then pressing the `enter` key. For example try the following command to open a folder on your computer:

_Input_

```bash
open .
```

`.` means the current folder that the CLI is in.

_Output_

![screenshot of the folder it opened](cli-open.png)

---

**If you're ever interested in knowing what folder you're currently in you can ask it:**
 
_Input_

```bash
pwd
```

`pwd` stands for "print working directory".

_Output_

```bash
/Users/himedlooff
```

---

**Interested in what files or folders are in the working directory?**

_Input_

```bash
ls
```

`ls` stands for "list", and gives you a list of all of the files and folders in the current folder. Compare what your CLI is showing to the folder that the CLI opened when you typed `open .`. They should show the same files and folders.

_Output_

```bash
Applications		Movies
Desktop			    Music
Documents		    Pictures
Downloads
Dropbox
Library
```

---

**Now let's make a new folder for our project.**

_Input_

```bash
mkdir frontend-tools-demo
```

Then:

```bash
ls
```

`mkdir` stands for "make directory".

_Output_

```bash
Applications		Library
Desktop			    Movies
Documents		    Music
Downloads           Pictures
Dropbox
frontend-tools-demo
```

---

You should now have a new folder in the working directory. We'll use this folder as an example project folder. To move into it type the following:

```bash
cd frontend-tools-demo
```

`cd` stands for "change directory".

_Note that if you type `cd front` then press the `tab` key, the CLI will attempt to autocomplete the directory name based on the list of files in the working directory._

Now that we have some CLI basics out of the way we can move on to installing Bower, a tool to help us manage the different libraries we use in our projects.

---

Next: ...

---
