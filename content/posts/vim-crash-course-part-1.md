---
title: "Vim Crash Course For IntelliJ Users Part 1"
date: 2019-07-21T22:30:59+08:00
draft: false
---
*This crash course is tailored for IntelliJ users but the concept applies universally to all Vim-based editors.*

Have you ever been interested to pick up Vim or Emacs with Evil but find it too daunting? Then this crash course is for you. It basically contain the things which I had known earlier, picking up Vim would be relatively easier.

## Why learn Vim?

- Fluid navigation of source code
- Key combinations which makes editing more productive
- Reduce chances for wrist related injury
- Fun to use!

## Install/Setup

Install these plugins in IntelliJ:

- [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
- [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
- [Relative Line Numbers](https://plugins.jetbrains.com/plugin/7414-relative-line-numbers)

## Basic Navigation

Place your right hand on the keyboard with your fingers on the `hjkl` keys. This is where your hand will be 90% of the time. Always reset your hand back to this position.

Vim has 3 modes -- Normal, Insert and Visual. It starts in Normal mode by default. This is also the mode you should be in most of the time. The other modes should be as short lived as possible. If you are used to typing in modern editors, you would usually be tempted to stay in Insert mode and try to navigate like you usually would. Resist the temptation! In other words, after finishing the insert you wanted to do, return to Normal mode immediately with the ESC key. Practice navigating in Normal mode. Navigating in insert mode is *very* counter productive.

The rest of the crash course on this page are commands to be used in Normal mode.

### Main Keys: h, j, k, l

These are your main keys when in Vim. It allows you to go left, down, up, right respectively. Is it intuitive? I would say nothing is more intuitive than actual arrow keys. But once you get used to `hjkl`, in combination with other keys, it definitely increases your productivity.

#### *number* + h/j/k/l

Move the cursor *number* of characters towards the `h/j/k/l` direction respectively. You should turn on relative line numbers to effectively use the `j/k` movement. For example, `3j` will move the cursor 3 line down.

### Horizontal Jumps (Find in line): f/F/t/T + *char*

So you can now navigate up/down the text fluently, you would want to master how to move the cursor horizontally next. Besides jumping with `*number*-h/l`, it would be more intuitive to use `f*char*` to move the cursor to the first instance of the `*char*` found to the right.

```
This is a line.
^
```

Given your cursor is on `T`, if you type `fl`, this would be the where the cursor would end up to:
```
This is a line.
          ^
```

`t` does the same except it places the cursor right before the specified character:

```
This is a line.
         ^
```

Finally, `F` and `T` does the same except it looks the left instead of the right.

#### Repeat Last Find: ;

What if the there are more than one `l` on the line? Simply type `;` to repeat the previous jump until the cursor reached the place you wanted.

### Precise Jumps: w, e, b, %, 0, ^, $

- w -> Go to next **w**ord
- b -> Go to previous word (**b**ack)
- e -> Go to **e**nd of word
- % -> Go to the other pair of the bracket or braces
- 0 -> Go to start of line
- ^ -> Go to start of non-whitespace of line
- $ -> Go to end of line

**Pro-tip:** `w/b` can also be prefixed with a number like `h/j/k/l` to jump more than once.

### Major Jumps: gg, G, H, M, L, C(trl)-Up, C-Down, C-O, C-I

- gg -> Go to start of document
- G -> Go to end of document
- H -> Go to first line on the page
- M -> Go to middle of the page
- L -> Go to last line on the page
- C-Up/C-Down -> Simply just page up and page down
- C-o/C-i -> Jump to previous place/Jump back to next place

### AceJump: Jump to any place on the page

With AceJump plugin, by default, `Ctrl+;` will activate a mode where you can type in a few characters and a character will be displayed left of matching words. Typing in that character will jump the cursor to the position.

This jumping is useful when you want to immediately jump to another line and another column more quickly.

## Closing

That's the end of part 1 of the crash course. Making use of these commands regularly should allow you to train your muscle memory. Once the muscle memory has strengthened, navigating in Vim should come as second nature. Hope this part 1 write up has been beneficial to you.

Stay tuned for part 2.
