## Xfce Debian Install ##

sudo apt install xfce4 slick-greeter xfce4-{artwork,battery-plugin,clipman-plugin,cpufreq-plugin,cpugraph-plugin,datetime-plugin,dict,diskperf-plugin,fsguard-plugin,genmon-plugin,mailwatch-plugin,netload-plugin,notes-plugin,notifyd,places-plugin,power-manager,screenshooter,sensors-plugin,smartbookmark-plugin,systemload-plugin,taskmanager,terminal,timer-plugin,verve-plugin,wavelan-plugin,weather-plugin,xkb-plugin,whiskermenu-plugin} mousepad ristretto network-manager-gnome cups system-config-printer simple-scan

## Slick Greeter ##

sudo mkdir /etc/lightdm/lightdm.conf.d
sudo nano /etc/lightdm/lightdm.conf.d/70-xfce.conf

[SeatDefaults]
user-session=xfce

## Theming ##

sudo apt install elementary-xfce-icon-theme greybird-gtk-theme dmz-cursor-theme
sudo update-alternatives --config x-cursor-theme
