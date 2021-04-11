# [i3-gaps] Minimalist Neko/Dotfiles
# What is Dotfiles
Dotfiles is a folder or file which filesystem utilities do not display by default when showing a directory listing. it's commonly used to storing user configuation and utilities


# About this repository

I made this repository to back up my dotfiles on my i3 configuration and sharing. most of the themes i used are default themes and still wip, so do not expecting more.

# Setup
i used [LXAppearance](https://wiki.lxde.org/en/LXAppearance#:~:text=LXAppearance%20is%20the%20standard%20theme,to%20enable%20the%20accessibility%20features.) to configure the theme, such as arc-dark, etc. i also used it to configure my icons as well. \
Anyway, Here is my setup : 

![enter image description here](https://cdn.discordapp.com/attachments/494541988046176257/830635695373811722/2021-04-11-094902_1366x768_scrot.png)
![enter image description here](https://cdn.discordapp.com/attachments/494541988046176257/830627609830359040/2021-04-11-073117_1366x768_scrot.png)
![enter image description here](https://cdn.discordapp.com/attachments/494541988046176257/830632858279739402/2021-04-11-093649_1366x768_scrot.png)
- OS : Arch Linux
- WM : i3-gaps
- FM : Thunar
- Terminal : xfce4-terminal
- compositor : picom
- Theme : [Arc-Dark](https://github.com/arc-design/arc-theme)
- icons : [Papirus-Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)
- Text Editor : nvim (terminal), geany (graphical)
- Bar : [Polybar](https://github.com/adi1090x/polybar-themes) , i3bar
- Polkit : LXpolkit
# Installation

- Install chzmoi first

> Arch Linux / Other Arch based distribution (Alter Linux, Manjaro, EndeavourOS, etc...) \
> sudo pacman -S chzmoi

> Snap (ubuntu, etc..)\
> sudo snap install chzmoi --classic

More info here : https://www.chezmoi.io/docs/install/

- Run this command
>chezmoi init https://github.com/shikikan-neko08/dotfiles.git && chezmoi apply

