# KArc-theme

An Arc port to the KDE Aurorae engine. KArc is a flat theme with support for transparency using QTCurve. KArc also supports translucent window backgrounds (blurred and increased contract) using Desktop Effects.

####KArc is available in the following variants: 

#####KArc

![alt tag](http://i.imgur.com/BCgStHS.png)

#####KArc-Darker

![alt tag](http://i.imgur.com/q73i1Re.png)

#####KArc-Dark

![alt tag](http://i.imgur.com/eN4LWgG.png)

### Requirements
* KDE Plasma 5 (tested on 5.4.2)
* QTCurve theme engine

### Installation

     git clone https://github.com/zbeptz/KArc-theme.git && cd KArc-theme
     cp -r {KArc,KArc-Dark} ~/.local/share/aurorae/themes/
     cd desktoptheme && cp -r KArc ~/.local/share/plasma/desktoptheme
     cd .. && cp {KArcDark.colors,KArc.colors} ~/.local/share/color-schemes
     cp KArc.qtcurve ~/.local/share/QTCurve
     
To enable translucency, go to `System Settings > Desktop Behavior > Desktop Effects`, then select `Background Contrast` and `Blur`. Blur strength can be set light->strong.

### Bug reporting

If you find a bug, please report it at https://github.com/zbeptz/KArc-theme/issues
