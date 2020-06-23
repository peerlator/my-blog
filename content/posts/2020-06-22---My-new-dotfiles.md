---
title: "My New Dotfiles"
date: "2029-06-22"
template: "post"
draft: false
slug: "my-dotfiles"
category: "blog"
tags:
  - "Dotfiles"
  - "Dev. Environment"
description: "In this post I just wanted to update you on the tools I currently use and the method I use to manage my dotfiles."
socialImage: ""
---

In this post, I decided to update you on my current [dotfiles](https://github.com/peerlator/dotfiles) configuration. I have made some major changes ranging from the programs used to the way I sync the dotfiles.

## 1. The syncing method

In comparison to the old method of syncing, where I synced the files from the `.dotfiles` directory to the actual places, I now sync from the actual place to the `.dotfiles` directory. I chose to do that over the other method because some applications like UltiSnippets or Doom Emacs have built-in functions for editing the config files and before I had to just write scripts to separate those files from the others. Shortly said it was one big mess. In addition, now don't have to run a sync command for the changes to take effect. To simplify the syncing process I developed a simple shell script check out my dotfiles to find out more about how I sync my dotfiles now

## 2. Appearance

Although I still use i3wm and polybar, the apperance has changed a lot. I switched from the Dracula theme to solarized dark and tried to give my apperance some different vibes.

## 3. Simplicity

Over time I noticed that when it comes to an efficient development environment less is often more. I removed a lot of unnecessary programs like the popup-python-shell and popup-conky. I also switched from VS Code to and removed stuff like the icon searcher and the pywal live theme updating. While stuff like that was fun it was not very practical as it always only worked somewhat and just added mess to the dotfiles.

## 4. My editor of choice

After getting frustrated over having to reach to that damn mouse every time you wanted to do something in VSCode I just ditched it and switched over to vim. I recently started also using Doom Emacs and I think I will make it my main editor.
