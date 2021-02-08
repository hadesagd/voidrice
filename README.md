# The Voidrice (Luke Smith <https://lukesmith.xyz>'s dotfiles)
## My fork with a few modifications to use BSPWM instead of DWM as window manager

These are the dotfiles deployed by [LARBS](https://larbs.xyz) and as seen on
[my YouTube channel](https://youtube.com/c/lukesmithxyz).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- sxhkd (general key binder)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- calcurse (calendar program)
	- tmux
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/files`
	- Directory bookmarks in `~/.config/directories`

## Usage

These dotfiles are intended to go with the following programs:

- [bspwm](https://github.com/baskerville/bspwm) (window manager)
- [sxhkd](https://github.com/baskerville/sxhkd) (hotkey daemon for shortcuts)
- [st](https://github.com/hadesagd/st) (terminal emulator fork of LukeSmithxyz st terminal)

These dotfiles go with a fork of LukeSmithxyz LARBS

- [LARBS](https://github.com/hadesagd/LARBS) (Downloading the larbs.sh from this repo does the trick of autoinstalling everything, WARNING this is work in process and things may/will break)
