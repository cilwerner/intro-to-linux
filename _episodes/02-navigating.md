---
title: "Navigating Files and Directories"
teaching: 10
exercises: 0
questions:
- "What is the directory tree?"
- "How can I move around the computer?"
- "What happens if I get lost?"
- "How can I see files and directories?"
objectives:
- "To gain understanding of the directory tree, and navigate through it as effectively as a GUI interface"
- "Explain the similarities and differences between files and directories."
- "Gain understanding of relative and actual paths."
- "Use options and arguments to change the behaviour of a shell command."
- "Demonstrate the usage of tab completion, and explain its advantages."
keypoints:
- "Information is stored in files, which are stored in directories. A directory is itself a file which contains references to other files."
- "The `pwd` command will always show where you are at any time."
- "The `ls` command lists the contents of the present working directory. Additional options and arguments can filter this list further."
- "The `cd` command allows you to navigate through directories, **BUT** you also need to direct it to where you want to go using `cd [path]`."
- "The root directory is specified by the root directory, referred to as `/`."
- "Directory names in a path are separated with '/' on Unix and Mac, but by '\' on Windows."
- "An absolute path specifies a location from the "
- "`..` means 'the directory above the current one' in the directory tree, whereas `.` on its own specifies 'the current directory."
---

<p align="center"><img src="../fig/ICHEC_Logo.jpg" width="40%"/></p>

## The directory tree

If you are used to using click and select GUI operations for finding your way through files and folders on your
computer, then using the command line to navigate around for the first time is similar to being dropped into a 
thick maze in the dark without a torch. 

{% include links.md %}
