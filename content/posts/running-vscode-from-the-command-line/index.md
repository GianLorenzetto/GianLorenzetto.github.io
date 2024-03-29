---
title: Running VS Code From the Command Line in Mac OS X
tags: ["development","software","cli","macOS","vscode"]
date: 2016-09-15 15:22:00 +0800
---

I'm in love with VS Code, I'll admit it. To make the joy complete, I wanted to fire it up from the command line ([iTerm](https://www.iterm2.com) 2 of course).

A quick Google resulted in [this SO answer](http://stackoverflow.com/questions/29971053/how-to-open-visual-studio-code-from-the-command-line-on-osx).

The TL;DR version - VS Code has a built in Shell Command to add itself to the path!

Pop open the command palette (Cmd + Shift + p) and start typing `shell command`, this will bring up some options, like so:

{{< figure src="ss_add_vscode_to_path.png" title="SQL Server collation setting" >}}

Just select the install option, restart your terminal (or re-source your profile) and away you go!
