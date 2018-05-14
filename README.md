# Freeplay Theme for EmulationStation

Changelog
-----------

- May 2018 - Work in progress...

License
-----------
Creative Commons CC BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/3.0/

Screenshots
-----------
![System Select Screen](http://i.imgur.com/wIjmpyt.png) ![Detailed Game List](http://i.imgur.com/AJSVHLx.png)

Recommended Installation Method
-----------
This theme will eventually be added to the es-themes menu in Retropie.  In the meantime, it can be installed for testing using the following commands:


NEW INSTALL:
```
sudo git clone --recursive --depth 1 "https://github.com/rxbrad/es-theme-freeplay.git" "/etc/emulationstation/themes/freeplay"
```

UPDATE EXISTING INSTALL:
```
cd "/etc/emulationstation/themes/freeplay"

sudo git pull

sudo git submodule update --init --recursive
```