# Shade package manager

A package manager for Linux

## Installation

- Download and move `src/shade` to a directory in your path.
- Move `src/config` to `/etc/shade/config`
- Run `shade -s` as a privileged user
- Add `/usr/local/shade/bin/` to your $PATH

## Usage

- Use `shade -i <package>` to install packages
- Use `shade -r <package>` to uninstall packages
- Use `shade -u` to update buildscripts
- Use `shade -U` to update package (works only for cached git repos as of now)
- Update packages with `shade -i <package>`

## macOS support

macOS isn't fully supported as of now. Basic functions still work, but some packages may not install properly
