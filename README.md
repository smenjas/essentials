# Web Development Essentials for Linux & Mac

![Octocat](octocat.png)

## What is this?
These scripts and dotfiles configure a Mac or Linux system for software
development.

## Why?
So I can set up my development environment automatically, not manually.

## Who made this?
- I'm a web developer who mostly writes JavaScript & Python.
- I prefer Linux and Mac development environments.

## Setup
Run the setup script to prepare a new computer for development:
```sh
git clone https://github.com/smenjas/essentials.git
cd essentials/
./setup
```

The `setup` script will run `create-symlinks` to link your dotfiles and `~/bin`
directory.  Doing so creates a symlink called `this` in the repository root,
pointing to the appropriate directory for your operating system.  This way you
can have different implementations on different systems.

If you don't already have a `~/.gitconfig`, the setup script will copy the
example (`this/dotfiles/gitconfig`) and open a text editor.  Tell `git` your
name and email address.

## License
Released as open source software under the terms of the [ISC
License](https://en.wikipedia.org/wiki/ISC_license).
