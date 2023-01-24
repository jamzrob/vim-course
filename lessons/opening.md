---
path: "/opening"
title: "Opening VIM"
order: "2A"
description: "Opening VIM"
section: "Basics"
icon: "book"
---

## Before you do
* Navigate to an empty directory (create your own).  We will be doing a bit of
  editing.

* Ensure you have no vim rc active.
  * If you are using vim, rename ~/.vimrc -> ~/.vimrc2
  * If you are using nvim, rename ~/.config/nvim/init.vim -> ~/.config/nvim/init.vim2

### Exercises
We will be using curl to grab a few exercises throughout this class.  Here is
an example.

#### Note
Notice that i name the downloaded file then `&& vim name`

```bash
curl https://raw.githubusercontent.com/jamzrob/vim-course/main/lessons/exercise-0-hjkl.md > exercise.md && vim exercise.md
```

## Lets open vim!
So you are in an empty directory, lets do this! Simply type `vim` and press
enter.  (Ensure you have no vim rc)

```bash
> vim
```

* What are you thoughts?
* What are things you expected to see?

## Lets try editing a file
```bash
> vim test.js
```

You are now in `NORMAL` mode.  This probably doesn't feel all that normal.
And you are right, its really not that normal.

## Lets talk Modes
There are a few modes that you should be aware of.

* Normal
* Insert
* Visual 
* Visual Line

## My First If Statement
Lets write our first if statement.

Currently, you are in `NORMAL` mode.  This is where you can execute commands
to navigate, edit, and execute vim/sys commands.  To get out of this mode,
press `i`

After pressing `i` you should see something like `-- INSERT --` in the bottom
left hand side of vim.

Now that you are in insert mode, type the following

```js
if (true) {

}
```

Press `<esc>` or `<Ctrl-c>` (abbreviated `<C-c>`) to leave `INSERT` mode and back
to `NORMAL`.

Goodness, isn't default vim ugly?

type `:q` to quit vim.



