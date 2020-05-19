# Are You On The Right Path?
Goal: This kit would allow you to run programs as root when the main user of the system runs any program as root.

## How it works
This version of the rootkit works by appending the PATH variable in .bashrc  
It will create clones of basic commands that the user is likely to use such as `ls` or `cat` or `cd` etc.  
It would hide the directory in which the magic happens :)

## Requirements

It should work on any standard linux system (no guarantees though)

## Cleanup
1. When you're done, navigate to the directory you installed from, and run `sudo ./cleanup` to remove any files related to the kit. _(unless, obviously, you overwrote sudo)_

2. There is also a reset script if you want to reinstall it for some reason, instead of deleting it. Just navigate to this directory "/AreYouOnTheRightPath" and run `sudo ./reset`.