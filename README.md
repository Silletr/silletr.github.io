# Lazy Developer Helper [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Lua](https://img.shields.io/badge/Lua-5.4.8-purple.svg?logo=lua&logoColor=white)](https://www.lua.org/)
[![Python](https://img.shields.io/badge/python-3.11+-blue)](https://www.python.org)
[![Stars](https://img.shields.io/github/stars/Silletr/LazyDevHelper?style=flat-square&color=yellow)](https://github.com/Silletr/LazyDevHelper/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/Silletr/LazyDevHelper/pulls)
[![Netlify Status](https://api.netlify.com/api/v1/badges/44b13cb1-cb19-479f-ad38-2838f2dc7618/deploy-status)](https://app.netlify.com/projects/lazydevhelper/deploys)


## Contents
<!-- toc -->
- [Video example](#video-example)
- [Introduction](#introduction)
- [Features](#features)
- [Future Features](#future-features)
- [Install using Packer](#install-using-packer)
- [Avaible in](#available-in)
- [Usage](#usage)
<!-- tocstop -->

## Video example

![Video example of commands](https://github.com/Silletr/Silletr.github.io/raw/de9a1893f70867cfbff5f1f978259ca3ac1708d1/images/example.gif)

## Introduction

Have you ever found yourself adding multiple dependencies to your code before installing them? Do you hate switching between your editor and terminal? 🤔

LazyDevHelper solves this problem! It's a Neovim plugin that lets you manage Python dependencies directly from your editor, eliminating the need to switch to the terminal.
And plugin have Discord channel [from now](https://discord.gg/QnthFV3Zgp)

## Features

✨ Install Python packages directly from Neovim.  
✨ Manage dependencies without leaving your editor.  
✨ Compatible with modern Neovim configurations.

## Future Features
- [x] Will be added supporting Rust-, Lua- library manager.
- [ ] Code will be optimized better.

## Available in
- [vim.org](https://www.vim.org/scripts/script.php?script_id=6156)
- [dotfyle.com](https://dotfyle.com/plugins/Silletr/LazyDevHelper)
- [Awesome-NeoVim](https://github.com/rockerBOO/awesome-neovim?tab=readme-ov-file#utility)
- Soon will be in neovimcraft.

### Installation Methods
## Install using Packer
```lua
  use {
    'Silletr/LazyDevHelper',
    config = function()
      require("LazyDeveloperHelper")
    end
  }
```
## Usage
Command example:
![Command Example](images/command_example.png)

Example output:
![Installation Output](images/output_example.png)
