# RPI-System-Status-Dashboard

    sudo apt-get install lighttpd php5-cgi
    sudo lighttpd-enable-mod fastcgi fastcgi-php
    sudo service lighttpd force-reload

    sudo mv /var/www/html /var/www/html_backup
    sudo mkdir /var/www/html

    cd /tmp/
    wget https://github.com/ColinWaddell/CurrantPi/archive/master.zip -O temp.zip
    unzip temp.zip; rm temp.zip
    sudo cp -r /tmp/CurrantPi-master/* /var/www/html/
    rm -rf /tmp/CurrantPi-master

Go to ip of RaspberryPi in browser
