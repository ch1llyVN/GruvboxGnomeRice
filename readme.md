# TUTORIAL HOW TO INSTALL STEP BY STEP
## Components
1. [kitty](https://sw.kovidgoyal.net/kitty/)
2. [Open Bar](https://extensions.gnome.org/extension/6580/open-bar/)
3. [PaperWM](https://extensions.gnome.org/extension/6099/paperwm/)
4. [Kando Adapter](https://extensions.gnome.org/extension/7068/kando-integration/)
5. [Kando](https://kando.menu/installation-on-linux/)
## Installation
First, put the `kitty`, `paperwm` to .config, then put the contents in `themes` and `icons` to your `.themes` and `.icons` (`/usr/share/icons` and `/usr/share/themes`) if you want to install for all user. After that open kando and open setting -> open the directory -> put the `config.json` and replace the config file then open `kando/menu-themes` and put `gruvnavbar` folder in that directory. The final step, open extension manager then select Open Bar -> setting admin -> import the file in `openbar` folder named `gruvbox`

## Preview
![alt text](https://github.com/ch1llyVN/GruvboxGnomeRice/blob/main/preview/screenshot1.png?raw=true)
![alt text](https://github.com/ch1llyVN/GruvboxGnomeRice/blob/main/preview/screenshot2.png?raw=true)

## Other Themes
### Spotify
1) Install [Spicetify](https://spicetify.app/docs/advanced-usage/installation/).
2) Download and install the ["text" theme](https://github.com/spicetify/spicetify-themes/tree/master).
3) Download the theme in the "spotify theme" folder open the file called "color.ini".
4) Copy the contents and add them to the "color.ini" file in `/spicetify/Themes/text/`.
5) Then apply it like you would any other color variation for the text theme.
### Krita
1) Download the theme in the "Krita Theme" folder.
2) Open Krita.
3) Click on "Settings".
4) Click on "Manage resources".
5) Click on "Open resource folder".
6) Open the "color-schemes" folder (create one if you can't find it).
7) Drag the "gruvboxy.colours" file inside the "color-schemes" folder.
8) Apply the Theme in Krita.
### Discord 
Put this in your quick css editor (Vencord)
```css
@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/DiscordRecolor/DiscordRecolor.css);

:root {
  --accentcolor: 137,180,130;
  --accentcolor2: 211,134,155;
  --linkcolor: 125,174,163;
  --mentioncolor: 211,134,155;
  --textbrightest: 221,199,161;
  --textbrighter: 212,190,152;
  --textbright: 168,153,132;
  --textdark: 146,131,116;
  --textdarker: 146,131,116;
  --textdarkest: 80,80,80;
  --font: gg sans;
  --backgroundaccent: 80,73,69;
  --backgroundprimary: 60,56,54;
  --backgroundsecondary: 50,48,47;
  --backgroundsecondaryalt: 40,40,40;
  --backgroundtertiary: 29,32,33;
  --backgroundfloating: 20,22,23;
  --settingsicons: 1;
}
```

