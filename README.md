# DFMGR3 (Dotfile Manager 3)
*there's probably been 2 others, idk I didn't check*

## What is this
A minimal dotfiles repo. Various configs are submodules. Each comes with an install script that creates symlinks in ~/.config and does anything else needed for setup. This repo just executes those install scripts. 

## Setup:
1. Clone:
```bash
git clone https://github.com/tedtasman/dfmgr3.git --recurse-submodules
```

2. Install:
```bash
./dfmgr3/install
```
*if you already have some of the things in your ~/.config, this will fail. Deal with that first*

