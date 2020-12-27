
 1、安装
   sudo apt-get install ubuntu-desktop
   sudo apt-get install unity  unity-tweak-tool
  
2、更新ubuntu及组件
   sudo apt-get update
   sudo apt-get upgrade

   sudo apt-get update
   sudo apt-get dist-upgrade
3、移除所有无效的包和缓存
   sudo apt-get autoremove
   sudo apt-get autoclean

   unity –version
   service lightdm restart



   1、安装GNOME 3

sudo apt-get install gnome-session-flashback gnome-session-flashback gnome-shell gnome-tweak-tool gnome-themes*
sudo apt-get -y –auto-remove purge gnome-session-flashback gnome-session-flashback gnome-shell gnome-tweak-tool gnome-themes*



设置自动登录：
自动登录 GNOME SHELL CLASSIC：
sudo /usr/lib/lightdm/lightdm-set-defaults -s gnome-classic
自动登录 GNOME3：  
sudo /usr/lib/lightdm/lightdm-set-defaults -s gnome-shell

2、删除UNITY：

sudo apt-get -y –auto-remove purge unity
sudo apt-get -y –auto-remove purge unity-common
sudo apt-get -y –auto-remove purge unity-lens*
sudo apt-get -y –auto-remove purge unity-services
sudo apt-get -y –auto-remove purge unity-asset-pool

sudo apt-get autoremove
sudo apt-get autoclean
