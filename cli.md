The command line
================

It all starts with the command line interface or CLI, the universal tool. It allows you to interact directly with your operating system by typing commands. On Mac you can interact with the CLI using the Terminal app. Issuing commands are done by first typing the command into Terminal and then pressing the `enter` key. For example try the following command to open a folder on your computer:

**Input**

```bash
open .
```

**Output**

![screenshot of the folder it opened](cli-open.png)

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
