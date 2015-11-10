# DisplayLink Installer Script with Linux Mint 17.x support

A modified version of the [Ubuntu](http://www.displaylink.com/downloads/ubuntu.php) install script that detects Linux Mint 17.x as a valid installation option.

**This does not make it supported! Read the details over at [DisplayLink](https://github.com/DisplayLink)**

## To use it

 - Download the Ubuntu driver package as normal from [DisplayLink](http://www.displaylink.com/downloads/ubuntu.php)
 - Extract the driver package without executing the installer

    unzip <driver-filename>.zip
    bash <filename>.run --noexec –keep

 - Download the modified installer script

    curl https://github.com/kxseven/displaylink-dl-3000-install-script/raw/master/displaylink-installer-modified.sh > displaylink-installer-modified.sh
    chmod +x displaylink-installer-modified.sh

 - Run the modified installer as you would the default one
