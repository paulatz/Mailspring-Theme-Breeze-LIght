Theme to fit with KDE/Plasma Breeze look.
It uses Tela icons by default, but Breeze icons are also available. In order to switch from one to the other, just change the variable @iconurl in variables.less to point to icons-tela/ or to icons-breeze/.

INSTALLATION:
Clone this repository, or download and decompress the zip, than use the "Edit/Install theme..." function of Mailspring. Be careful, if you want to clone directly into the packages folder of Mailspring, or put it in a directory that is not calle breeze-light that you will have to edit the @myurl variable accordingly for the resources to be found correctly.

<img src="https://raw.githubusercontent.com/paulatz/Mailspring-Theme-Breeze-Light/master/preview.jpg"/>

HOWTO:
It is relatively easy to adapt this theme to other KDE looks and feels, depending on what you want to achive:
- Icons: just replace the icons in icons/ with those of your choice. The files starting with "24" are 24x24, those starting with "16" are 16x16.
- Colors (light themes): there are still some colors hardcoded here and there, but changing thos defined in variables.less should be enough.
- Colors (dark themes): this requires some more work, as there are quite a few "darken" and "lighten" around that would not work properly. I'm trying to put all of them in variables.less and ui-variables.less, but more work is required.

KNOWN BUGS:
- It is possible that some icon will not themed depending at some screen resolution, i.e. if non "retina" icons are used. If this happens, please let contact me for a fix.



