<p align="center">
  <img src="https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-icon-theme/master/preview.png" alt="preview"/>
</p>

![more 2400 icons for apps](https://img.shields.io/badge/icons%20for%20apps-2400+-brightgreen.svg) ![more 1700 icons for actions](https://img.shields.io/badge/icons%20for%20actions-1700+-brightgreen.svg) ![more 1600 icons for panel](https://img.shields.io/badge/icons%20for%20panel-1600+-brightgreen.svg) ![more 90 icons for places](https://img.shields.io/badge/icons%20for%20places-90+-brightgreen.svg)

# About
Papirus - it's SVG icon theme for Linux, based on [Paper](https://github.com/snwh/paper-icon-theme) with more additionals (hardcode-tray support, libreoffice icon theme, filezilla theme, smplayer themes ...) and modifications. Available light and dark version for GTK and KDE.

# Install / Update
## ROOT directory
```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-icon-theme/master/install-papirus-root.sh | sh
```
## HOME directory for GTK
```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-icon-theme/master/install-papirus-home-gtk.sh | sh
```

## HOME directory for KDE
```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-icon-theme/master/install-papirus-home-kde.sh | sh
```

**Depends:**
- wget
- tar
- libqt4-svg (optional, need for right work on Qt4-apps)

# Remove
```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-icon-theme/master/remove-papirus.sh | sh
```

# Hardcoded tray icons

Papirus now support [Hardcode-Tray](https://github.com/bil-elmoussaoui/Hardcode-Tray) script

![hardcode-tray](hardcode-tray-preview.png)


# Recommends
- For GTK better use icons with GTK theme [Arc Dark](https://github.com/horst3180/arc-theme)
- For KDE better use with [Arc KDE](https://github.com/PapirusDevelopmentTeam/arc-kde)

# Icon request
- Application name
- Icon name (see desktop-file option **Icon** on `/usr/share/applications`)
- Original icon image

# Donate
If you like my project , you can donate:

<span class="paypal"><a href="https://www.paypal.me/varlesh" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>

<span class="Yandex.Money"><a href="http://yasobe.ru/na/varlesh#form_submit" title="Donate to this project using Yandex.Money"><img src="https://money.yandex.ru/img/ym_logo.gif" alt="Yandex.Money donate button" /></a></span>

# License
GNU LGPL v3
