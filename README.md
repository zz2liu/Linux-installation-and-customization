# Linux-installation-and-customization
Install and customize a linux system
## Antergos xfce
### Download and install the OS
* install with default settings: check firefox, chromium, libreoffice, extrafonts, AUR

### pacman -S or PackageManager GUI
* vim htop ncdu plank archlabs-plank-themes-git xfce4-whiskermenu-plugin
* wps-office ttf-wps-fonts

### Settings
* window manager tweaks - compositor - uncheck:show shadows under dock windows
* window manager - Button layout: remove the arrow
* keyboard - Application shortcuts - Add: xfce4-popup-wiskermenu; Key: Super+space
* sessions and startup - Application Autostart - Add: plank

### panel - preferences
* remove the panel2 (docker)
* replace the application-menu with Whisker-menu

### plank - preferences
* Appearance - Theme: Transpanel, Position: Left, IconSize: 28
