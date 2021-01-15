# chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb
chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb

deb-package: https://github.com/Griggorii/chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb/releases/tag/chromium-browser

$ sudo rm -rf /usr/lib/chromium-browser

$ cd /var/lib/dpkg/info && rm -rf chromium-browser*

Double installation !

$ sudo dpkg -i ./chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb

$ sudo dpkg -i ./chromium-browser_87.0.4280.88-0ubuntu

Local State copy setting too:

$ mkdir ~/.config/chromium ~/.config/chromium/Default && cp 'Local State' ~/.config/chromium

Run check profile chrome://gpu/


