# Shade package manager

A package manager for Linux and macOS

## Installation

- Download and move `src/shade` to a directory in your path.
- Move `src/config` to `/etc/shade/config`
- Run `shade setup` as a privileged user
- Add `/usr/local/shade/bin/` to your $PATH

## Usage

- Use `shade install <package>` to install packages
- Use `shade uninstall <package>` to uninstall packages
- Use `shade update` to update buildscripts
- Use `shade upgrade` to update package (works only for cached git repos as of now)
- Update individual packages with `shade install <package>`

## Contributing and support

If you have a question, you can open an issue or join our [Matrix room](https://matrix.to/#/!QFHcZFQVmhZjDjYMYR:matrix.org?via=matrix.org).
If you want to contribute, feel free to fork this repo and create a pull request.
