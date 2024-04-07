---
title: The Vim Cheat Sheet I've learned
date: 2024-04-06
categories: [Linux, Vim]
tags: [vim, linux]     # TAG names should always be lowercase
---

## Mode
`Normal Mode` - The default mode opening Vim, where users can navigate, delete, copy, and perform other non-editing tasks using various commands

`Insert Mode` - The mode in which users can directly input and edit text into the file



|  Command     | Description      |
| ------------- | ------------- |
| `i` | Insert Mode |
| `ESC` | Normal Mode |

## How to Terminate the Vim

|  Command     | Description      |
| ------------- | ------------- |
| `q` | Terminate |
| `q!` | Forcing Terminate |
| `w` | Save |
| `w!` | Forcing Save |
| `wq` | Save and Terminate |
| `wq!` | Forcing Save and terminate |

## Insert Mode

|  Command     | Description      |
| ------------- | ------------- |
| `i` | insert before the cursor |
| `a` | insert after the cursor |
| `I` | insert at the beginning of the line |
| `A` | insert at the end of the line |

### Navigation

|  Command     | Description      |
| ------------- | ------------- |
| `0` | jump to the start of the line |
| `$` | jump to the end of the line |
| `w` | word |
| `b` | backward |
| `ctrl u` | scrolling to up |
| `ctrl d` | scrolling to down |
| `{` | jump to the start of the paragraph  |
| `}` | jump to the next paragraph |

### Normal Mode

|  Command     | Description      |
| ------------- | ------------- |
| `x` | delete the word in cursor |
| `yy` | yank (copy) a line |
| `dd` | delete (cut) a line |
| `p` | put (paste) before cursor |
| `.` | repeat last command |
| `u` | undo |
| `ctrl R` | redo |

### References
https://vim.rtorr.com/


