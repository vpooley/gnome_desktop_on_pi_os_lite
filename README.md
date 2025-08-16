# gnome_desktop_on_pi_os_lite
Want to run Pi OS but don't want the jank lightweight desktop environment?  
Install &amp; setup Debian's standard Gnome desktop onto a fresh Raspberry Pi OS Lite install  

# How?
1. Boot up Pi OS Lite on your device.  
2. If your Pi can access the internet and you have root privileges via sudo, download and run inline in a terminal...  
    ```wget -qO - https://github.com/vpooley/gnome_desktop_on_pi_os_lite/releases/download/v1.0/gnome_desktop_on_pi_os_lite.sh | sudo bash```  
3. Once complete run `sudo raspi-config` and use the menu options to disable screen blanking and to enable the Raspberry Pi boot splash if desired.
