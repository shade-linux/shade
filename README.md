# Shade package manager

A simple package manager for Linux written in shell

## Installation

- Download and move `src/shade` to a directory in your path.
- Run `shade init --local` as a normal user, or `shade init --global` as the root user
- Add `/opt/shade/bin/` and `~/.shade/bin/` to your $PATH

## Why another package manager?

Shade has a few advantages over other packages managers

- Shade buildscripts are written in shell, so you don't need shade to build packages
- Shade is written in shell, so it is portable and can run on macOS, BSD, and even WSL (although without support)
- Shade is also easily extensible, as you can edit it without needing to recompile
- Shade is fast

## Usage

- Use `shade install <package>` to install packages
- Use `shade uninstall <package>` to uninstall packages
- Use `shade update` to update buildscripts
- Use `shade upgrade` to update package (works only for cached git repos as of now)
- Update individual packages with `shade reinstall <package>`

## Contributing and support

If you have a question, you can open an issue, join our [Matrix room](https://matrix.to/#/!QFHcZFQVmhZjDjYMYR:matrix.org?via=matrix.org), or ask in Github Discussions.
If you want to contribute, feel free to fork this repo and create a pull request.
