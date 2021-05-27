---
title: "Working with files and directories"
teaching: 10
exercises: 0
questions:
- "How do I create, copy, delete files and directories?"
objectives:
- "How to create a directory hierarchy that matches a given diagram and how to navigate through it."
- "Delete, copy and move specified files and/or directories"
keypoints:
- "Most files' names are `something.extension`. The extension isn't required, and doesn't guarantee anything,
  but is normally used to indicate the type of data in the file."
- "`cp [old] [new]` copies a file."
- "`mv [old] [path]` moves a file into the specified path, `mv [old] [new]` renames a file."
- "`mkdir [path]` creates a new directory."
- "`rmdir [path]` removes an empty directory. `rm [path]` removes a file. These are irreversible as the shell
  does not have a recycle bin."
- "`*` matches zero or more characters in a filename, so `*.txt` matches all files ending in `.txt`."
- "`?` matches any single character in a filename, so `?.txt` matches `a.txt` but not `any.txt`."
- ""
---

<p align="center"><img src="../fig/ICHEC_Logo.jpg" width="40%"/></p>

## The directory tree

If you are used to using click and select GUI operations for finding your way through files and folders on your
computer, then using the command line to navigate around for the first time is similar to being dropped into a 
thick maze in the dark without a torch. 

{% include links.md %}
