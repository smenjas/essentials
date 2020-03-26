# Web Development Essentials for Linux & Mac

## What?
These scripts and dotfiles configure a Mac or Linux system for software
development.

## Why?
So I can set up my development environment automatically, not manually.

## Who?
- I tend to focus on backend web development and data science.
- I used to mostly write PHP, but I've switched to Python.
- I prefer Linux and Mac.

## Setup
Run the setup script to prepare a new computer for development:
```sh
git clone https://github.com/smenjas/essentials.git
cd essentials/
./setup
```

The script will run create-symlinks to link your dotfiles and ~/bin directory.
Doing so creates a symlink called "this" in the repository root, pointing to
the appropriate directory for your operating system.  This way you can have
different implementations on different systems.

If you don't already have a ~/.gitconfig, the setup script will copy the
example (this/dotfiles/gitconfig) and open a text editor.  Scroll to the
bottom, and tell git your name and email address.

Voila!  My idea of a basic development environment.

## License Released as open source software under the terms of the [ISC
License](https://en.wikipedia.org/wiki/ISC_license).
