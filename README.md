# dotfiles
Chezmoi init scripts for setting up new laptops

This is the first, public step of the Jedsy laptop setup. It is just enough to give the laptop access to the consecutive private steps.

## Usage

### Setup a new machine

To set up a new machine, you can install, configure and run chezmoi all with a single command. The output of the command will tell you what to do next.

```bash
sh -c "$(curl -fsLS https://get.chezmoi.io)" -- -b "$HOME/.local/bin" init -S /tmp/chezmoi --apply PackageGlider
```
