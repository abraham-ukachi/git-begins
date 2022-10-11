# `git-begins`
> Author: [Abraham Ukachi](https://github.com/abraham-ukachi) \ 
> School: [La Plateforme_](https://laplateforme.io) \
> Project: **GIT** (~4 jobs)

**...and so it begins !!!** 😱😅

Git and Github are one of the most important-- if not the most important tool for computer geeks, IT students, programmers / developers, ...basically, anyone taking this field (ie. computer science) seriously **MUST** know how to use these tool.

As for me, I've been using git & github for a couple of years now before we started this course here at **La Plateforme_**. However, I had never dove deep into the nitty-gritty of this tool like I did during this course because I mostly used softwares or apps like **WebStorm** and **Atom** that handled a lot of those commands in the background.

One of the many things I learned in this course that I didn't really know before, believe it or not, was [how to resolve merge conflicts in Git](#How to resolve merge conflicts in Git) 


## How to resolve merge conflicts in Git

There are **three ways** to resolve a merge conflict in Git:

### 1. Accept the local version

To accept all changes on a file from the local version, run:

```sh
git checkout --ours <file name>
```

Alternatively, to accept the local version for all conflicting files, use:

```sh
git merge --strategy-option ours
```

### 2. Accept the remote version

To update the changes on a file from the remote branch, run:

```sh
git checkout --theirs <file name>
```

Accept the remote version for all conflicting files with:

```sh
git merge --strategy-option theirs
```

### 3. Review changes individually

The final option is to review each change separately. This option is also the best path to take, especially when working with multiple files and people. To make this job more manageable, use special tools to help review individual conflicts.

Ultimately, the choice of what parts of the code stay and which do not depends on the developer's decision for the current project.
