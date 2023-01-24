---
path: "/basic-usage"
title: "Using Vim"
order: "2B"
description: "Let's use vim for the first time!"
section: "Basics"
---

## My First Moves

### Exercises
We will be using curl to grab a few exercises throughout this class.  Here is
an example.

### Basic navigation

Time to curl down our first little exercise

```bash
curl https://raw.githubusercontent.com/jamzrob/vim-course/main/lessons/exercise-0-hjkl.md > exercise.md && vim exercise.md
```

### Deleting, Yanking, and Pasting
These are going to be some of your fundamental movements within vim.  This is
where you will see some significant speed ups compared to a conventional editor.


```bash
curl https://raw.githubusercontent.com/jamzrob/vim-course/main/lessons/exercise-1-dyp.md > exercise.md && vim exercise.md
```

### Insert!
We are going to go over entering into insert mode

```bash
curl https://raw.githubusercontent.com/jamzrob/vim-course/main/lessons/exercise-2-insert.md > exercise.md && vim exercise.md
```

## Recap
Lets talk about what happened.  I would love to get some feedback from you.
What do you think about all of this nonsense?  Does it seem like to much?  Or
does it seem exciting?  I hope you are excited.

### We learned
* h,j,k,l for basic movement.
* w,b for word hopping.  Effectively the same as Option/Ctrl + arrow keys
* yy to "copy" a line, called Yank
* dd to delete, and yank, a line
* p and P to paste the contents of the implicit register below / above
* Most of the ways to go into insert mode!
  * i and a for which side of the cursor
  * I and A for which side of the line
  * o and O for below / above line
* zz - I snuck that one in...

That is a grand total of 16 different motions

