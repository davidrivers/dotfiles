## Installation/Updating
### Ubuntu
`bash -c "mkdir -p ~/Dev && mv ~/Dev/dotfiles ~/OLD-DOTFILES 2>/dev/null && git clone git@github.com:davidrivers/dotfiles.git ~/Dev/dotfiles && chmod +x ~/Dev/dotfiles/install/ubuntu.sh && ~/Dev/dotfiles/install/ubuntu.sh"`

### Mac
`bash -c "mkdir -p ~/Dev && mv ~/Dev/dotfiles ~/OLD-DOTFILES 2>/dev/null && git clone git@github.com:davidrivers/dotfiles.git ~/Dev/dotfiles && chmod +x ~/Dev/dotfiles/install/mac.sh && ~/Dev/dotfiles/install/mac.sh"`

## TODO
* Add steps to re-source fish/tmux/etc. configs, post-install/update
* Maybe automatically `nvm use` upon cd'ing into (certain?) ~/Dev dirs
* [Unset Ubuntu Terminal profile setting of "Use colors for system theme"](https://askubuntu.com/questions/628122/how-can-i-set-the-background-color-of-gnome-terminal-using-gconftool-2)
* Script the customization of Ubuntu settings (edit keys, auto-hide Dock, Dash Serach settings, themes, etc.), similarly using dconf or gconftool-2
* Add installation step for ag (silver-searcher)
* Keep track of all executables installed (in order to provide an uninstallation process)?:
  ** github make file (in ~/bin): bass
  ** curl one-liner: nvm, pathogen
  ** brew/brew-cask installed apps
  ** apps installed from installer wizard files
