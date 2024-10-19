## Pre-requisites ##
To be able to use Hyprland, you should enable ```wayland``` as your display server. This can require some work in case you have **nvidia** graphics card. However, with the lates proprietary drivers, and some tweaks it is possible to configure your Hyprland setup with your nvidia GPU.

Below are the list of programs that needs to be installed for this setup to work.
* Terminal: ```alacritty```
* File Manager: ```thunar```
* Menu: ```rofi```
* Display Manager: ```gdm```
* Wayland Status Bar: ```waybar```
* Network: ```networkmanager``` ```network-manager-applet```
* Shell: ```zsh```
* Terminal Prompt Themes ```oh-my-posh```


## "TO DO" List:
* Alacritty history... The commands ran earlier is not rememebered by the terminal instance like in other terminals.
* Nvidia wake-up problem... If computer goes to sleep, the screen doesn't wake up. This needs to be solved. (Although it could be a general problem, not hyprland related).
* Notification app.
* Installation script... Although manual copying of the folders in this repository into the ```~/.config``` folder should be sufficient, an installation script would be useful to automate things.
