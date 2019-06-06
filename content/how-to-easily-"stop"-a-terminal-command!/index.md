---
title: "How To Easily “Stop” a Terminal Command!"
description: "When you find yourself running a terminal command that you don’t know how to exit from. Don’t just close the whole terminal, you can close the that command! There’s commands/apps that are designed to…"
date: "2016-07-17T18:25:00.183Z"
categories: 
  - Vim
  - Tech
  - Terminal
  - Command Line
  - Tips

published: true
canonical_link: https://medium.com/tooling-tips/how-to-easily-stop-a-terminal-command-15d4324109f
redirect_from:
  - /how-to-easily-stop-a-terminal-command-15d4324109f
---

![](./asset-1.jpeg)

When you find yourself running a terminal command that you don’t know how to exit from. Don’t just close the whole terminal, you can close the that command!

> If you want to force quit “kill” a running command, you can use “Ctrl + C”. most of the applications running from the terminal will be forced to quit.

There’s commands/apps that are designed to keep running until the user asks it to end. and there’s other commands/apps that are designed to show the output and exit automatically.

Here’s how to stop 3 of the most common commands.

### Nano Editor

Nano is a simple text editor, you could have faced it when dealing with “git commit”.

If you’re inside **nano** editor. Press “_Ctrl + X_” to exit. it will prompt you whether you want to save before quitting or not.

### Vim Editor

Vim is another text editor, unlike nano, this one is sophisticated and powerful one.

If you were running Vim editor and you want to quit, you can press “_Esc_” then type a colon “_:_” followed by “_q!_” to force quit without saving.

If you want to save do the same process but replace “_q!_” with “_wq_” (which means **w**rite then **q**uit).

### Less

Less is a command that let you view the content of an input (either the output of another command or a content of a file).

**Less** is different from the editors above, if you’re inside commands that don’t need input, like “less” or top, you can press “_q_”.

### Others

Sometimes nothing from the above will work to quit the command gracefully. In these situations, you can use the “kill” command which is “_Ctrl + C_”.

---

In general, try to quit the application gracefully so it can do what it’s designed to do when quitting. If it didn’t work just force quit (kill) it.
