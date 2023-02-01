# Dotfiles-gruv

### Screenshots
![img](https://i.imgur.com/C7rqgNk.png)
![gif](https://i.imgur.com/tTi6v9O.gif)

## Programs needed 
* rofi
* bspwm (actually using bspwm-rounded-corners)
* sxhkd
* polybar
* networkmanager-dmenu
* emacs
* [doom emacs](https://github.com/doomemacs/doomemacs)
* firefox
* nitrogen
* [feather-icons](https://github.com/feathericons/feather#feather) (included in directory usr/share/fonts)
* [i3lock-color](https://github.com/Raymo111/i3lock-color)
* [cliblur](https://gitlab.com/kerkmann/cliblur)
* [jfetch](https://github.com/Jimmysit0/jfetch) (informations when you open the terminal)
* scrot
* todo

## Important
* Fonts needed: Space Mono NF (i recommend this [pre-release version](https://github.com/ryanoasis/nerd-fonts/releases)), material design icons and feather icons (included in directory usr/)
* Music player: i use [spotify-tui](https://github.com/Rigellute/spotify-tui), my config for colors is not perfect but i tried, you also have to install spotifyd to use spotify-tui
* if you want, you can use [sptlrx](https://github.com/raitonoberu/sptlrx) for lyrics in your terminal, works great with a combination of spotify-tui and sptlrx.
* Change some values in polybar like wlan for your specific wifi adapter, battery module, etc.
 * to modify firefox follow this [instructions](https://github.com/andreasgrafen/cascade#how-to-use-a-userchromecss-theme), specifically the about:config part
 * to complete firefox modification, place the directory chrome in ~/.mozilla/firefox/your_release.default-release/ and activate dark mode
 * my [startpage](https://peyrzival.github.io/startpage/) (a fork of [nwvh startpage](https://github.com/nwvh/startpage)), to put it as a new tab in firefox use this [extension](https://addons.mozilla.org/pt-BR/firefox/addon/new-tab-override/)
 * my text editor is doom emacs, i use the config of [distrotube dotfiles](https://gitlab.com/dwt1/dotfiles) but for minor modifications, i use [lunarvim](https://www.lunarvim.org/)
 * put the directory bin/ in $HOME/.local/, is necessary for some keybindings to work
 * i use fish as main shell with some aliases, if you want, its at config/fish/ (this configuration file is derived from the [distrotube dotfiles](https://gitlab.com/dwt1/dotfiles) but contains some modifications).
 * to better experience with fish, i recommend you to install [starship](https://starship.rs). my config file of starship is at config/starship.toml 
 * i use a [picom fork](https://github.com/pijulius/picom) to have fluffy animations, the conf of this is in the directory config
 * `yay -S todo`, a todo manager
