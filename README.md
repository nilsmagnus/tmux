## min tmux config

Hent Tmux Plugin Manager https://github.com/tmux-plugins/tpm

> mkdir -f ~/.config/tmux/plugins
> git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm

### Linux og Mac

cd ~/.config
git clone https://github.com/finnjohnsen/tmux


## Cheat Sheet

1. reload config: tmux source $HOME/.config/tmux/tmux.conf
1. create: c-b c
1. split horizontal: c-b "
1. split vertical: c-b %
1. hopp mellom panes: c-b <piltaster>
1. drepe c-b % eller c-b x
1. c-b q bytt pane etter nummer

### zoom
c-b z
c-b !

### flytt et vindu inn i et pane
1. bytt til vinduet du vil flytte
2. marker c-b m
1. bytt til vinduet som har pane
1. c-b :join-pane

## Alacritty
Alacritty er en lettvekt terminal emulator som funker i Linux og Mac (og muligens Windows).

Her er mitt Alacritty -oppsett; som egentlig kun starter tmux automatisk
git clone https://github.com/finnjohnsen/alacritty ~/.config/alacritty
