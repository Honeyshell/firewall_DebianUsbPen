# firewall_DebianUsbPen
Firewall for my debian usb pen

HOW TO INSTALL

$ sudo wget --no-check-certificate -O /etc/init.d/firewall.sh https://raw.githubusercontent.com/Honeyshell/firewall_DebianUsbPen/master/firewall.sh $ sudo chmod a+x /etc/init.d/firewall.sh $ sudo update-rc.d firewall.sh defaults 20

Redémarrer le serveur $ sudo shutdown -r now
