# Jasper's dotfiles)

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/Cirelon/dwm) (window manager)
- [dwmblocks](https://github.com/Cirelon/slstatus) (statusbar)
- [st](https://github.com/Cirelon/alacritty) (terminal emulator)

## Install these dotfiles and all dependencies

Use JBS to autoinstall everything:

```
curl -LO cirelon.com/jbs.sh && ./jbs.sh 
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/Cirelon/JBS/blob/master/progs.csv).
