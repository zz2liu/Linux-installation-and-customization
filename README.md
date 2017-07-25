# Linux-installation-and-customization
Install and customize a linux system
## Antergos xfce
### Download and install the OS
* install with default settings
* check xfce4
* check chromium, libreoffice, AUR
* update with `sudo pacman -Syu`

### Basic tweak
* `pacman -S vim htop ncdu xfce4-whiskermenu-plugin`
* Settings - keyboard - Application shortcuts - Add: xfce4-popup-wiskermenu; Key: Super+space
* panel - preferences - add: whisker-menu, remove:plication-menu
* remove the panel2 (docker)

### More polished (abundant):
#### plank - preferences
* `pacman -S plank archlabs-plank-themes-git`
* window manager tweaks - compositor - uncheck:show shadows under dock windows
* window manager - Button layout: remove the arrow
* sessions and startup - Application Autostart - Add: plank
* Plank - Appearance - Theme: Transpanel, Position: Left, IconSize: 28
#### WPS office, firefox, shutter
* `pacman -S wps-office ttf-wps-fonts firefox shutter perl-goo-canvas`

### random tips
* Pacman: https://www.digitalocean.com/community/tutorials/how-to-use-arch-linux-package-management
 * Clean the package cache: `pacman -Scc`
