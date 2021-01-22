Theme to fit with KDE/Plasma Breeze look.

Still very much work in progress, but it works. If you are good with this kind of things, feel free to fork the project.

TODO:
1. still a few icons missing here and there

<img src="https://raw.githubusercontent.com/paulatz/Mailspring-Theme-Breeze-Light/master/preview.jpg"/>

HOWTO:
It is realatively easy to adapt this theme to other KDE looks and feels, depending on what you want to achive:
- Icons: just replace the icons in icons/ with those of your choice. The files starting with "24" are 24x24, those starting with "16" are 16x16.
- Colors (light themes): there are still some colors hardcoded here and there, but changing thos defined in variables.less should be enough.
- Colors (dark themes): this requires some more work, as there are quite a few "darken" and "lighten" around that would not work properly. I'm trying to put all of them in variables.less and ui-variables.less, but more work is required.



