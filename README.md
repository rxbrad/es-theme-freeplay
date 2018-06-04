# Freeplay Theme for EmulationStation

Changelog
-----------

- June 1, 2018 - Initial Release

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

Changing Theme Color
-----------
![Red](https://i.imgur.com/YLa8c8A.png)![Orange](https://i.imgur.com/TG7M0TH.png)![Gold](https://i.imgur.com/UU3v0qs.png)![Yellow](https://i.imgur.com/fqaclTh.png)![Green](https://i.imgur.com/b5TOhBK.png)![Blue](https://i.imgur.com/U47t22G.png)![Glacier](https://i.imgur.com/OoUmMJn.png)![Indigo](https://i.imgur.com/EFXJSg8.png)![Fuchsia](https://i.imgur.com/d9fSqdW.png)![White](https://i.imgur.com/nY2fYsY.png)![Platinum](https://i.imgur.com/pQtRBDA.png)![Black](https://i.imgur.com/65KWrpT.png)

There are 12 different color variants for this theme.  The color can be changed by editing the color.xml file, and uncommenting the line for the desired color (make sure that only one line is uncommented).

For a Raspberry Pi RetroPie install, the color can be edited with the following command:
```
sudo nano /etc/emulationstation/themes/freeplay/color.xml
```

I'm also working on a script that can be used to automatically install/update all 12 color variants at once (this is done outside of the ESThemes utility).  Check it out at https://github.com/rxbrad/rxbrad_themeutils
