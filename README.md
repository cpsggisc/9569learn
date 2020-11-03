# 9569learn
9569 Learning Group

- [Version Control](#version-control)
- [So, what is Version Control?](#so--what-is-version-control-)
- [Git and GitHub](#git-and-github)
  * [Forking a Repository on GitHub](#forking-a-repository-on-github)
    + [Task 1](#task-1)
  * [Creating a Folder On GitHub](#creating-a-folder-on-github)
    + [Task 2](#task-2)
  * [Deleting a File On GitHub](#deleting-a-file-on-github)
    + [Task 3](#task-3)
  * [Pull Request](#pull-request)
  * [Markdown Language](#markdown-language)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Version Control

> Save Early, Save Often — *Every programmer who lost their code*

Imagine you are taking short notes down in `Word`. You made some more changes to the notes, delete some sections. Before you close the file, it prompted you to save and you clicked `Yes` . Right after you click, you realized you deleted the wrong sections! *Sianz. Now I gotta find those parts of the notes and reinsert.* Well, you wouldn't need to go through all this experience if you would have used version control.

# So, what is Version Control?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. ʳᵉᶠ 

Fortunately, this system is so ubiquitous right now and you might even have used them in Google Docs under `File>Version History>See Version History` to restore that important paragraph that your project mate deleted for your group project 🤣.

![versioncontrol1.gif](versioncontrol1.gif)

Example of version control in Google Docs. 

There are multiple version control systems out there like Apache's `Subversion`, Concurrent Versions System ( `CVS`), but we will be using Git (which why this file is hosted on github) 

# Git and GitHub

> Git $$\neq$$ GitHub

Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. ʳᵉᶠ TLDR: Git is a program that tracks changes made to files. To use Git on your local machine, you need to install it from [git-scm.com](http://git-scm.com).

On the other hand, GitHub is a cloud-based **hosting service** that lets you manage Git *repositories*, which is roughly a folder that contains various different versions of the files.

## Forking a Repository on GitHub

*Forking a repository* means that you're making a copy of someone's project. To do this on GitHub, on the top-right corner of the page, click `Fork`. 

![Version%20Control%20163e0801d7b74c45b99654c3cfae4e9a/Untitled.png](Version%20Control%20163e0801d7b74c45b99654c3cfae4e9a/Untitled.png)

### Task 1

Fork this repository to add to your own GitHub account. 

After forking, your will arrive at `[github.com/YOUR_ACCOUNT/9569learn](http://github.com/YOUR_ACCOUNT/9569learn)` , your own copy of the repository.

## Creating a Folder On GitHub

To create a new folder in a repository click `Add file>create a new file`. Type your new folder’s name in the area where you would write the file name, and at the end of the file name type a `/` to initialize it as a folder. After this you can create a new file in the folder. ʳᵉᶠ After you're done, scroll down and click on `Commit new file`.

![versioncontrol2.gif](versioncontrol2.gif)

Or, you can just drag and drop. 😂. 

![versioncontrol3.gif](versioncontrol3.gif)

### Task 2

In your forked repository, create 2 folders, one called `Databases` and `DeleteMe` that each contains a file called `mysql.py` inside the folders. 

## Deleting a File On GitHub

Browse to the file in your repository that you want to delete. Locate the dustbin icon on the top right hand corner of the editor (next to the pencil icon) and click on it. Click `Commit changes` afterwards.

![Version%20Control%20163e0801d7b74c45b99654c3cfae4e9a/Untitled%201.png](Version%20Control%20163e0801d7b74c45b99654c3cfae4e9a/Untitled%201.png)

### Task 3

Delete the file [`mysql.py`](http://mysql.py) in the folder `DeleteMe`. What happens to the folder `DeleteMe` in your repository?

## Pull Request

## Markdown Language

[https://medium.com/edge-coders/the-mistakes-i-made-as-a-beginner-programmer-ac8b3e54c312](https://medium.com/edge-coders/the-mistakes-i-made-as-a-beginner-programmer-ac8b3e54c312)

[BRW ](https://www.notion.so/BRW-8ae084e0afe14be0baed22db6fcdb408)
