# Laptop Setup

This is heavily inspired from https://github.com/mattstratton/matty-dotfiles with some tweaks of my own.

## Installation

* Install [YADM](https://yadm.io/): `curl -fLo /usr/local/bin/yadm https://github.com/TheLocehiliosan/yadm/raw/master/yadm && chmod a+x /usr/local/bin/yadm`
* Bootstrap the computer: `yadm clone --bootstrap https://github.com/lirossarvet/dotfiles.git`
* Delete `/usr/local/bin/yadm` and run `brew bundle` again so Homebrew manages it

# SublimeText plugins
* PrettyJSON
* Agila Theme
  * theme stays as default
  * color_scheme goes to agila oceanic next
* Git blame
* Elixir
* SideBarEnhancements
* SublimeLinter
* SublimeLinter-golangclilint
* Whitespace
